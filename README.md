# List of Artefacts

This is a list of artefacts for FSE 2020 Anonymous Review.
The relevant GitHub repos are also provided with anonymized links.

## StealthApp

This app performs a malicious behavior to leak the IMEI of a device to the out
of the world via SMS.
It utilizes functions of 2 benign apps to achieve obtaining IMEI number and sending
SMS respectively instead of implementing these functions itself.
In this way, it hides its malicious behaviors.
  * The source code of this app can be found at: <https://anonymous.4open.science/r/c5ecc1b3-90dd-47c0-b622-a797d7768666/>
  * The required 2 benign apps are: com.globalcanofworms.android.simpleweatheralert and org.communicorpbulgaria. bgradio respectively. Out of anonymous review consideration, shortcut links to download these 2 apps will be revealed later. But they also can be downloaded from [AndroZoo](https://androzoo.uni.lu/) with SHA256: 7E8365752A1AEE0F15E65E3D5A7A56B691E208880545987DEEA493B35965F3D5 and 3754F46387F856CE4398790B7F3CA62F5E62EE41DD8DBDD47C3B9EC4B393F578 respectively.

## TikTokDownloader

This app plagiarizes the "signature" algorithm implemented in TikTok by using DICI
to achieve downloading videos from their server which is blocked by TikTok normally.
  * The source code of this app can be found at: <https://github.com/gaojun0816/tiktok_stealer>
  * The required TikTok app is: musical-ly-7-3-0.apk. Out of anonymous review consideration, the link to download this app will be provided later.

## DICIDer

DICIDer is a tool takes as input an Android APK file and outputs a list of DICI 
paths that trace how direct inter-app code invocations are planned in the analyzed app.
  * The source code of this tool can be found at: <https://anonymous.4open.science/r/d6b67f88-341d-4696-881d-39ea08329b13/>
  * The tool requires the source of [Soot](https://github.com/Sable/soot) and [FlowDroid](https://github.com/secure-software-engineering/FlowDroid) to be add as required projects on the build path.




