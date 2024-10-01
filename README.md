# Setup Binaryen

[![Release](https://img.shields.io/github/v/release/phi-ag/setup-binaryen?style=for-the-badge)](https://github.com/phi-ag/setup-binaryen/releases)
[![Check](https://img.shields.io/github/actions/workflow/status/phi-ag/setup-binaryen/check.yml?style=for-the-badge&label=check)](https://github.com/phi-ag/setup-binaryen/actions/workflows/check.yml)

Minimal shell script action to setup [Binaryen](https://github.com/WebAssembly/binaryen)

## Usage

```yaml
steps:
  - name: Setup Binaryen
    uses: phi-ag/setup-binaryen@v1
```

Use a specific version

```yaml
steps:
  - name: Setup Binaryen
    uses: phi-ag/setup-binaryen@v1
    with:
      version: "118"
```
