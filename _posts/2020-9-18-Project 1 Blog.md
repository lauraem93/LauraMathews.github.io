
## Purpose of the Project ##
This viginette creates functions to access two hockey data APIs and a final function that can retrieve data from either API. After creating the functions, they are used to retrieve data from the APIs and an exploratory data analysis is done on some of the data available in the APIs. There were no significant findings from the data analysis done in this project.

## Project Link ##

[Project 1](https://lauraem93.github.io/Project1/)

## Process of Creating the Viginette ##
This project required a lot of planning ahead. I found it very helpful to plan out on paper how I would approach creating the functions rather than just jumping right into the programming. There were a lot of little pieces to keep up with and add to the project. Even creating a broad plan first, it was difficult to figure out how to add something in if I found I had forgotten to include it (such as the ability to access the data from team name or id number). I had to be very careful to not mess up the rest of the work that had already been done in the function. I could have been more organized with creating the functions and would make sure I had all of the pieces I needed planned out first. Looking back I also would have created the url differently in my functions. For each modifier, filter, teamID, etc. specified, I created the url immediately after manipulating the user input. It may have been more efficient to manipulate the different pieces and save them and then at the end of the function create a url that puts all of the pieces together.

The most difficult part of the project was including the ability for the user to specify a team name or id number. I probably did not use the most efficient method for this step. I had trouble figuring out how to get R to recognize an id number as a number and not a character when it was given in a string in the function call. I was able to use the grepl() function to fix this problem. I also struggled a bit with getting it to github because I have never used github before.

My biggest take away for future projects is create a detailed plan before starting the programming. It is also helpful to start early and work on it every day. This project was not something that could have been done in one night.
