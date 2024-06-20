[![GitHub](https://img.shields.io/github/license/wukongdaily/DockerTarBuilder.svg?label=LICENSE&logo=github&logoColor=%20)](https://github.com/wukongdaily/DockerTarBuilder/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/wukongdaily/DockerTarBuilder.svg?style=flat&logo=appveyor&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/wukongdaily/DockerTarBuilder.svg?style=flat&logo=appveyor&label=Forks&logo=github)

## 🤔 这是什么？
它是一个工作流。可快速构建指定架构/平台的docker镜像

## 使用说明
https://wkdaily.cpolar.cn/archives/gc


#### 1.在工作流的输入框里输入镜像名称（注意检查句首不要有空格）

> 小雅alist和小雅tvbox 逗号是英文版逗号

```xiaoyaliu/alist,haroldli/xiaoya-tvbox```

下面例举一些我们观众可能会用到的docker镜像 方便你复制粘贴
monlor 利用docker-compose方式部署的小雅全家桶，用到4款docker镜像 我将emby 和 jellyfin分开写 方便复制  

> Emby 全家桶

```ghcr.io/monlor/xiaoya-alist,ghcr.io/monlor/xiaoya-metadata,ghcr.io/monlor/xiaoya-embyserver```

> Jellyfin 全家桶

```ghcr.io/monlor/xiaoya-alist,ghcr.io/monlor/xiaoya-metadata,ghcr.io/monlor/xiaoya-jellyfin```

> Emby + Jellyfin

```ghcr.io/monlor/xiaoya-alist,ghcr.io/monlor/xiaoya-metadata,ghcr.io/monlor/xiaoya-embyserver,ghcr.io/monlor/xiaoya-jellyfin```

> 智能家居 HomeAssistant

```homeassistant/home-assistant:latest```

> 1panel面板docker版本

```moelin/1panel:latest```

#### 2.下载docker镜像
下载后是一个压缩包zip，解压工具推荐如下。zip解压到tar.gz 然后继续解压到tar，用tar的镜像比较稳妥。兼容性好

## 教学视频
https://www.bilibili.com/video/BV1EZ421M7mL
## 解压工具
> Windows 上推荐使用7zip<br>
> macOS 推荐使用MacZip<br>
> Linux上推荐直接用tar 命令

## 相关项目
https://github.com/wukongdaily/OrangePiShell
## 在哪里可以搜索或查询docker镜像的详细信息
### [查询镜像的详细信息 点击这里直达](https://docker.fxxk.dedyn.io/)
