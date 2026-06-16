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

Parts are split at 95M to stay below GitHub's 100 MiB per-file limit.
