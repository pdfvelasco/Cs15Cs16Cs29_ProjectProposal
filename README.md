# CS3SY26_ProjectProposal by Aline Teresa Mendoza from CS Unit of PSHS


## Project Proposal Template:

### Project Title or Name of the Application	:
### Section			   	      : Cesium
### Group Members			    : GUTIERREZ, GRATELA, VELASCO
### Date (Proposal Date)  : Nov 12, 2026

### Project Description:

- The project would be designed as a roleplay game that uses user interactions with educational NPCs to achieve desired academic understanding. These interactions would consist of two main parts: dialogue and interactive, with the former being preliminary lessons that guide the player while the latter consists of problems sourced from online resources. Additionally, mission-tasks would be used to incentivize players into completing certain interactions and thus improve the performance in such. This would address one main problem that many scholars experience: the lack of motivation when studying. Students often fall into a cycle of demotivating study sessions that spiral into burn out and discouragement, with our project seeking to solve this problem. Rather than jumping straight to problem sets over problem sets, this game will aim to make studying more engaging and fun by making players study to progress. This helps students set a clear goal as to what they wish to accomplish through studying.


- Character() -
Attributes: name, level |
Name would be predetermined here.
Level will be set to zero at the start.
Methods: level_up() |
This will act as a template for other classes.

  NPC() -
Attributes: name |
Name would be predetermined here.
Methods: talk() |
This class will only talk to the player, without doing anything else. It will also act as a template for other classes.

  Teacher(NPC, Character) -
Attributes: name, level, subject |
Name and Level attributes would be inherited from NPC and Character classes respectively
Subject is independently defined here
Methods: talk(), level_up(), teach() |
This class inherits from the Character and NPC classes, and it can either talk to the player normally, or teach the player either how to play the game or lessons related to their subject. The depth of the lesson depends on the level. After some time, it can also level up and give more information.

  Questioner(NPC, Character) -
Attributes: name, level, subject |
Name and Level attributes would be inherited from NPC and Character classes respectively
Subject is independently defined here
Methods: talk(), level_up(), ask_question(), check_answer() |
This class inherits from the Character and NPC classes, and it can either talk to the player normally, or ask the player questions about their subject. The difficulty of the questions depends on the level, and the questions come from a fixed list. After some time, it can also level up and give harder questions.

  Player(Character) -
Attributes: name, level, xp |
Name and Level attributes would be inherited from the Character class.
XP would be automatically set to zero.
Methods: level_up(), interact(), answer(), use_hint() |
This class inherits from the Character class, and it acts as the user’s way to interact with the other classes. It can answer questions and gain XP to level up. As its level increases, it also unlocks more hints to the questions.


- The target demographic would be composed of students of any age who are interested in studying Biology, Chemistry, and Physics, from the very basics all the way to the complex. The youngest of generations will also be catered for given the projects lowering the barrier of entry for studying these subjects as it is designed to be technologically easy to use and understand. Aside from the newest, it can also help those who do not learn through the traditional classroom/study setting by introducing them to an alternative way of engaging with knowledge. Overall, our demographic would be those drawn to discovering new ways of learning, and then synthesizing their knowledge for a better tomorrow.
 

- The description is then followed by the class diagram, depicting clearly what was described.

![Class Diagram]([https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png](https://drive.google.com/file/d/1LyIv-edkXH4uWzO8tnoGRB8TvOYI2guu/view?usp=sharing))

### Goals:  The users would be able to learn and understand more about various topics across Biology, Chemistry, and Physics after using the application. The application would also provide interested people with an alternative engaging way to learn other than the traditional way of studying.


Describe the long term outcomes of your project followed by a couple of objectives to meet the goals stated in this paragraph

- Objective 1: Ensure all questions and their respective answers are understandable, factual, and match their assigned difficulty level by doing proper research.
- Objective 2: Make sure the codes are written properly to be able to execute the application efficiently and effectively by debugging and making proper adjustments by applying the lessons of OOP.
- Objective 3: Ensure that the application maintains to be fun and engaging by performing test runs and adjusting accordingly before the final execution of the application. 


[Click here for Rubrics and Sample projects](https://docs.google.com/document/d/1xKd1CqK6DcNWS2_oJPBNtY5n3I3Hqiw8FY3W295Iqfk/edit?usp=sharing)
