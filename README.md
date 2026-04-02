# Procedural Roguelike with Dynamic Difficulty — Final Year Project 🎮

A procedurally generated roguelike game built in Unity (C#) for my final year project at the University of Brighton. The game investigates whether players prefer an experience tailored to their performance over a purely random one.

## About

The project explores **dynamic difficulty adjustment (DDA)** in roguelike games. The game generates dungeons from pre-made rooms and continuously tracks player performance — using it to make subsequent rooms easier or harder in real time.

To rigorously test the hypothesis, two versions of the game were created:
- **Version A** — dynamic difficulty, rooms adapt based on player performance
- **Version B** — static random difficulty, no adaptation

Both versions were tested on multiple participants, with data collected on rooms completed and average difficulty per room. The results showed a strong positive correlation between rooms completed and difficulty faced — confirming the dynamic difficulty system was working as intended: stronger players were challenged more, and weaker players were given a more accessible experience.

## Key Features

- **Procedural dungeon generation** using pre-made modular rooms assembled at runtime
- **Dynamic difficulty adjustment** — player performance is tracked per room and used to scale future room difficulty
- **Simple enemy AI** — enemies react to and pursue the player within each room
- **Two-version testing framework** — built for direct A/B comparison between adaptive and random difficulty
- **Data collection system** — records rooms completed and difficulty per room for post-test analysis

## Research Findings

Testing across multiple participants produced a clear result: there was a strong correlation between the number of rooms completed and the average difficulty encountered. This indicates the DDA system functioned correctly — higher-performing players faced progressively harder content, while lower-performing players encountered more manageable rooms.

The data suggested players responded positively to a tailored experience, supporting the hypothesis that adaptive difficulty improves engagement in roguelike games.

## Tech

- **Engine:** Unity
- **Language:** C#
- **IDE:** Visual Studio / Rider
- **Methodology:** A/B user testing with quantitative data collection

## How to Run

1. Clone the repository
2. Open in Unity (recommended: Unity 2021 LTS or later)
3. Open the main scene from the `Assets` folder
4. Press Play in the Unity Editor to try the dynamic difficulty version

## Project Context

- **Institution:** University of Brighton
- **Degree:** BSc Computer Science for Games — First Class Honours
- **Year:** 2023–2024
- **Full portfolio entry:** [alexmooreportfolio.uk](https://www.alexmooreportfolio.uk/)
