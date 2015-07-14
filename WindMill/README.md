## 1.First things first: Lets set up your Bluemix accounts!
      http://ace.ng.bluemix.net
  This will take care of your Sign Up and Log In into the Bluemix portal.


## 2.Get to know our App

### What is our App?
Wind is common and renewable source of energy. With the global growth of wind energy industry, if we can optimize the the production of energy with Internet of things, we can optimize and increase the production of energy. We have used the internet of things to develop a prototypre which can optimize the production of energy usind Wind energy.

### The app requires Internet of Things boilerplate and DashDB service from Bluemix. Internet of things boilerplate use Node-Red

A quick introduction to [Node-RED] (http://nodered.org/) would be handy. Nevertheless, we can pick the skills on the go.

## 3.Lets get started
####  Set up the Node-RED boilerplate and DashDB service
  *  Login to your Bluemix account.
  What you see here is the list of your Applications and Services in Bluemix. We are going to create a Internet of Things boilerplate application and bind a DashDB service to this application.

*Now, a Boilerplate can be imagined as a bundled Application with relevant bound Services for a particular targeted usage to get up and running quickly.*    

  * In the upper menu bar, go to __CATALOG__.
  
*This page lists all kinds of different boilerplates, runtimes and services that are offered by Bluemix. Browsing through this page can give you an idea about all the exciting features offered by Bluemix.*

* From the Boilerplates section, select the _Internet of Things_ starter boilerplate.

Here you can see the SDK for Node.JS and Cloudant No SQL Service that come as a part of the Internet of Things boilerplate. For our app, we are not going to use these bundled services. Instead we will bind our own DashDB service.

* Provide a unique name to the app on the right side of the page and click __CREATE__.
* In a couple of minutes, your application will be staging and ready to run.

*You will land up on the 'Start coding with Internet of Things' page. The instructions on this page are to get familiar with Cloud Foundry command line interface to control your application. You can go through the steps and try them out at leisure. We won't be needing that for our app right now.*

* On the left panel, click on __Overview__. This is the overview of your Application showing the link to go to the App, status of the app, instances, memory and the services bound to it.
* We want to bind the DashDB service to the App. Lets click on the ADD A SERVICE OR API button.
* Search for DashDB in the search tab or select the dashDB service in the Big Data section.
* In the right hand side panel, the App name would be pre-filled and the service name would be randomly generated. The selected plan should be defaulted to Entry plan. Click CREATE.
* The App would be required to RESTAGE. Your DashDB service is now bound with the Node-RED App and it should show up on the App Overview page.
