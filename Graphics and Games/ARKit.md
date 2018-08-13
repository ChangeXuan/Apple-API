# ARKit
### Integrate iOS device camera and motion features to produce augmented reality experiences in your app or game.
## 概述
Augmented reality (AR) describes user experiences that add 2D or 3D elements to the live view from a device's camera in a way that makes those elements appear to inhabit the real world. ARKit combines device motion tracking, camera scene capture, advanced scene processing, and display conveniences to simplify the task of building an AR experience.
### 重要事项
ARKit requires an iOS device with an A9 or later processor.

To make your app available only on devices supporting ARKit, use the arkit key in the UIRequiredDeviceCapabilities section of your app's Info.plist. If augmented reality is a secondary feature of your app, use the isSupported property to determine whether the current device supports the session configuration you want to use.
