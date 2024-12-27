# VHDL: Incorrect Register Initialization Leading to Unexpected Behavior

This repository demonstrates a common error in VHDL code: incorrect initialization of an internal signal or register.  The provided example showcases how initializing a register to an invalid value ('x"00"') can result in unexpected and potentially difficult-to-debug behavior.

The `bug.vhdl` file contains the erroneous code.  The `bugSolution.vhdl` file presents the corrected code with the proper initialization.