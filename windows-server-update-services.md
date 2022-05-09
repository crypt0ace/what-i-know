# Windows Server Update Services:

- Used to distribute updates to computers in network
- Windows Update downloads and executes code over the internet. This introduces a huge attack vector if not done properly.
- 3rd Party code is also distributed trough Windows Update, such as drivers.
- Any malicious code that manages to be delivered through Windows Update will look trustworthy.
- Can be used for persistence or lateral movement
- `https://h4ms1k.github.io/Red_Team_WSUS/`