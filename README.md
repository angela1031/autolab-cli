# Auto Lab CLI

Releases of the Auto Lab command-line tool. Install on macOS or Linux:

```bash
curl -fsSL https://app.auto-lab.ai/install | bash
```

The binary is named `kortix`. After installing, run `kortix login` to sign in at
[app.auto-lab.ai](https://app.auto-lab.ai), and `kortix update` to upgrade later.

Each [release](https://github.com/angela1031/autolab-cli/releases) carries
`kortix-{darwin,linux}-{arm64,x64}` and a `SHA256SUMS` file. This repository holds only the
installer (`scripts/install.sh`) and release assets; releases are published by Auto Lab.
