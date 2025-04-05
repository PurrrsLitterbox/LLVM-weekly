# Note for All Users

Weekly updates, check [latestlink.txt](https://raw.githubusercontent.com/PurrrsLitterbox/LLVM-weekly/refs/heads/main/latestlink.txt) file for latest release.

This clang releases is following LLVM Project's main branch, which may contains unstable commits. Use with cautions!

Built every sunday on 07:00 WIB/00:00 UTC

# Installation

```bash
mkdir $HOME/.kaleidoscope
tar -xf clang.tar.zst -C $HOME/.kaleidoscope
echo "export PATH=$HOME/.kaleidoscope/bin:$PATH" >> ~/.bashrc
source $HOME/.bashrc
clang --version
``` 

# Features

==> Minimal LLVM 21.0.0git targeting 'AArch64', 'ARM', and 'X86'

==> Stripped binaries

==> Download size 236MB

==> Compressed tar archive with zstd v1.5.7

==> Build LLVM Polly & LLD

==> Build with ThinLTO + PGO
