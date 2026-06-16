# MitigationBench target dependency pack

This folder contains split parts of:

```text
mitigationbench-target-dependencies.zip
```

Recombine on Linux/macOS:

```bash
cat mitigationbench-target-dependencies.zip.part-* > mitigationbench-target-dependencies.zip
sha256sum -c mitigationbench-target-dependencies.zip.sha256
unzip mitigationbench-target-dependencies.zip
```

Recombine on Windows PowerShell:

```powershell
cmd /c copy /b mitigationbench-target-dependencies.zip.part-* mitigationbench-target-dependencies.zip
```

Parts are split at 25M to stay below connector and GitHub file-size limits.
