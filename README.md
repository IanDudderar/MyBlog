# MyBlog

### HW0: Indroduction
Hello! My name is Ian and this is my first time using GitHub. Hopefully by the end of this course I will be much more familiar with it.

***

### HW1:
Attributes of good software include acceptability, dependability and securty, efficiency, and maintainability. This ensures that the software will be understandable to the users and the machines they may use, as well as be secure and not cause major damage in case of failure. It should also not waste resources and should be created so that it can be changed and upkept along with the changing needs of customers. Other attributes that may be useful could be that is it small and does not take up excess space, cost effective, accurate and performs the task at hand, and be written so that others may understand the code.

I think depending on what the software engineer is being asked to perform, a license could be required. However I think there are many jobs and uses where something as official as a license, like a doctor, would seem excessive. The book states that engineers cannot be perfectionists, and following that logic I don't think you can create a licensed standard. However, if something is being designed with extremely dangerous or secure info some sort of a license could be required.

ACM/IEEE clause examples
Public- Workers should not use their knowledge to bypass or leak information of the general public.
Client and Employer- Engineers spend their time working to achieve the standards and requirements set by the persons contracting the software.
Product- Software engineered to detect or diagnose an illness for example must be at the highest standards to achieve it works properly.
Judgement- Engineers must not be bias or alter a project for own self-gain.
Management- A team of individuals needs to be managed appropriately to ensure that projects are completed accurately.
Profession- Persons should not pursue or program software that may be used for malicious intent and cause harm to the image of the company.
Colleagues- Lots of projects are group efforts and you must support and encourage those around you to create a positive work environment.
Self- One can only improve if they notice their own flaws and practice their craft.

Working on a system of this magnitude creates obvious moral conflict due to the privacy invasion that comes with it. Going further, the development of this type of system can and will lead to the development of further systems which are even more morally incorrect. What the software is being used for may not even be the issue, but one must also consider what the program is capable of being used for. One may argue that the invasion of privacy is necessary to prevent terrorism, and while in a vacuum this could be correct, the posibility of the technology being used for other things besides terrorist prevention is very clear and possible.

***

### HW3: Reliability

All of the architectural styles that support fault tolerance are diverse. This is so that the errors they may encounter will not be similar. It helps to have each portion of the system developed by different people so that a groupthink issue does not occur. This could be further implemented by requiring different tools and IDEs, different algorithms, and even different languages. To take it a step further one could develop specifications individually and define them in different language as well.

Using N-version programming for a control software such as radiation therapy does not sound like a great idea to me. Perhaps this is an unrealistic method of thinking but I would hope these machines are already designed to be as accurate and cautious as possible. In my eyes taking the time and energy to create something one time while performing it more seriously can result in better results than creating something multiple times in a less serious manner. In other words I feel that as N increases the chance for error may also increase.

If exceptions to not get handled properly, errors in the code will result in the program to halt. In other words any errors may completely shut down any program or website or tool that is being used. This doesn't sound very high availability to me. To prevent this we use exception handling to receive and process any error that my occur, and handle it in the code, so that the rest of the program can continue running, even if this specific piece must be paused or restarted with different inputs.

If for some reason the train manages to reach speeds over the max speed, possibly due to downhill travel, the software must apply the brakes to lower the speed.
If the train is at accelerating, and it reaches its max speed, the software much take over the throttle and halt any further acceleration.
If the train is heading down a single path and the light is red, software must bring the train must come to a stop.
If the train is heading down multiple paths and has the option to follow a path that is red and one that is not, the software must guide the train down the non-red path.
If the light indicator is not red and the speed is not over the speed limit, the conductor should have control over the trains speed and direction if necessary.

***

### HW4: Accidents and Failures
Consider the FBI's Sentinel project. The FBI wanted to make information more readily accessible in order to prevent further attacks such as 9/11. By replacing paper files with digital ones, they could create a virtual case file and perform their jobs more efficiently. The only issue is that such a simple and comprehensible idea is not always an easy technical fix. The series of articles documents the trials and tribulations of the Bureau over a span of almost ten years! Trying to combat the challenges of inefficient budget combined with the misjudged time frame, they seemed to miscalculate on so many levels. In a rapidly growing industry of technology, these delays can sometimes result in completely wasted projects, as things progress, and requirements and technical abilities grow. The FBI managed to make an eventual comeback, celebrating the eventual release of their Sentinel, despite the many bumps encountered along the way. Not to be outdone, however, the up-and-running Sentinel did not go as planned and required many expensive fixes and adjustments. The roller coaster of feelings in the entire tale is quite intriguing. 

When you combine the Sentinel saga with the other articles on security and failures, some things start to become clearer. Things will fail. This is inevitable, and while failure should not be aimed for, it should be recognized. Project planning is very important and requires diligence and adequate time. Poor planning and project management will greatly contribute to the rapid downfall of an idea. While it is important to be prepared, it is also absolutely essential to realize that not everything can actually be planned out, and you must prepare for things to not go as planned. No matter how precisely the work is planned things can and will go wrong, and workers must be able to quickly understand and adjust these issues as things move along. This must be achieved on a deeper level so that the systemic factors are recognized. Systemic factors investigate not just the issue at hand, but further into WHY such an error was made in the first place. It is dire essential that these are realized so that future infractions will be prevented, instead of just patched after recognition, as frequently by this time irreversible damage has already been done. To build on this further, the resilience of the project must be considered so that when issues are encountered all is not completely lost, similar to the Apollo 13 mission.

On top of everything else, the only true way to check for issues is to actually test for them. Teams must adequately test their programs throughout the entire process, not just at the end. Tests need to be thorough and include any and all possibilities of inputs. This becomes even more important when you consider the security aspects of certain designs. If an application such as online banking has not been actively certified it is left more vulnerable to outside attacks. Not only is this compromising to the users in that their data has been breached, but it can also reduce the availability of the system, generating even larger issues. If something has to be taken offline so that it can be repaired, user access is limited or even halted, and in the example of online banking, people may be temporarily locked out of their accounts if such a thing has not been planned for or tested against.


***

### HW5: Requirements
4.5 Gas Pump Requirements-The pump must contain the desired fuel. The credit card reader must determine if the user has the appropriate funds in his or her bank account. The pump must be able to measure fuel quantity that is being dispensed. The pump must be able to calculate the cost based on the price and amount dispensed. It should then have access to the users account so that the money can be deducted. The pump must stop dispensing fuel when the price cap has been reached. The machine must also return the users card after use.

ATM Requirements- The ATM must contain cash in enough different bills to output specific numbers. The ATM must be able to read a users card and determine if the code is correct. The ATM must be able to ensure the user has sufficient funds in his or her account, and subtract the amount withdrawn once dispensed. The machine must also return the users card after use. The ATM machine should include some sort of alarm security system.

Internet Banking Requirements- Must be secure and only accessible via username and password. It must be able to access any accounts being used through the bank and view current funds. When funds are transferred it must correctly calculate to add to the new account and subtract from the other account. No amount larger than what is currently in an account may be transferred.

4.6 It seems as though often times non-functional requirements are implemented to increase the usability or efficiency of the functional requirements. Because of this I feel that many non-functional requirements could be grouped under the functional requirement that they support. This could take place on a web database or spreadsheet, or in a larger system if one is used for requirements change management. As the requirements changed during development these things could be edited and updated.

4.7 Some use cases for ATM-  Goal: To withdraw money  Steps: Insert card, enter appropriate pin number, select amount to be withdrawn, remove money, remove card.    Goal: To steal money Steps: attempt to break the machine, ATM alarm goes off and alerts the police.     Goal: Withdraw more money than in account   Steps: Enter card, enter proper pin, attempt to enter amount larger than account contains, ATM machine should reject offer and return card.      Goal: User a stolen debit card  Steps: Enter card to machine, try to enter correct pin but fail, ATM should inform user of the incorrect pin and return the card. 

The articles for today seem to focus heavily on proper testing and adaquate requirements of a system. They also reinforce the idea of being able to adapt and keep up with any developing changes along the way. For instance, managing project requirement change through a structure of requirements change management is very important to systematically lay out the developments and how they are progressing. It is important that these are managed and written down properly. One should not simply try to remember the mutating requirements as they are changed, as one can only hold so much information in short term memory, as suggested by the "Magical Number Seven" principle.
As specifications are adapted, tests must also follow suit. Previous requirements may be thoroughly tested by test cases, but newer test cases must be ran to ensure emerging rsystem requirements are also met. By documenting and managing the requirements it makes it structured and easier to program and run test cases on each one, ensuring that the development of the project encounters as few hiccups as possible.
