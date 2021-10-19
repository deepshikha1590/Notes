Mobile Testing
--------
Most critical factor that we have to consider while doing test planning is checking the **Mobile Application type.** There are mostly three types of mobile applications: Mobile Web, Native App, and Hybrid App. The classification is based on the development efforts and App redistribution strategy.


* **Mobile Web(Web App)** -Web apps are not real application, they are websites that open in our smartphones with the help of a web browser.

Mobile websites have the largest audience.
 
Example: Tutorials point

Benefits : 
* **Easy access**
* **Easy development** : Developing responsive design and restructuring the content to be properly displayed on a smaller screen/hardware will make any desktop website mobile friendly.
* **Easy update ** Just update in one location and all the users automatically have access to the latest version of the site.
*  No installation required, as compared to native or hybrid app.

Downside :
*  Mobile websites cannot use some of the features. For example, access to the file system and local resources isn’t available in websites.
*  Users won’t have the app’s icon on their home screen as a constant reminder. The website needs to be opened in a web browser only.


**Native App** - A native app is developed specifically for one platform. It can be installed through an application store (such as Google Play Store or Apple’s App Store).

Example − Whatsapp.

Benefits −

*  Native Apps live on the device and are accessed through icons on the device home screen.

*  They can take full advantage of all the device features − they can use the camera, the GPS, the list of contacts, and so on. 

*  Native apps can use the device’s notification system and can work offline.

*  Publishers can make use of push-notifications, alerting users every time a new piece of content is published or when their attention is required.

*  Native Apps maintain UI design of each operating system, thus they offer the best user experience. For example, a Native App can have a left-aligned header in Android and a center-aligned header in iOS.

Downside −

*  High cost for building the app : Native apps developed for one platform will not run on another platform. An App built for Android will not run on iOS. We need to build a different App altogether for iOS. Because of this reason, we need to maintain multiple versions of the App.

*  Even though you might publish native Apps, you’ll want to keep the mobile website well maintained, as mobile brings more traffic. So maintenance is higher.


**Hybrid App**
They can be well described as a mixture of Web App and Native App.

Example - Wikipedia.

Benefits −

*  Developing a Hybrid App is cheaper than developing a Native App. It can be built for cross-platforms, i.e., reduced cost for App development.

*  Maintenance is simple, as there are not many versions to be maintained.

*  It can be found in the App Store, which makes the distribution easy.

* It has a browser embedded within the app only.

Downside −

*  Graphics are less accustomed with the operating system as compared to Native Apps.

*  Hybrid Apps are slower than Native Apps.

----------------------------------------------------------------------------------------------------------------

**Simulators and Emulators**
-----------------------------
These are primarily software programs designed to provide simulation for important features of a smartphone. They are very similar in nature, so sometimes, they are used interchangeably.

****A simulator/emulator cannot mimic the following features −

* Mobile device battery
* Mobile device’s camera
* Difficult to mimic interruptions like incoming calls and SMS.
* Not so much realistic simulation for mobile device memory usage.


Note***Best practice indicates that, while actual development is in progress, we should use an emulator or a simulator. Before finalizing the product, there should be a sanity check with chosen real devices. For example, there is a huge number of Android smartphone users, so the smart choice is to have a sanity check for the latest Android device and regression can be conducted over simulators.
