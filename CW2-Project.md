# MA Advanced Modelling and Animation 2018: Create a Piece of Interactive Entertainment in 3rd person in Unity (CW2) _by Arjun Khara_

#### 1. Introduction
#### 2. Team Organisation
#### 3. Key Milestones
#### 4. Design Decisions
#### 5. Design Material and Assets
#### 6. Code and Technical Considerations
#### 7. Self-Reflection
#### 8. Conclusion


## 1. Introduction
19-Fortuna is a third-person game built in Unity by a group of seven members. The game centers around the narrative of a mech robot that mines for tholin crystals on the eponymous asteroid, (i.e 19 Fortuna). The asteroid, rich in tholin — a highly commodofied material on Earth — is also teeming with rock monsters who pose a problem for the mining mech. The mission is to drill as many tholin crystals as possible while avoiding the rock monsters. Armed with only a drill, and an electromagnetic pulse that generates when the mech appropriates a tholin crystal for use, the main strategy of the game is drill for minerals and avoid being attacked through motion mechanics in the game — strafing, dodging, and keeping out of proximity from the rock monsters. At each stage of this report, I have documented both the actionable steps as well as my reflections on these steps as a consequence to the project's successful outcome.
![alt_tag](https://github.com/arjunkhara/3D-Modelling-Repo/blob/master/cw2-images/19-Fortuna.jpg)
_Team Photo Credit: Arjun Khara_

This project documents the creation of the game '19-Fortuna' and my part, records, and reflections as project manager of the group. This document also serves as a submission for assignment 2 for Advanced Modelling and Animation (IS74023B) at Goldsmiths College, University of London. This  submission forms the individual write up component, presented in a development diary style, and records how the team was organised, key milestones and design decisions, assets, code, design material, and self-reflection on what worked well, what was less successful, what I may focus on next if I had more time, or what I would change if starting the whole process again.

## 2. Team Organisation
The team for this project comprised 7 members - 4 from the MA Computer Games Art and Design programme, and 3 from the MA Independent Games Design programme. The organisational chart for this project is detailed below. Owing to the relatively larger team size, I was able to assign each team member a specific role and responsibility, based on that team member's forte and desire to specialise. As such, each member was responsbile for one primary / vital function of the project, but also served in a supporting role for the every other team member. From this organisation system, I was able to keep a rotating roster of responsibilities for every member, with a key area of focus assigned to each. The team comprised:
![alt_tag](https://github.com/arjunkhara/3D-Modelling-Repo/blob/master/cw2-images/Organisational-Chart-19-Fortuna-01.png)
_Organisational Chart Credit: Arjun Khara_

1. Project Leader: Arjun Khara  
2. Art Director: Touraj Khosravi  
3. Lead Programmer: Thomas Tanugi  
4. Modeller: Daniel Nicholson  
5. Animator: Doruk Hasdogan  
6. Environment Artist: Ece Hasdogan  
7. Sound Artist: Billy Wichaya Karnchanapee  

However, given each member also has additional responsibilities, the flip side of the team's organisation includes the following arrangement for roles and support staff, which each team member was required to uphold. The following list details each team member's name and the assigned responsibilities:  

1. Arjun Khara (Project Leader; Game Researcher; Supporting Modeller; Programmer Bug Fixing)  
2. Touraj Khosravi (Art Director; Crystals Designer; Modelling Retopologist)  
3. Thomas Tanugi (Lead Programmer; Supporting Modeller; Bug Fixing Oversight)  
4. Daniel Nicholson (Modeller for Spaceship; Modeller for Crystals; Supporting Programmer and Bug Fixer)  
5. Doruk Hasdogan (Animator; Environment Artist Support; Unity General Support)  
6. Ece Hasdogan (Environment Artist; Modeller for Monsters; Supporting Modeller)  
7. Billy Karnchanapee (Sound Artist; Support Programmer; Unity Bug Fixing; GitHub Repository Management)  

Within this roles-based list, each member's responsibilities overlapped with other members to create a cohesive team that could lean on each other to accomplish set tasks. The game's requirements, though simple as per the assignment brief, nonetheless merited a more sound strategy, given the size of our team. Therefore, each team member was required to exercise their discretion over their selected area of responsibilities and provide additional support to the rest of the team. Because of the team's size and time of year (towards end of term) getting the entire group together was a challenge. Further work cycles and key milestone measurement representatives were also established to ensure that each task was being looked after and each dependency was being delivered on time.
![alt_tag](https://github.com/arjunkhara/3D-Modelling-Repo/blob/master/cw2-images/19-Fortuna-Venn-Responsibilities-01.png)
_Responsibilities Venn Diagram Credit: Arjun Khara_


1. Thomas Tanugi — drone leaving the mech; face the mech and turn
2. Billy Karnachanapee — work on making the drill particles more believable
3. Billy Karnachanapee — Skyrim model movement of mech camera pan
4. Billy Karnachanapee — crystal breaks down
5. Touraj Khosravi — mech texture and materials
6. Arjun Khara — monster attacking animation
7. Ece Hasdogan — monster variety
8. Arjun Khara — UI tutorial for players
9. Doruk Hasdogan — crystal prefabs
10. Arjun Khara; Ece Hasdogan; Doruk Hasdogan — Youtube video demonstration
11. Billy Karnachanapee — total sound implementation
12. Doruk Hasdogan — replace drill animation

We therefore allocated three compulsory meet ups for all hands, followed by regular sessions where those who could meet in person did so, while the others dialed into the meeting via Skype. At all stages, the team was kept apprised of each other's activities since all members were, to a greater or lesser degree, involved in everyone else's work. We therefore adopted an agile dependencies model through which the team completed their tasks and marked off their milestones in parallel, rather than sequentially. This ensured that the team maximised the ample resources afforded to each, and that no one person was laden with singularly massive tasks.


## 3. Key Milestones
The key milestones for this project consisted of the following six tasks:  
1. Generate game concept  
2. Agree on roles and assign responsibilities  
3. Set up dependencies for tasks  
4. Establish first-run MVP and alpha testing  
5. Run bug-fixing and establish beta testing  
6. Revisit user-testing reports and demonstrate final version  

###### 1. Generate Game Concept
The game concept began as a series of sketches and discussions on what types of genre would best suit the third-person player game built in Unity. Given also the size of the group and to manage the expectations of each member, it was decided that a game set in the future would work best. The game concept that was settled was a non-duelling space mining game that challenged the talents of each of the group's members. We wanted a game that afforded ample opportunities for each member without over exceeding the assignment's mandate or taking on too many tasks that we would not be able to achieve in the limited time frame. Ultimately, it was decided that a search and self-rescue game that limited weapons and built in a low-poly style would best meet the challenges and rigours of the game. The concept was further refined to reflect a future setting (Year 2118) in which a mining robot would drill for crystals while avoiding rock monsters that inhabit the asteroid. Once the game's concept was finalised, the next key milestone could be established. The game concept key milestone was met on February 23, 2018.

###### 2. Roles and Responsibilities
With the game concept finalised, a definition of all the roles and responsibilities was drawn up. Each member then picked their roles based on their (i) interest and (ii) skills within that area of speciality. My role was project leader, assigned to oversee all aspects of the team and to guide the larger decisions of the project and manage the team towards its completion. Each member picked their roles and responsibilities which were agreed on by all the other team members. Because the team members already knew each other before the project commenced, there was an amicable and cordial relationship maintained throughout. Familiarity with each other's expertise was also instrumental in getting the team to co-operate intrinsically with each other. Competing interests were therefore kept to a minimum and each team member readily accepted their roles within the game and took their responsbilities seriously from the outset. The assigned roles and responsibilites milestone was completed on the 27 February 2018.

###### 3. Dependencies for Tasks
Once the roles and responsibilities were finalised, a dependencies roster was established to provide all the team members with an overview of what the large milestone tasks of the game were. This dependencies roster (below) was vital in getting all members on the same page with respect to the overall timeline and goals. The dependencies roster was updated at intervals but the overall timeline remained the same. Some flexibility was built into the roster to ensure that individual members who faced scheduling or conflicting tasks were catered for. Setting up the dependencies roster took some time since I was responsible for working with each of the team's members to understand and accommodate their individual requirements for the game, expectations from themselves and from each other, and to balance the timeline with realistic goals and asset management. These meetings took place individually, as a one-to-one between myself as the project leader and each team member, since I needed to know at a discretionary level if any team mates had concerns about the performance and reliability of the other team members. Since I recruited each team member, it was my responsibility to ensure that all were happy and eager to work with the others and towards the final result. I also had to manage expectations on the grades that each team member wanted, and ensured that all of us were committed to creating an exceptional piece of work that went well beyond the standards required by the course and assignment. I am happy to reflect that each team member, without exception, expressed an intense desire to work at a distinction level, and not just settle for a pass. The dependencies milestone was completed on 5 March 2018.

###### 4. First Run MVP and Alpha Testing
The first run MVP and alpha testing was settled for three weeks before the assignment due date, which was initially set for 10 April. Also, Thomas and I were both due to leave for internship and project research work at the end of the term, on 23 March 2018, and so we wanted to get the project completed by 20 March 2018. All of us agreed that the team would need to meet regularly, at least twice a week, for a build session that lasted at least 7 hours. This was accomplished with much success and the team met six times between the first milestone and the end of the project, and put in a total of 400 hours of work to get the game completed and to a high standard. Therefore, the first run MVP and alpha testing was ready ahead of schedule on 17 March 2018.

###### 5. Bug-Fixing and Beta Testing
Running bug-fixing and beta testing was conducted immediately after the alpha testing phase was completed, and marked another milestone in our team's endeavours. The bug-fixing took a total of two days, with four of the seven team members with programming experience, working on the project. We knew that bug-fixing would be a time-consuming and necessary process, and that we would run out of time closer to the end date of the project. We therefore assigned a permanent bug-fixer from our group to test the game during design and development. Billy was assigned as bug fixer and his role, beyond sound recording, was to test the game and involve other students from different programmes to test the game and give their feedback. The game was therefore put through its paces during development, which proved a wise decision on reflection given the number of bugs we caught. The bug-fixing report and general beta deployment was ready on 19 March 2018.

###### 6. Further User-Testing and Demonstration
On 23 March 2018 the team had a fully-working prototype of the game that we demonstrated to our class and to Steve and Mike (our instructors). The game was well-received, with feedback going mainly to refining existing assets. Mike even praised the ingenuity of our game, and particularly paid praise to how the team had managed to simplify and drill down to the primary feedback loops that made the game work. Other feedback included refining drilling effects and navigation of the robot to make it look less stick-like. On the whole, however, the feedback was highly positive from both our instructors and our class mates, some of whom took to playing the game after our demonstration. I documented each piece of feedback from our instructors and class mates during these demonstration sessions, and ran them by the group in our meetings afterwards to assess whether the feedback was viable for inclusion or if it could be fixed at a later date, since some of the feedback involved tweaks that went far beyond the course requirements and time allocated. In the end, the project was a success and marked a key milestone of MVP completion. Beyond this date, we continued working on making existing assets stronger, and augmenting the overall distinct gameplay experience.



## 4. Design Decisions
19-Fortuna is based on a space-mining operation that takes place a hundred years from the present. Because of the game's nature, I opted to be the main researcher given my background with astronomy as a serious hobby and past minor study at degree level. The game was based on a real life asteroid, called 19-Fortuna — an asteroid orbiting in the belt between Mars and Jupiter — and therefore required some attention to the realities of what a mining operation on the asteroid might be like so that our design decisions were fully informed and guided. Discovered on 22 April 1852 by John Russell Hind, 19-Fortuna is a main-belt asteroid approximately 250 km in diameter. The size alone provided for ample level and environment design, which is why I researched asteroids within this size band. The size would provide an adequate limit for the team's environment modellers to visualise and design. 
![alt_tag](https://github.com/arjunkhara/3D-Modelling-Repo/blob/master/cw2-images/19Fortuna-LB1-crab-mag11.jpg) 
Photo Credit: I, Kevin Heider CC BY-SA 3.0 https://creativecommons.org/licenses/by-sa/3.0 or GFDL http://www.gnu.org/copyleft/fdl.html, via Wikimedia Commons.

With the space-mining theme in place, the group turned towards the actual gameplay mechanics that would drive the design. It was agreed that for a space mining operation to be feasible, the asteroid would need to have a certain class of minerals that would be of interest to scientists and terra-formers in the present. Once again, 19 Fortuna provided the perfect foil: the asteroid is rich in a mineral called tholin, which might yield potential chemical properties of interest to energy markets. Therefore, we decided that tholin would be the main material that the mining operation in 2118 would be concerned with. While in reality tholin exists as a granulated mineralised deposits, for the purposes of the game's design, we decided that the tholin deposits would be in the form of crystals, which would provide a more aesthetically pleasing and identifiable design for the game and its players. 
![alt_tag](https://github.com/arjunkhara/3D-Modelling-Repo/blob/master/cw2-images/Star-Field-Generation-19-Fortuna.jpg)

The crystals for the robot to mine were therefore designed to reflect the speculated properties of tholin — a lavender-turquoise hue with a hexagonal crystalline shard appearance. The environment design of the game was therefore framed by this research. Because crystalline structures usually exist in the presence of some liquid, we decided that the environment should also be designed with hydrocarbon lakes, which would add to the visual engagement of the game. Finally, given the lack of any atmosphere on 19 Fortuna, the game's sphere would be dark against a star field, with actual constellations and planets within the orbital view. Lighting for the levels were therefore determined to come from the crystals itself that would glow from within, and provide players with the necessary lighting to see the environment.
![alt_tag](https://github.com/arjunkhara/3D-Modelling-Repo/blob/master/cw2-images/19-Fortuna-robot-1.png)

With the environment design in place, the team turned to solve the problem of narrative. I conceived of a plot that involved a future corporation called the Mining Federation of Space-Based Entrepreneurs (MFSBE) which looks like the abbreviations of a listed company. The MFSBE is an unethical corporation that exploits its resources to maximise profit in an almost dystopian space-faring age. With the Earth in desperate need of extra-planetary resources — having depleted our own through over-consumption — the MFSBE has carved out a niche by providing tholin from asteroid mining operations, that drive specific industrial operations on Earth. The MFSBE uses indentured miners — a race of tough humanoid creatures from Europa, enslaved and forced to work in dangerous conditions for virtually no pay. In the game, the miners have been wiped out on 19 Fortuna by rock monsters, natives of the asteroid, which were not detected by the MFSBE's research team, owing to typical cost-cutting measures. Rather than send in rescue missions, the MFSBE has turned to mining robot mechs to do the job. The mech therefore was modelled to emulate a biped drilling robot that harnesses the tholin crystals. However, each mech is controlled by a human being, and so while the conditions are marginally safer for the pilot in a mech, the dangers of being attacked by a rock monster remain high.
![alt_tag](https://github.com/arjunkhara/3D-Modelling-Repo/blob/master/cw2-images/19-Fortuna-Robot-2.png)

Likewise, the script used in the game to facilitate dialog between the player and the orbiting space ship that rescues the mech in the last stage of the game (discussed below) shows the almost cavalier and uncaring attitude displayed by the MFSBE for its employees. This tone sets the expectations of the game and its players — the mech and its pilot (the player) are alone doing the bidding of a shady and highly profitable corporation for rank pay. The desperate and degrading situation of the earth and its inhabitants is therefore reflected in the vast openess and in some cases helplessness of space, in which the wonders of discovering life on other worlds is eclipsed by the dangers of getting killed by these creatures. This backstory point is a major driver of the game's play design and is critical in setting up the expectations of the player — alien creatures remain hostile to the grasping and greedy hands of earth-based corporations.
![alt_tag](https://github.com/arjunkhara/3D-Modelling-Repo/blob/master/cw2-images/Initial-Voiceover-Script-19-Fortuna.png)

This is the driving design factor of the game — the player is armed with a mech without any weapons (more space for more crystals) and is therefore required to use his or her wits to outsmart the rock monsters who thankfully are not as intelligent as human beings. This narrative informed the design of the game and the mech — a drilling robot who's task is to drill crystals and avoid rock monsters by either running away or by hacking its reconnaissance camera to shoot an electromagnetic pulse (EMP) if it harvests sufficient crystals. The player is therefore challenged with a threat situation against an enemy but without the use of conventional weapons. This design decision places the game apart from typical third person shooters in which the protagonist(s) engages with enemies with weapons. In 19-Fortuna, the game requires players to use movement mechanics as they defensive measures. As an added twist, the asteroid has become unstable with all the mining operations — accounted and unaccounted — taking place. In the game, the asteroid begins to break apart in the last stage, and the player has to race the mech back to the extraction point or risk being marooned and lost to the fiery ends of the doomed asteroid.
![alt_tag](https://github.com/arjunkhara/3D-Modelling-Repo/blob/master/cw2-images/19-Fortuna-Robot-3.png)

The primary design decisions are therefore informed by real-world research and narratives which players do no necessarily encounter but nonetheless experience through the game. Given the relative complexity of the game's narrative, it was decided that a low-poly design would best meet the resource requirements of the game. A low-poly design would also work in favour of visual aesthetics, given the beauty of the space-like scene in which the game takes place. Each sub-design decision was therefore taken on the premise of these primary design considerations. It is fortunate that the team decided to base the game's design on real-world scenarios and with well-developed back stories because these provided a robust framework in which we could build and concieve the game and its mechanics. On reflection, I am extremely grateful for this unplanned decision, because basing a game on actual research keeps the project focused and the team on track to working towards something real and easily visualised. The design of the game and its accompanying decisions are therefore based on this research and the accompanying narrative that is fictional in nature but nonetheless a viable future that is easily imagined. And if the design is easily imagined, it is easier to convince players of the game's experience.
![alt_tag](https://github.com/arjunkhara/3D-Modelling-Repo/blob/master/cw2-images/19-Fortuna-Robot-4.png)

## 5. Design Material and Assets
1. Mech  
2. Crystals  
3. Hydrocarbon Lakes  
4. Sky Sphere  
5. Spaceship  
6. Sounds and Script  
7. Lighting  

## 6. Code and Technical Considerations
The table below is a games analysis practice chart that Daniel Nicholson, Thomas Tanugi, and I worked on together to understand how a game is designed and constructed. We will use this example (from Richard Leinfellner's class: Game Design and Analytics) to build out our own construct for the game.

![alt_Tag](https://github.com/arjunkhara/3D-Modelling-Repo/blob/master/cw2-images/Initial-Game-Analysis-19-Fortuna.png)

## 7. Self-Reflection

## 8. Conclusion
