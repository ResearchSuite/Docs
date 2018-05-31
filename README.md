# Introduction

ResearchSuite is an extension of the ResearchKit(iOS) and ResearchStack(Android) open source frameworks for developing research study apps, which allow for researchers to easily develop intuitive and standardized data-collecting mobile apps. 

ResearchSuite was built on top of ResearchKit/ResearchStack and extends the available surveys to include adaptable visual assessments and custom active tasks and supports integration of various backend modules.

In general terms, the structure of a ResearchSuite app is defined by a JSON file, which specifies the survey or active task steps to be instantiated by the app. The JSON file is converted into an array of Step objects, which the application uses to create a Task using the ResearchSuite Task Builder, which it presents to the research participant. The results of the task are handled by the ResearchSuite Results Processor, which includes modules for storing the results locally and emailing them to researcher, sending them to the Ohmage-Omh study manager, or sending them to a custom server.

<img src="https://github.com/ResearchSuite/Docs/blob/master/rs-diagram.png?raw=true" width="500">

### **ResearchSuite SDL-Rx Survey Tasks ([iOS](https://github.com/ResearchSuite/sdl-rkx),[Android](https://github.com/ResearchSuite/sdl-rsx))**
***

* **Demographic Task**

  <img src="https://github.com/ResearchSuite/Docs/blob/master/demography.png?raw=true" width="500">

* **Notification Task**

  <img src="https://github.com/ResearchSuite/Docs/blob/master/notification.png?raw=true" width="500">

* **AVA YADL Full Assessment Task**

  <img src="https://github.com/ResearchSuite/Docs/blob/master/yadlfull.png?raw=true" width="500">

* **AVA YADL Spot Assessment Task**

  <img src="https://github.com/ResearchSuite/Docs/blob/master/yadlspot.png?raw=true" width="500">
 
* **AVA PAM Task**

  <img src="https://github.com/ResearchSuite/Docs/blob/master/pam.png?raw=true" width="200">

* **Geofencing Task**

  <img src="https://github.com/ResearchSuite/Docs/blob/master/geofence.png?raw=true" width="200">


***
### **iOS**


* **ResearchKit documentation:** [http://researchkit.org/docs/index.html](http://researchkit.org/docs/index.html)

* **Getting Started:**
  * [iOS ResearchSuite Demo](https://github.com/ResearchSuite/ResearchSuite-Demo-iOS)
  

* **Other available iOS demo projects:**
  * [AVA YADL Reference App - iOS](https://github.com/ResearchSuite/AVA-YADL-iOS) - generates a YADL survey and stores the results on your iOS device
  * [AVA MEDL Reference App - iOS](https://github.com/ResearchSuite/AVA-MEDL-iOS)  - generates a MEDL survey and stores the results on your iOS device
  * [AVA PAM Reference App - iOS](https://github.com/ResearchSuite/AVA-PAM-iOS) - generates a PAM survey and stores the results on your iOS device

***
### **Android**

* **ResearchStack documentation:** [http://researchstack.org/#documentation](http://researchstack.org/#documentation)

* **Getting Started:**
  * [Android ResearchSuite Demo](https://github.com/ResearchSuite/ResearchSuite-Demo-Android)
  * [Step-by-step tutorial](https://docs.google.com/presentation/d/1k43p1Y1f3kubWCeWUIBFi3kLVN8gWFoHozA9gBRrS2s/edit?usp=sharing)

* **Available Android demo projects:**
  * [AVA YADL Reference App - Android](https://github.com/ResearchSuite/AVA-YADL-Android) - generates a YADL survey and stores the results on your Android device
  * [AVA MEDL Reference App - Android](https://github.com/ResearchSuite/AVA-MEDL-Android) - generates a MEDL survey and stores the results on your Android device
  * [AVA PAM Reference App - Android](https://github.com/ResearchSuite/AVA-PAM-Android) - generates a PAM survey and stores the results on your Android device



