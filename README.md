# olympics

The final project is a program that displays the medal winners in several sports in a Winter Olympics. A GUI will list the sports, and when the user selects one, it will display the medal winners for that sport. It uses a file to store the data, writes to it with new data, and reads from it for all data

![olympics](https://github.com/bell-kevin/olympics/blob/main/olympics.PNG)

There are 2 major categories of events – timed and scored. In a scored event, like figure skating, the highest score wins. In a timed event, like speed skating, the lowest time wins. Your project must handle both scored and timed events, sorting the scores appropriately to identify the medal winners. Note that there MUST be sorting in the project, using a sorting algorithm you add to the code -- do not use a sorting method in the library. Do not store the data already sorted.

Create 4 events, 2 scored and 2 times, with 5 competitors in each event. You only need the names of the competitors, plus their score/time, no other details. Create a file that contains the data for those 4 events -- pre-load it with the competitors and their scores/times by typing the data into a file, which will be read into the program. Make sure the data is not in sorted order.

The project must allow the user to create a fifth event, specify if it is timed or scored, and enter the name and the 5 competitors with times/scores in that new event. The input process for the data for the new event can use the console, or it can be part of the GUI for displaying the winners, or it can be a separate GUI program, your choice. In all cases, the data for the new event must be written to the same file with the other four events.

Create a GUI to display the medal winners in the selected event. List the events in a combo box where the user selects one. For the chosen event, display the medals and winners, in order – gold, silver, bronze. Only display the 3 winners, not all of the competitors in the event.

Carefully check the rubric, make sure you have addressed all the elements listed.

As this is a project to measure your competency, you must do this work on your own. You may ask the instructors for clarification. This is not a team project or a collaborative effort, the code and logic must be yours alone.

Submission

Submit the root folder for the final project. If it doesn’t run on the instructor’s computer, it will be graded with a zero.

Note the following rubric for submissions of this project, which will be included in the final grade.

The maximum score for a perfect project submitted on the first try is 200 points. Remember that you need 80% or 160 points to pass. Anything between those values of 160 and 200 is still passing. Be aware of the time you have left to work on this project -- don't work on perfection to the point that you run out of time.

== We're Using GitHub Under Protest ==

This project is currently hosted on GitHub.  This is not ideal; GitHub is a
proprietary, trade-secret system that is not Free and Open Souce Software
(FOSS).  We are deeply concerned about using a proprietary system like GitHub
to develop our FOSS project. I have a [website](https://bellKevin.me) where the
project contributors are actively discussing how we can move away from GitHub
in the long term.  We urge you to read about the [Give up GitHub](https://GiveUpGitHub.org) campaign 
from [the Software Freedom Conservancy](https://sfconservancy.org) to understand some of the reasons why GitHub is not 
a good place to host FOSS projects.

If you are a contributor who personally has already quit using GitHub, please
email me at **bellKevin@pm.me** for how to send us contributions without
using GitHub directly.

Any use of this project's code by GitHub Copilot, past or present, is done
without our permission.  We do not consent to GitHub's use of this project's
code in Copilot.

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/img/GiveUpGitHub.png)
