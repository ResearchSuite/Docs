# Docs

ResearchSuite is an extension of the ResearchKit(iOS) and ResearchStack(Android) open source frameworks for developing research study apps, which allow for researchers to easily develop intuitive and standardized data-collecting mobile apps. 

ResearchSuite was built on top of ResearchKit/ResearchStack and extends the available surveys to include adaptable visual assessments and custom active tasks and supports integration of various backend modules.

In general terms, the structure of a ResearchSuite app is defined by a JSON file, which specifies the survey or active task steps to be instantiated by the app. The JSON file is converted into an array of Step objects, which the application uses to create a Task using the ResearchSuite Task Builder, which it presents to the research participant. The results of the task are handled by the ResearchSuite Results Processor, which includes modules for storing the results locally and emailing them to researcher, sending them to the Ohmage-Omh study manager, or sending them to a custom server.

### **ResearchSuite SDL-Rx Survey Tasks**
***

* AVA YADL Full Assessment Task
<img src="https://github.com/ResearchSuite/Docs/blob/master/yadlfull.png?raw=true" width="300">

* AVA YADL Spot Assessment Task
<img src="https://github.com/ResearchSuite/Docs/blob/master/yadlspot.png?raw=true" width="300">
 
* AVA PAM Task
<img src="https://github.com/ResearchSuite/Docs/blob/master/pam.png?raw=true" width="300">

* Geofencing Task
<img src="https://github.com/ResearchSuite/Docs/blob/master/geofence.png?raw=true" width="300">

* Demographic Task
<img src="https://github.com/ResearchSuite/Docs/blob/master/demography.png?raw=true" width="300">

* Notification Task
<img src="https://github.com/ResearchSuite/Docs/blob/master/notification.png?raw=true" width="300">





### **iOS**
***

* **ResearchKit documentation:** [http://researchkit.org/docs/index.html](http://researchkit.org/docs/index.html)

* **Getting Started:**
  * [iOS ResearchSuite Demo](https://github.com/ResearchSuite/ResearchSuite-Demo-iOS)
  

* **Other available iOS demo projects:**
  * [AVA MEDL Reference App](https://github.com/ResearchSuite/AVA-MEDL-iOS)
  * [AVA YADL Reference App](https://github.com/ResearchSuite/AVA-YADL-iOS)
  * [AVA PAM Reference App](https://github.com/ResearchSuite/AVA-PAM-iOS)

### **Android**
***
* **ResearchStack documentation:** [http://researchstack.org/#documentation](http://researchstack.org/#documentation)

* **Getting Started:**
  * [Android ResearchSuite Demo](https://github.com/ResearchSuite/ResearchSuite-Demo-Android)
  * [Step-by-step tutorial](https://docs.google.com/presentation/d/1k43p1Y1f3kubWCeWUIBFi3kLVN8gWFoHozA9gBRrS2s/edit?usp=sharing)

* **Available Android demo projects:**
  * [AVA YADL Reference App](https://github.com/ResearchSuite/AVA-YADL-Android)
  * [AVA MEDL Reference App](https://github.com/ResearchSuite/AVA-MEDL-Android)
  * [AVA PAM Reference App](https://github.com/ResearchSuite/AVA-PAM-Android)



