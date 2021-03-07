Milestone 2
========

Milestone 2 Proposal for the Lightning Sharks Team Proposal. By Josh Weintraub, Eric Miller, Alec Oortman, Alexander Costa, and Daniel Grotch

The Problem
************

**Initial Problem**: With some students attending in person and some attending remotely, it can be difficult to encourage participation online when answering or asking questions from the remote students.

:Instructors: On the instructor side, this is a problem because it becomes hard to engage with a class that has low participation. For example, there are often times where instructors ask questions, and no one on Zoom answers (whereas it would be easier to converse naturally face-to-face). This makes it hard for instructors to gauge how well the students are learning.

:Students: On the students' end, especially those who attend remotely, this is an issue because students working from a home environment tend to feel less connected to the lecture than those in the classroom and feel less inclined to participate remotely. Also, in the classroom, asking a question provides some anonymity (especially in a lecture hall), but remote formats (like Zoom) will highlight the student's name, which can be a problem if they have anxiety. 


**A Typical Interaction**: 

:Goal: The instructor desires to teach the students a lesson related to the current class unit.

:Plan: The instructor plans out a lesson that involves the ability of the students in the crowd to solicit feedback, instructions, and answers to various questions. 

:Specify: The instructor writes up a lesson plan to be executed during the class period.

:Perform: The instructor executes this plan. For example, they may ask a questions to the class, making the class dependent on student participaiton.

:Perceive: In a case that much of the class is remote, they find it difficult to encourage participation, and end up staring into an empty screen without responses.

:Analyze: This can be for a variety of reasons, including that the student is nnot paying attention (due to in-home distractions), it is difficult to respond one-at-a-time, or the student is too embarrassed to answer in a Zoom (where their name will be highlighted). Sometimes, even if feedback did come from a remote student, it may be difficult for in-person students to hear the remote student and continue the conversation.

:Compare: The success of the lesson often depends on planned feedback from the audeince. When this situation occurs, the instructor is not able to effectively convey their information to both types of students, and as a result, the lesson does not meet the desired level of success, as the lesson could not be taught to the audience.

Users: 
	Instructors are primarily affected by this problem. They struggle to get participation from the remote users, which causes issues when attempting to establish an ongoing discussion or receive feedback from students to know what they can improve or clarify. 

	Remote users are also affected by this problem because they are missing out on learning opportunities and will not retain the information being presented. In-person students are somewhat affected because they do not get as much involvement from their peers, but they still receive the benefit of being directly present in class. If there were a solution encouraging them to participate more, they may be inclined to learn more from the class, which benefits both types of users.

Existing Solutions
******************

Many existing solutions exist in order to solicit a higher level of student participation. They tend to follow the Section 508 Guidelines in order to help eliminate existing barriers in ICT which naturally separate the remote student from the instructor, replacing them with more usable interfaces than the typical Zoom lecture (with one instructor speaking to a large group of students and asking for spoken feedback).

1. Tophat:
	It existed before remote learning was popular, but the program quickly found its place in the hybrid synchronous environment. Top Hat allows instructors to present topic-relevant questions to their students to measure how well the class is understanding the material. The only downside to this solution is the time-sensitivity of questions. Some students may be penalized for missing a question even if it was due to some delay through the remote lecture. Tophat follows many golden rules, including the principle of offering informative feedback. In a general class lesson, the user may not know whether they are understanding the material as the instructor had planned, and Tophat questions combat this confusion.

2. Zoom Breakout Rooms: 
	The breakout rooms encourage students to work together and engage in the class discussion. By breaking students into small groups and assigning a task for the group to complete, students are very compelled to participate because it will be obvious that they are not participating. They would not want to let down their group and their lack of cooperation will most likely be reported to the instructor. The only downside to this solution is that a student could suffer if the rest of their group does not participate. The breakout rooms adhere to the golden rule of keeping users in control. In a normal classroom setting (not a computer interface), this is not as important to the students. However, without having any control, student users may lose interest in the interface and zone out. With breakout rooms, students are awarded with accountability, in terms of leading a small breakout room towards its goal, which will likely keep them more engaged.

3. Zoom Quiz Questions:
	The instructor can send out a question to the viewers to respond to. Could be used as an attendance system if the question is simple but it's very rudimentary and doesn’t connect to any outside sources of information. These questions follow the golden rule of seeking universal usability, as it creates the opportunity for both verbal feedback (which was already available) and a more keyboard-based feedback which is often more usable.

Proposed Solutions
******************

1. Tiered Point System
	A tiered, points system for participation to keep students engaged during class. The program would afford students with many options to contribute to the class and reward the students who do all or some of the options. The goal of the program is to incentivize in-class participation through a variety of human-computer solutions that block distractions, keep students involved and encourage challenges. The points can be treated similarly to earned sky miles, where 100 points = 1 extra point on an exam or can be used to drop a quiz. Certain signifiers for this may include a point total for each student at the top of their screen, and attractive animations as they score more points, in order to further afford them an incentive to participate and stay focused.

	+---------------------------------+------------+
	| Action                          | Points     |
	+=================================+============+
	| Lockdown Phone                  | 10         |
	+---------------------------------+------------+
	| Lockdown Browser                | 10         |
	+---------------------------------+------------+
	| Camera on/in focus              | 8          |
	+---------------------------------+------------+
	| Tracking Zoom Window Focus      | 5          |
	+---------------------------------+------------+
	| "Verify Attention Button" [1]_  | 3          |
	+---------------------------------+------------+

2. Anonymous Input Solicitation
	Create a place where students can submit questions anonymously due to Zoom highlighting their name. This would afford more students who do not want to be in the spotlight with the ability to feel more comfortable asking questions over hybrid-asynchronous remote learning. A signifier for this may be an input box (similar to the chat), but with a silhouette with a question mark that represents anonymity. This will afford exactly what it signfiies: the student has the ability to ask a question without embarrassment, as the instructor will be unaware of their identity.

	This can be turned into a challenge: ask at least 2 good questions to receive 2 pts 

3. Question Queueing System
	A system for asking question without having others talking over each-other. When you want to ask a question you put your name in the Queue which works like a regular data structure and then it tells you your place in line to ask the question or provide feedback to the instructor. For the instructor, a good way to signify that new questions are coming in would be to animate the question falling into the end of a list (which also correctly signifies the property that it works as a queue in a first-come, first-serve basis).

 The easiest way to measure success will be based on the actions listed in the tiered point system table, as these all indicate a more engaged and participatory audience. However, we must also request separate feedback from students and instructors through surveys to ensure that the system isn't being cheated (i.e., students are following the above actions for the sake of the actions themselves, without paying attention to the lectures). Part of this survey could include quizzing students over what was presented in the class lesson, in order to see if the inclusion of these tools genuinely helps their understanding of the material.

Video Proposal
***************
:Video Proposal: `Link to Video Proposal and explanation <https://youtu.be/0G2Vg3iO_Qo>`__

.. [1] A "Click Here" Type Button will appear randomly for a brief period where the student will need to click in order to get attendance credit
