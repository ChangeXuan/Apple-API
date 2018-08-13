# MessageUI
### Create a user interface for composing email and text messages, so users can edit and send messages without leaving your app.
## 概述
The Message UI framework provides specialized view controllers for presenting standard composition interfaces for email and SMS (Short Messaging Service) text messages. Use these interfaces to add message delivery capabilities without requiring the user to leave your app.

To display a composition interface, present the corresponding view controller modally from your app. Once presented, the user has the option to customize the contents before sending or canceling the message. Your custom delegate object then handles the dismissal of the view controller based on the user’s action. For information on how to present and dismiss view controllers, see View Controller Programming Guide for iOS.
