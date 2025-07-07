This project implements a Synchronous FIFO buffer in SystemVerilog, designed for use in digital systems where data transfer occurs under a single clock domain. The FIFO supports parameterized depth and data width, and handles core functionalities such as write, read, full, and empty conditions.
🔧 Features:
Parameterized DATA_WIDTH and DEPTH
Synchronous read and write operations
Proper full and empty flag handling
Testbench included for functional simulation
Verified using waveform outputs (via Cadence/EDA Playground)

🛠 Use Cases:
Data buffering between modules in synchronous systems
Pipelined data processing
Communication protocols and memory management
