dotNetCoreExec
===

### プロジェクトの作成

```
dotnet new console -o ./ -n NetCore.Docker
```

### 単一の実行ファイルの作成

```
dotnet publish --self-contained true -p:PublishSingleFile=true -r linux-x64
```
