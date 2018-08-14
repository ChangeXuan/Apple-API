# Core Telephony
### Access information about a user's cellular service provider, such as its unique identifier and whether it allows VoIP. Get the identifier and status of a current call.
## 概述
Use the Core Telephony framework to obtain information about a user’s home cellular service provider—that is, the provider with whom the user has an account. Carriers can use this information to write applications that provide services only for their own subscribers. You can also use this framework to obtain information about current cellular calls.

A CTCarrier object gives you information about the user’s cellular service provider, such as whether it allows use of VoIP (Voice over Internet Protocol) on its network. A CTCall object gives you information about a current call, including a unique identifier and state information—dialing, incoming, connected, or disconnected.
