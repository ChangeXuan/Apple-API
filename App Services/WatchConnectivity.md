# WatchConnectivity
### Implement two-way communication between an iOS app and its paired watchOS app.
## 概述
Use this framework to transfer data between your iOS app and the WatchKit extension of a paired watchOS app. You can pass small amounts of data or entire files. You also use this framework to trigger an update to your watchOS app's complication.

After initiating a transfer from your app, the system assumes responsibility for the transmission of any data. Most transfers happen in the background when the receiving app is inactive. When the app wakes up, it is notified of any data that arrived while it was inactive. Live communication is also possible when both apps are active.
