# HealthKit
### Share health and fitness data with other apps, while maintaining the user's privacy and control over their data.
## 概述
HealthKit stores data from apps on iPhone and Apple Watch. It also works directly with some health and fitness devices. In iOS 8.0, the system can automatically save data from compatible Bluetooth LE heart rate monitors. The system can also automatically import activity data from the M7 motion coprocessor, if available. Other devices and data sources must have a companion app that can access the data and save it to HealthKit for them.

HealthKit saves data in an encrypted database called the HealthKit store. You can access this database using the HKHealthStore class. Both iPhone and Apple Watch have their own HealthKit store. Health data is synced between Apple Watch and iPhone; however, old data is periodically purged from Apple Watch to save space. Use the earliestPermittedSampleDate() method to determine the age of the oldest sample on Apple Watch.

HealthKit is designed to manage data from a wide range of sources, automatically merging the data from different sources based on user’s preferences. Apps can also access the raw data for each source, merging the data themselves.

HealthKit provides an app to help manage the user’s health data. The Health app acts as the user’s interface to the HealthKit data. Users can view, add, delete, and otherwise manage all of their health and fitness data using this app. They can also edit the sharing permissions for each data type.

HealthKit and the Health app are unavailable on iPad.
