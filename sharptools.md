## OffensivePipeline
- Downloads tools from the internet, builds them and obfuscates them.

## SharpCollection
- Nightly builds of common C# offensive tools, fresh from their respective master branches built and released in a CDI fashion using Azure DevOps release pipelines.

## NetLoader
- Takes a file on disk or on SMB share or URL. Then it can help unhook ETW and load a C# binary in memory patching AMSI as well. (Tried but got caught)

## DInjector
- Generate a shellcode, Encrypt it with `ecnrypt.py`, Serve the `dll` on webserver, Use `cradle.ps1` to load it. Uses D\Invoke API to load the shellcode.
