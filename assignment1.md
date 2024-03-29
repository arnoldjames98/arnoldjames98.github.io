---
title: Team Assignment 1
---


# Develop a Research Question

**Note:** Our research question changed over the course of the semester project. Originally, our research question was focused on how to create a full, biodegrable crab robot which included a biodegradable power source and could support its own weight. However, once we got to the prototyping phase of our project, we realized that this research question would not be tractable within a single semester. Therefore, we shifted our focus to the design of a just the leg mechanism of the robot. By focusing on just the design of the legs, we could spend less time figuring out how to avoid using any electronic components to power the robot and instead focus on how to leverage the compliance of our biodegradable materials to optimize the performance of our robotic legs.

While our research question is not completely different than the original one that we constructed when originally preparing this assignment, there is some discussion in this assignment that is specific to the old research question that we ended up changing. For context, we have not removed any of our responses that are specific to the old research question, but instead have added notes after these parts that describe how our new research question changes these responses.


## **Research Question**:

**Updated Research Question**: _How can the concepts of foldable robotics be applied to the design of a **crab-inspired, compliant leg mechanism** constructed entirely from biodegradable materials?_

**Original Research Question:** _How can the concepts of foldable robotics be applied to the design of a **seed spreading robot** that is constructed entirely from biodegradable materials?_


---




**_Tractability_: Is your question tractable and achievable? Discuss your plan for scoping your problem to fit in a 15-week course.**
*   **How have you focused or constrained the problem to differentiate yourself and/or become more tractable? Examples include looking at one specific type of motion, using a specific animal as a source of inspiration (for generating unique specifications), or limiting yourself to a particular set of materials, parts, cost requirements, etc.**

**Updated Response**: While our updated research question is still focused on designing a fully biodegrable system and is still related to robot locomotion, we have now changed it to be more tractable for the semester project. Instead of focusing on a goal-oriented robot for spreading seeds, we have focused our research question on the design of crab-inspired legs with compliance. While it is possible that our original research question could be completed within 15 weeks, the specific assignments designed for the foldable robotics class are focused on the dyanmics and optimization of our system, and focusing on the leg mechanism rather than the full system made these assignments more tractable. In addition, building a prototype of the full system based on the previous research question was difficult due to limited materials and access to manufacturing equipment. Therefore, our updated research question proved to be other tractable and achievable.

**Original Response**: Our group’s topic for the project this semester is “Disposable/Degradable Robots.” However, the design of a foldable robot composed entirely of degradable materials is too broad of a topic due to the variety of different approaches and applications. There, we decided to focus our research this semester on an agricultural/environmental application of the idea of creating a disposable/degradable robot. The application we selected is the spreading of seeds in the environment. We chose this application because it leverages the benefits of biodegradability into the design of our robot while limiting the scope of our project to a single goal. Using only biodegradable materials will greatly limit the possible materials and approaches that we take to solving the problem of autonomous seed spreading, and this limitation will make our problem much more tractable to solve within the 15-week course.

The research question itself does not specify the complexity of any given design that aims to address the question, but we believe that our goal-oriented research question balances the tradeoff between an overly broad question that would leave us with no clear direction and an overly specific research question that does not offer many different solutions. Based on the material covered in the course, especially locomotion, we believe that our research question can be answered with approaches that align well with the course material. Additionally, our research question explicitly states that we intend to use concepts from foldable robots to solve our problem, and given the biodegradability constraint included in our research question, using the same material for joints and links will simplify our possible designs. Overall, we believe our research question is tractable by clearly specifying our goals, which were selected to align with material covered in the course.


---




**Novelty: Is your question novel? How have you established novelty?**
*   **_What keywords did you use when performing a literature review on your topic?_**

A list of different keywords that we used when performing the literature review are included below. Many of these keywords were paired with the word “robot” or “autonomous” to narrow down our searches to robotics-oriented research, and a number of different combinations of the following keywords were used.

**Note**: Some of these searches are specific to the old research question focused on designing a seed spreading robot. However, most of these searches are still relevant to our updated research question. One additional one specific to the design of the legs is "klann linkage." Note that keywords 12-15 were added after the research question was updated.



        1. Degradable
        2. Disposable
        3. Agriculture
        4. Seed spreading
        5. Seed sowing
        6. Seed dispenser
        7. Reforestation
        8. Tree planting
        9. Foldable
        10. Origami
        11. Printable
        12. Klann Linkage
        13. Compliance
        14. Stiffness
        15. Cardboard
	
*   **_What were the four most highly cited references? Provide a short summary of each, focusing on whether these papers have already done what you set out to do._**

**Updated Response**: All of the references cited below are specific to the seed spreading application that we originally had planned to focus on. Therefore, we have found four new articles that are more focused on our updated research question. The first is [1], the authors dynamically model a water running robot that uses both Klann Linkage mechanisms and compliance to optimize running on water. Since we decided to also use a Klann linkage mechanism to mechanically recreate a crab-like gait and we also considered using compliance to further improve this mechanism for our task, this paper was interesting. Another important article that we considered when answering our research was [2], where the authors propose a manufacturing framework for designing foldable robots. Since our research question explicitly includes that we must use the concept of foldable robotics to answer our research question, having a background on the manufacturing of foldable robots is important. Another important aspect of our research question is that our design will be crab-inspired. Therefore, we looked at previous literature focused on the design of crab like robots, like the work presented in [3]. While this research is not recent, it is focused on the design of a controller for a crab-inspired robot and was therefore of interest to our group. The final piece of our research question was how to make the robot biodegradable. From our literature review, it seemed that most biodegradable robots are microrobots for medical application. Since we planned to use cardboard, we also searched for robots made out of this material. We found a snake inspired robot that used cardboard material in [4], but the focus of the robot was not to be biodegradable, just to have some compliance. Therefore, no previous work directly answered our research question, but there is significant work that has been done focusing on specific aspects of our research question.

**Original Response**: While previous research in degradable robotics has focused on possible medical applications, there is little research on the environmental and agricultural applications of such robots. In [5], the authors introduce a seed spreading robot for agricultural applications called “Agribot” which both ploughs and sows seeds. Agribot is a wheeled robot made of metal components and controlled by a microcontroller. While this robot is not biodegradable, its goal in spreading seeds matches our research question’s end goal._ _The seed dispenser used in [6] is another robot that was used for dispersing seeds across a field that could be used for reforestation. By utilizing a quadcopter, seed dispenser, and an Arduino coded to generate its coordinates, the user can not only control but also communicate with this device. In the event that the device fails, the operator can take control of it. Due to the amount of hardware in this device, it is not degradable and is quite large. In [7], a smart seed sowing robot was fabricated to aid in the process of sowing seeds. This robot is able to dispense seeds from a seed container, while being controlled from a mobile application. Unfortunately, this robot’s design is not biodegradable but it still aims to spread seeds like our research question. In [8], a tree planting robot was designed and prototyped. This robot is able to spread seeds by using an array of sensors, wheels and motors. This design was meant to be priced mid-range and solve the solution of deforestation. This design however, was not created to be biodegradable. This is a flaw of the widespread nature of this design, and something that this project will be aiming to improve. 

Unlike previous research, we intend to design a fully biodegradable robot that can be used for agricultural and reforestation applications. By designing a low-cost, highly manufacturable robot using foldable materials, we aim to design a robot that could be mass produced and be safely left in the environment once the robot’s task (seed spreading) is complete.



---




**Interesting: Is your question interesting, timely, and relevant?**
*   **What makes it important to others?**

**Updated Response**: Our research question is important to others because its potential positive impacts on both the different fields of research related to the research question and society in general. First, expanding the field of foldable robotics is important since it is a newer field of robotics that can allow more people to gain the skills and supplies needed to make high quality robots. Whereas previously the field of robotics has a significant barrier due to the expensive nature of robots, foldable robots offer a much more accessible avenue for people to create useful robots. Our research question also considers relevant/popular ideas like using bio-inspiration and compliance to improve the quality of our design, and incorporating these ideas into our research will help us produce a better robot and help others consider ways they could apply these concepts to their work. Therefore, answering our research question will demonstrate how others could apply the concepts of foldable robots to their problems. Additionally, our focus on biodegradability will encourage other researchers to consider how to make their robots more eco-friendly so that robots can be used to benefit society. 

**Original Response**: Our research question is important to others since a biodegradable robot that is able to spread seeds has the potential to positively affect both people and the environment. First, the agricultural application of such a robot could increase the production of food, especially in places where buying expensive farm equipment is cost prohibitive. Our research question was selected to encourage the design of a low-cost and easy to manufacture robot, and such a robot could help those in need of assistance in food production. Another important aspect of our question is the focus on the biodegradability of the robot. With a biodegradable robot, people would be able to set-up the robot and let it spread seeds autonomously without worrying about tracking the robot to retrieve it. Therefore, such a robot could have a positive environmental impact, which is clearly important to many people.



*   **Why is this idea important now? What prevented it from being answered 10 years ago?**

**Updated Response**: Our previous response about the importance of biodegradability for creating eco-friendly robots is still relevant. Additionally, our updated research question incorporates requirements like using bio-inspiration, designing in compliance to our system, and applying the concepts of foldable robotics to our design. All three of these ideas are important to current robotics research that is taking place. Since our work builds on this previous research, especially the foldable robotics research of the past 10 years, it is clear that our research question can be addressed much better today than 10 years ago.

**Original Response**: Our idea is important now because of the usefulness of engineering devices that have a positive impact on the environment. The effects of climate change are clear, so many engineers, scientists, and policymakers must work together to address these problems. Our idea can be used for environmentally positive goals such as reforestation, but is also designed in a way such that once the robot has completed its task, it can safely decompose into the environment. Therefore, our idea is environmentally friendly in both its intended goal and design. The recently growing field of foldable robots is what allows us to answer our question now. Within the past 10 years, many researchers have developed useful foldable robotic designs and analysis methods, so now we are poised to use this technology to solve our research question using these methods.



*   **Within what contexts could other people use your results?**

**Updated Response**: While our updated research question is less translational to solving specific problems (like deforestation), the results of our research question are still useful to others, especially other researchers. As other researchers work within the fields of foldable robotics, or focusing on problems related to the environment, our research on designing biodegradable systems for locomotion will help encourage research in these directions.

**Original Response**: By the end of this semester, we will have designed one possible robot that addresses our research question. This robot, if effective, could be used for applications such as agriculture or reforestation. However, since this robot is only one possible solution to our research question, other people could use our results to come up with other, possibly better solutions. From our literature review, we did not find any other research that solves our specific research question, but our results could encourage other researchers to try to tackle this problem or similar ones. Therefore, both our robot and the idea of the robot could be used by others.



*   **What are the potential broader impacts on society?**

**Updated Response**: The focus of this research on biodegradability is the aspect of the research question that is likely to have the most broad impacts on society. While answering our specific research question will not result in a direct benefit to society, our work can be built upon by other researchers that can impact society.

**Original Response**: As referenced previously, if we can successfully design low-cost, easy-to-manufacture robot that is biodegradable and able to spread seeds, our robot could be used for both agricultural and environmental applications. In the agricultural application, our robot could improve the efficiency of food production in disadvantaged regions of the world where expensive farming equipment is cost prohibitive. In the environmental application, reforestation is currently an important goal that our robot could be well suited for. If our robot could in fact be mass produced, many robots could be released into the environment to spread seeds and simply be left once they complete their task.



---




**Open-Ended: Is your question open-ended? Could it leave room for a deeper look if given more time and resources? Discuss how you have structured your research question to permit further, deeper investigation.**

**Updated Response**: While our updated research question is more focused than the original one in terms of our team's goal, the updated research question is actually more open ended in terms of its applications. While previously we had focused on a single task specific application of our biodegrable crab robot, the updated research question is not limited to a single application. Therefore, there are many directions that could be taken from our question that would allow for depper investigation.

**Original Response**: The question that was created by the group is an open-ended question. It does not suggest a certain solution to the problem and allows room for the group to explore the question with multiple designs. It is not a goal-based question and does not start with the phrases “what” or “can.” This means that the question is not aimed at achieving a specific goal and is not a yes or no question. We have structured the question to leave space open to explore any possibilities within the field of foldable robotics to find a solution for seed spreading. That said, there are no specifics required for the robot in terms of its movement/locomotion, size, or the specific materials that we plan to use.

---




**Modular: Is your question modular? How does it fit with other complementary research thrusts?**

**Updated Response**: Yes, the updated research question is modular. The research question is designed to combine different research areas (e.g., foldable robotics and bio-inspired robots). Therefore, there are different elements that can be combined from the different research areas that make the question very modular and approached from different thrusts.

**Original Response**: This research question is modular because it incorporates an element that has not been tested currently. Some devices have implemented a seed spreading design but not with degradable materials in mind. Degradable materials keeps this question relevant as new materials will always be created, which can aid in researching this question further. This research question can benefit the research field by using the same idea but applying it to different problems. A degradable robot can be applied to the medical field [9] and to home projects with differing problems, resulting in similar solutions.



---




**Team Fit: How does answering this question leverage your interests and abilities?**

**_James:_** Our updated research question even better leverages my interests and abilities than the first research question. While I still think the focus on biodegradability is positive and useful, I am interested in how to design mechanically intelligent systems. I think that improving on the Klann linkage mechanism by incorporating compliance into the links is an interesting research topic since it has many applications to robotics.

**_Cree:_** This project leverages my interests by working with a device that can benefit others. I am also interested in foldable robotics as a whole. I am always interested in finding different and creative ways to solve problems. My abilities are leveraged with some manufacturing and fabrication techniques that can be applied to this project. I enjoy working with my hands and applying the foldable application is part of what I want to do with my degree.

**_Katie:_** Answering this question helps leverage my interests in the design of robotic devices that can help benefit society. I am interested in the idea of foldable robotics, especially in finding more innovative ways to solve problems and in finding simple yet more effective ways to help the environment. The fabrication of our project will also leverage my abilities through the manufacturing of a foldable robot that is able to autonomously plant seeds.

**_Daniel:_** This project leverages more of my interests rather than skills, which I hope to get better at as the project continues. I am interested in researching the field of robotics when it comes to most applications, but especially when it comes to helping out either people or the environment. Due to this project being important to the future as robotics will continue to be even more widespread, creating a degradable nature in robotics is vital to the Earth’s ecosystems.



---




**Topic Fit: How does the question use foldable robotics techniques to answer it?**

**Updated Response**: The following response is still mostly accurate, since both our original and updated research questions focus on biodegrability, which lends itself to using foldable robotics techniques, since many foldable materials are also biodegradable (paper, cardboard, etc.). However, our updated research questions also includes the idea of using compliance to improve our design. Compliance can be used to make our design more mechanically intelligent so that the material properties of the leg mechanism are used to improve the functionality of the mechanism. Since many foldable materials are also compliant, and their compliance can be tuned by adding or removing material, focusing our research question on the use of compliance futher lends itself to using foldable robotics techniques to answer our research question.

**Original Response**: Our research question includes the requirement that possible designs apply the “concepts of foldable robotics,” though this statement alone does not demonstrate that our question was selected to be conducive to designs using foldable robotics. However, the biodegradability constraint and the application to seed spreading together suggest that foldable robotics is highly applicable to this problem. The biodegradability required by our design means that our design cannot include common materials used in robotics, most notably common metal materials used for robotic structures and electronics. Foldable robotic devices aim to use compliant materials that can be used for both the links and joints of robotic mechanisms, and many of these materials (e.g., paper) are biodegradable. The application of our design to seed spreading was selected so that the biodegradability of the design is desirable, since then a robot spreading seeds does not need to be recovered after it has completed its task, and will not cause environmental harm. Foldable robots can also have the benefit of being highly manufacturable, and this characteristic would be desirable for a robot that is intended to be left in the environment after it completes its task.


## References

[1] H. Kim, Y. Liu, K. Jeong, M. Sitti and T. Seo, "Dynamic analysis on hexapedal water-running robot with compliant joints," _2017 14th International Conference on Ubiquitous Robots and Ambient Intelligence (URAI)_, 2017, pp. 250-251, doi: 10.1109/URAI.2017.7992797.

[2] D. Aukes, B. Goldberg, M. Cutkosky, and R. Wood, "An analytic framework for developing inherently-manufacturable pop-up laminate devices," _2014 Smart Mater. Struct._ 23 pp. 094013, doi: 10.1088/0964-1726/23/9/094013.

[3] W. C. Flannigan, G. M. Nelson and R. D. Quinn, "Locomotion controller for a crab-like robot," Proceedings. _1998 IEEE International Conference on Robotics and Automation_ (Cat. No.98CH36146), 1998, pp. 152-156 vol.1, doi: 10.1109/ROBOT.1998.676345.

[4] M. Vespignani, K. Melo, M. Mutlu and A. J. Ijspeert, "Compliant snake robot locomotion on horizontal pipes," 2015 IEEE International Symposium on Safety, Security, and Rescue Robotics (SSRR), 2015, pp. 1-8, doi: 10.1109/SSRR.2015.7442941.

[5] A. Gollakota and M. B. Srinivas, "Agribot — A multipurpose agricultural robot," _2011 Annual IEEE India Conference_, Hyderabad, 2011, pp. 1-4, doi: [10.1109/INDCON.2011.6139624](https://ieeexplore-ieee-org.ezproxy1.lib.asu.edu/document/6139624).

[6] E. Fortes, “Seed Plant Drone for Reforestation”, _Bridgewater State University_, 2017, Accessed: 29- Jan- 2021, [Online]. Available: [https://vc.bridgew.edu/cgi/viewcontent.cgi?referer=https://scholar.google.com/&httpsredir=1&article=1033&context=grad_rev](https://vc.bridgew.edu/cgi/viewcontent.cgi?referer=https://scholar.google.com/&httpsredir=1&article=1033&context=grad_rev). 

[7] P. Kumar and G. Ashok, “Design and fabrication of smart seed sowing robot”, _Materials Today: Proceedings,_ 2020, Accessed: 31-Jan-2021, [Online]. Available: [https://doi.org/10.1016/j.matpr.2020.07.432](https://doi.org/10.1016/j.matpr.2020.07.432) 

[8] S. Prajapati, S. Rai, M. Mali, M. Kumar, and A. Kumar, “AUTOMATIC TREE PLANTING ROBOT,” vol. 8, no. 3, p. 6, 2020.

[9] S. Miyashita, S. Guitron, M. Ludersdorfer, C. R. Sung and D. Rus, "An untethered miniature origami robot that self-folds, walks, swims, and degrades," 2015 IEEE International Conference on Robotics and Automation (ICRA), Seattle, WA, 2015, pp. 1490-1496, doi: [10.1109/ICRA.2015.7139386](https://ieeexplore-ieee-org.ezproxy1.lib.asu.edu/document/7139386).


---
	
	
## PDF of Final Submission

Note: This does not include the updates made after changes were made in later assignments.

<embed src="https://arnoldjames98.github.io/assignment1.pdf" width="800" height="500" type="application/pdf" />

