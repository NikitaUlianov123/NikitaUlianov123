## Nikita Ulianov

CS graduate from CSUN (B.S. Computer Science, 2026). I build low-level projects, mostly in C#: compilers, obfuscators, emulators, and OS internals. Software engineering instructor at Great Minds Robotics since 2023, teaching students ages 10–18 everything from OOP to neural networks and game theory.

### Current: OpenBrick

An educational robotics platform built by the Great Minds Robotics team. Students write a program once in **Clay**, a small robotics language, and the same program drives a simulated robot in **Brickyard** and a physical robot, **Brick**. Everything ships behind one VS Code extension, **Sculptor**.

- Clay language work, backed by a conformance test corpus of about 1,500 programs
- Firmware for the Brick main board (STM32 Nucleo H7A3): a UART "smart port" link to PIC sensor boards at 1 Mbaud
- On-robot run logging: a binary log format saved to flash with rotation and a space budget, pulled back off the board from the command line or from Sculptor

*Source currently private.*

### Public projects

- **[C-Flat_Compiler](https://github.com/NikitaUlianov123/C-Flat_Compiler)**: a full compiler for a C#-inspired language, with a tokenizer, parser, semantic analysis, and code generation. Classes, function overloads, and an `ifn't` statement
- **[Obfuscator](https://github.com/NikitaUlianov123/Obfuscator)**: a 5-person team project to obfuscate C# and RobotC code, including an ASCII-art steganography technique that hides executable logic in images, and a custom compiler and VM for RobotC
- **[AIWorld](https://github.com/NikitaUlianov123/AIWorld)**: a modular AI playground where you plug agents (BFS, DFS, A\*, ExpectiMax, Markov, Q-Learning) into environments (8 Puzzle, a cheese-maze grid, Chancy Tic-Tac-Toe), all written without ML libraries
- **[ComputerArchitecture](https://github.com/NikitaUlianov123/ComputerArchitecture)**: code from a computer architecture camp

### Other projects

- **OS emulator**: a virtual machine with an MLFQ scheduler, device interrupts, a buddy allocator, a disk with a file system, an interactive shell, and its own small language with `spawn` / `kill` / `wait` built in. Includes a step-through visualizer
- **Corner Critic**: a Visual Studio extension that shows a file's error and style status in the corner of the editor
- **[NeuralNetworks](https://github.com/NikitaUlianov123/NeuralNetworks)**, **[DataStructs](https://github.com/NikitaUlianov123/DataStructs)**, **[Chess](https://github.com/NikitaUlianov123/Chess)**: earlier work on neural networks, data structure implementations, and a multiplayer chess game
