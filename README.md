# Asteroid Game 🚀

A fun and simple asteroid shooting game built using Python and Pygame. The player controls a spaceship that spawns in the middle of the screen and must shoot down randomly generated asteroids. When shot, larger asteroids split into smaller ones that scatter in different directions.

## Features

- **Spaceship**: Spawns in the center of the screen and can be rotated to shoot in any direction.
- **Asteroids**: Appear randomly on the screen and come in different sizes. Larger asteroids break into smaller ones when hit.
- **Game Mechanics**: Use an OOP (Object-Oriented Programming) approach to structure the game components (player, asteroids, shots).
- **Pygame Framework**: Built using Pygame for smooth graphics and interactions.

## Gameplay

- **Objective**: Destroy all the asteroids before they collide with your spaceship.
- **Controls**:
  - `W` to move forward.
  - `S` to move backward.
  - `A` and `D` to rotate the spaceship left and right.
  - `Spacebar` to shoot.

As asteroids are hit, they will split into smaller ones, making it progressively harder to clear the screen.

## Installation

1. **Clone the repository**:

```bash
git clone https://github.com/your-username/asteroid-game.git
```

3. **Navigate to the project directory**:

```bash
cd asteroid-game
```

3. **Create a virtual environment**:

```bash
python -m venv venv
```

4. **Activate the virtual environment**:

* On macOS and Linux:

```bash
source venv/bin/activate
```

* On Windows:

```bash
venv\Scripts\activate
```

5. **Install dependencies**:

The game requires Python3 and Pygame. If you don't have Pygame installed, you can do so using pip:

```bash
pip install pygame
```

6. **Run the game**:
   
Once the dependencies are installed, run the game using

```bash
python3 main_py
```

7. **Deactivate the virtual environment** (when you're done):

```bash
deactivate
```
