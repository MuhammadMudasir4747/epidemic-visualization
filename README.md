# Disease Spread Simulation using Pygame

This project is a **visual simulation of disease spread** in a population of moving individuals using Python and Pygame. It demonstrates how a disease can transmit from infected to uninfected nodes based on proximity, with configurable parameters like infection probability, recovery or death chances, and movement speed.

---

## 📸 Preview

Each node on the screen represents a person:

- 🟢 Green: Uninfected  
- 🟡 Yellow: Infected  
- 🔵 Blue: Recovered  
- 🔴 Red: Dead  

Lines indicate close contact (within infection distance) between individuals.

---

## 🚀 Features

- Animated movement and collisions with window boundaries
- Dynamic infection spread based on proximity
- Recovery or death after a configurable infection duration
- Spatial hashing for efficient edge detection
- Runs at 60 FPS using asyncio loop

---

## ⚙️ Simulation Parameters

You can modify these in the script:

```python
NUM_NODES = 100           # Total number of nodes
INFECT_DISTANCE = 50      # Distance for possible transmission
TRANSMISSION_PROB = 0.01  # Probability of infection spread
INFECT_DURATION = 300     # Frames until recovery/death decision
DEATH_PROB = 0.2          # Probability of death (vs recovery)

🛠️ Requirements
Python 3.x

Pygame

(Optional) asyncio for smoother animation loop

Install Pygame:
pip install pygame

Now To RUN:
python disease_simulation.py

