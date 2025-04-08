# Note for All Users

Weekly updates, simply curl [latestlink.txt](https://raw.githubusercontent.com/PurrrsLitterbox/LLVM-weekly/refs/heads/main/latestlink.txt) file from your shell scripts to download latest release.

This clang releases is following LLVM Project's main branch, which may contains unstable commits. Use with cautions!

Build started every sunday on 07:00 WIB/00:00 UTC

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

==> Shipped with Binutils version 2.44

==> GLibC version 2.35

==> Stripped binaries

==> Download size 251MB

==> Compressed tar archive with ZSTD

==> Build LLVM Polly & LLD

==> Build with ThinLTO + PGO
