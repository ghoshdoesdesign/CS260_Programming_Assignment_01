# CS260_Programming_Assignment_01

In your first assignment you will:
Practice your web programming prototyping skills (HTML, CSS, Javascript, GitHub) by building a simple web app
Deploy, test, and debug your app locally (using a Node.js + Express server and your Chrome Developer Tools)
Document and showcase your app’s design and interactive features
You will build a personal transportation conversion app to accomplish these goals.
It's 2023 and there are many modes of personal transportation that can get you from point A to point B. The modern commuter may struggle to compare and choose from all of these options!
For this assignment, you'll be making an application which, given an input of a desired distance to travel and a type of personal transportation, the user is able to see how much time it will take to travel that distance using the selected type of transportation, as well as the equivalent amount of time using a different mode of transportation for comparison. More detailed instructions are below.
You will submit the assignment as a Design Report (PDF) featuring a short write-up,  the link to your GitHub repository containing your source code, screenshots and a short, narrated (or subtitled) video that showcases all of your app’s awesome interactive features.


Instructions
Follow this GitHub Classroom link to set up your repository with starter code. (New to GitHub, web development tools, or otherwise feeling lost? Follow this link for very detailed walkthrough set-up instructions, including tips on testing for mobile dimensions.)
Follow the instructions in the included README.md to set up your development environment and to deploy a local Node.js+Express server running with the starter code for your app. Make sure to track your code on GitHub and save your progress as you go.
Note: Using our GitHub classroom and starter code is optional - feel free to use your own set-up - as long as we are able to access your code via a GitHub repo link, and can run your code with little additional effort on our part. If our course staff can’t view it, they can’t grade it - following the given setup instructions is the most straightforward way to ensure we can access and grade your work. 

Application Functionality
Your application must have the following functionalities:
Distance to Time Conversion  - Allow a user to enter the type of personal electric transport listed in the table below (ones in red required) and a desired distance to travel. The user should see how much time it will take to complete their journey. For example: Traveling 8 miles using a Liftboard electric longboard will result in a 30 minute travel time (it travels at 16 mph).
Compare (at least) Two Options - The user should also be able to see and compare this result with the equivalent amount of time required to travel that distance for another personal transportation mode. For example: 4 miles on a Liftboard will take 15 minutes, which converts to roughly 12.6 minutes on a Onewheel (which travels at 19 mph). To clarify – this means select one mode and compare to any other single mode (one to one).  However, there is extra credit if you enable a way to communicate from one to all other modes. 

TYPE OF ELECTRIC TRANSPORT
SPEED
RANGE
Walking
3.1 MPH
30 miles
Boosted Mini S Board
18 MPH
7 miles
Evolve Bamboo GTR 2in1
24 MPH
31 miles
OneWheel XR
19 MPH
18 miles
MotoTec Skateboard
22 MPH
10 miles
Segway Ninebot S
 10 MPH
13 miles
Segway Ninebot S-PLUS
 12 MPH
22 miles
Razor Scooter
 18 MPH
15 miles
GeoBlade 500
 15 MPH
8 miles
Hovertrax Hoverboard
 9 MPH
6 miles


One possible way of achieving these goals is to break your application down in the following fashion:
The main view is the electric transport converter.
Provide an input field for entering a distance and a radio button to select the type of electric transport
Create a text element for showing the converted value (time to travel, given distance)
Provide a button that executes the calculation and updates the text with the converted value
This is not the only design, nor is it necessarily a brilliant design, for this transportation conversion application. You are free to design your own app provided that it has the functionality as enumerated above. There are numerous design opportunities to explore in this simple app!
Grading Criteria
Full credit (20 points) will be given if your web application runs, contains the functionality as detailed in the instructions, and your documentation (writeup, photos, video) is complete.
Up to 6 extra points will be granted if you implement the following additions / usability improvements (1 extra point for each). Note: these additional features must be present in your documentation for us to count them towards your grade!
Extra Credit Points
All The Transportion Modes - Support all transport types above, not just the ones in red, on the table.
Time to Distance Conversion - Allow a user to enter how much time they have. The user should be able to see how far they can travel on various transportation types. For example, if the user enter 5 minutes, they should see that they can travel  0.25 miles walking, 1.5 miles on a Booster Mini S, 2.1 miles on an Evolve Skateboard, etc.
✨ A E S T H E T I C ✨ - Provide improved visuals and/or aesthetic iconography.
Range Limitations - Provide a way to handle range limitations within the user interface.  For example, visual indication that a given user input distance is out of range of one or more specific transportation options.
Responsive Design - App design adapts for usability in both mobile and desktop dimensions. (Learn more about testing for responsive design with different screen dimensions here, or in the Detailed Set-Up Instructions Appendices!)
One-to-All Modes Comparison - Provide a way to set one transportation mode and communicate/visualize results in all other included transportation modes.
How to Submit Your Assignment
This project should be submitted as a Final Design Report in PDF format. While we won't be grading it this time, we will, in future assignments, take into consideration the overall visual design of this document –  so start thinking ahead to how you would like to present this material! 
Your Design Report should contain:
Your name
A title for your application
A title image (think portfolio cover photo) to represent the project
Text to describe the resulting app and how it works (from an interaction, not implementation, walkthrough.)
A link to the up-to-date GitHub repository containing your code
A series of still screenshots that describe the implemented interactions
A link to your documentation video, which should:
Be a non-private YouTube or Google drive video that staff can access
Show all implemented elements of interaction 
Is at most 60 seconds in length (or up to 90 seconds if you included extra credit elements.)
Include some narration and/or subtitles/title cards. 

Examples from Spring 2022 
(Note: these were made in Android Studio, and have all of the extra credit functionality included. Yours should be  implemented as a web app - and remember, how you design it is up to you!)
https://www.youtube.com/watch?v=MJSYLx8GwUE - by Mod Yensuang
I think this app is excellent (all the functionality, including extra credit, plus nice design, and a cool app name!) However, I feel that the video could have better presented the application’s interactions rather than its implementation. In other words, describe how the app works and show all of its features as if you were a designer showing the product to a user, not a CS160 student explaining how it was built to your professor.)
https://www.youtube.com/watch?v=p1OKrZ3eB-8  - by Esther Shin
