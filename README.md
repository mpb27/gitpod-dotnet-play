[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/mpb27/gitpod-dotnet-play)

# gitpod-dotnet-play
Playing with dotnet on GitPod.


Create self contained executable including .NET runtime in a single file:

```bash
dotnet publish -c Release -r linux-x64 --self-contained=true -p:PublishSingleFile=true
```

Create single file executable excluding .NET runtime but including required dlls:

```bash
dotnet publish -c Release -r linux-x64 --self-contained=false -p:PublishSingleFile=true
```
