# WebKit
### Display web content in windows. Implement browser features such as following user-activated links, managing a back-forward list, and managing a history of recently visited pages.
## 概述
WebKit provides a set of classes to display web content in windows, and implements browser features such as following links when clicked by the user, managing a back-forward list, and managing a history of pages recently visited. WebKit greatly simplifies the complicated process of loading webpages—that is, asynchronously requesting web content from an HTTP server where the response may arrive incrementally, in random order, or partially due to network errors. WebKit also simplifies the process of displaying that content which can contain various MIME types, and compound frame elements each with their own set of scroll bars.
### 重要事项
Call WebKit functions and methods only from your app's main thread or main dispatch queue.
