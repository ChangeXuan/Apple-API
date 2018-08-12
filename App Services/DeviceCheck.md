# DeviceCheck
### Access per-device, per-developer data that your associated server can use in its business logic.
## 概述
Using the DeviceCheck APIs, in combination with server-to-server APIs, you can set and query two bits of data per device, while maintaining user privacy. You might use this data to identify devices that have already taken advantage of a promotional offer that you provide, or to flag a device that you've determined to be fraudulent. The DeviceCheck APIs also let you verify that the token you receive comes from an authentic Apple device on which your app has been downloaded.
### 注意
```
You're responsible for keeping track of whether a user is entitled to redeem any offer that you provide. Typically, you use the DeviceCheck APIs to ensure that a new user hasn't already redeemed an offer under a different user name on the same device.

You're also responsible for determining when to reset the bits for a device; for example, when it's resold.
```
Your app uses the DeviceCheck APIs to generate an ephemeral token that identifies a device. Your associated server combines this token with an authentication key that you receive from Apple, and uses the result to request access to the per-device bits. After successful authentication, Apple passes the current values of the bits, along with the date they were last modified, to your server. Your server applies its business logic to this information and communicates the results to your app as appropriate.
