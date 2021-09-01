Steps to reproduce:
1. `> dotnet build`
2. `> code .`
3. Wait for intellisense to start working in fs-proj/Library.fs
4. `> dotnet build`
5. Observe that it must rebuild fs-proj.fsproj instead of an incremental build