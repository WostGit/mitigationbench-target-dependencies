# MitigationBench Lite Dependency Pack Plus Probes

This directory contains a single under-100MB ZIP:

```text
mitigationbench-target-dependencies-lite.zip
```

Verify:

```bash
sha256sum -c mitigationbench-target-dependencies-lite.zip.sha256
unzip mitigationbench-target-dependencies-lite.zip
```

This pack intentionally excludes heavyweight Docker images, full datasets,
and large legacy toolchains. It includes pointer files, probe scripts,
and backup plans for environments where Docker is unavailable.
