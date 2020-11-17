# MyBlog

### HW0: Indroduction
Hello! My name is Ian and this is my first time using GitHub. Hopefully by the end of this course I will be much more familiar with it.

***

### HW1: CHAPTER 1
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

Working on a system of this magnitude creates obvious moral conflict due to the privacy invasion that comes with it. Going further, the development of this type of system can and will lead to the development of further systems which are even more morally incorrect. What the software is being used for may not even be the issue, but one must also consider what the program is capable of being used for. One may argue that the invasion of privacy is necessary to prevent terrorism, and while in a vacuum this could be correct, the possibility of the technology being used for other things besides terrorist prevention is very clear and possible.

***

### HW2: Reflections on software engineering practices

As we sift through the various articles and documents revolving software engineering, one thing becomes overwhelmingly clear. There are no shortcuts to be taken or low-effort pay-offs in this field. You cannot make assumptions or expect things to get easier. The only way to ensure that the path laid out ahead of you will be as smooth as possible is to consider every possibility and prepare yourself for success. I loved the example in the Kode Vicious article about the guy frustrated with his management for wanting explanations on his bug fixes. I think his feelings towards the situation were completely normal. Who wants to have to explain every single thing they do? But the written article really reinforces the ideas that in programming you cannot make assumptions and you cannot take things for granted. Things must be perfectly laid out for everyone to understand and in an environment where things are based solely around logic, that logic must be step by step explained. This method of thinking is further branched into the other passages as well. The notion that minor things cannot be overlooked-because it’s the little things that make a difference. In fact, it is explicitly stated to not let small tasks get ahead of you-in this instance referring to merging and testing branches periodically as things continue to develop, instead of waiting until things pile up. No matter how insignificant a task may seem, when allowed to grow in number they can become daunting and confusing and end up taking more time and brainpower than necessary.

These seem like issues that may be encountered by a worker looking to make things easier. The silver bullet article brushes on other areas of computing and electronic development that have been able to make grand leaps in their technology and field of study, many of which allowed for accelerated work environments and learning. This does not appear to be the case with software engineering, and anyone who may we waiting for something of this nature to occur is simply out of luck. While other fields may have been fortunate enough to experience these jumps, software engineers will not, and therefore it is again important to reiterate the necessity to be diligent and patient and on top of things, instead of looking for a quick or easy way out. 


***

### HW3: Chapters 11 & 12

All of the architectural styles that support fault tolerance are diverse. This is so that the errors they may encounter will not be similar. It helps to have each portion of the system developed by different people so that a groupthink issue does not occur. This could be further implemented by requiring different tools and IDEs, different algorithms, and even different languages. To take it a step further one could develop specifications individually and define them in different language as well.

Using N-version programming for a control software such as radiation therapy does not sound like a great idea to me. Perhaps this is an unrealistic method of thinking but I would hope these machines are already designed to be as accurate and cautious as possible. In my eyes taking the time and energy to create something one time while performing it more seriously can result in better results than creating something multiple times in a less serious manner. In other words I feel that as N increases the chance for error may also increase.

If exceptions to not get handled properly, errors in the code will result in the program to halt. In other words any errors may completely shut down any program or website or tool that is being used. This doesn't sound very high availability to me. To prevent this we use exception handling to receive and process any error that my occur, and handle it in the code, so that the rest of the program can continue running, even if this specific piece must be paused or restarted with different inputs.

If for some reason the train manages to reach speeds over the max speed, possibly due to downhill travel, the software must apply the brakes to lower the speed.
If the train is at accelerating, and it reaches its max speed, the software much take over the throttle and halt any further acceleration.
If the train is heading down a single path and the light is red, software must bring the train must come to a stop.
If the train is heading down multiple paths and has the option to follow a path that is red and one that is not, the software must guide the train down the non-red path.
If the light indicator is not red and the speed is not over the speed limit, the conductor should have control over the trains speed and direction if necessary.

***

### HW4: Reflections on software failures
Consider the FBI's Sentinel project. The FBI wanted to make information more readily accessible in order to prevent further attacks such as 9/11. By replacing paper files with digital ones, they could create a virtual case file and perform their jobs more efficiently. The only issue is that such a simple and comprehensible idea is not always an easy technical fix. The series of articles documents the trials and tribulations of the Bureau over a span of almost ten years! Trying to combat the challenges of inefficient budget combined with the misjudged time frame, they seemed to miscalculate on so many levels. In a rapidly growing industry of technology, these delays can sometimes result in completely wasted projects, as things progress, and requirements and technical abilities grow. The FBI managed to make an eventual comeback, celebrating the eventual release of their Sentinel, despite the many bumps encountered along the way. Not to be outdone, however, the up-and-running Sentinel did not go as planned and required many expensive fixes and adjustments. The roller coaster of feelings in the entire tale is quite intriguing. 

When you combine the Sentinel saga with the other articles on security and failures, some things start to become clearer. Things will fail. This is inevitable, and while failure should not be aimed for, it should be recognized. Project planning is very important and requires diligence and adequate time. Poor planning and project management will greatly contribute to the rapid downfall of an idea. While it is important to be prepared, it is also absolutely essential to realize that not everything can actually be planned out, and you must prepare for things to not go as planned. No matter how precisely the work is planned things can and will go wrong, and workers must be able to quickly understand and adjust these issues as things move along. This must be achieved on a deeper level so that the systemic factors are recognized. Systemic factors investigate not just the issue at hand, but further into WHY such an error was made in the first place. It is dire essential that these are realized so that future infractions will be prevented, instead of just patched after recognition, as frequently by this time irreversible damage has already been done. To build on this further, the resilience of the project must be considered so that when issues are encountered all is not completely lost, similar to the Apollo 13 mission.

On top of everything else, the only true way to check for issues is to actually test for them. Teams must adequately test their programs throughout the entire process, not just at the end. Tests need to be thorough and include any and all possibilities of inputs. This becomes even more important when you consider the security aspects of certain designs. If an application such as online banking has not been actively certified it is left more vulnerable to outside attacks. Not only is this compromising to the users in that their data has been breached, but it can also reduce the availability of the system, generating even larger issues. If something has to be taken offline so that it can be repaired, user access is limited or even halted, and in the example of online banking, people may be temporarily locked out of their accounts if such a thing has not been planned for or tested against.


***

### HW5: Chapter 4 and reflections
4.5 Gas Pump Requirements-The pump must contain the desired fuel. The credit card reader must determine if the user has the appropriate funds in his or her bank account. The pump must be able to measure fuel quantity that is being dispensed. The pump must be able to calculate the cost based on the price and amount dispensed. It should then have access to the users account so that the money can be deducted. The pump must stop dispensing fuel when the price cap has been reached. The machine must also return the users card after use.

ATM Requirements- The ATM must contain cash in enough different bills to output specific numbers. The ATM must be able to read a users card and determine if the code is correct. The ATM must be able to ensure the user has sufficient funds in his or her account, and subtract the amount withdrawn once dispensed. The machine must also return the users card after use. The ATM machine should include some sort of alarm security system.

Internet Banking Requirements- Must be secure and only accessible via username and password. It must be able to access any accounts being used through the bank and view current funds. When funds are transferred it must correctly calculate to add to the new account and subtract from the other account. No amount larger than what is currently in an account may be transferred.

4.6 It seems as though often times non-functional requirements are implemented to increase the usability or efficiency of the functional requirements. Because of this I feel that many non-functional requirements could be grouped under the functional requirement that they support. This could take place on a web database or spreadsheet, or in a larger system if one is used for requirements change management. As the requirements changed during development these things could be edited and updated.

4.7 Some use cases for ATM-  Goal: To withdraw money  Steps: Insert card, enter appropriate pin number, select amount to be withdrawn, remove money, remove card.    Goal: To steal money Steps: attempt to break the machine, ATM alarm goes off and alerts the police.     Goal: Withdraw more money than in account   Steps: Enter card, enter proper pin, attempt to enter amount larger than account contains, ATM machine should reject offer and return card.      Goal: User a stolen debit card  Steps: Enter card to machine, try to enter correct pin but fail, ATM should inform user of the incorrect pin and return the card. 

The articles for today seem to focus heavily on proper testing and adaquate requirements of a system. They also reinforce the idea of being able to adapt and keep up with any developing changes along the way. For instance, managing project requirement change through a structure of requirements change management is very important to systematically lay out the developments and how they are progressing. It is important that these are managed and written down properly. One should not simply try to remember the mutating requirements as they are changed, as one can only hold so much information in short term memory, as suggested by the "Magical Number Seven" principle.
As specifications are adapted, tests must also follow suit. Previous requirements may be thoroughly tested by test cases, but newer test cases must be ran to ensure emerging rsystem requirements are also met. By documenting and managing the requirements it makes it structured and easier to program and run test cases on each one, ensuring that the development of the project encounters as few hiccups as possible.

***

### HW6: Chapter 2
A System to Control Antilock Braking in a Car - According to the book, a lot of software involving safety is developed using the waterfall process. This makes sense, because when safety is a key factor, lots of planning must go into a project to ensure mistakes are not made and injuries do not occur. Also, safety standards are unlikely to change frequently, so it is doubtful that software specifications of something of this nature would be altered. The case of antilock braking seems very straightforward. Plan it out, design it, implement and test, and perform minimal maintenence. However, I will say that this seems like something that could re-use code very frequently as it is unlikely to change , which dips into the Integration and Configuration category of process model, so I suppose this could be argued as well.
A Virtual Reality System to Support Software Maintenance - This case will almost certainly depend on user feedback and require multiple changes so Incremental Development should be used. It is cheaper than the waterfall model, and customer feedback will be abundant. There is no way to know what the final product needs to look like until some ideas have been implemented and tested. 
A University Accounting System that Replaces an Existing System - If this case is referring to some sort of system that is going to be updated, I could see the Incremental Development approach being taken. After all, it is possile that newer editions of this will be continually released for use. That being said, if I understand correctly, I believe the proper method would be Integration and Configuration, as most of the code will likely be taken from the old system and re-used. Assuming frequent updates will not be necessary I think this is the strongest option.
An Interactive Travel Planning System that Helps Users Plan Journeys with the Lowest Environmental Impact - For this one all I can say for sure is that the Waterfall Model is the worst option. It simply wouldn't make sense. As for the other two, I'm leaning towards Incremental Development. The fact that it is a user-based software makes me think changes will often be required as users request for different updates or changes.

***

### HW8: Mythical Man Month
The beginning of this text reads like a very enjoyable and informative textbook. It provides a lot of useful information in an easy to read format that made me as the reader feel as though a superior with ample experiences was giving me some useful advice to ponder over. This idea follows the writing style of the majority of textbooks I have encountered, barring the “enjoyable” aspect. When a student receives information from such things, it is often perceived with a mind wide open and waiting to learn whatever may be coming from the book. There is no personal guard up in a student’s mind waiting to debate or argue against whatever the author may the saying or “teaching”. The general information about the software engineering field provided by this specific author was received in such a way by me. I very much enjoyed hearing about the tar pit metaphor and the ups and downs of the profession. It made me realize that it is an area that will forever be “unsolved”, meaning it will always have room for growth and innovation, which is promising to a young student. It also details the difficulties and struggles present, where lessons are constantly acquired, often at a consequence. The early pages did a wonderful job mentally preparing my brain for what may soon come. Like the student I am I gladly absorbed the information being handed to me. 

	As I read on, however, I began to realize the entire document was not going to provide the same experience as my early “textbook interpretation.” As the concept of man-months became prominent I registered that I was reading something intended possibly to sway the opinion of the author’s peers. At a relatively early point I asked myself why managers might add more manpower if doing so makes things worse. As it so happens, the author wanted me to propose this question as his intention is to have me on his side of the debate. And I must say it worked. I will say for complete transparency I found it funny that he starts by declaring the man-month to be a false and misleading unit of measurement, and proceeds to use it throughout the paper to argue his points, but this is most likely done to establish a common ground of communication that may be measured for the sake of understanding and comparing.
	
	I particularly enjoyed the comment that things don’t take as long as they “ought to”, which is a very common fallacy in everyday logic. In any activity people develop a preconceived notion of how much time something may take, with very little evidence to support their claim, and yet they fully believe it. He mentions that programmers are optimists; I assume this is because we overestimate our intelligence, especially in a field where the workers consider themselves smarter than average. The proposal that more data surrounding debugging figures and timeframes should be shared to allow for more accurate estimates is a wonderful one. If the data is available to be analyzed, by not openly share it? To me personally the Mills proposal makes a lot of sense and I would be curious to know why it is not common practice. The main point being argued seems to be that more manpower does not equal faster results, and I think in some cases the opposite is actually being implied. This is supported inherently by the further argument on conceptual integrity, where less “diverse brains” is a good thing. All of this is tied together by the author sharing one of his own personal experiences in the workplace which he claims cost a large sum of money. Though only having read the first four chapters thus far, I am fully on board with the authors argument and I would be curious to read an opposing one. 
	
***

### HW9: Chapter 8 and Reflections on Testing
8.7: In order to test the Wilderness Weather System, one needs to develop tests that run through all of the operations. Due to inheritance this can get complicated because certain operations need to be tested anywhere that it may be used. A potential scenario to work with these could be attempting to collect data remotely during different weather environments. Attempt to turn the station on and off, attempt to configure which types of data you want to transmit, and then run and collect to analyze said data.

8.10: Attempting to label the importance of certain functionalities seems like it would lead to an ethical dilemma involving safety and usability. Look at a car for example; seatbelts are rarely used for their designed function. Meanwhile there are plenty of other non-safety features of a vehicle that must be accessed every day in order to promote proper functionality. From a safety perspective it would make more sense to identify the seatbelts as the more important function, however from a usability point of view one might claim that since seatbelts are rarely called into action they don’t require as much testing as something that will be used under different conditions every single day.

After reading the article about testing and taking it into context with everything else we have done it is very apparent that testing done properly should and will require a lot of time, planning, and money. It seems people often want to cut corners and overlook certain areas of testing both to save time and money but also because they find it tedious and mundane. The concept that needing to test code equates to admitting faults is powerful because it is not uncommon to encounter someone who has a difficult time admitting their mistakes or that he or she is not perfect. But in this field, it seems extremely important to not only admit flaws but to seek them out. All software should be thoroughly tested in the appropriate manner, followed by debugging to locate any errors or design flaws discovered while testing. The “Pesticide Paradox” stating every method used to debug will leave a residue of smaller bugs seems like a very real and unsolved problem, assuming I understand it correctly. Am I to believe that there is no such thing as a perfectly written software, as the article suggests? That is both unbelievable and eye opening to me. 

***

### HW10: Chapter 15
As software constantly develops and progresses, there is no doubt that projects and ideas will build and grow off of one another. The entire nature of the industry revolves around stacking progress on top of itself. I believe this should be an understood aspect of the field. Should this be any different if the software created was paid for by a customer hiring a contractor? Maybe. In this scenario I would think both parties involved have an ethic obligation to respect the work and ideas of one another. The customer must not treat the code as their own and the developer must not treat the product as theirs. However, each party does have a right to what they paid for or developed. As stated before, they should make ethically conscious decisions while also not being limited by the selfishness of the other. To be more specific, the developer should have the right to re-use some of the code he or she created while contracted, as long as he or she is not crossing any copyright or patented ideas, nor profiting off of the ideas of another. If you wanted to get technical and be fair, financial imbursements for such cases could be created, but this sounds like it would become messy quite quickly and turn into a web of monetary confusion. I know in the world today you cannot exactly count on those around you to always act ethically towards you, including cases such as these, but I think in a perfect world this is how the system would operate.

***

### HW11: Chapter 9
9.8: Chapter 9 brushes on three different types of software maintenance, the first being fixes and repairs to mistakes or potential vulnerabilities. This could mean changes to the code, or even a redesign of the whole system. The next type is a response to another piece of the system has been changed. Think software updates or hardware upgrades. The created application must be modified so that it runs smoothly with these changes. The third type of maintenance stems from the desire to add new funtionality or features to a design. Similar to a upgrade, but with new additions and operations. These types all seem similar with some overlap because they in fact are. In many cases it would not be uncommon for maintenance to be performed for multiple interconnected reasons that may fall under multiple categories. It can be tricky to put labels on something so multipurposeful. No matter how you choose to seperate or label them, the book makes it clear that performing maintenance is costly, and the best way to assist this is to create code that is easily alterable for future programmers.

9.10: Overlapping into the previous question, it is fair to state that the professional world of software development would operate more smoothly for those involved if engineers took the care and effort to develop code that could be easily maintained. This saves money as well as time, and allows any future developer to have his or her workload lightened. The employer is not always directly involved with the project, so it may not be explicitly requested to create code that may be easily maintained. However, as a contractor one should be aware that if people spent a little bit of effort in the present, a lot of future effort could be spared for everyone. 

***

### HW13: Chapter 17
One of the most major and obvious risks of moving to a distrubuted system is the risk of a security breach. Because the system is made up of many different individual components, only one small part of it needs to be broken into for a hacker to potentially gain access to other parts. In order to be secure and safe, a remote network should be able to defend against interception, interruption, modification, and fabrication. This can be tricky because it is possible for each piece of the system to have a different security policies. Organizations working to form a distributed system should plan for compatible policies in order for them to work together safely. Another risk is the decline in quality of service offered. If one part should fail or become overloaded, the entire system will suffer in speed or quality. The more pieces involved the more unpredictable it can become. The system should be designed with these things in mind, so that when faults should occur it will not shut down the entire thing. Requirements should also be determined in advance so that the system can be designed to meet them. A third difficulty in establishing a distributed system involves keeping its distributive nature transparent to users, or in otherwords concealing the idea. Because there is not a central control unit over the network, users may notice differences in behaviors at different times. One can use middleware to design the system so that resources may be changed without having to change the application to help conceal the fact. However, it is also not a foreign concept to simply be honest with the user about the system they are using, so that they may be prepared to deal with any of the implications that come with it.

***

### HW 14: Chapter 18
In order to use a REST structure to construct an interest calculator, one would need to identify a resource. I suppose in this case the resource involved would be some sort of currency. Currency can be represented in multiple ways, whether it be physical bills like Dollars or Euros, or even a simple number on a screen or in a bank account database to be accessed by a debit card. I am not certain what the identifier would be. Perhaps the specific ID linked to the loan account. One could use the different actions: create, read, update, and delete, to retrieve the dollar amount and percentage of interest and use it to calculate and update the data values. Doing so would make it easier for people to use such features on mobile devices or simple websites. 

***

### HW 15: Chapter 19
The term system is a broad term which refers to an intentional group of components that collaborate in order to produce a specific result, often times a set of services to its users. There are more complex and specific terms that can be pulled from this, and they can even be piled on top of each other to produce “systems of systems,” in which many systems work together as a system themselves. Sociotechnical systems are a form of complex system which consists of so many moving parts, both people and technology, that it is impossible to have a complete understanding of its behavior. In other words, its non-deterministic. As a result, some emergent properties arise upon completion. These properties are specific in that they are only apparent once the system as a whole begins moving together. These can be difficult to predict due to the sheer amount of variables present in the system. Because the system is non-deterministic, success is no longer predictable, and therefore becomes subjective. When you cannot predetermine the actions of a system, you cannot know exactly how successful the system will be ahead of time.

***

### HW 17: Team Progress 1
Approaching this week’s deliverable, our team made a ton of breakthrough progress. Previously, our general mood leading up to each deliverable was uncertain and ill prepared. We quite often felt as though we did not have a full grasp on what we were supposed to be accomplishing or wondering if we were going to be able to perform as well as the other groups. After having to completely change our project topic things were feeling very shaky for us. I am now very proud to report that at some point things finally clicked for us, as we managed to get some testing framework up and running and producing the required specs for the assignment. We are all very proud of the progress we have been able to accomplish and are very optimistic moving forward.

***

### HW 18: Chapter 21 and Chapter 22
Three of the most commonly used architectural patterns in real-time systems include observe and react, environmental control, and process pipeline. In observe and react, the system sensors itself to determine if an event occurs. The data examined through monitoring is usually presented onto a screen or other type of display. When an event does occur, as a response the system begins a process to handle the event to trigger some sort of response. This action can even be accompanied by an alarm or alert of some sort. A good example of this is a burglar alarm in a building. The environmental control setting is similar in that it relies on sensors to provide information, however in these instances the system can actually make changes to the environment itself as a response, based on control signals sent to system actuators. Think for example the use of an anti-skid braking system used in vehicles in which the wheels are constantly monitored and adjusted automatically based on the information received. This architectural pattern works great when a systems environment must be continuously monitored for changes. The process pipeline architecture is used when data must first be interpreted differently before a process can be initiated. A positive here is that this can be done concurrently so the data can be processed quite quickly. This is great news in cases where data constantly being transmitted, or else some data could potentially be lost. For instance, in radio transmission the signals must constantly be transformed to sound waves in almost constant time or else the incoming sounds would not make sense in succession. 

When incorporating fixed price contracts, the contractor assumes a much greater risk than the client. In the world of software engineering, things are quite often unpredictable, and it can be difficult to accurately assess the coming future. When using fixed price contracts, the price is bid on and set ahead of time and therefore will not change. Should any unsuspecting issues arise, which they frequently will, the contractor does not get to suddenly charge more money to accommodate any losses, as the financials are already agreed upon. Say for instance a developer quits or is fired. The quality production of the software will suffer. Another common occurrence is for the number of resources required to complete a project to be underestimated. This would result in a loss for the contractor, or at least less of a return than originally anticipated. For these reasons and more it is a very important roll for a manager to understand risk management.

