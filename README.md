# Android-Documentation-Easter-Eggs
Compilation of easter eggs found in the Android Documentation

- [isUserAGoat()](#isuseragoat)
- [isUserAMonkey()](#isuseramonkey)
- [LIKE TRANSACTION](#like_transaction)
- [TWEET TRANSACTION](#tweet_transaction)
- [GRAVITY_DEATH_STAR_I](#gravity_death_star_i)
- [GRAVITY_THE_ISLAND](#gravity_the_island)
- [Log.wtf()](#logwtf)



## [isUserAGoat()](https://developer.android.com/reference/android/os/UserManager.html#isUserAGoat())
   _Used to determine whether the user making this call is subject to teleportations._

## [isUserAMonkey()](https://developer.android.com/reference/android/app/ActivityManager.html#isUserAMonkey())
   _Returns "true" if the user interface is currently being messed with by a monkey._
   
## [LIKE_TRANSACTION](https://developer.android.com/reference/android/os/IBinder.html#LIKE_TRANSACTION)
   _IBinder protocol transaction code: tell an app asynchronously that the caller likes it. The app is responsible for incrementing and maintaining its own like counter, and may display this value to the user to indicate the quality of the app. This is an optional command that applications do not need to handle, so the default implementation is to do nothing._
   
   _There is no response returned and nothing about the system will be functionally affected by it, but it will improve the app's self-esteem._
   
## [TWEET_TRANSACTION](https://developer.android.com/reference/android/os/IBinder.html#TWEET_TRANSACTION)
   _IBinder protocol transaction code: send a tweet to the target object. The data in the parcel is intended to be delivered to a shared messaging service associated with the object; it can be anything, as long as it is not more than 130 UTF-8 characters to conservatively fit within common messaging services. As part of HONEYCOMB_MR2, all Binder objects are expected to support this protocol for fully integrated tweeting across the platform. To support older code, the default implementation logs the tweet to the main log as a simple emulation of broadcasting it publicly over the Internet._

   _Also, upon completing the dispatch, the object must make a cup of tea, return it to the caller, and exclaim "jolly good message old boy!"._
   
## [GRAVITY_DEATH_STAR_I](https://developer.android.com/reference/android/hardware/SensorManager.html#GRAVITY_DEATH_STAR_I)
   _Gravity (estimate) on the first Death Star in Empire units (m/s^2)_
   
## [GRAVITY_THE_ISLAND](https://developer.android.com/reference/android/hardware/SensorManager.html#GRAVITY_THE_ISLAND)
   _Gravity on the island_

   _Constant Value: 4.815162_
   
## [Log.wtf()](https://developer.android.com/reference/android/util/Log#wtf(java.lang.String,%20java.lang.String))
   _What a Terrible Failure: Report a condition that should never happen. The error will always be logged at level ASSERT with the call stack. Depending on system configuration, a report may be added to the DropBoxManager and/or the process may be terminated immediately with an error dialog._
