# elevator-display-simulation
A simulation project showcasing an interactive elevator display for an eight-floored building, allowing users to input initial and destination floors. The display dynamically updates floor numbers and directional indicators based on user input, providing an immersive experience of elevator functionality.

## Overview

The Elevator Display Simulation project presents an interactive display of an eight-floored building's elevator, facilitating user input for initial and destination floors. Activation of the display is triggered by a button press, showcasing floor numbers alongside directional arrows indicating upward or downward movement, or a dash at the destination floor.

## Sub-Circuits Used

1. **Display**: Manages the seven-segment display for showcasing floor numbers.
2. **Counter (Synchronous)**: Functions as both an up and down counter for managing floor movement.
3. **Comparator**: Facilitates comparisons between initial and final floor inputs.
4. **4x1 MUX**: Controls the sixteen-segment display to display directional arrows.
5. **S-R Flip Flop**: Manages display activation and deactivation.

## Elements Used

1. **Seven-Segment Display**: Displays floor numbers.
2. **Sixteen-Segment Display**: Displays directional arrows and destination dash.
3. **Button**: Initiates elevator display activation.
   
## Working

- **User Inputs**: Users provide initial floor (A) and destination (B), initiating elevator display activation upon button enablement.
- **Comparator Logic**: Utilizing a combinational circuit element, 'comparator' (comparator 1), determines the counter's function as either an up or down counter based on A and B comparison.
- **Floor Selection**: Additional comparators (comparator 2 and 3) facilitate floor number selection, enabling the display when initial and final floor values align. The display halts upon reaching the destination floor, managed by a S-R flip-flop.
- **Display Logic**: Sub-circuits like "Display" and "4x1 MUX" control the seven-segment and sixteen-segment displays respectively, dynamically showcasing floor changes and directional indicators.

## Functionality

- **Floor Movement**: When ascending, the seven-segment display increments by 1 until reaching the destination, with the sixteen-segment display showing an up arrow during ascent and a dash at the final floor. Conversely, when descending, the seven-segment display decrements by 1 until reaching the destination, with the sixteen-segment display showing a down arrow during descent and a dash at the final floor.

[View Project on CircuitVerse](https://circuitverse.org/users/156106/projects/pro-ef6eb6d3-b034-4552-b894-9589c7010bae) 


## Contributors

- [Sowmya Venigalla](https://github.com/savasyavenigalla)
- [Metlapalli Ragini](https://github.com/Ragini-Metlapalli)
- [Saniya Ismail Kondkar](https://github.com/saniyaismail)


