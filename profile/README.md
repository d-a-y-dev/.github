# RAM Simulation & 5-Stage Pipeline Mips Visualiser

# Overview

This project is a RAM (Random Access Memory) simulation that provides basic read and write functionalities. Additionally, we have a simulation for 5-stage pipeline for better visualization. The interactive visualization is achieved using IMGUI (Immediate Mode Graphical User Interface) and SDL2.

## Initial Goals

- Creating RAM simulation into Mips simulation.
- Creating RAM visualiser for read and write along with Mips 5-stage pipeline.
- Deploy to pages so people could use the visualiser to see the dataflow.

## Achieved Goals
- [x] Basic RAM simulation with mips sim, [here](https://github.com/d-a-y-dev/ram-sim)
- [x] 5-stage pipeline visualiser, [here](https://github.com/d-a-y-dev/mips-visualiser)
- [x] Auto deployment to [GitHub Pages](https://d-a-y-dev.github.io/mips-visualiser/)
- [x] Mips visualiser supports both data forwarding and without
- [ ] Integrating/Implementing RAM visualiser into 5-stage visualiser

## Future Goals
- Integrating/Implementing RAM visualiser into 5-stage visualiser
- Fix all caveats in 5-Stage visualiser
- Add data forwarding lines
- Improve UI (to be more accurate)
- Instruction lists (able to see which instruction is being run)

# 5-Stage pipeline visualiser
source code could be found [here](https://github.com/d-a-y-dev/mips-visualiser)

demo [here](https://d-a-y-dev.github.io/mips-visualiser/)
## Caveats
- Not all instructions are supported yet (Wrong visualisation)
    - Branching
    - Load/Store
- Does not have data forwarding lines yet

## Instructions
Clicking "run" (without anything in the box) will run the default instructions, then you could see the dataflow for each instructions.
![image](https://github.com/d-a-y-dev/d-a-y-dev.github.io/assets/88727759/35fbd437-84cc-4a74-bdac-dc0cdb0bbca8)

Dataforwarding could be enabled/disabled via the "Data Forward" checkbox, (after that click 'run', you need to rerun the sim)
![image](https://github.com/d-a-y-dev/d-a-y-dev.github.io/assets/88727759/6e05af46-5219-4686-a211-7e644ac1b9de)

Click on the arrows to move forward/backward 1 cycle                
![image](https://github.com/d-a-y-dev/d-a-y-dev.github.io/assets/88727759/9f3a9c84-96ee-445c-bb3a-26a19eedd9c5)

To put in your own instructions, compiled the instructions then put in the hex'd instruction into the box (as a single line) then click 'run'.           
![image](https://github.com/d-a-y-dev/d-a-y-dev.github.io/assets/88727759/52a6c175-a150-44b3-8e05-6e84b31bf840)

<!-- ## Requirements

Ensure you have the following dependencies installed before running the project:

- C++ Compiler
- IMGUI Library
- SDL2 Library -->

# Ram Sim
![Alt text](https://github.com/d-a-y-dev/d-a-y-dev.github.io/assets/104582029/7affc6bf-b3cb-40bd-80b4-04788df4e647)
![Alt text](https://github.com/d-a-y-dev/d-a-y-dev.github.io/assets/104582029/82519b59-2313-4572-9dd6-70bc973a769a)
![Alt text](https://github.com/d-a-y-dev/d-a-y-dev.github.io/assets/104582029/46f0f171-6be5-4369-89e2-38cac9399101)
![Alt text](https://github.com/d-a-y-dev/d-a-y-dev.github.io/assets/104582029/1fe1e00d-bfc5-46cb-9604-caf3e03fcbe4)
![Alt text](https://github.com/d-a-y-dev/d-a-y-dev.github.io/assets/104582029/381418af-46d2-431e-978a-55f6d5dd64e4)
![Alt text](https://github.com/d-a-y-dev/d-a-y-dev.github.io/assets/104582029/517a0245-8ed3-4c39-ba16-734f428232ac)
![Alt text](https://github.com/d-a-y-dev/d-a-y-dev.github.io/assets/104582029/b1418736-f727-443c-bd1e-df577116223e)
