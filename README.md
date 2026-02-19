# rv32i-core
A single-cycle RV32I RISC-V processor core implemented in SystemVerilog from scratch. The design implements the full RV32I base integer instruction set — 37 instructions spanning arithmetic, logical, shift, branch, jump, and memory operations, built around a classic fetch-decode-execute architecture.
The project was built module by module with independent testbenches for each component, simulated using Icarus Verilog and verified through GTKWave waveform analysis. The processor successfully executes hand-assembled RISC-V programs loaded directly into instruction memory.
