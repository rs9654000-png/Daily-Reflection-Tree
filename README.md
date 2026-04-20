# Daily Reflection Decision Tree
## Overview
This project implements a deterministic decision tree system that provides daily action suggestions based on user inputs such as mood, energy, sleep quality, and productivity.
The goal is to simulate structured daily reflection and decision-making using rule-based logic.
##  Approach
The system takes four inputs:
- Mood (good / neutral / bad)
- Energy (high / medium / low)
- Sleep Quality (good / poor)
- Productivity (high / low)
Based on these inputs, a decision tree (if-else logic) is used to generate a suitable suggestion or advice.

##  Decision Logic

The decision tree follows rule-based conditions such as:

- If mood is bad and energy is low → suggest rest and do self care 
- If mood is bad and energy is high → suggest physical activity 
- If mood is good but productivity is low → suggest task planning  
- If sleep quality is poor → suggest rest prioritization  
- Otherwise → continue routine  
This ensures deterministic and consistent outputs.

## guardrails 
To ensure reliability and correctness:

- Input validation is applied for all fields  
- Only predefined input values are accepted  
- Invalid inputs return error messages  
- No randomness in output  

##  How to Run

1. Open terminal  
2. Navigate to project folder  
3. Run the following command:
python decision_tree.py

Daily-Reflection-Tree/
│── decision_tree.py
│── sample_outputs.md
