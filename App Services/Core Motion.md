# Core Motion
### 处理有关加速度计，陀螺仪，计步器和环境相关的传感器的事件。
## 概述
Core Motion从板载的硬件中获取iOS的移动和环境相关的数据信息，
可以从以下设备获取相关的信息：加速度计，陀螺仪，计步器，磁力计，气压计。
你可以使用这个框架，并可以把硬件生成的数据信息合理的使用到你的应用中。
例如，一个游戏可能会使用到加速度计和陀螺仪数据来控制屏幕已达到控制游戏的行为
这个框架中的许多数据服务能够让你去访问到硬件信息的原始数据，当然，你也可以访问到已经被处理过的数据。
获取到的被处理过的数据不会包括那些影响你作出行为的数据。
例如，一个经过处理的加速度的数据仅仅是从用户那产生的，而不是由重力影响产生的。
