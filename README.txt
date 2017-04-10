GuideMii
Easy way to see the world

My final project will be about giving users a chance to explore more of their world when on a vacation or road trip. When traveling I always aim to see more than just the well-established locations and high traffic sights such as Grand Canyon, Space needle or the Washington monument. To find some of these places you have rely on word of mouth. This web app will make the process easier and more complete by sourcing data from APIs like google, Government accounts, or maybe even crowd sourced info. The final product will be a route with all the POIs (points of interest) that you have chosen to visit and gives you a one button link to a complete google map route you can start at any time.
The front page will have simple UI of a start point endpoint form, option section to filter out POIs leaving you a more tailored POI list, interactive map section that shows the current route as is, and a div to display matching POIs along your route that you can click and visually see the updated map route to match the selected POIs.
User pages will get show a small info page, much like Facebook, about who they are, maybe a section of where they have visited and links to their current desired routes. POIS get a page that contain basic info on the location and user pictures from the specific location & more. The User database will house basic user info as well as tie ins for Facebook and google id info to later populate the map with their friends so long as they are in along the desired route. Routes that are saved for each user - these routes will be form fitted to the google maps API so a simple touch will launch a google maps API and guide you with their help.
Pictures are saved on each Users entity and shared via a location tag in
simple format: would be to allow user to tie the picture to a location themselves,
complicated version: I want the submitted photo to be scanned and EXIF data to place the photo in the right location and then scrub the data clean so that it won’t have any residual personal data.
POIs will show up in a small row of the webpage that will scroll from displaying the ones closest to the starting point these are simply grabbed from an API and not stored anywhere, until the point where the POIs becomes popular and then the data is stored into a table.

POIs table:	data from a wiki || visitor log ||pictures if any found ||user reviews ||and if a place / location has bad reviews the POI might be deleted from showing up at all.

These are starting points for the project all input will be much appreciated and encouraged when entering the team.

 I will need these roles filled:
Front-end developer:
use the google map API to display an easy to use map for start and end-point information. Create templates for POIs once they become popular. Create user profile template if they choose to create one.
Back-end developer:
use the API as needed to populate the front end. Create end points to allow users to see their routes in a clickable format that sends the user out to google maps with all the waypoints placed in there. hold user info.
Security architect:
work towards Facebook and google authentication login||keep user info secure to include photos and user personal info || find a way to use and then scrub EXIF data once submitted|| if not able to use Facebook or google to authenticate use a regular and login password.
