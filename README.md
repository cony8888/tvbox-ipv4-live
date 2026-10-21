# TVBox IPv4 直播源合集

整理日期：2026-10-22。5,399 条播放地址，按大陆、港澳台和国际分组，安徽频道优先。

## 直接订阅

TVBox 配置地址：
```
https://raw.githubusercontent.com/cony8888/tvbox-ipv4-live/main/tvbox.json
```

直播列表：
```
https://raw.githubusercontent.com/cony8888/tvbox-ipv4-live/main/live-ipv4.m3u
```

不支持 M3U 的客户端可使用同目录 live-ipv4.txt。镜像配置文件为 tvbox-mirror.json，内置 gh-proxy.com 前缀；此第三方服务可用性无保证。

## 检查范围

仅做入口公网 IPv4 和域名 A 记录筛选；没有安徽移动家庭宽带逐台实测，不保证播放、频道内容、后续跳转或分片 IPv4 可达。镜像只帮助下载列表，不代理视频。频道范围受公开来源限制。这是一次快照，没有配置自动更新。

## 来源和许可

国内补充来自 [vbskycn/iptv](https://github.com/vbskycn/iptv)，原列表 https://live.zbds.top/tv/iptv4.m3u ，项目 GPL-3.0。全球列表来自 [iptv-org/iptv](https://github.com/iptv-org/iptv)，项目 Unlicense。保留原频道标识、台标与播放参数，移除明显 IPv6/非公网/广告/MP4 条目并按地区分组。本合集按 GPL-3.0 分发，见 LICENSE；许可不授予频道视频内容权利。修改及整理由用户委托 Codex 完成，2026-10-22。

本公开版删除了 509 条含查询参数、鉴权路径或凭据指令的记录，并移除可选请求头。没有安徽移动逐台播放实测，部分需要请求头的流可能不能播放。
