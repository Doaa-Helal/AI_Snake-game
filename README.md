# AI Snake Game

This project is an AI-powered Snake game built using Python and PyTorch. The AI agent is trained using reinforcement learning to play the Snake game autonomously.

## Folder Structure
├── .gitignore ├── agent.py ├── app.py ├── arial.ttf ├── eating.mp3 ├── game.py ├── gameover.mp3 ├── helper.py ├── model.pth ├── model.py ├── README.md ├── x.png



## Files Description

- `agent.py`: Contains the `Agent` class which implements the reinforcement learning agent.
- `app.py`: Entry point for the application (currently empty).
- `arial.ttf`: Font file used in the game.
- `bggame.png`: Background image for the game.
- `eating.mp3`: Sound effect for eating food.
- `game.py`: Contains the `SnakeGameAI` class which implements the game logic for the AI-controlled game.
- `gameover.mp3`: Sound effect for game over.
- `helper.py`: Contains helper functions for plotting the training progress.
- `model/`: Directory containing the saved model.
  - `model.pth`: Saved model file.
- `model.py`: Contains the neural network model and the Q-learning trainer.
- `snake_human.py`: Contains the `SnakeGame` class which implements the game logic for the human-controlled game.
- `x.png`: Image file used in the game.

## How to Run

1. Install the required dependencies:
   ```sh
   pip install -r requirements.txt

2. To train the AI agent, run:

   ```sh
   python agent.py

3. To play the game manually, run:

   ```sh
   python snake_human.py


Dependencies
--- 

- Python 3.7+
- PyTorch
- NumPy
- Matplotlib
- Pygame

Usage
--- 

- The AI agent will automatically start training and playing the game when you run agent.py.
- You can play the game manually using the arrow keys when you run  snake_human.py.

Helper Technologies
---
- adobe premiere pro and adobe audition used for editing the sound effects


License
---
This project is licensed under the MIT License. ```
