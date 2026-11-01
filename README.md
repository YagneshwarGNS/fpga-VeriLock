FPGA-Based Home Security Door Lock

Project Overview

The FPGA-Based Home Security Door Lock is a digital security system designed using Verilog HDL and implemented on the Altera DE2-115 FPGA development board.

The system uses a keypad interface to accept password input, verifies the entered password, and controls the door lock based on authentication. An LCD interface provides feedback regarding the lock status and system operations.

Key Features

- Password-based door access control.
- Keypad input decoding using Verilog HDL.
- FSM-based lock control.
- Password storage and verification.
- LCD interfacing for displaying system messages.
- Modular RTL architecture.
- Functional verification using a Verilog testbench.
- FPGA implementation support for the DE2-115 board.

Hardware and Software Requirements

Hardware:
- Altera DE2-115 FPGA Development Board
- Matrix Keypad
- LCD Display
- Connecting wires and peripherals

Software:
- Intel Quartus Prime
- Verilog HDL
- ModelSim (for simulation)

Project Modules:

| Module | Description |
|---|---|
| home_security_lock.v | Top-level module |
| keypad_decoder.v | Decodes keypad input |
| lock_fsm.v | FSM-based lock control |
| password_store.v | Password storage and verification |
| message_picker.v | Selects LCD messages |
| lcd_controller.v | LCD interfacing |
| lcd_message_rom.v | Stores LCD messages |
| tb_home_security_lock.v | Functional verification testbench |
