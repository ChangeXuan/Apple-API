# DeviceCheck
### 你能够在你的关联服务器中访问每一台设备，每一个开发者的数据信息，并利用这些信息来丰富你的业务逻辑。
## 概述
使用DeviceCheck的APIs，并与服务器到服务器的APIs相结合，你能够在保证用户的隐私没被泄露时，设置和查询两位数据长度的设备信息。
您可以使用这些数据来识别已经利用了您提供的促销提议的设备，
或者使用标记功能区去把你认定的具有欺骗性质的设备进行标记。
当你的应用被下载时，你可以使用DeviceCheck的API来获取这一信息的令牌。

### 注意
```
You're responsible for keeping track of whether a user is entitled to redeem any offer that you provide. Typically, you use the DeviceCheck APIs to ensure that a new user hasn't already redeemed an offer under a different user name on the same device.

You're also responsible for determining when to reset the bits for a device; for example, when it's resold.
```
Your app uses the DeviceCheck APIs to generate an ephemeral token that identifies a device. Your associated server combines this token with an authentication key that you receive from Apple, and uses the result to request access to the per-device bits. After successful authentication, Apple passes the current values of the bits, along with the date they were last modified, to your server. Your server applies its business logic to this information and communicates the results to your app as appropriate.
