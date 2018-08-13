# PushKit
### Send push notifications to update your app.
## 概述
The PushKit framework sends specific types of notifications—such as VoIP invitations, watchOS complication updates, and file provider change notifications—directly to your app for processing. (For a complete list of supported notification types, see PKPushType.)

Unlike user notifications, which are supported by the UserNotifications framework, PushKit notifications are never presented to the user—they don't present badges, alerts, or sounds.
PushKit notifications offer the following advantages over user notifications:

- If your app isn't running, the system automatically launches it upon receiving the notification. Although you can also use silent user notifications to update your app in the background, your app isn't guaranteed to launch when a notification arrives. For more information, see Local and Remote Notification Programming Guide.

- Your app is given runtime to process the notification, even if it's running in the background.

- The device wakes only when it receives a PushKit notification, which can improve battery life.

- PushKit notifications can include more data than user notifications.
