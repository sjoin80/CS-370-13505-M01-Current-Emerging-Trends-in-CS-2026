# CS-370-13505-M01-Current-Emerging-Trends-in-CS-2026

# 🚀 Pirate Intelligent Agent (Reinforcement Learning)

## 📘 Project Overview  
This project implements an intelligent agent using **deep Q-learning** to solve a maze-based pathfinding problem. The goal of the agent (pirate) is to navigate through a maze environment and reach the treasure while maximizing cumulative reward.

The project demonstrates key reinforcement learning concepts including:
- Exploration vs. exploitation (epsilon-greedy strategy)
- Experience replay
- Neural network-based Q-value approximation
- Reward-driven decision making

---

## 💻 Project Files  

- `Joiner_Shelby_TreasureHuntGame_starterCode_.ipynb` – Main notebook containing the deep Q-learning implementation  
- `TreasureMaze.py` – Environment class defining the maze, rewards, and agent interactions  
- `GameExperience.py` – Handles experience replay and training data generation  
- `requirements.txt` – Project dependencies  
- `.html` export – Viewable version of the notebook  
- `PROJECT TWO - DESIGN DEFENSE_.docx` – Written analysis and algorithm evaluation  

---

## 🧠 What I Did  

For this project, I was provided with starter code that included the maze environment and experience handling classes. My primary responsibility was to complete the **deep Q-learning implementation** in the notebook.

I implemented:
- A neural network model to approximate Q-values  
- The training loop using reinforcement learning principles  
- Epsilon-greedy action selection for exploration vs. exploitation  
- Experience replay to improve training stability  
- Target network updates to stabilize learning  

This allowed the agent to learn optimal navigation strategies through repeated interaction with the environment.

---

## 🌍 Connection to Computer Science  

### What do computer scientists do and why does it matter?  
Computer scientists design systems that solve complex problems using algorithms, data, and computation. This work matters because it drives innovation across industries such as healthcare, transportation, and artificial intelligence.

### How do I approach a problem as a computer scientist?  
I approach problems by breaking them down into smaller components, identifying inputs and outputs, and selecting appropriate algorithms. In this project, I translated a pathfinding problem into a reinforcement learning framework and iteratively improved the solution.

### What are my ethical responsibilities?  
My responsibility is to ensure that systems are accurate, reliable, and safe. In AI systems, this includes protecting user data, ensuring transparency, and preventing harmful or biased outcomes.

---

## 🤖 Reinforcement Learning in This Project  

The agent interacts with the environment by taking actions and receiving rewards. The environment updates the agent’s state and provides feedback based on movement rules, such as penalties for invalid actions or rewards for reaching the goal.

Using experience replay, the agent stores past interactions and trains on them to improve performance over time.

This approach allows the agent to learn optimal behavior without being explicitly programmed with rules.

---

## 📊 Results  

Through training, the agent improves its ability to:
- Navigate efficiently through the maze  
- Avoid invalid or repeated moves  
- Consistently reach the goal state  

The final model demonstrates stable performance and a high success rate in completing the maze.

---

## 🧩 Reflection  

This project strengthened my understanding of how reinforcement learning differs from traditional machine learning. Instead of relying on labeled data, the agent learns through interaction and feedback.

I also gained hands-on experience with:
- Neural networks in TensorFlow/Keras  
- Training stability techniques like target networks  
- The importance of balancing exploration and exploitation  

This project connects directly to real-world applications such as robotics, autonomous navigation, and intelligent decision-making systems.

---

## 🔗 Repository Link  

https://github.com/sjoin80/CS-370-13505-M01-Current-Emerging-Trends-in-CS-2026
