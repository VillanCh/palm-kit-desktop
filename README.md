# palm-kit-desktop

[下载链接点击这里](https://github.com/VillanCh/palm-kit-desktop/releases/tag/0.1.0)



## 版本支持:

1. 暂时只支持 macos 版本
2. Windows 版本暂时没有经历适配, 如果想要可以来投喂我 :-)

## 外部依赖镜像 (Docker)

1. postgres:12
2. rabbitmq:3-management

## 使用步骤

1. 你有一台 mac, 下载本软件并安装
2. docker 环境配置正确
3. 执行 `docker pull postgres:12 && docker pull rabbitmq:3-management` 以安装必要的镜像

## 其他问题

1. XRAY && RAD 如果下载不到怎么办?

  `~/.palm-desktop` 是 palm-kit-desktop 的用户数据目录, 如果需要自己手动下载 xray / rad,  请放在 `~/.palm-desktop/` 下, 命名为 `xray_darwin_amd64` 和 `rad_darwin_amd64`

## 更多功能

大家可以在 issue 中许愿, 说不定下个版本就有了呢?
