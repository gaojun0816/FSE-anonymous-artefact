# List of Artefacts

This is a list of artefacts for our paper:
> Borrowing Your Enemy’s Arrows: the Case of Code Reuse in Android via Direct Inter-app Code Invocation
which is published on FSE 2020.

## The Tool
### DICIDer

DICIDer is a tool takes as input an Android APK file and outputs a list of DICI 
paths that trace how direct inter-app code invocations are planned in the analyzed app.
  * The source code of this tool can be found at: <https://github.com/gaojun0816/code_access_finder>
  * The tool requires the source of [Soot](https://github.com/Sable/soot) and [FlowDroid](https://github.com/secure-software-engineering/FlowDroid) to be add as required projects on the build path.

## Proof of Concept Apps
### StealthApp

This app performs a malicious behavior to leak the IMEI of a device to the out
of the world via SMS.
It utilizes functions of 2 benign apps to achieve obtaining IMEI number and sending
SMS respectively instead of implementing these functions itself.
In this way, it hides its malicious behaviors.
  * The source code of this app can be found at: <https://github.com/gaojun0816/stealthapp>
  * The required 2 benign apps are: [com.globalcanofworms.android.simpleweatheralert](https://drive.google.com/file/d/1p5506ipovDz5U67emR_6D2VgO4TyWdpF/view?usp=sharing) and [org.communicorpbulgaria.bgradio](https://drive.google.com/file/d/19ORelAxTMX6yHuyAiLU7qIOZc5ItTeO-/view?usp=sharing) respectively. they also can be downloaded from [AndroZoo](https://androzoo.uni.lu/) with SHA256: 7E8365752A1AEE0F15E65E3D5A7A56B691E208880545987DEEA493B35965F3D5 and 3754F46387F856CE4398790B7F3CA62F5E62EE41DD8DBDD47C3B9EC4B393F578 respectively.

### TikTokDownloader

This app plagiarizes the "signature" algorithm implemented in TikTok by using DICI
to achieve downloading videos from their server which is blocked by TikTok normally.
  * The source code of this app can be found at: <https://github.com/gaojun0816/TikTokDownloader>
  * The required TikTok app is: [musical-ly-7-3-0.apk](https://drive.google.com/file/d/15vBWULM9SSBDUkwMLASg4OoVVNY-mziN/view?usp=sharing).





