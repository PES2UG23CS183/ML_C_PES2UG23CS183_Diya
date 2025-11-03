# Hangman AI — Hybrid Model using Hidden Markov Model (HMM) and Reinforcement Learning (Q-Learning)

## Overview
This project presents an **AI-powered Hangman game** that learns to guess words intelligently by combining **Hidden Markov Models (HMM)** with **Reinforcement Learning (Q-Learning)**. The system predicts likely letters using statistical language modeling (HMM) and then optimizes its decision-making strategy through trial and error (RL). A **Streamlit web app** is also included for interactive gameplay where users can play against the trained AI.

---

## Team
Developed by:  
**Diya D Bhat**  
**Dhanya Prabhu**
**Eshwar RA** 
**Delisha Riyona Dzouza** 

---

## Project Description
This work explores a **hybrid AI approach** that merges probabilistic reasoning (HMM) and sequential decision-making (Reinforcement Learning) to tackle the Hangman word-guessing challenge.

- The **Hidden Markov Model (HMM)** learns letter patterns and transition probabilities from a large English word corpus. It estimates which letters are most probable given the current word pattern.
- The **Q-Learning agent** uses these HMM-generated probabilities as part of its feature set to learn how to guess letters optimally. Over multiple episodes, it learns through rewards and penalties to balance exploration (trying new letters) and exploitation (choosing high-confidence guesses).

This hybrid design ensures the model benefits from both **linguistic understanding** and **experience-based learning**.  
The final Streamlit interface allows users to **interactively test or challenge the AI** and visualize its decision-making process.

---

## Dataset
The dataset used for training the HMM is a **text-based corpus of English words**.  
It can be any large word list such as:
- [SCOWL word list](http://wordlist.aspell.net/)
- [Kaggle English Word Lists](https://www.kaggle.com/datasets/rtatman/english-word-frequency)

Two files are used:
- **corpus.txt** → Training data for the HMM  
- **test.txt** → Evaluation set for model testing

Both files are text-based lists of words, one per line.

---

## Running the Project

### Step 1: Obtaining Access to the Codes

#### Option 1: Download the Repository as ZIP
1. In this repository, click the green **Code** button and select **Download ZIP**.  
2. Extract the ZIP file locally.  
3. Navigate to the project folder (e.g., `Hangman_AI_Project`) and open it in your preferred IDE or terminal.

#### Option 2: Clone the Repository
```bash
git clone https://github.com/<your-username>/Hangman-AI.git
cd Hangman-AI

