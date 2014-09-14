Pinafly Location Based Service App

Our goal is to develop an Android app which interacts with strategically placed beacons in order to learn more about the environment via public participation.
The concept is for Pinafly to be a platform for researchers to upload projects of things that they are interested in observing or monitoring in a specific area in hopes of obtaining quality crowdsourced data. 
The app will be able to detect the beacon, translate the unique identifier that the beacon transmits, and prompt the app user that they are within the beacon range. 
Once the user agrees to participate, the user will be able to submit a photograph and textual input, which will be directed to storage within a spreadsheet or database, so that the project-creator can have exclusive access to the data.  

Phases 1 - 4:
The first phase deals with beacon - app interactions. Researchers will place beacons in designated areas according to projects. Our first step must be to program the app to detect and translate the individual beacon’s unique identifier. Code for this is available and may be borrowed from https://github.com/Estimote/Android-SDK.
The app will alert those with the app on their device whenever they are within range of a beacon by triggering a push notification stating that the user is within range.

The second stage consists of the user responding to the prompt to collect a specific data point in a specified way. The data collection form on the app will focus on submittal of a photograph, entering one or a few true/false fields, and will also include a text box for any additional comments or observations.
The user will then submit the data (which will also automatically include the coordinates, date, and time) that s/he has collected via the app. The data will be directed into a spreadsheet or database which is only accessible by the researcher who initially uploaded the project.

The third phase will incorporate “egoboo” so that the user will have incentive to submit data via this app. Our idea is to use a lightning bug as the Pinafly logo, assigning each user a bug to represent them. 
The idea is that the more data points submitted via this app, the brighter the lightning bug’s bulb will become. Once the user submits data, the app will also prompt a pop-up to read “Great job! You’ve earned one point!” and the bulb of the lightning bug will become brighter or change color.

Phase 4 is still under consideration, but it potentially would consist of creating an administrative user interface which researchers would use to create these projects for Pinafly. This may be out of the scope for this course. 
