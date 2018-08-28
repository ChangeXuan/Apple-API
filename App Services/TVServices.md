# TVServices
### 帮助用户发现你的应用程序。添加顶部货架内容和您的TVOS应用程序的描述，将显示在电视上。
## 概述
Apps on tvOS often have built-in media content, access media content stored on a remote server, or have other information to display to the user. For example, a weather app might access video files on a server showing the weather in different locals, and have other content items representing ongoing weather alerts. To help users discover this content when your app is not the foreground app, you can highlight your content in the Top Shelf area of the Apple TV main menu. For design guidance, see Top Shelf in tvOS Human Interface Guidelines.

You provide Top Shelf information by adding a Top Shelf app extension to your app. Your extension returns an array describing available content for your app, and the system uses this information to update the Top Shelf area. You describe your media to the operating system using TVContentItem objects. Each TVContentItem object represents either a piece of content or acts as a container for other TVContentItem objects. A content object typically includes an image and a title for tvOS to display, along with other metadata related to the content item.
