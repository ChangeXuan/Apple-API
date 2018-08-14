# Media Player
### Add the ability to find and play songs, audio podcasts, audio books, and more from within your app.
## 概述
The Media Player framework provides developers with several ways to play media. Built-in music players provide an easy way to access and play audio from the user's music library in your app. External music players can also retrieve and play media items from the user's music library. To enable users to play videos containing MPMediaItem objects, use AVPlayer. You cannot play video media items using the Media Player framework.
### 重要事项
Starting in iOS 10, accessing a user's media library requires the user's consent. Add the Privacy - Media Library Usage Description key and a description of the key to the app's Info.plist file. Your app will crash if this key is not added to the project.
