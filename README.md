<img width="3188" height="1202" alt="hackcade github banner v2" src="https://github.com/user-attachments/assets/0c4c3dcb-c5f7-46e7-965d-e4571edb09e9" />

# [Game Name] 

## Basic Details

**Team Name:** EL-trism

### Team Members
- **Team Lead:** Mohammed Nihal Reyasath - TKMCE
- **Member 2:**  Sandesh KV - TKMCE
- **Member 3:**  Mohamed Sabeeh Shihab - TKMCE

## Game Description
College Dash is a 2D adventure/quiz game set in TKM College of Engineering Kollam, where players take on the role of a first-year student navigating campus life. The game combines exploration, puzzle-solving, and educational quizzes as players visit 7 different engineering departments, study subjects in the library, and collect assignment completion certificates. What makes it unique is the realistic college setting with authentic engineering quiz questions, a prerequisite learning system where players must study before taking exams, and the immersive campus environment that mirrors real academic life at TKM College.

## The Concept
The core idea revolves around a first-year student's journey to collect 7 assignment completion certificates from different engineering departments (CSE, ECE, EEE, Mechanical, Civil, Architecture, and Chemical Engineering) to win a ticket to the college's HESTIA event. Players must first obtain an ID card from the Principal's Office, use it to access the library and study subjects from textbooks, then visit department proffessors to take quizzes. The game features a prerequisite system where players cannot take department quizzes until they've studied the corresponding subject in the library, creating a realistic academic progression that mirrors real college life.

## Technical Details

### Technologies Used
-Languages: Ruby (RGSS1 - RPG Maker XP scripting language)
-Game Engines/Frameworks: RPG Maker XP (RMXP)
-Libraries/Assets: Custom Ruby modules for game systems, RMXP built-in graphics and audio
-Tools: RPG Maker XP Editor, Custom script integration, Event system

### Implementation

#### Installation / Setup

[To build and run the game manually from source:]
1. Create a new RPG Maker XP project
2. Copy the following folders into your RMXP project:
    - Graphics/ (tilesets, characters, pictures)
    - Audio/ (SE, BGM, ME)
    - scripts_source/ (all Ruby scripts)

 3. Import scripts in RMXP Script Editor in this order:
    - Core/Config.rb
    - Systems/CertificateInventory.rb
    - Systems/QuizSystem.rb
    - UI/HUD.rb
    - EventHelpers.rb
    - Scenes/Scene_CollegeDash.rb

 4. Set up game switches:
    - Switch 10: "All Certificates Collected"
    - Switch 11: "ID Card Given"
    - Switch 12: "All Certificates Collected"
    - Switch 13: "Need More Certificates"
    - Switch 14: "Already Has ID Card"

 5. Create maps and events as per the game design
 6. Test and play!


## Game Documentation
**Core Systems**
Certificate Inventory System: Tracks collected certificates and studied subjects
Quiz System: Multiple-choice questions with random selection per department
HUD System: Displays certificate count and ID card status
Library System: Textbook-style hints with navigation between definitions
Prerequisite System: Must study subjects before taking department quizzes
**Game Flow**
Start: Player begins at College Main Gate
ID Card: Obtain ID card from Principal's office
Library Access: Use ID card to enter library and study subjects
Department Visits: Take quizzes after studying (prerequisite system)
Certificate Collection: Collect all 7 department certificates
Victory: Return to Principal with all certificates to win HESTIA ticket

### Screenshots (Add at least 3)

![Screenshot1](https://drive.google.com/file/d/1zTpDSk6_EBeJ9tILNTWulBllBmOIQZ1V/view?usp=drive_link)
- studying from library

![Screenshot2](Add screenshot 2 link)  
- (https://drive.google.com/file/d/1dqA63Khi24eD9mRziMu0RHa5611K0pqT/view?usp=drive_link) - principal requesting to get all certificates

![Screenshot3](Add screenshot 3 link)  
(https://drive.google.com/file/d/1HMwBxGqP6LtgxQXgQcyA2d1BVEP_vE-A/view?usp=sharing) - TKM campus entrance map

### Game Demo

#### Gameplay Video
(https://www.youtube.com/watch?v=KVy8sZ7pG2Y)  

## Game Download / Deployment
- **Playable Version / Download:** [Link to executable or archive]
- **Deployed Web Version (if any):** [Link to web build]

