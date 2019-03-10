# Parking-App-UI-UX
This contains wire-frames for an android app used to find parking spots in our university.
I used the Balsamiq software for designing the wireframes.
All the wireframes are in .png format.
This also contains a video to show how all the wireframes are connected to each other to make one smooth user experience.
Video is compressed into "ParkOne-Designs.rar".
Now i will name all the wireframes in the order they appear to the user and try to explain the functionalities of each one.

1. Home tab : This is the first tab user see after opening the application. It gives the user to choose from two option buttons
              named "2 wheeler" or "4 wheeler" depending on what the user is looking for. The home tab also offers existing users
              the link to login and new users a link to sign up tab of the application.
2. Nav Bar  : This is the navigation bar which helps user to move through the application from the home tab itself. The navigation
              bar contains links to the bookinng tab, login/sign up, 2 wheelers tab, 4 wheelers tab, Location and help.
3. Login tab : This gives user different options to create an account or log in itno an existing one. This tab contains options 
               for users to directly link their facebook account or google account or create an account using email address or phone
               number.
4. 2 wheeler tab : This is the tab which will user go to when they click the "2 wheeler" button on the home tab. This tab contains
                   a dashboard which contains 4 tab buttons named "available" "booked" "handicap" "faculty". There's a search bar on
                   the top which can be used by user to search for specific locations around the university campus. 
                   This tab also contains a google maps API integrated which shows the exact points of parking spots on the map in the
                   form of small markings. so for example a student wants to find parking spot near Gate numer 3, So the student will
                   search Gate no. 3 in the search bar, and all the parking spots around gate number 3 will be shown on the map.
                   If a student clicks on a marking on the map that marking will take user to another tab named "spot details", which 
                   will let the student know about all the details related to that specific parking spot which that marking on the map
                   represents.
5. Available tab : This tab is generated when any user clicks on the "available" button in the dashboard in "2 wheeler app". This tab
                   enables user to know how many parking spots are available near it's location.
6. Booked tab : This tab is generated when any user clicks on the "booked" button in the dashboard in "2 wheeler app". This tab
                enables user to know how many parking spots are already booked near it's location.
7. Handicap tab : This tab is generated when any user clicks on the "handicap" button in the dashboard in "2 wheeler app". This tab
                   enables user to know how many parking spots are reserved for handicapped people near it's location.
8. Faculty tab : This tab is generated when any user clicks on the "faculty" button in the dashboard in "2 wheeler app". This tab
                 enables user to know how many parking spots are available near it's location which are reserved for the faculties of                    the college.
9. Spot Details tab : This tab is generated when an user clicks on the markings of the map which shows the near by parking spots, this                         tab gives the details about the specific parking spot, details include exact "Location" of the spot,"Availability"                       of the spot wether the spot is available or not, "Timing" which tells the user about the time span in which the                         spot is available, "Tariff" on the spot if any, "Security" which lets the user know how safe that spot is,                               "Vehicle type" which tells the user what that spot is for, 2 wheeler or 4 wheeler, "Help" which gives the user                           necessary contact information of the spot operator. This tab also contains the "Book" button which user can click                       on if they want to book a parking spot
10. Book tab : This tab will give an alert box message to the user saying if they really want to book that spot or not, and that alert                  box will have two optins of yes or no, if the user clicks yes then the spot will be booked and it will take the user to                  "spot booked" tab, if the user clicks no then the the alert box will disappear.
11. Spot Booked tab : This tab will give confirmation to the user after there spot is successfully booked. This tab will also contain                         two links, one will give the user details about the spot and take them back to the "spot details" tab, second link                       will take the user to the google maps app and give user the exact directions of the spot.
