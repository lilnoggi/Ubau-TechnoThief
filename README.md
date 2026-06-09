### CS1_Project

<div align="center">

<img width="350" height="250" alt="AbsentMindLogo" src="https://github.com/user-attachments/assets/18883af3-f3e6-4956-8f66-f64c3db590cc"/>
  
# UBAU: Techno-Thief

![Engine](https://img.shields.io/badge/Engine-Unreal_Engine_5.6.1-0E1128?style=flat&logo=unreal-engine&logoColor=white)
![Language](https://img.shields.io/badge/Language-C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![Build](https://img.shields.io/badge/Build-In_Development-F28D1A?style=flat)

</div>

<br>

Ubau is a first-person stealth survival game set in a dystopian mega-city ruled by technocrats and automated security system. Players take control of an 11-year-old scavenger surviving beneath towering concrete structures while uncovering the horrifying truth behind the city's hidden infrastructure.

Developed by **Absent Mind Studio**

## Technical Overview
* **Engine:** Unreal Engine 5.6.1
* **Version Control:** Git

## The Team

**Game Design**
* Rhiannon

**Programming**
* Campbell (Lead)
* Mani (Lead)
* Florin
* KTZ
* Zoe

**Art & Visuals**
* Sadik (Lead)
* Ali (Lead)
* Mei Mei
* Kyrah
* Yohan

## Essential Git Rules for the Team

To prevent merge conflicts and corrupted files, all team members must strictly adhere to the following rules:

### 1. Branch Workflow
* **Never push directly to 'main'.**
* All actual development must happen in **Feature Branches** (e.g., 'feature/**your-name)-player-movement').
* Once a feature is completely functional, merge it into your **Personal Branch** (e.g., 'Your-Name').
* Personal branches will be merged into 'main' as a group before major presentation milestones.

### 2. Checking Out
Unreal Engine's '.uasset' (Blueprints, Models) and '.umap' (Levels) files are binary files. **Git cannot merge them.**
* We operate on a strict manual checkout system using the '#git-checkout' channel in our Discord.
* Before editing any shared file (e.g., 'BP_PlayerCharacter' or the main level map), you must message the channel: *"Checking out [Filename]"*.
* When your work is finished and successfully pushed, you must message: *"Checking in [Filename]"*.
* If you modify a binary file that someone else currently has checked out, your work will be discarded to prevent repositary conflicts.

## 3. Repository Safety
* No one is allowed to modify the '.gitignore' file without group consensus.
* We will never commit the 'Intermediate', 'Saved', or 'DerivedDataCache' folders to the repository.
