
# Social Media Interaction Element for SmartPhone Application
 
Overall system will pull the following information from SIS:

- User (ex. dss4121 would be mine)
- User's class schedule
- Class Cancellations (may need to implement a course cancellation notification in SIS, or parse from emails using a prefix in subject line.)
- Class locations (room number, building)
 
User can then give profile information for the following services:

- Facebook - To determine which RIT students are in user's social circle
- Foursquare - Areas of campus will be on foursquare, giving ability to check in and comment on areas of campus.
 
System will pull information from Yelp for:

- Names of retail and food service places on campus
- Rating and description of retail and food service places on campus.
 
The map itself will contain:

- Map of campus
- References for the interior maps of buildings when user enters a building
- Floor plan for each level of building
- Map of tunnel system under RIT
 
Use Case (Assuming that user has input relevant info for Facebook, Foursquare, SIS)
 
User will have a GPS blip on a map of campus And Number and letter labels on all buildings, On the right, there is a slider, used for zoom when outdoors, and to move between floors when indoors. When GPS location implies user has entered a building, or user has tapped building on map, user is prompted (ex. "You just entered GOL Building 40, yes - no") to determine if application should load interior map.
 
On the upper left is a red or green button with text reading "Social" When social is disabled (default) users can see nearby areas with star ratings from Yelp Areas that show up can be filtered by type (food, retail, entertainment etc.)
 
When social is enabled, User can see the same nearby locations, filtered the same way. In social version it will show locations of friends if they have checked in anywhere with foursquare. Also, the descriptions of each area will be determined by the current mayor of that area in foursquare. All the foursquare competition (for mayorship etc.) should be among students only, not all of foursquare. The comments and ratings of other students will be accessible by tapping a location. Comments from people that may be in user's social circle are prioritised first. Yelp data will be used in social mode if a location has no student-input information on a location.
 
System is able to handle the dynamic nature of a user's social circle, which areas user frequents, suggestions based on users with similar taste, events on campus user may be interested in, and future games/events (eg. system could conceivably be played with for a special capture the flag mode, or use foursquare or possibly twitter messages for communication in a game like Humans vs. Zombies, maybe at a certain hour every day, GPS blips of all remaining players appear to everyone, features that add to the gameplay. These are just dumb ideas of events that might use our system as a platform, not something that we should worry about including.) A system that can be used for future games/events, in other words.

A simple “quickest path to x” mode should be available in either mode, as well as “path to x without going outdoors” for winter.
