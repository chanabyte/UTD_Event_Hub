
1. README.txt - Describes every file in the folder for easy navigation and understanding
===================================================================

Files Breakdown:
===============

1. README.txt                     - this file
2. Previous Reports               - all reports submitted till now without modification
   |
   +- Project Proposal.pdf
   +- Project Requirements Doc.pdf
   +- Project Deliverable 1
	        |
                +- Future Plans.pdf
                +- Individual Contributions.pdf
                +- Technical Documentation.pdf
                +- User Documentation.pdf
3. UTD Events Hub PPT.pptx
4. Final Report.pdf               - the final report with all the information requested for 
5. source_code                    - includes all the code to run the program, including assets and images
6. data_collection                - includes the code required to be run to procure data
   |
   +- Instagram_Scraper_Code.py     
   +- scraper.py             
   +- Instagram_Scraper_Results   
   +- all_image_links.csv         
   +- Organization Folders         
   +- events.csv                  
   +- events.json                  
   +- Text_For_JSON_1.py           
   +- Text_For_JSON_2.py           
   +- Output_Results_1.json       
   +- Output_Results_with_links_and_org.json 
   +- Main.py  
7. Unit Testing
8. Integration Testing




HOW TO USE
===========

This project is built using React and displays event data scraped from the UTD calendar
Follow the steps below to run the app locally:

Prerequisites:
--------------
1. Node.js installed (https://nodejs.org/)
   To check if they are installed, run these commands in the terminal
      
      node -v
      npm -v
   
   If version numbers appear, your environment is ready

2. A code editor like Visual Studio Code (not required buy recommended)


Step-by-Step Instructions:
--------------------------

1. Unzip the project folder ('utd-event-hub.zip') to any location on your computer.

2. Open a terminal in the root project folder ('utd-event-hub'). It should look like this in the terminal:

   C:/.../utd-event-hub              - /utd-event-hub/src is the path to find App.js

3. Install all required dependencies:

   npm install

4. Start the development server:

   npm start

5. Your default browser will open automatically at:

   http://localhost:3000

6. You should see the UTD Event Hub homepage showing event cards, grouped by date, with filters and search functionality.


Notes:
------
- Event data is stored in 'src/events.json'
- You can test the functionality by searching, filtering by time, department, or location

