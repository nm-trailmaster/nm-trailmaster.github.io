# Project Overview

### Team Roster
 
 * Austin Preston [GitHub](https://github.com/apreston26)
 
 * Curtis Chavez [GitHub](https://github.com/Curtis19-99?tab=repositories)
 
 * Jason Drake [GitHub](https://github.com/jdrake16)

### NM Trailmaster Summary 

A lot of New Mexicans can agree that the true beauty of this state is not found in Urban areas, but outside in nature. 
This app provides information on popular trails in ABQ (including parking options and the best times to visit said trails), It also provides information on some of the more popular camp sites in NM (including phone numbers to those in charge of maintaining these campsites, as well as a list of items you should bring when camping). 

NM Trailmaster is building a community of people who want to share their “sacred spots” with other nature-connoisseurs. Users will be able to upload photos and share coordinates to trails they would like to share with the community. NM Trailmaster is a gateway to many paths others have walked in our beatiful southwestern landscape.

### Overview 

Please be sure to read our short overview about our app NM TrailMasters [here](docs/pdf/overview.pdf)

### Summary of the Current State of the App

The app currently has a couple functionalities. It features a handful of trails and campsites that can be viewed by any user for informational purposes. The app also includes a feature that allows a verified user to post information on trails that they want to share with the community. Eventually users will be able to upload pictures with their trails but that functionality not yet in place.

##### Stretch goals/possible enhancements
      
 * Weather functions (to plan trips in advance).
 * Take the Trailmaster challenge and visit all the trails and campsites.
 * Camp log (for simple journal entries, notes).

# Functional Documentation

### Intended Users

* People that are looking for alternative ways to exercise.
	> As an introvert, I hate doing cardio in a gym environment. I need something to help me get active in a way that doesn’t give me social anxiety. Having access to many local trails will help keep me active without taking me out of my comfort zone.
* Broke students that want to find cheaper ways to entertain themselves.
	> As a college student, I’m often strapped for cash. I need a way to de-stress that won't brake the bank. Hiking is usually the best option and with the Trailmasters app I can easily find trails in my area.
* Adventurers that want to challenge themselves.
	> As a hiking enthusiast, I need a way to keep track of all the awesome trails I’ve blazed, so that I may share them and inspire others to participate in more wholesome recreational activities. The NM Trailmaster's community feed makes this a breeze.
 
### Functional Design 
 
 * [Wireframe](docs/wireframe.md)
 
 * [App Tour]()
 
### User Instructions

* Once the build instructions are followed, the app can now be ran.
* Once the app has built and downloaded to your phone or emulator we can begin to explore some of the finctionality of the app.
* The opening splash screen has a required Google sign in button. This is where you need to select the sign in button and sign in with any Google account to have the ability to gain access into the app.
* Once past the splash screen the user will see the large buttons and a small button at the top. The small button at the top right is to sign out of Google on the app.
* From the main screen with three buttons you have the option to go to trail, campsite, and community.
* Inside the Trails button you can click on the "ABQ Trails" button to go into preloaded trails. From here you can go into and read any trail information by clicking on it.
* Inside the Camping button you can click on the "Camping" button to go into preloaded campsites. From here you can go into and read any campsite information by clicking on it. You can also click on the "Essentials" button to read all information inside.
* Inside the Community button you can click on the "Bulletin Board" button. This will take you to a screen where other posted trails will be located. You can post to the bulletin board by pressing the button with the plus sign located in the bottom right. From here it will give you an option to put the Name of Trail, Description of Trail, Latitude of Trail, Longitude of Trail, and slide the rating scroll bar. Just click ok to post. Side note you cannot post a trail until all of the fields are filled out.

# Technical Documentation 

### Technical Design 

* [Entity Relationship Diagram](docs/erd.md)

* [DDL](https://github.com/nm-trailmaster/trailmaster-service/blob/master/docs/ddl.md)

### Outlines of Technology Stacks

Back end 

* Spring , Hibernate, Apache Derby, Room, Gson, SQLite, Digital Ocean for server hosting

Front end

* Android operating system, Android libraries, Retrofit, ReactiveX, Google Sign In
 
### REST Service Endpoint Documentation 

To learn how to use all of our server endpoints please see the form [here](docs/endpoints.md)

### Build Instructions

* Clone repository using SSH key in the code pull down menu from https://github.com/nm-trailmaster/nm-trailmaster.github.io.

* Import the project into IntelliJ using SHH key (git@github.com:nm-trailmaster/nm-trailmaster.github.io.git).

* Build project and run application.

## Implementation 

* [Server Implementation](https://github.com/nm-trailmaster/trailmaster-service/tree/master/src/main/java/edu/cnm/deepdive/trailmasterservice)

* [Android Implementation](https://github.com/nm-trailmaster/nm-trailmaster-app/tree/master/app/src/main/java/edu/cnm/deepdive/trailmaster)

# Copyright & Licence Information 
 
 To see all of the technologies used and their copyrighted information please visit our [Copyrights and Licenses Info](docs/copyrightsAndLicenses.md)
