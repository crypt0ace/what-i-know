# Event Tracing for Windows:

- Windows OS logging mechanism for diagnostics
- Main components:
```
Providers - Generates events
Consumers - Retreive Events
Controllers - Start/Stop Event Tracing Sessions
Tracing Sessions - Responsible for collecting events from providers
```
- `logman.exe` = Controller
- `TamperETW`
- `https://blog.palantir.com/tampering-with-windows-event-tracing-background-offense-and-defense-4be7ac62ac63`
- `https://www.bordergate.co.uk/unhooking-event-tracing-for-windows/`
- `https://modexp.wordpress.com/2020/04/08/red-teams-etw/`