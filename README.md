# Tortoise and Hare Race Simulation

## Overview

This project is a simulation of the classic **Tortoise and Hare** race, implemented in **C++** as part of my first **Object-Oriented Programming (OOP) mini-project**. The simulation uses **random number generation** to determine the movement of the tortoise and hare according to predefined probability rules.

## Features

- Simulates a race between a **tortoise** and a **hare** on an 80-square track.
- Uses **random number generation** to determine each animal's movement per turn.
- Implements different movement types such as **fast plod, slip, slow plod** for the tortoise and **sleep, big hop, big slip, small hop** for the hare.
- Displays the race track with the current positions of the competitors.
- Handles special conditions such as **tortoise biting the hare (OUCH!!!)** when they land on the same square.
- Determines and announces the **winner** when either animal reaches the finish line.

## Implementation Details

- Uses **pointers** and **pass-by-reference** for updating positions.
- **Randomized movements** ensure each race is unique.
- **System calls (**``** and **``**)** create a real-time race effect.
- Runs within a loop until a winner is determined.

## Rules

| Animal   | Move Type | Probability | Distance Moved   |
| -------- | --------- | ----------- | ---------------- |
| Tortoise | Fast plod | 50%         | 4 squares right  |
| Tortoise | Slip      | 20%         | 5 squares left   |
| Tortoise | Slow plod | 30%         | 1 square right   |
| Hare     | Sleep     | 38%         | 0 squares        |
| Hare     | Big hop   | 20%         | 11 squares right |
| Hare     | Big slip  | 20%         | 9 squares left   |
| Hare     | Small hop | 22%         | 1 square right   |


## Future Enhancements

- Implement **Object-Oriented Programming (OOP) principles** (e.g., create classes for `Tortoise` and `Hare`).
- Add **graphical visualization** instead of console-based display.
- Allow user to **bet on the winner** before the race starts.
- Enhance the **UI** with better animations.

