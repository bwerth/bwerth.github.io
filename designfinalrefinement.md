## Final Design Refinement Brief

### Overview of Product

Meats By Dre developed an app to allow users who are blind to more easily navigate subway stations.
The app is specifically designed for the Park Street station, but could easily be altered for any station.
Users can activate the app in a subway station and select a subway line.
The app will then guide then safely to the correct platform using directional audio cues.
A more detailed description of the app is contained in the [Design Refinement Brief](designrefinement.md).

### Final Adjustments

Over the course of this project we have not only iteratively developed a solution, but we have iteratively developed our problem. We believe that our solution is exciting and impactful because it effectively solves a problem that is seriously affecting visually-impaired people everywhere. The documentation we have developed up to this point suggests that this kind of solution, even for a problem as specific as the one we have chosen to solve will make a significant difference in the comfort and safety of blind people in the face of transportation.

After creating the basic app Meats by Dre tested several versions of the app.
They focused on improving the instructions that the app provides the user. The first iteration lacked comprehensive instructions that covered all of the features available to the user, so new instructions were added. 
AB testing revealed that adding detail and reordering parts of the instructions improved the performance of the users tested.
A detailed report on the findings of the formal usability study is available in the [Formal Usability Test Brief](formal_usability.md).

### Analysis of Original Goals

In the initial design proposal, detailed in the [Design Brief](designbrief.md), the team identifies several objectives any successful design would need to fulfill.
They require the app to:

* Orient the user in the space so that they know where they are and where everything is
* Reduce the amount of time spent navigating the station
* Reduce the stress and anxiety involved around using public transportation
* Not involve the use of a touch screen. One of our sources spoke at length about the inconveniences associated with touch screens, which are not accessible by the blind
* Be inexpensive to use or implement
* Properly indicate the locations of the entrance, correct platform, the bathroom, and the exit
* Be applicable to a specific problem faced by people who are blind.
 
The app achieves the majority of these goals. Only one of the initial goals is not satisfied, specifically avoiding the use of a touch screen.
After further user studies the team found that the dislike for touch screens was not a shared priority among the interviewed users.
This finding led the team to prioritize other goals.
The team designed metrics for the requirements, and evaluated the degree to which their solution succeeded in accomplishing them.
The requirements were given a score between one and five, with one corresponding to not achieving the gaol, and five to meeting or exceeding the goal set.


Goal | Explanation | Score
---- | ----------- | -----
Orient user | The app orients the user so that they can find important locations. However, the set of locations available is more restricted than originally hoped. | 4
Reduce time navigating | While further testing is needed to be certain of the efficacy of the app, current projections suggest that there will be a reduction in time spent. | 3
Reduce stress | The app will help reduce stress. A larger scale test will be required before the degree to which this helps can be accurately measured. | 3
No touch screen | This was rejected as a priority during design, and a touch screen was used. | 1
Be inexpensive | The app leverages tools already possessed by the user, so their is no cost beyond the cost to download the app. | 5
Find entrance, platforms, bathroom, exit | The app is only capable of finding the platforms, though it could readily be extended to find other locations | 2
Be applicable to a specific prblem | The app addresses a very specific problem, that of navigation the Park Street station. | 5


Meats By Dre feels that their product adequately addresses the majority of the original criteria they set.
They consider the app a success, and feel that with a few minor changes it would prove a helpful tool.


### Areas of Opportunity

There are some elements of the app which still require further testing and development prior to full-scale deployment.
User safety is a core design requirement, and while Meats By Dre has designed their app to ensure the safety of their users, there is still further testing required.
Care has been taken to design the app so that its failure modes do not place its users in danger.
In particular the feature requiring users to request guidance means that a failure to provide a direction cannot be mistaken for instructions to continue in a straight line.
Despite the team's careful design, they feel it would be irresponsible to deploy the app without extensive testing in realistic environments.

Another area for potential growth is the system of providing directions to users.
The app currently uses auditory cues to guide users, but in a loud station this may not be practical.
The team is currently investigating the use of tactile cues, but implementing them remains a work in progress.

An additional need is for a reliable emergency stop cue.
It is vital that the system is able to provide a warning if the user is too close to the tracks, or is some other danger. We want to effectively ensure that our users feel safe in the subway system because above all else, they should not be concerned that they are at risk in any way for not being able to see.

Also, if we were to continue with this project, we would want to perform further development and testing with our physical prototype. As we have discussed in this report and over the course of the project, it is a challenge to present a prototype that effectively simulates the experience and even as we moved closer and closer to an effective prototype in our final refinement phase, we felt this was a weakness. We would be very excited in the future to perform full usability tests with vibrating wristbands to see how effectively the experience we have largely developed through simulation on the computer translates to the real world with the kind of physical prototype that would actually be used in the subway.

Finally, we belive a weakness of our process is the fact that we did not have a chance to more thoroughly iterate on our designs with visually-impaired people. As we noticed in testing with fellow designers and students at Olin during our formal usability test, someone who is blind views the world very differently from someone who is not. There are certain parts of our design such as the manual query for directions that we believe the visually-impaired would appreciate more than students who are imagining what it must be like to be blind. With this said, we believe there is significant value in testing designs with other user experience designers because there are types of feedback that we know we would not have gotten from non-designers. For example, some of the feedback we received on the controls of the wireframe as well as instructions were very pointed and useful because the person testing had a mind for user experience design enough to be able to provide very specific and pointed feedback. 

Despite these concerns the app achieves its intended purpose, and with some additional development could be made into a useful tool for users who are blind.

### Effort Chart


 Person | Contributions 
 ------ | -------------------------------------
Henry   | Ideation<br>Coded app<br> 
Bryan   | Formal usability study<br>Wrote text for formal usability study<br>Ideation<br>Website Design<br>Wrote text for report<br>
Camille | Ideation<br>Formal usability study<br>Wrote text for formal usability study<br>
Noah    | Ideation<br>Wrote text for report<br>

## [Homepage](index.md)
