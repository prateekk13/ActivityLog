# ActivityLog



Technical LOG


Criteria = If it needs licensing, Simplicity, Offline ease of use, Cost-effectiveness, How complex is the setup process? Data storage limitation.


Date: 13th March 2024
Time: 2:35pm
•	Description: Meeting with the team where we discussed about the updated problem statement which got approved.


Time: 11:34pm 
•	Description: Studied my problem Statement

Time: 11:53 pm

•	Description: The first web app I use is Avenza maps
o	 Avenza Maps is an offline mobile application that is available for both Android and iOS. We can import our maps, download maps from the map store, and can use the maps offline. The maps download is downloaded in pdf format. Despite being offline, have good GPS Tech.

 
Interface
•	Not open source
•	licensing = both free and paid
•	Cost- effectiveness = There is a free version of it available where there are many options for offline maps. It includes some paid maps too which start from 6.99 to 79.99 dollars. 
•	Setup = Setup is quite easy. Download the app from the app store and download the map you want from the app store which is there in the application. 
•	Data storage – As it needs to download the map first from its store it occupies some storage. The map is starting from a few kilobytes to a few megabytes. 


Date: 15th March 2024
Time: 3:01pm

Maps.me = I needed something where I could use WiFi to do my initial download and then be able to mark places and keep track of them for later use, all while hiking, driving, or just sitting around waiting. Downloadable chunks of maps, turn-by-turn navigation, labeling favorite locations, searching for public restrooms, and following trails.
Maps.me is a free mobile application with a ton of features. It does not require an account to do any of the things mentioned above, and it also doesn't display ads.
Advantages: Click on any point to save that place and put your marker. Gooogle maps is good but doesn’t give small details (in rural areas). Some small places, narrow streets may not be available in google maps, but it does here. 
	Does not need camera, contacts, microphone permission (in iOS).
	Can mark any place and can go to that place later.
Disadvantages: Ask for permission in android.
	Not fully free.


Date: 18th March 2024
Time: 1:01pm
Description:

Field maps –
About:
•	ArcGIS Field maps combines data collection, map viewing, and location tracking into a single app that is easy to use and simple to deploy. 
•	To Collect data – blue add button
•	When collecting data, you can select a feature template and add info by filling out smart forms.
•	The overflow menu is where you can change the basemap, access bookmarks, view your map legend and measure between points on the map.
•	Layers menu is where you can see all layers, toggle on/off. 
•	This apps also supports working indoors.
•	Viewing a web map or mobile app package that contains facilities and levels will show a floor picking tool that appears when a building is in the view.
•	Choosing a floor filters the features in that facility based on their vertical order.
•	The field map also allows us to sketch and add markers to map with markups.
•	Can add labels.
•	Markup is saved as a layer in the device.
•	Also supports location tracking.
•	While working offline, we can use this app to create a map area that allows us to view assets and collect data while working offline.


Procedure:
	Login to AGOL (ArcGIS Online) using Fleming credentials.
	Go to the 9 dots after logging in.
Choose Field Map designer.



 
Choose Field Map designer.


Select “New Map” option.
 
Figure:

Create layer and I gave ‘Pkalshan-Trial’ as my layer name. 
 
Figure:

We can choose between these 3-layer type. In this case I chose point layer. 
 
Figure:


I created one more layer named ‘PKalshan_Trial1’ and chose the layer type same as before. 
 
Figure:
•	I need high accuracy and elevation values as well which is denoted by z.
•	M-values are used to measure the distance along a line feature from a vertex (a known location) to an event.
•	Turn On all 3 layers/options

 


•	Give your map a suitable title and click on ‘Create Map’
 

 
Interface

•	These are the layers which I am going to use.
 

•	Then I added a few layers which I shared to ArcGIS Online created in another course.

 

Next step is adding a Geofence. We can add Geofence if we want to.
Setting up geofences allows you to automatically deliver important information to mobile workers based on their location. For example, you may want to let mobile workers know when they’re entering hazardous terrain or restricted areas.
You may also want to control when location sharing is enabled based on where mobile workers are located. For example, you may only want to view the location of mobile workers when they enter a specific work zone or company property.

 

Then I created a new Geofence which I named as ‘Hazardous Area’ to restrict the people or to warn them not to enter in the restricted area.



 

Adding Message is very necessary otherwise it wont let to move ahead.



Buffer is the thing which will create a boundary or an area in which a worker should not be enter if we have created a buffer which is devoted to the restricted area.
 


See the difference between the buffer area giving.



 
100m buffer
 
10000meter buffer
 

We will go with 10000 meters for now which is --  

 
Message is necessary

 
Sync is must

Only then offline can be on

 


 

 

ONE MORE TIME

 


 


 







