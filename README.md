# gitignore

.DS_Storeとか、環境依存の不要なファイルをgitに混入させない設定

## ディレクトリとファイル作って、vimで編集

```terminal
mkdir -p ~/.config/git && vim $_/ignore
```

## ignoreの中身

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
