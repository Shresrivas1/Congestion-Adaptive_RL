# Congestion-Adaptive_RL

**Adaptive Congestion Control using Reinforcement Learning**

This project implements a Reinforcement Learning (RL)–based approach for adaptive network congestion control. The system dynamically learns optimal control strategies by interacting with a simulated network environment and responding intelligently to varying congestion conditions.

---

## Project Summary

Network congestion is a dynamic and complex problem where traditional static congestion control mechanisms often fail to adapt efficiently to changing traffic patterns.

This project formulates congestion control as a **reinforcement learning problem**, where an agent:
- Observes network congestion states
- Takes adaptive control actions
- Receives feedback in the form of rewards
- Learns optimal policies over time

The trained RL agent improves congestion management and overall system performance by continuously adapting to the environment.

---

## Repository Contents

```
Congestion-Adaptive_RL/
│
├── final8 (1).ipynb    # Complete implementation (environment, training, evaluation)
├── README.md          # Project documentation
```

---

##  How to Run the Project

### 1️ Clone the Repository
```bash
git clone https://github.com/Shresrivas1/Congestion-Adaptive_RL.git
```

### 2️ Navigate to the Project Directory
```bash
cd Congestion-Adaptive_RL
```

### 3️ Install Required Dependencies
```bash
pip install numpy pandas matplotlib gym torch
```

### 4️ Run the Jupyter Notebook
```bash
jupyter notebook "final8 (1).ipynb"
```

---

##  Project Workflow

1. Initialize the congestion control simulation environment  
2. Train the reinforcement learning agent through iterative interactions  
3. Observe reward signals and update the policy  
4. Evaluate system behavior under different congestion scenarios  

---

##  Tools & Technologies Used

- Python
- Jupyter Notebook
- Reinforcement Learning
- NumPy
- Pandas
- Matplotlib
- OpenAI Gym
- PyTorch

---

## Author

**Shreyanshu Ranjan**  
 Email: shreyanshuranjan3579@gmail.com  
 GitHub: https://github.com/Shresrivas1/Congestion-Adaptive_RL  

---

## License

This project is intended for **academic and research purposes** only.

---

## Acknowledgements

This project was developed as part of an academic exploration into intelligent network control systems using modern reinforcement learning techniques.
