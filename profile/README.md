# The Blot Bot Project
Blot Bot is a vertical plotter, built partly for a school project, which allows motors to move a pen to physically draw designs on paper.
The Blot Bot ecosystem allows anyone with stepper motors and a microcontroller to repurpose their hardware using Blot Bot's open-source software.<br>

## The Organisation
The organisation contains a couple repositories:
- Blot Bot has a firmware binary which can be flashed on to any Arduino-compatible board, such as the ESP32.
- Blot Bot also has an interfacing library, core-lib aka `bbcore`, with many useful utilities such as generating drawing instructions and handling the networking between the firmware and the software.
- To implement `bbcore`, I am developing a desktop application which allows you to design and print drawings within a single app.

Information for specific aspects of the project can be found in their respective repositories.
<br>

## A-Level NEA information
The library [bbcore](https://github.com/blot-bot-org/core-lib), and the desktop app [desktop](https://github.com/blot-bot-org/desktop) (only) are being developed for my A-Level Computer Science NEA project.
I have tried my best to decouple `bbcore` from the frontend, to allow any frontend such as a CLI to be developed around `bbcore`.<br><br>
Centre Number: 20570<br>
Candidate number: 9056
<br><br>

## A little showcase
Here is a screenshot of the "Entropy" drawing style from my [desktop app](https://github.com/blot-bot-org/desktop):
![Screenshot of Islands](https://raw.githubusercontent.com/blot-bot-org/showcase/refs/heads/main/entropy.jpg)
