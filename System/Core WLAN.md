# Core WLAN
### Query AirPort interfaces and choose wireless networks.
## 概述
The CoreWLAN framework provides APIs for querying AirPort interfaces and choosing networks.

You access the Wi-Fi subsystem by working with a CWWiFiClient instance. This client object provides methods to obtain a handle on all of the system's Wi-Fi interfaces, represented by CWInterface objects. You can also use the client to register to receive Wi-Fi event notifications. You assign a delegate conforming to the CWEventDelegate protocol to process these notifications.

Because creating the client object is resource intensive, it's usually best to work with a single object over the life of your app rather than creating a series of short lived instances. For convenience, the client class defines a shared instance singleton that you can use for this purpose.

You can use the CoreWLAN framework in an app that adopts App Sandbox without any special exceptions as long as you use the interface objects vended from a client instance. If you initialize interface objects directly, you incur low level system socket accesses that are not considered sandbox safe. 
