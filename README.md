# 💉 Vaccine Administration VR Simulation

This repository contains the C# scripts developed for a Unity-based VR simulation that guides users through the proper procedure for administering a vaccine. The simulation offers an interactive, step-by-step experience, enhancing learning through visual cues, real-time feedback, and scoring.

## 🧠 Project Overview

The VR simulation encompasses the following steps:

1. **Start Simulation**: User initiates the simulation by clicking the Start button.
2. **MCQ Prompt**: A multiple-choice question asks where the vaccine should be administered.
3. **Preparation**:
   - Pick up the alcohol bottle and cotton.
   - Apply alcohol to the cotton.
4. **Application**:
   - Rub the patient's shoulder with the cotton.
   - Dispose of the used cotton.
5. **Injection**:
   - Grab the syringe.
   - Perform the injection on the patient's shoulder.
   - Dispose of the used syringe.
6. **Feedback**:
   - View the score based on performance.
   - Reflect on the procedure.

## 📁 Repository Contents

- `StartButton.cs`: Manages the initiation of the simulation.
- `MCQHandler.cs`: Handles the multiple-choice question logic.
- `AlcoholApplication.cs`: Controls the interaction with the alcohol bottle and cotton.
- `ShoulderRub.cs`: Manages the rubbing action on the patient's shoulder.
- `CottonDisposal.cs`: Handles the disposal of the used cotton.
- `SyringeInteraction.cs`: Manages the syringe pickup and injection process.
- `SyringeDisposal.cs`: Handles the disposal of the used syringe.
- `ScoreManager.cs`: Calculates and displays the user's score.

## 🛠️ Getting Started

To integrate these scripts into your Unity project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/rahimcantcode/rahimVaccine.git
   ```

2. **Import into Unity**:
   - Open your Unity project.
   - Copy the cloned scripts into your project's `Assets` folder.

3. **Assign Scripts to GameObjects**:
   - Attach each script to the corresponding GameObject in your scene.
   - Ensure that all necessary components (e.g., colliders, rigidbodies) are properly configured.

## 🎓 Acknowledgments

This project was developed as part of the Special Topics CS 5390 course at Southern Methodist University (SMU).


