<table>
  <tr>
    <td width="140">
      <img src="media/kais-game-logo.png" alt="Kai's Game logo" width="120">
    </td>
    <td>
      <h1>Kai's Game</h1>
      <p>A challenging 3D obstacle runner made in Unity and C#.</p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/kaiforsyth-git/Kais-Game/releases/download/v0.1.0-alpha/Kais-Game-Trailer.mp4"><strong>Watch the GitHub Trailer</strong></a>
  &nbsp;•&nbsp;
  <a href="https://github.com/kaiforsyth-git/kais-game/releases"><strong>Download the Windows Build</strong></a>
</p>

## About the Game

Kai's Game is a dark and difficult 3D obstacle runner where the player guides an automatically moving ball using only left and right controls.

The goal is to complete all ten levels and collect every skin. Early levels are accessible to almost anyone, but the difficulty builds steadily until later levels demand route memory, fast reactions, accurate inputs and careful path optimisation.

The movement is designed to feel fast and precise. Each failed attempt helps the player learn the course, improve their timing and push further into the game.

## Features

<table>
  <tr>
    <td>10 challenging levels</td>
    <td>Fast, precise movement</td>
    <td>No mid-level checkpoints</td>
    <td>Increasing difficulty</td>
  </tr>
  <tr>
    <td>13 collectible skins</td>
    <td>Shop and secret unlocks</td>
    <td>Unique skin effects</td>
    <td>Full ending sequence</td>
  </tr>
</table>

## Screenshots

<p align="center">
  <img src="media/screenshots/titlescreen.png" width="60%" alt="Kai's Game title screen">
</p>

<p align="center">
  <img src="media/screenshots/blue-ui.png" width="49%" alt="Blue level gameplay">
  <img src="media/screenshots/green-7.png" width="49%" alt="Green level gameplay">
</p>

## Download and Play

1. Open the repository's **Releases** section.
2. Download the latest Windows ZIP file.
3. Right-click the ZIP file and select **Extract All**.
4. Open the extracted folder.
5. Launch `Kai's Game.exe`.

> Windows may show a security warning because the Alpha build is not digitally signed. Select **More info**, then **Run anyway**.

### Controls

| Action | Control |
|---|---|
| Move left | `A` or `Left Arrow` |
| Move right | `D` or `Right Arrow` |
| Pause | `Esc` |

The player moves forward automatically. Stay on the course and reach the end of each level.

## Developer Mode

Developer Mode allows reviewers to quickly test different parts of the game.

> Press `L` to activate Developer Mode. Once activated, it stays enabled until the game is fully reset. All other developer controls require Developer Mode to be active.

| Function | Control |
|---|---|
| Activate Developer Mode | `L` |
| Toggle obstacle immunity | `G` |
| Unlock all skins | `U` |
| Load Levels 1 to 9 | `1` to `9` |
| Load Level 10 | `0` |
| Fully reset the game | `Ctrl + Shift + Backspace` |

> **Warning:** Fully resetting the game permanently deletes all saved progress, unlocked skins, statistics and settings.

## Development

Kai's Game is a solo project that I designed, programmed, tested and polished in Unity.

The project involved building the skin unlocking, purchasing and selection systems, creating custom shaders and effects, designing ten levels and polishing the gameplay, menus, audio and presentation.

### Tools Used

- Unity
- C#
- Shader Graph
- Blender
- DaVinci Resolve
- Photopea
- OBS Studio

This repository contains the playable builds and portfolio media. The full Unity project and source files are being kept private.

## Current Status

**Alpha v0.1**

Normal Mode is playable from beginning to end and currently includes all ten levels, thirteen skins, the skin shop, player statistics, music, sound effects and a complete ending sequence.

The ending includes changing fog, slowing music and a full credits sequence rather than a basic completion screen.

The main game is working, but some parts will continue to be adjusted and polished during development. This includes the user interface, audio, the Blood skin effects and smaller changes across the levels and presentation.

### Planned Development

1. Finish the remaining skins, including Diamond and Nebula
2. Add Easy Mode, where each death sends the player back one level
3. Develop additional downloadable content
4. Add online leaderboards
5. Complete final testing and polish
6. Publish the game on Steam

The exact content and order may change as development continues.
