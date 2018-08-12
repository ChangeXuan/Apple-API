# EventKitUI
### Display a user interface for viewing, selecting, and editing the user's calender and remonders data.
## 概述
The EventKitUI framework provides the classes needed to create, edit, and display events using a view controller. It provides several configurable view controller classes.
### 重要事项
```
An iOS app linked on or after iOS 10.0 must include in its Info.plist file the usage description keys for the types of data it needs to access or it will crash. To access data through EventKitUI, you need to include descriptions for the NSCalendarsUsageDescription and NSContactsUsageDescription keys. (The EventKitUI framework may need to access Contacts data to choose the correct display name or avatar for a contact in a calendar.)
```
