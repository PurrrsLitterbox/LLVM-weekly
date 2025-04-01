# Download 
Check latest release [here](https://github.com/purrrslitterbox/clang-releases/releases/latest)

# Installation
```bash
mkdir $HOME/.kaleidoscope
tar -xf clang.tar.zst -C $HOME/.kaleidoscope
echo "export PATH=$HOME/.kaleidoscope/bin:$PATH" >> ~/.bashrc
source $HOME/.bashrc
clang --version
``` 

# Features 
```
==> Minimal LLVM 19.1.7-20250328 targeting 'AArch64', 'ARM', and 'X86'
==> Stripped binaries
==> Download size 279MB
==> Compressed tar archive with zstd v1.5.7
==> Build LLVM Polly & LLD
==> Build with ThinLTO + PGO
```
