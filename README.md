# cpk
![GitHub release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/sn3ksoftware/sandpkg?include_prereleases&sort=semver)

Welcome to the repository for cpk alpha (Cub Package Manager).

## Versions avaliable for spkg:
spkg(OpenTerm) |
------------ |
v0.11/Alpha |

## Why cpk?
[OpenTerm](https://github.com/louisdh/openterm) does not have a inbuilt package manager (and it has a custom scripting system called Cub).
Hence, I decided to write one in Cub.
(By the way, spkg uses [this](https://github.com/sn3ksoftware/sandboxrepo) repository by default.)

# Installation
cpk was originally written for OpenTerm.
You can download the alpha release by following the instructions below.

## OpenTerm
Run these commands in your shell.

```
curl -O https://raw.githubusercontent.com/sn3ksoftware/cpk/testing/openterm/cpkinstall.tar.gz
tar -C ~/.scripts -zxvf cpkinstall.tar.gz
cpkinstall
```
(The installer is a bit buggy right now, so try running sandinstall muitiple times if it does not work the first time.

# License
The entirety of the cpk code, including the installer, is distributed under the MIT License.
