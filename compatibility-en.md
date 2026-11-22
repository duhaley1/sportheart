# Compatibility and testing scope

2026-11-22

| Equipment | Connection | Evidence |
|---|---|---|
| iGPSPORT iGS630S | BLE | Tested: iGS630S |
| Garmin Edge 530 | Connect IQ + iPhone | Edge 530: owner reported a working connection. Firmware, extended locked-screen use and FIT export still need verification. |
| Other BLE equipment | BLE | Other models require individual testing. BLE support alone does not establish tested compatibility. |

Force quitting, restarting, wrist-off locking, and the display sleeping are different states. iGS630S testing confirmed reconnection after an equipment restart in both modes and background updates in iPhone mode. Other models require individual testing.

## Garmin Edge 530

Edge 530 uses a Connect IQ data field. Do not pair SportHeart in its heart-rate sensor list.

1. Pair your bike computer in Garmin Connect, then select it here.

2. Install SportHeart on the bike computer and add its data field to a cycling screen.

3. Select phone relay mode, start collection on your watch, then enable sharing here.

A receipt does not confirm that heart rate is displayed. Check the bike computer screen.

This field does not replace a native Garmin heart-rate sensor or guarantee training-load calculations.

## iGPSPORT iGS630S

iGS630S: Settings → Sensors → Add sensor → Heart rate.

Keep the iPhone app open for initial pairing in iPhone mode. The two modes use different senders and may require separate saved sensor entries.

During iGS630S testing, a simultaneous phone-equipment companion link sometimes prevented heart-rate data despite a sensor connection. Disconnecting that link, removing the saved heart-rate sensor and pairing again restored data. The cause is unconfirmed and other models may behave differently.

In iPhone mode, disconnect only the equipment's companion-app link. Leave iPhone Bluetooth and the watch connection on.

App Store: https://apps.apple.com/app/id6827442593

Connect IQ: https://apps.garmin.com/zh-CN/apps/0b750e18-5b36-4cc7-9470-b8f996dfa94a

Support: support-en.html
