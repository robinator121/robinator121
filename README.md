## hi, i'm Róbert (robinator121)

Computer Science Engineering student at the University of Debrecen, working in cloud operations on the side.
I like the layer where software stops being abstract: registers, exception levels, interrupts, memory layout,
and what actually happens when things fail.

Lately that means **AArch64**, **bare metal**, **C/C++**, and research on how bad randomness breaks simulations.

### things worth looking at

| repo | what it is |
|------|------------|
| [aarch64-baremetal](https://github.com/robinator121/aarch64-baremetal) | Bare-metal runtime for a QEMU Cortex-A53: EL2→EL1 via `ERET`, veactor table, PL011 UART, GICv2, drift-free virtual timer. Validated with GDB assertions. |
| [rngLABexperimental](https://github.com/robinator121/rngLABexperimental) | My BSc thesis research: how faults in random inputs propagate through Monte Carlo simulations, and how to tell sampler failure apart from a broken RNG. |
| [crashlog](https://github.com/robinator121/crashlog) | C11 append-only binary log: CRC-32 records, fault-injection tests, explicit tail repair. Asks one narrow question about interrupted writes and tests it properly. |
| [asm_lab](https://github.com/robinator121/asm_lab) | Hand-written AArch64 + NEON exercises. No AI-written code, all bugs are mine. |
| [t](https://github.com/robinator121/t) | Small CLI that generates code from templates, compiles, runs and reports exit codes. For prototyping and teaching. |

### tools i use

`C` · `C++` · `AArch64 asm` · `Python` · `Verilog` · `QEMU` · `GDB` · `Clang/LLD` · `Linux (Arch, btw)`

### currently

- pushing RNGLab toward v1.0 with ESP32/Arduino hardware entropy sources
- learning more about the space between silicon and the OS

<sub>no libc was harmed in the making of this profile.</sub>
