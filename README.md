WSA Android Demo
=============================

<img src="https://github.com/giolaq/AADevs/blob/main/gifs/aadevsui.gif" width="640" height="336" />

This is a sample Android App that showcases best practices for optimising for [Windows Subsystem for Android](https://learn.microsoft.com/en-us/windows/android/wsa/).

[Windows Subsystem for Android](https://learn.microsoft.com/en-us/windows/android/wsa/) can be installed on Windows 11 via the [Amazon Appstore](https://developer.amazon.com/apps-and-games/appstore-on-windows-11).

## ✅ Features

The app retrieves the first 20 Videos of our [Amazon Appstore Developers Youtube Channel](https://www.youtube.com/c/AmazonAppstoreDevelopers). This thanks to the library [YoutubeParser](https://github.com/prof18/YoutubeParser).

It shows how to :
- Implement A responsive UI with Jetpack Compose adapting to the app window resize
- Handle mouse events like hoovering or right click
- Handle special keyboard events like (CTRL-<Key>)
- Launch different Android notifications on Win11
- Check hardware features availabilities

## 💻 Building AADevs App

1. clone the repo:

`git clone git@github.com:giolaq/AADevs.git`

2. Create and an api key to be used by the YoutubeParser library to retrieve the feed:
  * Check here https://cloud.google.com/docs/authentication/api-keys?hl=en&visit_id=638007358010576297-2547601963&rd=1#creating-browser-api-keys
3. Put your Broswer API Key in your local.properties file in the root of your project

```

youtube_key="Your Browser API Key"

```

4. Open the project with Android Studio and run the app on Windows 11 connecting the WSA to Android Studio. For more info you can follow the instructions here:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/z_ehadkRyzY/0.jpg)](https://www.youtube.com/watch?v=z_ehadkRyzY)


## Using the Sample App

On Windows 11 you can resize the window of the app and see how it reacts to the dimensions changes.
If you go to the Notifications section, you can launch some notifications and see how they are perfectly integrated into the notification
system on Windows 11.

<img src="https://github.com/giolaq/AADevs/blob/main/gifs/notifications.gif" width="640" height="484" />
