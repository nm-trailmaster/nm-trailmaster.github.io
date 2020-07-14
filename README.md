## NM Trailmaster Summary 

A lot of New Mexicans can agree that the true beauty of this state is not found in Urban areas, but outside in nature. This app provides information on popular trails in ABQ (including parking options and the best times to visit said trails), It also provides information on some of the more popular camp sites in NM (including phone numbers to those in charge of maintaining these campsites, as well as a list of items you should bring when camping) and most importantly it is building a community of people who want to share their “sacred spots” with other nature-connoisseurs. Users will be able to upload photos and share coordinates to trails they would like to share with the community. NM Trailmaster is a gateway to many paths others have walked in our beatiful southwestern landscape.

## Intended Users

* People that are looking for alternative ways to exercise.
	> As an introvert, I hate doing cardio in a gym environment, I need something to help me get active in a way that doesn’t give me social anxiety. Having access to many local trails will help keep me active without taking me out of my comfort zone.
* Broke students that want to find cheaper ways to entertain themselves.
	> As a college student, I’m often strapped for cash. I need a way to de-stress that won't brake the bank. Hiking is usually the best option and with the Trailmasters app I can easily find trails in my area.
* Adventurers that want to challenge themselves.
	> As a hiking enthusiast, I need a way to keep track of all the awesome trails I’ve blazed, so that I may share them and inspire others to participate in more wholesome recreational activities. The NM Trailmaster's community feed makes this a breeze.
 
## Client component

* Functionality 
	* Browse a list of trails and campsites that have clear directions and pictures to create a stress-less outing.
	* Document your own favorite spots (with photos and pinpoints).
	* Never forget a thing again with our CampMasters essentials guide.
* Persistent data 
	* User photo galleries. 
	* Stored campsite coordinates.
* Device/external services
	* Navigational system
	* Camera

## Server component/External Services

* Functionality 
	* Post to our Trailmasters Community feed. 
	* Message your fellow Trailmasters to find the best spots!
* Persistent data
	* Liked posts
	* Messages
* External Services 
    * [Google Sign In API](https://developers.google.com/identity/sign-in/web/sign-in) (To allow users to post to our community feed.)
    * [Google Maps API](https://developers.google.com/maps/documentation/android-sdk/intro) (To allow users to save coordinates and guide them to destinations.)
    * Access to camera (To allow users to upload photos)

### Stretch goals/possible enhancements

* Weather functions (to plan trips in advance).
* Take the Trailmaster challenge and visit all the trails and campsites.
* Camp log (for simple journal entries, notes).

## Implementation 

* Server Implementation
    * [Entity](https://github.com/nm-trailmaster/trailmaster-service/tree/master/src/main/java/edu/cnm/deepdive/trailmasterservice/model/entity)
    * [Controller](https://github.com/nm-trailmaster/trailmaster-service/tree/master/src/main/java/edu/cnm/deepdive/trailmasterservice/controller)
    * [Service](https://github.com/nm-trailmaster/trailmaster-service/tree/master/src/main/java/edu/cnm/deepdive/trailmasterservice/service)

## Design documentation

* [Entity Relationship Diagram](docs/erd.md)

* [Wireframe](docs/wireframe.md)