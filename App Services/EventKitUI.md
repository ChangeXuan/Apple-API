# EventKitUI
### 显示一个用户界面，用于查看、选择和编辑用户的日历和提醒者数据。
## 概述
EnvikTUI框架提供了使用视图控制器创建、编辑和显示事件所需的类。它提供了几种可配置的视图控制器类。
### 重要事项

An iOS app linked on or after iOS 10.0 must include in its Info.plist file the usage description keys for the types of data it needs to access or it will crash. To access data through EventKitUI, you need to include descriptions for the NSCalendarsUsageDescription and NSContactsUsageDescription keys. (The EventKitUI framework may need to access Contacts data to choose the correct display name or avatar for a contact in a calendar.)

