# SmartTube install guide
  
- (**easiest**) Search for "AFTV news" from your Android TV Play Store, open it and enter [**28544**](https://aftv.news/28544)
- install a file transfer app on your Android TV, download the APK on your phone or computer and transfer it to your TV (e.g. [_Send Files to TV_](https://sendfilestotv.app/) from the Google Play Store / Amazon AppStore)
- download the APK onto a USB stick, put the USB stick into your TV and use a file manager app from the Google Play Store / Amazon AppStore (e.g. [_FX File Explorer_](https://play.google.com/store/apps/details?id=nextapp.fx) or [_X-plore_](https://play.google.com/store/apps/details?id=com.lonelycatgames.Xplore)). Android's preinstalled file manager does not work! Do **not** get the ad-infested _FileCommander_.
- if you are an advanced user, you can install it using ADB. [guide](https://fossbytes.com/side-load-apps-android-tv/#h-how-to-sideload-apps-on-your-android-tv-using-adb) | [alternative guide](https://www.aftvnews.com/sideload/)

**The app has a built-in updater** with changelog. You can also find all releases and the **changelog** on the [Telegram channel @SmartTubeNewsEN](https://t.me/s/SmartTubeNewsEN) (readable without account) or on [Github](https://github.com/yuliskov/SmartTube/releases/).
### Installation (Chromecast with Google TV)

On **Chromecast with Google TV**, installation of apps is blocked by default, so an extra step is required:

> **4.1. Enable Developer Options**
>
> On your Chromecast, open the side menu and go to _Settings > System > About_. Scroll down to the _Android TV OS build_ section and click that repeatedly. A toast message will appear, explaining that you are a few steps away from being a developer. Continue clicking until you trigger it.
>
>
> **4.2. Turn on the "unknown sources" setting**
>
> Go back to the main _Settings_ page and select _Apps > Security & Restrictions > Unknown sources_. Turn on the toggle for \[_Downloader by AFTVnews_ or\] whichever file browser you decided to use [...].
>
> [[source & picture guide](https://www.androidpolice.com/2021/02/07/how-to-sideload-any-apk-on-the-chromecast-with-android-tv/#install-the-apk)]

After this, you can follow the [general installation guide](#installation) above.


### Installation (Xiaomi devices with Chinese firmware)

Xiaomi's **Chinese firmware** might block the installation **of the beta version**. The international firmware is not affected. Solutions:
1. use SmartTube's **stable version** instead (**recommended**)
2. use the international firmware for your device
3. (if your device is from 2020 or before) You can do a factory reset and then install SmartTube beta before doing any system updates. You can then safely update your system, SmartTube should continue working.


### Updating

The app has a built-in updater. You only need to follow the installation procedure **once**. A few seconds after launching SmartTube, it will notify you if there is any update and also show a changelog. You can disable automatic update checks or manually update in the settings under "about".

If the installation fails, either your **disk space is full** or the update didn't download correctly; clear up space and try updating again (_Settings > About > Check for updates_).
