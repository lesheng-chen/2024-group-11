# 2024-group-11
Overview of Software Engineering - University of Bristol MSc Group Project

Qiyuan Chen, ty23828@bristol.ac.uk, ty23828

Ahmed El Ashry, pu20789@bristol.ac.uk, ahmedcoolestman

Jialun He, cb23036@bristol.ac.uk, kkggbo

Ching-Chun Juan, iq23062@bristol.ac.uk, alicejuancc

Chen Lesheng，pp23991@bristol.ac.uk,chenlesheng2000(se2023passok)



# Group Photo
![image](https://github.com/UoB-COMSM0110/2024-group-11/assets/69910719/2221f7df-e9b5-4e8e-b8aa-bd7b3e7a9eb7)

# Introduction
With this project, we sought to create an engaging, visually pleasing and unique game. To achieve this, we wanted to introduce a twist to an easily recognisable and unique popular mobile platform and provide users with a computer version. We wanted to create a twist on a game we all played and loved growing up, so we decided to choose the frenzy-causing Flappy Bird from 2013. To make our game unique, we decided to add key differences, these include a multiplayer mode, a surprise attacking eagle enemy, coin collection, movable pipes, and customizable birds and backgrounds are just a few of the features that make our game unique and exciting. We worked together to achieve this game by following the agile software development methodology and instilling a strict test-driven and user-tested development ethos throughout our game development. We divided roles, planned tasks and collaborated on the implementation and documentation of features. This report will seek to outline the development process for our game, which we have called "Flight Chase" to illustrate the multiplayer "Chase" element at its core. 


# Game ideas:
## Game Idea 1: Flappy Bird Name: Chameleon Chase 
In this version of Flappy Bird, the pipes and the bird are dynamically changing colours. 
The twist is that the player must control the bird to match its colour with the upcoming pipes to pass through them.
The second twist is that the pipes move dynamically to trap the bird.
The third twist is that there are two players and the two players each control a racing bird (whose speed can be adjusted by the arrow keys)

## Game Idea 2: BrickBreaker

In "Pixel Bouncer," the classic brick breaker game takes a twist with a pixelated, retro aesthetic. 
Players control a bouncing pixel ball to break colourful pixel bricks in a dynamic and evolving environment. 
The twist comes with various power-ups, challenging obstacles, and a unique bouncing mechanic.
The speed and direction can be adjusted by the paddle. Hitting  a CERTAIN moving animal ends the game. 
There are multiple imitating levels of increasing difficulty and hitting a certain ball can reverse direction, change ball size, and reverse
gravity. 

## Game Idea 3: NS-Shaft

In the game, a player can control the left and right direction keys to move to the left or right. 
As the platform continues to rise, the goal is to allow the player to go down the maximum number of floors.
The player has a total of 12 points of health. If contacting the spikes on the ceiling or the spike platform, 
he will receive negative points of damage. 
The game ends when the health points reach zero or the player falls to the bottom.

  Twist:
  Items appear randomly to allow the player to restore health points or change the platform on the field.

  Challenges: 
  1. Implementing dynamic behaviours for various platforms (ordinary, fake, spring, crawler, spiked) and ensuring precise collision detection.
  2. Managing the health system and accurately calculating damage from spiked platforms.
  3. Balancing difficulty across platform types, adjusting spiked platform frequency, and the speed of the rising platform.



# Paper Protopyes
## 1. NS-Shaft
[![](./Images/Prototype1.png)](https://drive.google.com/file/d/1rs3dhTJLfhT_UdmvRboXBJdfwgNGlJ5o/view?usp=sharing)
## 2.Colourful Flappy Bird
[![](./Images/Prototype2.png)](https://drive.google.com/file/d/1P0VZh37yRYIMSRiT_hydD6VuRLFyvlS6/view?usp=sharing)


# Requirements

## Stakeholders and user stories
1. Game Developers and Designers
- I want a robust game engine that supports both 2D and 3D graphics, allowing for flexible and visually stunning gameplay
- I want an efficient debugging tool that provides real-time insights into the game's performance, helping me identify and fix issues quickly
- I want an easy-to-use scripting language that allows rapid prototyping and iteration of game mechanics, enhancing the development workflow
- I want a comprehensive multilayer framework that supports various modes (co-op, competitive) and provides tools for seamless online integration
- I want documentation that is clear, concise, and regularly updated, enabling me to understand and implement new features without unnecessary delays

Game Designers User Story
- I want an intuitive level editor that allows me to create diverse and engaging game environments with ease, allowing me to realise my creative visions
- I want access to a vast library of assets - incl. characters, objects and environments, to enhance the visual appeal of the game without compromising the
performance
- I want a flexible AI system that allows me to create challenging and dynamic enemy behaviours, contributing to an immersive and enjoyable player experience
- I want analytics tools that provide valuable player data, allowing me to make informed decisions about game balance, difficulty and feature improvement
- I want collaboration features that enable seamless communication with the development team, ensuring a smooth integration of design elements into the final
project
2. Game Publisher User Story
- I want a detailed, customizable analytics dashboard that provides info on player engagement, retention, and monetization, supporting data-driven decision
making
- I want a reliable and secure solution to protect IP while minimizing impact on player experience
- I want marketing tools integrated into the game platform, allowing for targeted promotions, advertisements, and community engagement to boost game visibility
and sales
- I want seamless integration with popular gaming platforms and storefronts, simplifying the distribution process and maximising the game's reach
- I want a transparent and collaborative relationship with the development team, including regular progress updates and open communication channels 

3. Players (End Users)
- As a player, I want the game to have the feature of saving the current progress so that I can restore the status after shutting down the game.

4. Investors and Financiers
- As an investor and financier, I want to experience constant updates and new content to ensure the game remains fresh, attracts new players, and retains old players.

5. Platform Providers
  Through platform providers, users can easily play this game on the platform, and the game possesses payment systems, achievements, and community interaction functionalities, 
allowing users to have a seamless gaming experience and added value services. At the same time, the platform's security and privacy policies can protect user information safety 
and interests.

6. Marketing and PR teams
  Through the efforts of marketing and PR team members, users are more easily attracted by the visual and narrative elements of the game, and extensive publicity and promotion 
provide users with more ways to learn about the game. Additionally, if users provide sufficient feedback, members of the marketing and PR teams can measure the effectiveness 
of marketing campaigns, optimize future marketing strategies, and better communicate with the media and players.

7. Quality Assurance Testers
- I want the game development team to provide comprehensive test plans and test cases to ensure the stability, performance and user experience of the game is optimal.
- I want to be able to use professional testing tools and automated test scripts to discover and report problems promptly.
- I want the development team to respond to test feedback, fix discovered defects promptly and provide detailed test reports and records to track and verify problem resolution.

8. Community Managers
- I want to build and maintain an active game community and promote communication, interaction and cooperation among players.
- I want to work closely with the development team to understand player needs and feedback and adjust game content and features to maintain community activity and user satisfaction.

9. Legal Advisors
- I want the game development team to comply with relevant laws and regulations, including on intellectual property, user privacy, consumer rights, etc.
- I want to maintain close communication with the game development team, resolve disputes and disputes involving legal issues promptly and ensure the legality and stability of the game.

10. Educational Institutions 
- I want the game development team to provide an educational version or educational mode to support teaching and learning activities.

<!-- 
## Worked Through Use Case Specification
Player/Gamer

User Story: I want to customize my bird's appearance in the chameleon chase

Customizing the Bird's Appearance

Actor: Player

Precondition: The player launched Chameleon Chase

Main Flow:

  1. The player selects the customization menu
  2. Accesses Bird Appearance Options
  3. Choose a Colour Scheme
  4. Applys Patterns and Accessories
  5. Previews Customized Bird
  6. Saves the Customization

Postcondition: The player's bird is updated according to their customization

Alternative: If the customized version is not saved, the default is selected

Exceptions: Technical issues/limitations stop customization from being saved

Success Scenario: Personalised gameplay with customized bird

Future: Customization options expand with new updates, and achievements (Such as bronze, silver, and gold for high scores) can be attached to the user's bird 
-->
## Use Case Diagram
![image](https://github.com/UoB-COMSM0110/2024-group-11/blob/main/Images/flappy_bird_diagram.png)


## Reflection
Our team learned a lot from using user stories and use cases. We found that a well-written user story helps guide our development work by making clear what needs to be done. Use cases are great too. They help us describe how the system should behave, ensuring that everyone in the team is on the same page. This approach improves our communication and makes our work more transparent and efficient. We also realized how crucial it is to keep getting feedback and to adjust our plans based on that feedback. So that, we can make sure our final product can meet our users' needs.


## Use Case Specification
![image](https://github.com/UoB-COMSM0110/2024-group-11/blob/main/Images/Use_Case_Specification.png)



## Design
### Class diagram

Regarding the system architecture, before the development process, we initially defined the core elements of the game: birds, pipes, coins, and user interface buttons. During this stage, we formulated the initial version of the class diagram.

![image](https://github.com/UoB-COMSM0110/2024-group-11/blob/main/Images/classDiagram1.png)

As the game development progressed, we needed more classes and functions to increase the richness of the game, make the code tidier and enhance readability. Throughout this process, we iterated through seven versions, and by the final version, the class diagram has developed into the following architecture. Besides the core elements, we also added a class of the eagle as the twist to the game, to increase the difficulty, giving players surprises. Also, we transformed the main game screens: Main Menu, Settings Menu, Level (Playing screen), and GameOverMenu into classes to facilitate independent development.

![image](https://github.com/UoB-COMSM0110/2024-group-11/blob/main/Images/classDiagram3.png)


### Behavioural diagram

"Flight Chase" is a game with a straightforward objective: players must navigate through obstacles, such as pipes and eagles while collecting as many coins as possible. Therefore, we made a behavioural diagram so we can have a clearer understanding of the interaction between objects during the development process.

![image](https://github.com/UoB-COMSM0110/2024-group-11/blob/main/Images/behaviouralDiagram.png)

### Design Conclusion

In conclusion, before game development, we applied the software engineering methods learned in the taught component of this module to outline a rough system architecture. This allowed us to develop prototypes, facilitate rapid consensus among all team members on the content and reduce communication time.
Through adopting the Agile methodology, we iterated through seven versions throughout the development process. Despite this, we set up the initial system architecture at the first stage but new ideas constantly emerged during development. The final class diagram is much more complex than the initial version, and there are also many differences between the original design documents and the final game results. Design documents cannot provide all the details in the development stage as a reference. We had to improve and add the content in design documents while considering the variables and methods needed for the new classes during development.
However, it is undeniable that a clear system architecture is essential for the development process. It is the game's backbone and provides the foundation for other design elements.

# Evaluation

## Quality Evaluation
We used two methods, Think Aloud and Heuristic Evaluations, in the quality evaluation. They helped us understand the users’ thoughts well and helped with improvements in the next stage.

### Think Aloud
We have set up two tasks for Think Aloud: 
1. Change bird color.
2. Get 20 points.

In the process of completing the task, we take into account the user's behaviour and language. We invited 5 users to conduct this test and compiled the results of 3 more representative users.

Think Aloud 1:
Advantages: The game rules are simple and easy to understand. Also, it is easy to use and different objects have clear identification.
Disadvantages: People can't find the keyboard keys required for the game and don't know how to change some settings.

Think Aloud 2:
Advantages: Most people have experience in the same type of games and can understand and complete tasks well.
Disadvantages: People don’t know the function of elements different from traditional games, such as yellow dots that increase points.

Think Aloud 3:
Advantages: It can simulate gravity to make it fall and people can see your current score and life.
Disadvantages: People will not die when they hit bottom or top, which reduces the difficulty and playability of the game.

### Heuristic Evaluation
| Interface                 | Issue                                                        | Heuristic(s)            | Frequency 0 (rare) to 4 (common) | Impact 0 (easy) to 4 (difficult) | Persistence 0 (once) to 4 (repeated) | Severity = Sum Total of (F+I+P)/3 |
|---------------------------|--------------------------------------------------------------|-------------------------|----------------------------------|-----------------------------------|-------------------------------------|------------------------------------|
| Game tutorial interface   | There are no detailed operating instructions and I don’t know how to operate and don't know the rules of the game. | Help and documentation | 4                                | 4                                 | 2                                   | 3.33                               |
| Game settings menu        | Can't pause during game play                                  | User control and freedom| 3                                | 3                                 | 3                                   | 3.00                               |
| Game settings menu        | Navigation menus hide several important features, and users must remember where to find them. | Recognize rather than recall | 2                              | 2                                 | 4                                   | 2.67                               |
| Game tutorial interface   | Two-player mode has special rules different from the single-player mode. | Help and documentation | 1                                | 4                                 | 1                                   | 2.00                               |
| Game display interface    | The pattern of gold coins is not obvious and can easily be misunderstood. | Consistency and standards | 4                              | 1                                 | 4                                   | 3.00                               |
| Difficulty selection interface | No option to increase difficulty                          | User control and freedom | 2                                | 2                                 | 3                                   | 2.33                               |

According to Heuristic Evaluations, we found three issues with Severity at 3 or above indicating issues that need us to solve them in time. The key problem was that there were no detailed operating instructions, players didn't know how to operate and the rules were unclear. Its Severity is 3.33, which is the highest among all projects. It shows that it will greatly affect the user experience.

Combining Think Aloud and Heuristic Evaluations, we found that there are three major problems:
1. There are no detailed operating instructions and users do not know how to operate.
2. The game cannot be paused during the game.
3. Some game elements are not very recognizable.

These issues have been mentioned many times in Think Aloud and have relatively high Severity in Heuristic Evaluations. This means we will focus on and solve them in the next step. We held group discussions and identified solutions to address these issues in the next step.

Solution:
1. Added text guidance to the game to explain the rules.
2. Add a button to pause the game in the game.
3. Optimize the game graphics and replace the original elements with simple easy-to-read patterns, such as changing yellow dots to coin patterns.

We believed that after solving these problems, the quality of our game would be significantly improved.

## Quantitative evaluation

### NASA TLX
We use NASA TLX to evaluate the difficulty of the game. We invited ten participants to rate the easy mode and the difficult mode. The following are the scoring results:

Easy Mode: NASA TLX
| Participant Number | Mental demand | Physical demand | Temporal demand | Performance | Effort | Frustration |
|--------------------|---------------|-----------------|-----------------|-------------|--------|-------------|
| 1                  | 2             | 2               | 1               | 1           | 1      | 4           |
| 2                  | 11            | 8               | 13              | 12          | 16     | 3           |
| 3                  | 18            | 3               | 20              | 6           | 10     | 15          |
| 4                  | 4             | 5               | 8               | 6           | 4      | 8           |
| 5                  | 10            | 12              | 10              | 10          | 9      | 9           |
| 6                  | 3             | 3               | 3               | 3           | 3      | 1           |
| 7                  | 8             | 10              | 11              | 9           | 8      | 9           |
| 8                  | 5             | 5               | 6               | 6           | 6      | 4           |
| 9                  | 12            | 13              | 12              | 12          | 11     | 10          |
| 10                 | 2             | 1               | 1               | 2           | 3      | 2           |

Hard Mode: NASA TLX
| Participant Number | Mental demand | Physical demand | Temporal demand | Performance | Effort | Frustration |
|--------------------|---------------|-----------------|-----------------|-------------|--------|-------------|
| 1                  | 10            | 6               | 10              | 6           | 16     | 16          |
| 2                  | 14            | 16              | 18              | 14          | 17     | 15          |
| 3                  | 20            | 12              | 20              | 13          | 15     | 18          |
| 4                  | 10            | 16              | 15              | 16          | 20     | 17          |
| 5                  | 18            | 18              | 16              | 15          | 17     | 20          |
| 6                  | 15            | 16              | 15              | 14          | 18     | 14          |
| 7                  | 12            | 13              | 15              | 12          | 14     | 13          |
| 8                  | 10            | 15              | 18              | 15          | 12     | 8           |
| 9                  | 15            | 16              | 14              | 15          | 14     | 13          |
| 10                 | 5             | 5               | 10              | 10          | 11     | 10          |

Final Result
| Participant Number | Easy Mode Workload | Hard Mode Workload | Difference |
|--------------------|--------------------|--------------------|------------|
| 1                  | 11                 | 64                 | -53        |
| 2                  | 63                 | 94                 | -31        |
| 3                  | 72                 | 98                 | -26        |
| 4                  | 35                 | 94                 | -59        |
| 5                  | 60                 | 104                | -44        |
| 6                  | 16                 | 92                 | -76        |
| 7                  | 55                 | 79                 | -24        |
| 8                  | 32                 | 78                 | -46        |
| 9                  | 70                 | 87                 | -17        |
| 10                 | 11                 | 51                 | -40        |

To perform a significance test for NASA TLX, we used the Wilxocon signed-rank test. We analyzed the test results and believed that only a p value of 0.05 was significant. The following is the detection process:

Wilcoxon Signed-Rank Test Calculator process
| Difference | Rank | Signed Rank |
|------------|------|-------------|
| -17        | 1    | -1          |
| -24        | 2    | -2          |
| -26        | 3    | -3          |
| -31        | 4    | -4          |
| -40        | 5    | -5          |
| -44        | 6    | -6          |
| -46        | 7    | -7          |
| -53        | 8    | -8          |
| -59        | 9    | -9          |
| -76        | 10   | -10         |

We can conclude from the above that the positive sum of ranks is 0 and the sum of negative ranks is 55, so the W value is 0 (the W value is just the smaller of the positive and negative sums). This is well below the W value of 8 required for statistical significance. A W value of 0 is statistically significant with a p-value of 0.05. These results confirm that the increase in the difficulty of our game's "Hard" mode relative to the "Easy" mode is statistically significant. In addition, the result of W test statistic = 0 is consistent with a p-value of 0.005, further illustrating that our hard mode is more difficult than expected.

## Testing

### White Box Testing
We first find the code segment for collision implementation and set two tasks:
1. Boundary condition test: Check whether the object can correctly detect a collision when it touches the boundary.
2. Overlap test: Test whether the system can accurately calculate and respond to collisions when two objects overlap.

After the test, we found that the actual results were the same as the expected results and that there were no functional defects or abnormalities.

### Black Box Testing
We open the archive as a new player and set two tasks: 
1. Score accumulation: whether you can add points by interacting with gold coins or passing through pipes.
2. Highest score record: Whether the highest score scored by a player will be recorded.

After the test, we found that the actual results were the same as the expected results and that there were no functional defects or abnormalities.

## Implementation

Our game is a side-scrolling jumping game, where players control a bird to dodge pipes and eagles flying in from the right side of the screen while collecting coins to score points. In the early stages of development (before version 0.7), our team used graphics drawing methods in Processing to represent various objects. However, starting from version 0.7, we incorporated art and sound assets and refactored the code.

The main classes in our game include Button, Bird, Pipe, Coin, multiple Interface classes (Main Menu, Settings Menu, Level, and Game Over Menu), and Eagle. Most of these classes have relatively simple functionalities. The Button class primarily handles modifying other objects (such as changing the bird's color or the current menu) upon detecting mouse clicks. Interface classes are used to manage and present the user interface (UI). The Coin and Pipe classes generate randomly at certain positions in the game and move leftward periodically. The Eagle class rapidly moves from one position toward the bird's location and detects collisions.

Implementing the Bird class posed the greatest challenge, as the bird object needed to perform various functions, including responding to player commands (jumping), interacting correctly with other objects (pipes, coins, eagles), allowing players to change its color and quantity, implementing complex animation effects, and incorporating a health system. The three main challenges encountered were Collision Detection, Bird Transit Through Screen Borders, and Two-Player Mode.

### Challenge 1: Collision Detection.
There are 4 type of entities in the level: the player-controlled bird, pipes, coins, and eagles. Handling the collisions between these is an important part of our game. Initially, I thought to use double dispatch to implement this feature but after writing the collision interface and completing the bird-pipe collision detection methods, I realised this was unnecessary. In reality, only the bird colliding with pipes, coins, and eagles occurs in the game. Using double dispatch would lead to some methods that would never be implemented. Thus, I abandoned double dispatch and simplified collision detection to circle-to-circle collision detection (bird with coins and eagles) and circle-to-rectangle collision detection (bird with pipes). Circle-to-circle collision detection is simple, only requiring checking whether the distance between the centres of the two circles is less than the sum of their radii. However, circle-to-rectangle detection is more complex, first requiring the identification of the closest point on the rectangle to the circle and then determining if the distance from this point to the circle's centre is greater than the radius. This challenge is more of a mathematical challenge, but after spending some time understanding the principles, the coding implementation was straightforward. 

### Challenge 2: Bird Transit Through Screen Borders.
In the early versions of the game, the bird could not fly out of the top or fall out of the bottom of the window. Observing other team members experiencing our game, they would keep the bird on the floor for a long time as an easy way to dodge pipes. So, I decided to modify the game mechanics to allow the bird to transition between the top and bottom borders of the screen: when the bird falls off the screen at the bottom, it reappears from the top, and vice versa. Implementing this feature took quite some time. To make the animation look smooth, I ensured that the part of the bird disappearing from one side of the screen and the part appearing on the other were always complementary. After the bird's body completely left the screen, its position would be adjusted to the opposite side of the screen. This required changes not only to the existing method of displaying the bird but also to the collision detection methods (the bird should have collision detection for both parts during transit), and the death animation of the bird (after the bird dies, it should not appear from the top when it falls off the bottom of the screen). After a long time and numerous tests and adjustments, the effect finally met my satisfaction. 

### Challenge 3: Two-Player Mode.
The two-player mode is a highlight of our team's game, allowing two players to choose birds of different colours to play together and avoid pipes that match their bird's colour. After completing the single-player mode, we began to implement the two-player mode. The two-player mode implementation is not as simple as adding another bird entity; it accompanies many new features and adjustments to existing code. This includes adjustments to the pipe generation frequency: the highest in single-player mode, followed by the two-player mode with birds of different colours, and finally, the two-player mode with birds of the same colour, as it's necessary to lower the game difficulty if players have the same colour and need to avoid all pipes. Adjustments to the eagle's behaviour are required - in the two-player mode if both players are alive, the eagle will always attempt to lock onto a different player each time. The game's end conditions also need modification; when one player dies, the other should be able to continue playing, among other things. Implementing the two-player mode took us quite some time, and occasionally, new bugs would arise during the implementation process. However, after meticulously adjusting and testing all methods one by one, the two-player mode finally ran smoothly.

## Process


Our team collaborated effectively throughout the development process. We utilised various tools and methodologies to streamline our workflow and ensure productive teamwork.

Communication

We primarily used WhatsApp messaging for communication, having a running group chat to share updates, ask questions and issue reminders in real-time. This allowed us to maintain an agile approach, and quickly change tac if things weren’t working. Creating polls for meetings, decision-making and design choices allowed a democratic and team-centred approach when creating the game. Additionally, we often communicated using our Git messages, through commits and pull requests - allowing team members to stay up-to-date with each other’s changes.

Project Management

In addition to effective messaging to ensure tasks were carried out and deadlines were met, we utilised a shared KanBaan board to ensure all tasks were carried out. This enabled team members to implement features directly, even if they had missed meetings where discussions on the next steps took place. Alongside this, we used the existing communication channel in WhatsApp to assign responsibilities, track progress and prioritise tasks effectively. Team members were then given individual freedom to use certain task management tools independently to ensure tasks were carried out, with some opting for Notion and others for Trello. This allowed autonomy within the development process. 

Version Control

For code collaboration and version control, we relied on Git’s Version Control. We wrote code using the VSCode IDE before uploading it to Git. When needing to collaborate, users could pull/push code as required with separate branches for each member’s testing and features and another develop branch for incremental changes, before they would be continuously merged into the main branch. This ensured everyone had access to the latest codebase and could contribute seamlessly. We frequently implemented pair programming or discussion of features in-labs, with subsequent implementation to ensure collaboration and minimise errors. 

Documentation

Maintaining comprehensive documentation was crucial for clarity and knowledge sharing. We relied heavily on our in-person meetings to verbally discuss the project, next steps and features to implement. There, team members would take turns to illustrate their work and ensure each member was comfortable understanding the code and the result. This was backed up by information available on GitHub and on the WhatsApp communication channel. Alongside this, we used the Update Log to discuss the latest changes for each version. We discussed using a dedicated documentation tool but agreed that the project's scope meant it wasn’t needed initially. As the project expands, this is an area to look into, with more robust documentation required. 

Team Roles and Responsibilities

We assigned roles from the beginning of the project, which ensured clarity in responsibilities and accountability, facilitating a smooth development process. Project management was completed rotationally. This allowed team members with more expertise in one area to guide others onto the correct path. Correspondingly, members were able to contribute more in different fields. 

Jialun led the coding and code development process and the team responsible for code implementation and execution, while also helping out in design and animations. Qiyuan worked closely with Jialun on development and execution and implemented sound for the project alongside researching, implementing and utilising resources and libraries. Alice was responsible for the design and interface, and coding the main menu, buttons and pipes, alongside general gameplay design and class design. Ahmed was responsible for project planning and design as well as testing (both internal and external), creating focus groups, and carrying out evaluations as well as unit testing and code tests. Chen was responsible for the development and helped implement difficulty levels, accelerate bird/pipe movements and control gameplay physics. 

Team Evaluation
Our collaborative efforts were characterised by open communication, mutual respect, and a shared commitment to project success. Regular team meetings allowed us to discuss progress, address challenges, and brainstorm solutions collaboratively. Each team member brought unique skills and perspectives to the project, contributing to a well-rounded and innovative final product.
We recognised the importance of adaptability and flexibility in response to evolving project requirements and feedback. Team members were proactive in seeking clarification, providing constructive feedback, and offering support to one another when needed. Our teamwork was instrumental in overcoming challenges, achieving milestones, and delivering a high-quality project.

## Conclusion


Reflection

This project was an engaging opportunity from start to finish, allowing us to develop software engineering skills in a realistic setting to deliver a useful product. Initially, we were nervous about the execution of the project on time but increased in confidence when achieving our targeted milestones. The most important point for us was delivering an MVP before Week 4. This gave us confidence in ourselves, the agile approach and the tools and processes we used. Working together and learning more about each other along the way was equally rewarding as picking up new skills through the term, and having a team of 5 students from international backgrounds allowed us to share new perspectives and experiences. 

Over time, the scope of the project changed and developed. We started conservatively, in keeping with the agile approach, but were constantly able to outdo and outperform our expectations. In the end, we executed almost every feature concerning the project. 

Lessons Learned

Throughout the project, we learned key technical and professional skills. Technically, we learned a new Development language in Processing, understood the basics of game development, and implemented the Agile Software Engineering approach. Professionally, we learnt key skills in  time organisation and decision-making. Individually, each member benefited from the technical competencies acquired to carry out their tasks whereas as a team, we benefited from each other’s knowledge, curiosity and experiences. Successfully, we were able to design a game that met with the project brief and was enjoyable and challenging to play. However, we faced setbacks along the way, especially in streamlining work, preventing overlapping tasks and ensuring strict timing and scheduling. Despite this, we all enjoyed and learnt from working with each other. 

Challenges Faced

The project was not without technical challenges, as our vision for a multi-player game posed some tough issues. Technically, that was an important challenge to maintain separate sprites, scores, pipes, eagles, and movements for each player. This was achieved through careful software engineering, effective testing, and a structured object-oriented development approach. Likewise, ensuring game difficulty was appropriate was a key factor, with several challenges such as pipe movement, collision physics, and the movement of an enemy eagle. Ensuring these challenges were met was a well-planned object-oriented code approach which allowed for agility and versatility throughout the development process. Ensuring all this worked well, was a key challenge professionally, requiring dedication and commitment from team members as well as decision-making, task prioritisation and effective communication, which was streamlined enough for success, but could do with improvement. 

Future Work

To improve the game further and continue development, we have compelling ideas. We have discussed additional elements such as newer levels, 3-dimensional gameplay, multi-player modes via internet connectivity, and customisable “suits” or emojis to replace birds - with a user-led character store to purchase new “suits”/characters - purchasable with game tokens. These ideas would all require user and stakeholder feedback, prompt planning, evaluation and testing and a robust plan to carry out a new round of agile development. However, with the skills learnt from this project, and a greater influence on robust documentation and daily communication, we believe we are up to this new and exciting task. We hope you enjoy playing our game and look forward to developing it further following feedback, aiming for the perfect user experience. 

