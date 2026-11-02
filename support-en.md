# Sport Heart Assistant · App Support

Developer: duhaley. Contact: 924323178@qq.com. Support: [sportheart repository](https://github.com/duhaley1/sportheart).

## Getting started

1. Pair your iPhone and Apple Watch and install both apps.
2. Wear and unlock your Watch. Allow the requested Health and Bluetooth permissions.
3. Choose Watch or iPhone communication and tap Start. Watch mode sends directly; iPhone mode measures on Watch and relays through iPhone. Open the iPhone app and allow Bluetooth for iPhone mode.
4. On equipment supporting standard BLE heart-rate sensors, search for and add the sensor. The Watch name is SportHeart Watch; the iPhone name is SportHeart Phone.
5. Wait for a valid reading. Pause suspends sending; End ends the session. End sessions when finished to conserve battery.

## Free features and one-time purchase

Basic live heart rate, direct Watch and iPhone bridge BLE, Start, Pause and End are free forever, without session-time or usage-count limits. Optional Apple Health workout saving is also free.

Sport Heart Assistant Pro is one optional non-consumable purchase covering disconnect alerts, default aerobic above-limit alerts, Dynamic Island and Lock Screen display, five custom zones, reference calculations and advanced feedback. No subscription or automatic renewal. The App Store purchase sheet shows the final price. Use Restore Purchases in Settings with the same Apple Account. Both devices verify the same product; separate purchases are not required.

Basic heart rate and both BLE modes remain available when purchases are pending, unavailable or incomplete. Product availability depends on the released App Store version. If Watch has not yet unlocked, confirm network access and the same Apple Account, then reopen the app before trying again. Avoid paying a second time.

## Zones and alerts

The default aerobic reference zone is 121–150 bpm. Training alerts start disabled. Switches, training targets and feedback options save automatically. After editing zone parameters, tap Save and Return. Offline edits are saved on iPhone and applied when Watch reconnects.

Readings must remain outside the target for about 15 seconds before an alert, with a cooldown between alerts. Disconnect feedback requires an established connection followed by a sustained loss; intentional Pause or End does not trigger it. Feedback uses several short haptics, subject to system settings. Default zones and adult age formulas are general exercise references, not personal medical or metabolic thresholds.

## Dynamic Island and Lock Screen

Requires Sport Heart Assistant Pro and system Live Activity support. After collection starts and a fresh reading reaches iPhone, a Home shortcut appears; Settings also contains a switch. Open the iPhone app after each start so it receives Watch status and creates the display, then return Home or lock the screen. The system may delay updates. Stale readings are not shown as current. Second-by-second updates and operation after force quit are not guaranteed.

## Connection troubleshooting

- Sensor not found: verify an active session, Bluetooth permission, BLE Heart Rate receiver support and no conflicting sensor connection. Wear/unlock Watch; keep the iPhone app running for bridge mode.
- Saved sensor no longer connects: some receivers require forgetting and adding the heart-rate sensor after restarting the app/session. A matching name does not guarantee the same stored pairing identity.
- iGS630S connects without readings: keep Bluetooth on, disconnect the cycling computer's companion phone link, forget the old HR sensor, then add the HR sensor again. This recovery flow has been user-tested.
- No heart rate: check Watch wear/unlock status, Health permission and active workout collection.
- User testing covers Apple Watch S10, iPhone 15 Pro Max and iGPSPORT iGS630S. Other Garmin, Magene, treadmill and receiver models require individual verification. No universal compatibility or brand partnership is claimed.

## Health and privacy

Save to Apple Health is optional and applies to the next workout. Disable it to avoid duplicate records when equipment also records workouts. Uninstalling the app does not delete workouts already saved in Health; manage them in Health.

No health data is uploaded to developer servers. There is no developer account, advertising or analytics SDK. Apple Health syncing, Apple payments and receiving equipment's cloud services have their own policies. Read the [Privacy Policy](privacy-en.md).

## Contact

Use the repository's feedback facilities to contact duhaley. Include app/system versions, equipment model, communication mode and reproduction steps. Share diagnostic logs only voluntarily and after removing sensitive information. Never post health records, Apple Account details, payment receipts or unique device identifiers publicly.

For exercise feedback only, not medical diagnosis or emergency alerts. Stop exercising if unwell and seek appropriate help.

## Run checks

Settings → Connection Diagnostics → Runtime & Battery Records. Start collection on Home to record automatically; opening the page does not start a workout. Sync or share the latest summary without individual heart samples or receiver identities. Whole-device battery rates require at least 30 minutes and are not estimated during charging or interrupted runs.


Nearby iPad display: This free feature is off by default. When you enable it, the app uses the local network and Bonjour to discover nearby devices. iPad must enter the random session code and iPhone must approve before current heart rate, sample time and zone category are shared over TLS encryption. The code is held only in memory and expires when sharing stops. Age, resting heart rate, history and purchase entitlements are not shared. iPad displays only the current reading in memory; it does not store heart-rate history, pair with Apple Watch or relay BLE. Keep both apps in the foreground. Stopping, backgrounding or disconnecting ends sharing, and expired readings disappear. The developer cannot access this local connection.
