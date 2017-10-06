# Android-Documentation-Easter-Eggs
Compilation of easter eggs found in the Android Documentation

* [isUserAGoat()](https://developer.android.com/reference/android/os/UserManager.html#isUserAGoat())
   > Used to determine whether the user making this call is subject to teleportations.

* [isUserAMonkey()](https://developer.android.com/reference/android/app/ActivityManager.html#isUserAMonkey())
   > Returns "true" if the user interface is currently being messed with by a monkey.
   
* [LIKE_TRANSACTION](https://developer.android.com/reference/android/os/IBinder.html#LIKE_TRANSACTION)
   > IBinder protocol transaction code: tell an app asynchronously that the caller likes it. The app is responsible for incrementing and maintaining its own like counter, and may display this value to the user to indicate the quality of the app. This is an optional command that applications do not need to handle, so the default implementation is to do nothing.
   
   > There is no response returned and nothing about the system will be functionally affected by it, but it will improve the app's self-esteem.
   
* [TWEET_TRANSACTION](https://developer.android.com/reference/android/os/IBinder.html#TWEET_TRANSACTION)
   > IBinder protocol transaction code: send a tweet to the target object. The data in the parcel is intended to be delivered to a shared messaging service associated with the object; it can be anything, as long as it is not more than 130 UTF-8 characters to conservatively fit within common messaging services. As part of HONEYCOMB_MR2, all Binder objects are expected to support this protocol for fully integrated tweeting across the platform. To support older code, the default implementation logs the tweet to the main log as a simple emulation of broadcasting it publicly over the Internet.

   > Also, upon completing the dispatch, the object must make a cup of tea, return it to the caller, and exclaim "jolly good message old boy!".
   
