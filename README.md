# gitignore Mac用

.DS_Storeとか、環境依存の不要なファイルをgitに混入させない設定

## ディレクトリとファイル作って、vimで編集

```terminal
mkdir -p ~/.config/git && vim $_/ignore
```

## ignoreの中身 （コピペでOK）

```~/.config/git/ignore
# General
.DS_Store
.AppleDouble
.LSOverride

# Icon must end with two \r
Icon

# Thumbnails
._*

# Files that might appear in the root of a volume
.DocumentRevisions-V100
.fseventsd
.Spotlight-V100
.TemporaryItems
.Trashes
.VolumeIcon.icns
.com.apple.timemachine.donotpresent

# Directories potentially created on remote AFP share
.AppleDB
.AppleDesktop
Network Trash Folder
Temporary Items
.apdisk
```

Mac以外の人は以下の一覧から探して入れる。
参考: [gitignore/Global at master · github/gitignore](https://github.com/github/gitignore/tree/master/Global)

Cのディレクトリの.gitignoreは以下の設定を入れる。

```
# マークダウンのメモはいれない
*.md

# Prerequisites
*.d

# Object files
*.o
*.ko
*.obj
*.elf

# Linker output
*.ilk
*.map
*.exp

# Precompiled Headers
*.gch
*.pch

# Libraries
*.lib
*.a
*.la
*.lo

# Shared objects (inc. Windows DLLs)
*.dll
*.so
*.so.*
*.dylib

# Executables
*.exe
*.out
*.app
*.i*86
*.x86_64
*.hex

# Debug files
*.dSYM/
*.su
*.idb
*.pdb

# Kernel Module Compile Results
*.mod*
*.cmd
.tmp_versions/
modules.order
Module.symvers
Mkfile.old
dkms.conf
```

参考: [gitignore/C.gitignore at master · github/gitignore](https://github.com/github/gitignore/blob/master/C.gitignore)
