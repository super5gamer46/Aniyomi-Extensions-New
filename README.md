# How to Update Your Aniyomi Extensions

(Tested for gogoanime and a few other extensions)

### Windows Requirements:
- A Windows Computer
- [APK Toolkit](https://xdaforums.com/t/tool-apk-toolkit-v1-2-windows.4572881)
- The extensions apk this can be obtained if you deleted the original apk file using an app such as APK Extractor
- A brain

### Android Requirements:
- An Android device
- [APK Explorer & Editor](https://github.com/apk-editor/APK-Explorer-Editor/releases) (This is paid on the playstore however you can find it free on the [GitHub page](https://github.com/apk-editor/APK-Explorer-Editor/releases))
- Skip To Android Instructions

### Windows Instructions
Step Zero: Open one of the extensions animes in webview and save the url that first pops up somewhere
Step One: Load the apk onto your computer (<--this can be done with a usb cable or through ftp) and open up APK Toolkit.
Step Two: Drag the apk to the bar right under the text "Select apk, xapk, jar file or decompiled, extracted directory"
Step Three: Click decompile and open the Decompiled directory where you stored APK Toolkit.
Step Four: Open the extensions folder you want to update then open the smali directory.
Step Five: There should be an eu directory in there open it then open the kanade then tachiyomi directory.
Step Six: If your app supports multiple languages there might be more directorys, if there are more directorys repeat these next 2 steps on each directory.
Step Seven: Open the folder with the same name as the extension. Then open the file thats named websitename.smali in notepad.
Step Eight: Do ctrl+f then type in the url you saved earlier. Turn on Wrap around. Replace all instances of the old url with the new url.
Step Nine: Close APK Toolkit if you still have it open. Open it again. Theres a folder icon near the bar you dragged the apk file to. Click it
Step Ten: Select the folder in Decompiled that matches the extension your updating.
Step Eleven: Click Compile. Open the Compiled folder, below the Decompiled folder
Step Tweleve: Uninstall the old extension in aniyomi.
Step Thirteen: Put the updated extension on your device and install it like a normal apk (Play Protect might say something about it not recognizing it this is normal.). It should install normally and make sure to trust the extension
Your Done!!!!!!!!!


### Android Instructions
Step One: Figure out which url the outdated extension is using. This shouldnt be too hard just open up the anime extension in webview and jot down the url somewhere.
Step Two: Open up APK Explorer and search for Aniyomi:
Step Three: Click on the extension you want to update
Step Four: Open these directories: classes.dex/eu/kanade/tachiyomi/animeextension/en/EXTENSIONNAME/
Step Five: locate the file called EXTENSION NAME.smali and open it
Step Six: Find the url in the wall of text that the extension lead to before. There might be multiple instances of this url.
Step Seven: Click the Save icon in the top left and save.
Step Eight: Hit the back arrow until you are out of all the folders.
(Optional) Step 8A: Open up AndroidManifest.xml and change the version from example 14.81 to 14.82
Step Nine: Click the hammer icon in the top left and click Build
Step Ten: Go to the apks section then hold down on the app and click "Save to Downloads"
Step Eleven: Uninstall the old app and then install the new apk. (Updating will not work. The first time you do this)
Step Twelve: Trust the new app in aniyomi and now you have succesfully updated your aniyomi app!
