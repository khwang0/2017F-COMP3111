# 2017 Fall COMP3111/3111H Project LINE Chatbot

In this project you are supposed to develop a chatbot on the LINE platform. There are three topics for you to choose. You and your fellow group-mates shall pick one of these topic and complete the project according to the time-frame. The same time-frame is applied to all topics. Shall there be any problem you should contact Kevin (kevinw@cse.ust.hk) for clarification.

## Group: 

Each group should consist of 4 or 5 students. Unless there is a strong reason and an approval from the teaching team, there should not be any group with less than 4 students or more than 5 students before Milestone 1.  To form a group you need to submit the list of group member together with the topic you choose from 18 Sep to 22 Sep online. The link will be available on the course webpage later. Each student enrolled to the course must be in one group. No student can appear in more than one group. No group can include a student who is not enrolled in the course. Students does not sign up for any group will be grouped by the TA.

If a group has one or more students from COMP3111H, the group is labeled as H-group which is expected to accomplish more requirements (as specified in each topics). H-group and non H-group are graded together using the same set of rubrics.

## Time-frame:
* Wk 1 – 3: bootstrap: familiar with the platform and assigning groups
* Wk 4 – 5: planning/collecting user requirements
* Wk 6: Milestone 1 – Features Presentation
* Wk 9: Milestone 2 – Interim Review
* Wk 12: Milestone 3 - Submission of project
* Wk 12-13: <10 Minutes Powerpoint presentation of work

## Topics:
Your group should pick one of the following topics. You are not allowed to change the topic after submission. Each topic will be graded separately and therefore selecting any topic should have no statistical advantage. There is a requirement for H-group in each topic. These requirements may also optionally be implemented by non H-groups. A good implementation of these requirements is likely to receive a higher mark.

> Topic 1 – *Customer Service Bot*
>
> Context: Write a customer service for a travel agent that provides tour services in Guangdong province, China. The travel agent is so busy in answering phone calls every day to answer some really FAQ question but many of them are related to live data and they can’t just upload the excel online.
>
> Initial material provided by TA:
> * A mock company website with reference to some real travel agent. 
> *	Workflow of a tour application
> *	An excel of tour data that contains two table data
>     *	Package info (package id, destination, price, duration, hotel, spot, description, keywords, terms)
>     *	Tour info (package id, departure date, return date, name of tour guide, status)
> *	One page of content of the client’s initial wish
> *	Some test cases.
> *	Interview Template.
>
> Expectation to H-group:
> * Good integration to the tour application workflow (i.e., able to apply the tour with the bot).
> *	An additional web portal for the company’s employees to access the database.

> Topic 2 – *Dieting Chatbot*
>
> Context: A software house wish to develop a chatbot that help people lose weight by dieting. The chatbot should be giving advices to the user by considering his/her weight (which is input by the user daily), a menu in a restaurant when the user is walking in a restaurant, reasonable calorie computation, and some basic nutrient facts.
>
> Initial material provided by TA:
> * Some nutrient facts.
> * An excel table containing all possible foods in the given test cases and the hidden test cases.
> * Some demographic data about potential users.
> * Some sample menus in both text mode and images.
> * Focus group question template.
>
> Expectation to H-group:
> * Able to capture the menus from an image (i.e. doing OCR - https://github.com/Asprise/java-ocr-api)

> Topic 3 – *Chatbot for HKUST Freshmen*
>
> Context: You are helping freshmen in adjusting their life in HKUST. Instead of just giving career prospect or advices of subject selections, more helps will be provided to HKUST freshman so that they are more ready to adjust themselves in HKUST. Examples like giving suitable URL when they need to access Canvas, add/drop, hostel application, etc or giving directions. Since this is a very open project, each group should provide at least 8 features.
>
> Initial material provided by TA:
> *	Focus group question template.
>
> Expectation to H-group:
> * Users are able to make friends with other freshmen who have similar questions.

# Details of Milestone:

Each milestone has a due day. Each group should submit one copy of their documents/code accordingly. Late submission of documents will be penalized. Submission links will be available on webpage. All documents submitted for each milestone, unless specified, shall be prepared in one *single PDF file*.

## Milestone 0 (also known as assignment 1. Due: 27/9/2017):
Students should complete Lab 1 to Lab 3 and complete the assignment 1. The details specification of assignment 1 will be released later. 

## Milestone 1 (Due: 12 Oct 2017):
Students should submit:
*	Meeting record of interviewing clients (meeting minutes/tabular requirements) (For Topic 1 only)
*	Focus group meeting record and evidence (e.g. a photo) of such meeting really taken place (For Topic 2 and 3 only)
*	Related references gathered from the web 
*	Proposal of features and functions in the chatbot.
*	Architecture design presented in UML
TA will feedback:
*	A Boolean score based on the fulfillment of each item
*	Informal comments of the submit items.
*	Sign-off the proposed features. 

## Milestone 2 (Due: 3 Nov 2017):
Students should submit:
*	A running prototype on LINE that has implemented at least half of the features.
*	Evidence of pull request, merge and commit log messages
*	Rational of change of architecture design, if any
*	Formal approval from the mock client of change of feature, if any
TA will feedback:
*	Score of scale [0 to 5] to each fulfilled item.
*	A new requirement from the client/the marketing department.

## Milestone 3 (Due: 20 Nov 2017):
Student should submit:
*	A bitbucket repository containing their code.
*	A LINE bot account ID that allows TA to test and grade.
*	Test suites and the result.
*	Documentation of their code (Javadoc)
*	Evident of fulfillment of the proposed feature
*	Evident of fulfillment of the new client’s requirement
TA will feedback:
*	A score based on the fulfillment of given test cases.
*	A score based on the fulfillment of extra test cases given negotiated in the client’s meeting, if any.
*	A score based on the fulfillment of some extra test cases.
*	A score based on the submitted documents.
*	A score based on the design pattern of the project.

## Final Presentation (Week 13 during the lecture time):
Student should:
*	Prepare a one-page poster (format PDF, orientation: landscape, to be projected on screen) that describes their project features and how it meets the requirements.
*	Present their project within 5-7 minutes on stage.
*	Pick one or two features and describe its technical difficulty.
*	Answer questions raised by the instructor and TAs.
Instructor and TA will feedback:
*	A score based on the appropriateness of the features.
*	A score based on the hardness of the features.
*	A score based on the overall presentation.

# Resolution of Conflict in Groups:

It is not always but possible appearance of conflict within groups due to miscommunication, no show of a particular member or any other reasons. It is also important to make sure everyone are contributing the same amount of effort in the project. From 3 Nov to 6 Nov, all student may request TA’s intervention in resolving a conflict in group. TA will talk to all individual in the group and may do one of the followings:
*	Issue warning to any individual;
*	Adjust individual scores; or
*	Splitting the group;
To request TA’s intervention, students shall email to all TAs via (csta3111@cse.ust.hk) and state the problem in their group. 


