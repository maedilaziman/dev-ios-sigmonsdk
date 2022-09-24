# About
Sigmon SDK Development<br/>
<br/>
<br/>
To help you better understand how to install Sigmon SDK, please watch the video below
<br/>
<br/>
https://www.youtube.com/watch?v=44bI5ev9ASk
</br>
<br/>
<h2>Requirements</h2>
<ul>
<li>Mac OS Monterey 12.2.1</li>
<li>XCode 13.2.1</li>
<li>Swift 5.0</li>
</ul>
<h2>How To Install</h2>
<br/>
After donwload SigmonSDK.framework, please open your project and then add SigmonSDK.framework to your project like picture below.
<br/>
<img src="https://raw.githubusercontent.com/maedilaziman/dev-ios-sigmonsdk/master/Screenshots/IMG_01.png" width="200" />
<br/>
Once you have successfully add SigmonSDK.framework, select the project in the Project navigator, and then open the General tab, look at 'Frameworks, Libraries, and Embedded Content',
<br/>
please choose Embed Without Signing in the SigmonSDK.framework like picture below.
<br/>
<img src="https://raw.githubusercontent.com/maedilaziman/dev-ios-sigmonsdkp/master/Screenshots/IMG_02.png" width="200" />
<br/>
Select info.plist and add App Transport Security Settings until Privacy - Location When In Use Usage Description like picture below.
<br/>
<img src="https://raw.githubusercontent.com/maedilaziman/dev-ios-sigmonsdk/master/Screenshots/IMG_03.png" width="200" />
<br/>
You have successfully add SigmonSDK.framework to your project
<h2>How To Use</h2>
<br/>
Open your class UIViewController, then import SigmonSDK, in that class please implement protocol SMSDKMainSpeedTestComm like picture below.
<br/>
<img src="https://raw.githubusercontent.com/maedilaziman/dev-ios-sigmonsdk/master/Screenshots/IMG_04.png" width="200" />
<br/>
Declare SMSDKMainSpeedTestUI and SMSDKMainSpeedTestMainUI class like picture below.
<br/>
<img src="https://raw.githubusercontent.com/maedilaziman/dev-ios-sigmonsdk/master/Screenshots/IMG_05.png" width="200" />
<br/>
Initialize SMSDKMainSpeedTestUI and SMSDKMainSpeedTestMainUI class like picture below.
<br/>
<img src="https://raw.githubusercontent.com/maedilaziman/dev-ios-sigmonsdk/master/Screenshots/IMG_06.png" width="200" />
<br/>
After you have initialize SMSDKMainSpeedTestUI and SMSDKMainSpeedTestMainUI class, you can add startSpeedTest() action in your event. Like picture below.
startSpeedTest() method will return empty string if no error message.
<br/>
<img src="https://raw.githubusercontent.com/maedilaziman/dev-ios-sigmonsdk/master/Screenshots/IMG_07.png" width="200" />
<br/>
Note: before you access startSpeedTest() action, you have to initialize SMSDKMainSpeedTestUI and SMSDKMainSpeedTestMainUI class
<br/>