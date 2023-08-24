# podman-guide
guide of podman

## Sock
Podman 默认没有 `sock` 文件，可以通过下面的命令启用：

```shell
systemctl enable --now podman.socket
```
