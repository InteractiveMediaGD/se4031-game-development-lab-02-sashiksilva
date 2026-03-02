[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/N6izMXWQ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=22927138&assignment_repo_type=AssignmentRepo)
# 🧪 Lab 02 – Main VR Project Setup (VR Core Template) + Locomotion + Folder Structure

Duration: 2 Hours  
Project Type: Main continuous project (used from Lab 02 to Lab 09)

---

## Objective

Create the main VR project using the Unity **VR Core Template**, organize the project using a proper folder structure, and configure locomotion (teleportation and smooth movement).

---

## Learning Outcomes

By the end of this lab, you will be able to:

- Create a VR project using the VR Core Template
- Organize assets using a professional folder structure
- Identify and understand the XR player rig
- Create a simple test room
- Enable teleport locomotion
- Enable smooth locomotion

---

## Software Requirements

- Unity Hub  
- Unity 2022.3 LTS  
- Windows PC  
- VR Headset

---

## Project Name

VR_PartA_<YourITNumber>

Example:

VR_PartA_IT21012345

---

## Step 1 – Create VR Core Project

1. Open Unity Hub  
2. Click New Project  
3. Select template: VR Core  
4. Set project name:

VR_PartA_<YourITNumber>

5. Click Create  

Wait until Unity finishes loading.

---

## Step 2 – Create Folder Structure (Must Match Exactly)

In the Project window:

1. Create folder:

Assets/_Project

2. Inside `_Project`, create the following folders:

- Scenes  
- Scripts  
- Prefabs  
- Materials  
- Audio  
- UI  

Final structure should look like:

Assets  
└── _Project  
  ├── Scenes  
  ├── Scripts  
  ├── Prefabs  
  ├── Materials  
  ├── Audio  
  └── UI  

---

## Step 3 – Save Main Scene

1. Go to File → Save As  
2. Save location:

Assets/_Project/Scenes/

3. File name:

Main.unity

---

## Step 4 – Understand Player Rig (DO NOT DELETE)

In the Hierarchy window, locate the VR rig object. It may be named:

- XR Origin  
- XROrigin  
- Player  

Expand it and locate:

- Camera  
- Left Hand Controller  
- Right Hand Controller  

Do NOT delete or rename these objects.

---

## Step 5 – Create a Simple Test Room

### Create Floor

1. Hierarchy → Right Click → 3D Object → Plane  
2. Rename:

Floor

---

### Create Walls

1. Hierarchy → Right Click → 3D Object → Cube  
2. Duplicate to create 4 cubes  
3. Scale and position them to form four walls around the floor

---

## Step 6 – Verify Teleportation

1. Select the Floor object  
2. Inspector → Add Component → Teleportation Area (if not already added)  
3. Enter Play Mode  
4. If headset is connected, confirm teleportation works  

---

## Step 7 – Enable Smooth Movement

If the template supports smooth movement:

1. Select XR Origin / Player object  
2. Inspector → Add Component  
3. Search:

Continuous Move Provider (Action-based)

4. Set:

Move Speed = 1.5

---

## Submission Task

Record a 45–60 second demo video showing:

- Teleportation or smooth movement  
- Your test room (floor + walls)  
- Player movement inside the room  

Video filename format:

Lab02_<YourITNumber>.mp4

Example:

Lab02_IT21012345.mp4

---

## Submission Requirements

Each student must submit BOTH of the following items.

---

### 1) Unity Project Folder (NOT zipped)

Folder name format:

Lab02_Project_<YourITNumber>

Example:

Lab02_Project_IT21012345

Requirements:

- Upload the entire Unity project folder
- Do NOT zip or compress
- Must include:
  - Assets/
  - Packages/
  - ProjectSettings/

Do NOT include:

- Library/
- Temp/
- Logs/
- Build/

---

### 2) Demo Video (30–90 seconds)

Filename format:

Lab02_<YourITNumber>.mp4

Example:

Lab02_IT21012345.mp4

The video must clearly show:

- The project running
- Implemented locomotion features
- Scene interaction

---

### Important Notes

- Both project folder and video are mandatory  
- Incorrect naming = marks deduction  
- Missing files = lab considered incomplete  
- Late submissions follow course policy  

---

## Next Lab

Lab 03 – Environment Building + Materials + Lighting (VR safe design)

This project will continue until Lab 09.

---
