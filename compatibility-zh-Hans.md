# 查看兼容性与测试范围

2026-11-22

| 设备 | 连接方式 | 验证范围 |
|---|---|---|
| iGPSPORT iGS630S | BLE | 已实测：iGS630S |
| Garmin Edge 530 | Connect IQ + iPhone | Edge 530：用户反馈连接正常；固件、长时锁屏和 FIT 导出仍待验证。 |
| 其他 BLE 设备 | BLE | 其他机型需逐一验证；支持 BLE 标准不等于已实测兼容。 |

系统强退、重启、脱腕锁定和普通息屏不是同一状态。iGS630S 已实测两种通信方式重启后恢复连接，以及手机通信后台更新；其他设备仍需逐机验证。

## Garmin Edge 530

Edge 530 使用 Connect IQ 数据字段，不在心率传感器列表中配对 SportHeart。

在 Garmin Connect 配对码表；然后打开运动心率助手 → 设置 → Garmin 心率连接，选择设备。

2. 在码表安装 SportHeart 数据字段，并添加到骑行数据页面。

在手表选择手机桥接并开始；在 iPhone 的 Garmin 心率连接页面开启共享。

收到消息不代表码表已经显示心率，请在码表页面确认。

此字段不会替代 Garmin 原生心率传感器或保证训练负荷计算。

## iGPSPORT iGS630S

iGS630S：设置 → 传感器 → 添加传感器 → 心率。

手机通信首次配对建议保持手机 App 在前台。两种模式是不同发送端，运动设备可能需要分别保存传感器。

当前 iGS630S 测试中遇到：运动设备同时连接手机设备时，心率传感器可能显示已连接，但没有心率数据；断开运动设备与手机的设备连接，并忘记原心率传感器、重新配对后，心率恢复。具体原因尚未确认，其他机型表现可能不同。

使用手机通信时，只断开运动设备与手机伴侣 App 的设备连接，保持 iPhone 蓝牙开启，以及手机与手表之间的通信。

App Store: https://apps.apple.com/app/id6827442593

Connect IQ: https://apps.garmin.com/zh-CN/apps/0b750e18-5b36-4cc7-9470-b8f996dfa94a

Support: support-zh-Hans.html
