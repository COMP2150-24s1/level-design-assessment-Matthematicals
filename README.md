[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Matthew Ho
### Student number: 47729686 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
Throughout the level, the player unlocks new areas through exploration and new abilities. On a first playthrough of a section, the player may note areas that are not accessible to them and after unlocking the associated abilities (that allow them to 'unlock' previously locked spaces which will reward the player as well as being able to immediately test and experiment with what they have been given to reinforce how the ability can be used. This follows good design practice as the level is not overloaded with difficult platforming and has isolated elements that teach the player how to move through and interact with the level in a safe environment before challenging them with harder elements. E.g. section 1 introduces the basics that are used in the rest of the sections (spikes, moving platforms, and acid). The isolated elements that allow the player to learn what they can do is shown below:
![section 1](DocImages/Scan2024-04-07_172541_001.png)

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?
In the level, the player is introduced to more challenging platforming scenarios within each section of increasing difficulty. Within section 1, the player is able to freely test and experiment with the moving platform mechanics before they reach section 2 where their abilities are tested (mainly the ascending platform where the player must move around to avoid taking damage from the spikes). This culminates in section 3 where the player's abilities and experience is tested and the player must put what they've learned into practice by moving around a moving platform and avoiding damage from the enemies or by falling into the pit of acid.
![](DocImages//.png)

### 1.4. Exploration
To facilitate exploration in my level design, I opted to build the level around the style of the metroidvania genre. This means that the player must backtrack through section 1 of the level with their new abilities to unlock the next section. Autonomy is given to the player as there are multiple ways to get to the destination they have set. For example, after completing section 2 and receiving the staff weapon, they are able to break the destructible walls and unlock new paths such as the space with the key. They can then either backtrack through the way that they came, or can use the shortcut (with enemies) to make moving through the level easier and not annoying. This is shown in the following image:
![](DocImages/playerpathsection2.png)


## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Spikes

### 2.2. Moving Platforms

### 2.3. Acid

### 2.4. Checkpoints

### 2.5. Passthrough Platforms

### 2.6. Chompers

### 2.7. Weapon Pickup (Staff)

### 2.8. Health Pickups

### 2.9. Spitters

### 2.10. Keys

### 2.11. Weapon Pickup (Gun)



## 3. Spatiotemporal Design
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1
![section 1](DocImages/playerpathsection1.png)
### 3.3.	Level Map – Section 2
![](DocImages/playerpathsection2.png)
### 3.4.	Level Map – Section 3
![](DocImages/playerpathsection3.png)


## 4. Iterative Design (~400 words)
After completing the final design of the level, there are many elements changed between the initial design for the level and the finished version. For example, in the paper prototype for section 1 (as shown below) gameplay elements were introduced too fast for the player to understand what each specific element did and required a restructuring of the entire section as the level may have been too difficult.  
![section 1](DocImages/section1iterative.png)
Additionally, sections 2 and 3 required tweaking after playtesting some portions of the level felt unfair to the player such as the spike hitbox being too strict and damaging the player without them noticing as the spike's default hitbox included all of the spike which is hard to see. This was improved by tweaking the hitbox size to only include the main spike portion so the level is more forgiving. Another example of iterative design is when one of the enemies would target the player from offscreen and potentially knock them off the platform and lose a chunk of progress. This was then altered into a spot that is visible to the player while still maintaining the difficulty for the portion of the level (seen in the level map for section 3, near the 2nd moving platform). An issue found within section 3 is the method the player takes to make their way back to section 1 (where the end level door is located) where the player may have become lost after receiving the 2nd key. This was then improved through modifying the background tilemap to show arrow for the player to follow which provided a shortcut rather than requiring the player to backtrack through the completed platforming section where a fall into the pit of acid required the player to finish the platforming section and pick up the key again to then potentially fall back into the acid pool while backtracking.
For future improvements to the level design, portions of the level may benefit from negative space to increase the difficulty of the level as well as fit the theme of the level (exploring a cave) or more puzzle elements using the player's abilities to emphasise how the ability can be used or to provide additional ways to use them.


## Generative AI Use Acknowledgement

### Tool Used: None
**Nature of Use** 
**Evidence Attached?** 

**Additional Notes:**

