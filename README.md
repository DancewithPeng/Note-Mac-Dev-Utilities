# Note-Mac-Dev-Utilities
Mac系统下的常用开发工具

## sshfs - 通过sftp挂载远程服务器目录到本地
安装：在官网下载并安装`sshfs`和`FUSE for macOS`
```
https://osxfuse.github.io/
```

添加挂载点
```
sshfs [user@]hostname:[directory] mountpoint
```

卸载挂载点
```
umount mountpoint
```
