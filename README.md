# Docs

ResearchSuite is an extension of the ResearchKit(iOS) and ResearchStack(Android) open source frameworks for developing research study apps, which allow for researchers to easily develop intuitive and standardized data-collecting mobile apps. 

ResearchSuite was built on top of ResearchKit/ResearchStack and extends the available surveys to include adaptable visual assessments and custom active tasks and supports integration of various backend modules.

In general terms, the structure of a ResearchSuite app is defined by a JSON file, which specifies the survey or active task steps to be instantiated by the app. The JSON file is converted into an array of Step objects, which the application uses to create a Task using the ResearchSuite Task Builder, which it presents to the research participant. The results of the task are handled by the ResearchSuite Results Processor, which includes modules for storing the results locally and emailing them to researcher, sending them to the Ohmage-Omh study manager, or sending them to a custom server.


### **iOS**
***

* **ResearchKit documentation:** [http://researchkit.org/docs/index.html](http://researchkit.org/docs/index.html)

* **Available iOS demo projects:**

### **Android**
***
* **ResearchStack documentation:** [http://researchstack.org/#documentation](http://researchstack.org/#documentation)

* **Available Android demo projects using ResearchSuite:**
