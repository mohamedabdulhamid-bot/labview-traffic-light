# Basic Traffic Light Simulation in LabVIEW

A simple traffic light control system using flat sequence structure in LabVIEW. 
This project demonstrates basic timing control and sequential logic implementation.

**Features:**
- Sequential green-red light control  
- Configurable timing parameters
- Basic LED state management
- Continuous operation with while loop

## Requirements

* **Software:** LabVIEW 2022 or compatible version .
* **Hardware:** This is a simulation only. No hardware required.(you can make hardware if u needed just wire it and use arduino or any data aquistion)

## Installation & Usage

1.  **Clone this repository** to your local machine.
    ```bash
    git clone https://github.com/mohamedabdulhamid-bot/labview-traffic-light.git
    ```
2.  Open the LabVIEW Project file (`Traffic_Light_Project.lvproj`) or the main VI (`Advanced_Traffic_Light_Main.vi`) directly.
3.  Run the main VI by clicking the **Run** button (the white arrow) on the toolbar.
4.  Interact with the front panel to change timings .

## How It Works

The core of this simulation is a **State Machine** design pattern. The system cycles through predefined states (e.g., `Main Green`, `Side Yellow`, ` Main Green`). Each state:
*   Updates the front panel indicators.
*   Waits for a specific duration.
*   Transitions to the next logical state.

This architecture makes the code modular, easy to understand, and simple to modify.

## Block Diagram

![Block Diagram Screenshot](images/block_diagram_screenshot.png)

## Author

Created by [Mohamed Abdulhamid].

## License

This project is licensed under the MIT License - see the LICENSE file for details.