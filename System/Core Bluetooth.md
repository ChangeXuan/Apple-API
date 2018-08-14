# Core Bluetooth
### Communicate with Bluetooth 4.0 low-energy devices.
## 概述
The Core Bluetooth framework provides the classes needed for your apps to communicate with devices that are equipped with Bluetooth low energy wireless technology.

Do not subclass any of the classes of the Core Bluetooth framework. Overriding these classes is unsupported and results in undefined behavior.
### 重要事项
An iOS app linked on or after iOS 10.0 must include in its Info.plist file the usage description keys for the types of data it needs to access or it will crash. To access Bluetooth peripheral data specifically, it must include NSBluetoothPeripheralUsageDescription.
