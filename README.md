# 8-bit Single-Cycle Processor

In this project, I worked on designing and implementing a simple 8-bit single-cycle processor as part of CO224 Computer Architecture Course. The main objective was to enhance my understanding of computer architecture through practical implementation, using Verilog HDL to build the processor from scratch.

## Key Components of the Project

- Arithmetic Logic Unit (ALU): Created an 8-bit ALU capable of handling fundamental arithmetic operations (add, sub) and logical functions (and, or, mov, loadi).
- Register File: Built an 8×8 register file for fast and effective data storage and retrieval.
- Control Logic: Designed control logic to coordinate instruction flow and integrate the ALU and register file into a functional CPU.
- New Instructions: Added support for flow control commands (j, beq) and memory operations (lwd, swd) to enhance the processor's capabilities.

To boost the processor's efficiency, a memory hierarchy was implemented, consisting of:
- Data Memory: A 256-byte module with a 5-clock-cycle latency for data access.
- Data Cache: A direct-mapped cache (32 bytes, 4-byte block size) to minimize memory access delays.
- Instruction Cache: Added a 128-byte instruction cache with a 16-byte block size to improve instruction fetching.

## Outcome

The processor successfully executed a predefined set of instructions in a single cycle. The inclusion of the memory hierarchy significantly improved performance, reducing access times and enhancing overall efficiency. The project concluded with a performance comparison that highlighted the advantages of using caches.

##  Contributors

Ishan Kumarasinghe, e20211@eng.pdn.ac.lk <br>
Dasuni Kawya, e20197@eng.pdn.ac.lk
