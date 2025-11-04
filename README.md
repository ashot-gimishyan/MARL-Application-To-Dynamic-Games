# Application of Multi-Agent Reinforcement Learning to Dynamic Two-Player Games

**Author:** Ashot Gimishyan  
**University:** Moscow Institute of Physics and Technology (MIPT)  
**Year:** 2023  

---

## 📘 Overview

This project presents a research on the application of **Multi-Agent Reinforcement Learning (MARL)** to dynamic two-player games.  
A **modified bargaining problem** is introduced as an experimental framework that simulates negotiation dynamics between two agents competing for a shared resource.

The main goal is to explore how AI agents can **learn fair and efficient strategies** through interaction, adaptation, and strategic reasoning using modern MARL algorithms.

---

## 🧠 Research Focus

- Formulation of a **Modified Bargaining Game** as a dynamic two-player negotiation model.  
- Application of **multi-agent reinforcement learning** techniques for decision optimization.  
- Implementation and comparison of algorithms such as **MADDPG**, **PPO**, and **Q-learning**.  
- Analysis of convergence, fairness, and negotiation efficiency.  

---

## ⚙️ Implementation

The simulation and experiments are implemented in **Python** using the following structure:

- `NegotiationEnvironment` — defines the dynamic game and payoff mechanics.  
- `MADDPGAgent` — implements the actor–critic learning framework.  
- `ActorNetwork` & `CriticNetwork` — PyTorch neural network modules.  
- `train_maddpg()` — handles centralized training and decentralized execution.  

---

## 📊 Experimental Results

The trained agents successfully learned to reach **Nash-equilibrium-like outcomes**, improving both:
- **Average cumulative rewards**
- **Agreement rates** between agents across episodes.  

The results demonstrate the effectiveness of MARL in modeling real-world negotiation and conflict-resolution scenarios.

---

## 🧩 Technologies Used

- Python 3.x  
- PyTorch  
- NumPy, Matplotlib  
- OpenAI Gym (custom environment)  

---

## 📎 Citation

If you reference or build upon this work, please cite:

> Ashot Gimishyan. *Application of Multi-Agent Reinforcement Learning to Dynamic Two-Player Games.*  
> MIPT, 2023.

---

## 📬 Contact

**Ashot Gimishyan**  
System & Business Analyst  
📧 [LinkedIn](https://www.linkedin.com/in/ashot-gimishyan/)

---

> “Let’s move from the age of confrontation to the age of negotiation.” — *Richard Nixon*
