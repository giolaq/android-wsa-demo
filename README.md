AADevs aka Amazon Appstore Devs
=============================

<img src="https://github.com/giolaq/AADevs/blob/main/gifs/aadevsui.gif" width="640" height="336" />

This is a sample Android App that you can use to test [Amazon Appstore for Windows 11](https://developer.amazon.com/apps-and-games/appstore-on-windows-11)
and [Windows Subsystem for Android](https://learn.microsoft.com/en-us/windows/android/wsa/).

It contains some best practices and shows that many features [Ex. Notifications] are supported with no need of special code refactoring.

The UI is based on Jetpack Compose and follow the guidelines for supporting large screens in your app

AADevs retrieves the first 20 Videos of our [Amazon Appstore Developers Youtube Channel](https://www.youtube.com/c/AmazonAppstoreDevelopers). To decode the feed
from our Youtube Channel it uses the library available here https://github.com/prof18/YoutubeParser .


## 💻 Building AADevs App

First, clone the repo:

`git clone git@github.com:giolaq/AADevs.git`

Next, you will need an api key to be used by the YoutubeParser library to retrieve the feed:

* Create the Browser API Key following the instructions here https://cloud.google.com/docs/authentication/api-keys?hl=en&visit_id=638007358010576297-2547601963&rd=1#creating-browser-api-keys
* Put your Broswer API Key in your local.properties file in the root of your project

```

youtube_key="Your Browser API Key"

```

After this you can build and test the project.

You can open the project with Android Studio and run the app on Windows 11 connecting the WSA to Android Studio. For more info you can follow the instructions here:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/z_ehadkRyzY/0.jpg)](https://www.youtube.com/watch?v=z_ehadkRyzY)


## Using the Sample App

On Windows 11 you can resize the window of the app and see how it reacts to the dimensions changes.
If you go to the Notifications section, you can launch some notifications and see how they are perfectly integrated into the notification
system on Windows 11.

<img src="https://github.com/giolaq/AADevs/blob/main/gifs/notifications.gif" width="640" height="484" />
