# Dual-Port-Ram-Using-Verilog
- This repositary contains Verilog code for Dual Port RAM.

# What is a RAM?
RAM (Random Access Memory) is a kind of volatile memory used to store data temporarily while a system is operating. It allows:

- Random access: any memory cell can be accessed directly if its address is known.

- Read/Write operations.

# What is a Dual-Port RAM
Dual-Port RAM is a type of memory that allows two independent access ports (Port A and Port B) to interact with the memory simultaneously.

Each port can:

- Have its own address bus, data bus, control signals, and clock.

- Read from, write to, or do both, without depending on the other port.

# Why is this Important?
In systems where two units need to access the same memory at the same time, single-port RAM becomes a bottleneck. Dual-port RAM eliminates that bottleneck, enabling parallelism.
