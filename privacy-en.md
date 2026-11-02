Sport Heart Assistant Privacy Policy
Developer: duhaley
Effective: October 28, 2026
Support and contact: https://github.com/duhaley1/sportheart
Contact email: 924323178@qq.com

1. What the app processes
Sport Heart Assistant is a local workout heart-rate tool. After you start a session, Apple Watch reads workout heart rate and sends it locally to compatible equipment, directly over BLE or through your iPhone. We run no developer account service, health-data server, advertising or analytics SDK. Heart rate, workouts, age and resting heart rate are not uploaded to a developer server.

2. Permissions and purpose
Health access reads heart rate during your workout. Only if you enable Save to Apple Health does the app save a workout you intentionally start and end. Turning recording off does not disable basic heart-rate communication. Bluetooth supports standard BLE heart-rate sending and connection status. Workout and background processing serve your active session. Manage permissions in system Settings or Health.

3. Local storage
The latest operational summary stores start time, recorded duration, device battery changes, communication modes, and connection counts locally for your own long-run checks. It contains no heart-rate history or receiver identity. A new session replaces the previous summary.
Communication mode, alert preferences, custom zones, age and reference heart rates are stored on your devices. Your paired watch and iPhone exchange status and settings using Apple's companion communication frameworks. The app does not build a beat-by-beat history database. Apple Health manages saved workouts; Apple syncing or backup depends on your system settings and is not an upload to the developer.

4. Equipment and nearby Bluetooth
Current valid heart rate is sent only after you start or resume; missing readings are not invented. Ordinary BLE heart-rate communication is not an end-to-end private channel. Nearby devices able to subscribe to the standard service may read it. Cycling computers, treadmills and other receivers may save or upload readings under their own policies. The app does not control those services. Stop your session to stop sending.

5. Dynamic Island and Lock Screen
When enabled, system surfaces may display heart rate and status on the Lock Screen, Dynamic Island or devices synchronized by the system. People who can see your screen may see that information. Updates may be delayed and stale data is marked; second-by-second updates or continued operation after force quit are not guaranteed. Turn display off or use system privacy controls as needed.

6. One-time purchases
Basic heart rate, direct Watch BLE and iPhone bridge BLE communication remain free. Sport Heart Assistant Pro is an optional non-consumable purchase with no automatic renewal. The App Store handles payment, transactions, restoration and refunds. The app uses Apple-verified entitlements to unlock features, receives no card details and sends no health or transaction data to a developer server. Apple's processing is governed by Apple's policies.

7. Support, logs and external links
Diagnostics contain status, counts and errors, not an intentionally appended heart-rate history. Logs leave the app only when you explicitly share them. Review them before sharing. GitHub support, Apple payment services and reference links you open have their own policies. Do not post health records, Apple Account details, purchase receipts or device identifiers in public issues.

8. Your choices
Stop collection and sending, disable alerts or display, and revoke permissions at any time. Edit preferences locally. Deleting the app removes its local data, subject to system backup behavior. Uninstalling does not remove workouts already saved in Health; manage those in the Health app. No developer account is created, so no developer account-deletion process is needed. Apple transaction history is not deleted by uninstalling.

9. Scope
The app provides workout feedback, not medical diagnosis, a medical device or an emergency alarm. Default zones and age formulas are general adult references, not personalized medical advice or safety guarantees. Stop exercising if unwell and seek appropriate help; do not rely on alerts to determine safety. The reference parameter editor is intended for adults, not specifically designed for children.

10. Changes and contact
We update this policy when material functionality or processing changes. Policy files and support are available at https://github.com/duhaley1/sportheart . Contact developer duhaley through the repository's feedback facilities.


Nearby iPad display: This free feature is off by default. When you enable it, the app uses the local network and Bonjour to discover nearby devices. iPad must enter the random session code and iPhone must approve before current heart rate, sample time and zone category are shared over TLS encryption. The code is held only in memory and expires when sharing stops. Age, resting heart rate, history and purchase entitlements are not shared. iPad displays only the current reading in memory; it does not store heart-rate history, pair with Apple Watch or relay BLE. Keep both apps in the foreground. Stopping, backgrounding or disconnecting ends sharing, and expired readings disappear. The developer cannot access this local connection.
