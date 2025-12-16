# SPACE INVADERS - Typing Game

## Overview

**SPACE INVADERS** is a keyboard typing game combined with space shooting mechanics. Players destroy enemies by correctly typing words that appear on screen. Developed with Unity, this game is suitable for all ages who want to improve their typing speed and accuracy.

## Key Features

- **Multiple Levels**: Progressive difficulty levels from simple to complex words with diverse characters
- **Various Game Modes**: Different gameplay modes with unique challenges and rules
- **Beautiful Interface**: Dynamic backgrounds, effects, and soundtracks that change with each level
- **Score & Progress Tracking**: High score system, correct/incorrect word counts, typing speed (WPM) tracking
- **Customizable Weapons & Maps**: Choose weapons, maps, and background music for each level
- **Pause, Resume, Restart**: Full support for modern game features

## How to Play

1. **Start Game**: Select your preferred mode and level from the main menu
2. **Gameplay**:
   - Words fall from the top of the screen
   - Type each character correctly to shoot down the corresponding enemy
   - Incorrect typing increases the error count
   - Complete enough words or meet win conditions to advance
   - Let too many words fall or make too many errors to lose
3. **Controls**:
   - Use keyboard to input characters
   - Use mouse to navigate menus, select modes, levels, and weapons
   - Pause, resume, or exit the game at any time

## Project Structure

- `Assets/Scritps/`: All C# source code for gameplay, UI management, word generation, input handling, level management, etc.
- `Assets/Scenes/`: Main game scenes (menu, gameplay)
- `Assets/Resources/`: Images, sounds, sprites, fonts, etc.
- `Assets/Warped Shooting Fx/`: Additional effects, background music, pixel art
- `Assets/TextMesh Pro/`: High-quality font and text system
- `ProjectSettings/`, `Packages/`: Unity project configuration

## Key Source Files

- `GameManager.cs`: Manages all game logic, scoring, state, word generation, win/lose conditions
- `MainMenu.cs`: Handles main menu, level/mode unlocking, weapon selection, sound toggle
- `WordGenerator.cs`: Generates words for each level, manages word lists
- `WordDisplay.cs`: Displays words, handles effects for correct/incorrect typing
- `WordInput.cs`: Receives keyboard input, passes characters to GameManager
- `Words.cs`: Defines word objects, character checking, word removal on completion
- `BackgroundMusic.cs`, `BackGroundScroll.cs`: Background music and scrolling effects

## System Requirements

- Unity 2020 or higher (Unity 2021+ recommended)
- OS: Windows 10/11, macOS, Linux (depending on build)
- RAM: 2GB or more
- Physical keyboard for best experience

## Build & Run

1. Open project with Unity Hub
2. Select `menu.unity` or `gamePlay.unity` scene to test
3. Build project via `File > Build Settings` (choose appropriate platform)

## Contributing & Development

- Fork the repo, create a new branch for features/bugfixes
- Submit pull requests with detailed descriptions
- Contributions for vocabulary, game modes, effects, and sounds are welcome!

## License

Project developed for educational purposes, non-commercial use. Image and sound resources are from free sources or self-created.