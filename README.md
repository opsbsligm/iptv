# cn-iptv.m3u

Apple TV / APTV 可直接粘贴的中国大陆央视+卫视订阅清单。

- 门禁：清单可达 + 分段实测吞吐 >= 实时 1.5 倍 + 直播时效偏差 < 5 分钟 + 抽帧人工核对台标。
- 频道名以截帧画面台标人工核实，不采用第三方清单自带名称。
- 主体是上海电信 IPTV 网关（`101.66.x`），只在中国电信家宽/IPTV 线路可达；`CGTN`、内蒙古、延边、安多、苏州4K 为官方公网源。
- 画质：1 个 4K（苏州4K 3840x2160）、31 个 1080P、2 个 720P、9 个标清。实测无可用的央视 4K/8K 源。
- APTV 用法：APTV → 设置 → 订阅 → 新增播放列表 → 粘贴 `https://raw.githubusercontent.com/opsbsligm/iptv/main/cn-iptv.m3u`。

`cn-iptv-validated.m3u`(v1) 与 `cn-iptv-validated-v2.m3u`(v2) 已废弃：其中部分频道名来自源清单自带标签（实测有错），并含易 404 的海外中转线路。
