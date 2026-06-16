# MitigationBench Lite Dependency Pack

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
and large legacy toolchains. See dependency-pack-lite/pointers/ after unzip.
