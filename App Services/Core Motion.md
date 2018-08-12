# Core Motion
### Process accelerometer, gyroscope, pedometer, and environment-related events.
## 概述
Core Motion reports motion- and environment-related data from the onboard hardware of iOS devices, including from the accelerometers, gyroscopes, pedometers, magnetometers, and barometers. You use this framework to access hardware-generated data so that you can use it in your app. For example, a game might use accelerometer and gyroscope data to control onscreen game behavior.

Many services of this framework let you access both the raw values recorded by the hardware and a processed version of those values. Processed values do not include forms of bias that might adversely affect how you use that data. For example, a processed accelerometer value reflects only the acceleration caused by the user and not the acceleration caused by gravity.
### 重要注意事项
An iOS app linked on or after iOS 10.0 must include usage description keys in its Info.plist file for the types of data it needs. Failure to include these keys will cause the app to crash. To access motion and fitness data specifically, it must include NSMotionUsageDescription.
