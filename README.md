# Logic Gate Simulator

This project is a logic gate simulator that allows users to create and simulate digital logic circuits. It provides a visual interface for placing and connecting various logic gates and components. It is inspired by logic.ly.

## Features

- **Create and Simulate Circuits**: Place and connect various logic gates and components to build digital circuits
- **Save and Load Circuits**: Save your circuit designs to local storage and load them later
- **Custom Components**: Create and save integrated circuits by combining existing gates.

## Usage

- Use the mouse to move and connect components
    - Hold `shift` to connect multiple wires
- Use the slider to adjust the number of inputs
- Drag to select multiple components or press `Ctrl + A` to select all.
- Press each wire individually to select multiple wires
- Use the `Delete` key to remove components

## Using integrated circuits (IC)

- Clear all other components except for those that  will be used in the IC
- Add switches and output components; these will serve as the inputs and outputs of the integrated circuit
- Select an individual switch or output and begin typing to label the input/output
- Add other components and wire them up
- Press the `Create IC` button to name and add your IC
- Your IC can be accessed by pressing its corresponding button

- You can also remove (requires refresh) integrated circuits
- You see inside integrated circuits (removes all other components) by entering the index position (starts from 0)

[Preview Link](https://raw.githack.com/yusuf-ab/logic-gate-simulator/main/logic%20simulator.html)