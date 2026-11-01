## Archived: 2026-10-31

* **Repository Context**:
  * **Project**: MiRage Modular Keyboard by Zack Freedman of Voidstar Lab.
  * **Description**: A 60% ortholinear keyboard with three clickable OLED displays, intended for Kailh Choc switches, running custom CircuitPython firmware on a Seeedstudio Xiao RP2040.
  * **Status**: Incomplete. The project (PCB, firmware, keymaps, models) has major issues and is not ready to be reproduced. It is intended for a YouTube video and will eventually be improved, sold as a kit, and form part of a larger project called the "Fata Morgana cyberdeck".
  * **Architecture**:
    * PCB can be used as a "plank" keyboard or broken in half for a split board.
    * Uses PCA9505 I/O expanders for polling keys (matrices are not used, improving speed).
    * Custom keymap system using text files to define bindings for events (On press, On click, On double-click, On hold, On release) and layer functionality.
  * **Known Issues**:
    * PCB: VDD/VSS reversed on PCA9505, RESET pins need pull-ups, Choc footprints need extension for Cherry MX, QT PY incompatibility, header spacing issues, etc.
    * Enclosure: Missing access holes, USB cutout too small, rubber foot relief issues, poor fit and finish, etc.
    * Code: Unimplemented features (Rage board switching), slow code/widget updates, layer switch issues, event interaction bugs, missing visual feedback, etc.
* **Active Session Memories**:
  * Explored `README.md` to understand project scope and constraints.
  * Read instructions for the custom keymap system, layers, and project structure.
  * Created `.jules` directory to store memory logs.
