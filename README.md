# sonobuoy

[中文版本](./README.cn.md)

Sonobuoy is a diagnostic tool that makes it easier to understand the state of a Kubernetes cluster by running a set of Kubernetes conformance tests and other plugins in an accessible and non-destructive manner.

![sonobuoy](https://repo.x-cmd.io/sonobuoy.svg)

## Install

```sh
x install sonobuoy
```

## Code insight

Total: **37,426** lines of code across **402** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 23,798 | 4,310 | 3,425 | 164 |
| Json | 6,931 | 0 | 0 | 50 |
| Yaml | 2,660 | 5 | 16 | 146 |
| Sass | 1,284 | 3 | 42 | 7 |
| Svg | 803 | 8 | 0 | 35 |

## OpenSSF Scorecard

Overall score: **5.9 / 10**

Lowest-scoring checks:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed

## Source

- **Upstream**: <https://github.com/vmware-tanzu/sonobuoy>
- **Homepage**: <https://sonobuoy.io>
- **License**: Apache-2.0

## Release

- **Latest**: `v0.57.5` (2026-07-01)
- **Last commit**: 2026-07-27
- **Assets in release**: 10

## Popularity

- **Stars**: 3,051 · **Forks**: 361 · **Open issues**: 1,037 · **Contributors**: 98

## Totals (cumulative)

- **Releases**: 71 · **Merged PRs**: 930 · **Open PRs**: 8 · **Closed issues**: 1008 · **Open issues**: 29 · **Commits**: 1272

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 0 | 1 | 0 | 4 | 0 |
| last60d | 2026-07-13 | 0 | 1 | 3 | 1 | 5 | 1 |
| 90d | 2026-06-13 | 1 | 3 | 4 | 1 | 9 | 6 |
| last180d | 2026-03-15 | 1 | 4 | 5 | 1 | 10 | 9 |
| 360d | 2025-09-16 | 1 | 6 | 7 | 1 | 16 | 11 |
| last720d | 2024-09-21 | 2 | 14 | 8 | 12 | 17 | 19 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [sonobuoy_0.57.5_checksums.txt](https://github.com/vmware-tanzu/sonobuoy/releases/download/v0.57.5/sonobuoy_0.57.5_checksums.txt) | 913 B | `other` |
| [sonobuoy_0.57.5_darwin_amd64.tar.gz](https://github.com/vmware-tanzu/sonobuoy/releases/download/v0.57.5/sonobuoy_0.57.5_darwin_amd64.tar.gz) | 24.5 MiB | `native/darwin/x64` |
| [sonobuoy_0.57.5_darwin_arm64.tar.gz](https://github.com/vmware-tanzu/sonobuoy/releases/download/v0.57.5/sonobuoy_0.57.5_darwin_arm64.tar.gz) | 23.5 MiB | `native/darwin/arm64` |
| [sonobuoy_0.57.5_linux_386.tar.gz](https://github.com/vmware-tanzu/sonobuoy/releases/download/v0.57.5/sonobuoy_0.57.5_linux_386.tar.gz) | 23.3 MiB | `native/unknown` |
| [sonobuoy_0.57.5_linux_amd64.tar.gz](https://github.com/vmware-tanzu/sonobuoy/releases/download/v0.57.5/sonobuoy_0.57.5_linux_amd64.tar.gz) | 24.3 MiB | `native/linux/x64` |
| [sonobuoy_0.57.5_linux_arm64.tar.gz](https://github.com/vmware-tanzu/sonobuoy/releases/download/v0.57.5/sonobuoy_0.57.5_linux_arm64.tar.gz) | 22.8 MiB | `native/linux/arm64` |
| [sonobuoy_0.57.5_linux_ppc64le.tar.gz](https://github.com/vmware-tanzu/sonobuoy/releases/download/v0.57.5/sonobuoy_0.57.5_linux_ppc64le.tar.gz) | 22.8 MiB | `native/unknown` |
| [sonobuoy_0.57.5_linux_s390x.tar.gz](https://github.com/vmware-tanzu/sonobuoy/releases/download/v0.57.5/sonobuoy_0.57.5_linux_s390x.tar.gz) | 23.8 MiB | `native/unknown` |
| [sonobuoy_0.57.5_windows_386.tar.gz](https://github.com/vmware-tanzu/sonobuoy/releases/download/v0.57.5/sonobuoy_0.57.5_windows_386.tar.gz) | 24.0 MiB | `native/win/x64` |
| [sonobuoy_0.57.5_windows_amd64.tar.gz](https://github.com/vmware-tanzu/sonobuoy/releases/download/v0.57.5/sonobuoy_0.57.5_windows_amd64.tar.gz) | 24.6 MiB | `native/win/x64` |

## Distribution status

Reported by **13** distros on [repology.org](https://repology.org/project/sonobuoy). **4** are ✅ on the latest upstream release, **9** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `0.57.5` | ✅ latest |
| Nix unstable | `0.57.5` | ✅ latest |
| openSUSE Tumbleweed | `0.57.5` | ✅ latest |

## Improve this data

Install metadata for sonobuoy lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `sonobuoy` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/sonobuoy.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T19:35:22Z._
