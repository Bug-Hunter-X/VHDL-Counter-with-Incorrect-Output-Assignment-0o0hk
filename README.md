# VHDL Counter Bug
This repository demonstrates a common but subtle bug in VHDL code that can lead to unexpected behavior. The bug is related to the assignment of the internal counter signal to the output port.

## Bug Description
The VHDL code implements a simple counter. However, under certain clock conditions, the output might not reflect the actual value of the internal counter. This issue arises from how the assignment to the output port is handled.

## Solution
The solution involves a modification in how the output port is assigned. By adding a process to specifically handle the output, we make sure that the value of the counter is updated correctly during every clock cycle.

## How to run the code
You can run the code using a VHDL simulator like ModelSim or GHDL.