# Traffic Light Controller in VHDL

## Project Overview
This project involves designing a finite state machine (FSM) for a traffic light controller using VHDL. The primary focus was on managing state durations and displaying the remaining time in the `greenRed` state.

## Key Features
- **Finite State Machine Implementation**: Designed an FSM to control traffic light states.
- **State Duration Management**: Utilized a counter that decrements with clock edges and resets based on state duration.
- **Remaining Time Display**: Implemented a feature to show remaining time in the `greenRed` state, using a variable decremented every 8 clock cycles.
- **Simulation and Verification**: Created timing diagrams for:
  - The FSM operation
  - The `bcd_to_7seg` component
  - Overall system performance
- **Logisim Simulation**: Conducted simulations and captured results for analysis and validation.

## Simulation Results
Simulation results were captured in Logisim, demonstrating the correct functionality of the traffic light controller.
