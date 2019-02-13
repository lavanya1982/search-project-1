# search-project-1
search project 1


* Make sure you have these installed::

1.node.js

2.git 

3.gulp

Clone this repository into your local machine using the terminal (mac) or Gitbash (PC) > git clone https://github.com/lavanya1982/search-project-1

CD to the folder cd search-project-1

Run > npm install to install the project dependencies

Install gulp.js via the Mac terminal or Gitbash on a PC > npm install -g gulp

Run the Gulp command > gulp

Fire up your browser at http://localhost:8000


Running unit tests:

Run "ng test" to execute the unit tests via Karma.

Here is one way of test case.

What it does:

1.Creates the component

2.Loads the list of names from mongoDB or from JSON

3.Finds the name based on search query

4.Displays the name with the letter whatever you searched. (Makes sure that the letter or name should exists in your list)


_____________________________________________________________________________________________________________________________
Sno.	          Scenario	                                           Expected Result
_____________________________________________________________________________________________________________________________
1.     User taps on Search bar	                                The cursor should be visible on the screen 
2.     User types any character and taps on search               The matching data should get filtered (Refer to Image 2)
3.     User types any character  and taps on search	           Search should be on the basis of the matching sequence and 
                                                                    not the  initial  characters. It should be like search
                                                                   
4.     User types any character in any of the ways                 Search should not be case sensitive
       eg. ‘lavanya’ or ‘Lavanya’ or ‘LAVANYA’ and 
       taps on search   

5.     User types any character and no matching data               User should be notified about it .message to be shown  as 
                                                                   ‘No data found’  
                                                   
6.     User searches data offline                                  Enabled

7.     If user searches with blank field                           No change should occur on the screen

8.     User clears the search field after  to page again           The filter should get reset

9.     Verify response time of search                              The search results should be quick

10.    Click on one item                                           Should navigate to BioData page


