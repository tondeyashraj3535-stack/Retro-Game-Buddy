# Retro-Game-Buddy
**Retro Game Buddy** is a compact, portable retro gaming device designed as a small desktop companion. The project combines embedded electronics, PCB design, programming, and 3D-printed mechanical design into one functional device.

The device will feature a small OLED display, directional controls, action buttons, a buzzer/speaker, and a rechargeable battery. It will run simple retro-style games such as Snake, Pong, and Space Shooter, with a menu system for selecting games and displaying scores.

The project will initially be developed using a microcontroller-based prototype and then converted into a custom PCB. A custom 3D-printed enclosure will be designed to make the final device compact, durable, and visually appealing.

The main goal of the project is to create a fully functional mini gaming device while learning the complete hardware-development process—from circuit design and PCB layout to firmware programming, 3D CAD design, assembly, and testing.
# Half Life Project Journal

**Date:** 8 October 2026
**Project:** Retro Game Buddy
**Stage:** Project Planning & Concept Development

### Work Completed Today

* Selected **Retro Game Buddy** as my Half Life hardware project.
* Defined the main concept: a small, portable retro gaming device designed as a desktop companion.
* Planned the basic features:

  * OLED display
  * D-pad controls
  * A/B action buttons
  * Start/reset button
  * Buzzer or small speaker
  * Rechargeable battery
  * Multiple retro-style games
* Planned to initially prototype the device using a microcontroller.
* Decided to eventually design a **custom PCB** for the final version.
* Planned a **3D-printed enclosure** for the finished device.
* Identified the main learning areas: electronics, embedded programming, PCB design, CAD, 3D printing, assembly, and testing.

### Next Steps

1. Finalize the components.
2. Design the initial circuit.
3. Build and test the prototype.
4. Develop the game/menu software.
5. Design the custom PCB.
6. Design and 3D-print the enclosure.

### Today's Progress

**Project idea finalized and development plan created.**
# Half Life Project Journal

**Date:** 9 October 2026
**Project Name:** Retro Game Buddy
**Work Stage:** Wokwi Simulation and Game Development

### Work Completed Today

* Started developing the Retro Game Buddy prototype in Wokwi using an Arduino Nano.
* Connected an SSD1306 128×64 OLED display using the I2C interface.
* Planned and configured six push buttons for directional movement and game controls.
* Developed an OLED-based game menu for selecting retro games.
* Implemented the basic Snake game with movement controls, food generation, score tracking, and a game-over screen.
* Identified and fixed a memory overflow issue caused by the Arduino Nano's limited SRAM.
* Corrected the snake's starting position and resolved the immediate game-over issue.
* Adjusted the snake's movement speed to make gameplay more comfortable.

### Challenges Faced

* The initial program failed to compile because the arrays used too much memory.
* The game initially displayed the game-over screen immediately after starting.
* The snake's movement speed was too high for comfortable gameplay.

### Solutions Implemented

* Reduced the game grid size and changed the coordinate arrays to `uint8_t` to reduce memory usage.
* Corrected the snake's starting position and checked the collision logic.
* Planned to increase the movement interval to slow down the snake.

### Next Steps

1. Test the updated Snake game and fine-tune its speed.
2. Integrate Snake into the main game menu.
3. Develop the Pong game.
4. Add the Space Shooter game.
5. Improve the user interface and sound effects.
6. Begin planning the custom PCB and 3D-printed enclosure.

### Today's Progress

Successfully developed and tested the basic Snake game in Wokwi, resolved major programming issues, and continued building the Retro Game Buddy prototype.
<img width="878" height="777" alt="Screenshot 2026-10-09 175640" src="https://github.com/user-attachments/assets/d121e2d7-ce4b-4f69-bcd0-2e23871f44b1" />

