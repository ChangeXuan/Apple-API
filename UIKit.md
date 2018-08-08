# UIKit
### Construct and manage a graphical, event-driven user interface for your iOS or tvOS app.
## 概述
The UIKit framework provides the required infrastructure for your iOS or tvOS apps. It provides the window and view architecture for implementing your interface, the event handling infrastructure for delivering Multitouch and other types of input to your app, and the main run loop needed to manage interactions among the user, the system, and your app. Other features offered by the framework include animation support, document support, drawing and printing support, information about the current device, text management and display, search support, accessibility support, app extension support, and resource management.

#### Important
Use UIKit classes only from your app’s main thread or main dispatch queue, unless otherwise indicated. This restriction particularly applies to classes derived from UIResponder or that involve manipulating your app’s user interface in any way.
