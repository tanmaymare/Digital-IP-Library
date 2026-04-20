# Verilog Codes

Here are some verilog codes that i had written and simulated using Icarus Verilog in "codes" folder. 
The ones in the "Vivado simulations" are done on vivado and also has been implemented on FPGA (Basys 3 trainer board)



# Checklist
|   Sr.No  | Module name             | Status     | Notes                       |
|-----------------------|---------------------------------|------------|-----------------------------|
|  | example   | ✅ Done, ⏳ In Progress, 📋 Planned     | ......... |
| 1 | Basic Gates : And, Or, Not , Xor | ✅ Done | Wrote modules and testbenches of each gate and then using icarus verilog and GTK wave simulated them. |
| 2 | Mux | ✅ Done | Build 2:1 , 4:1 and 8:1 modules and there respective test benches using icarus verilog |
| 3 | encoders & decoders | ✅ Done | 4:2 Priority encoder, decoders 2:4 and 3:8 | 
| 4 | Majority gate & 3 input Xor followed by And | ✅ Done |  Majority gate: consisting 3 And gates followed by Or gate, 3 input Xor logic followed by And |

After shifting to Vivado with basys 3 implementation
 |   Sr.No  | Module name             | Status     | Notes                       |
|-----------------------|---------------------------------|------------|-----------------------------|
| 5 | Half Adder and Full adder | ✅ Done | Simulated half adder and full adder on vivado and then implementation on the FPGA board ( basys 3 ) | 
| 6 | Flip flops : J -K , S -R , D , T | ⏳ In Progress | Have completed the D FF simulation but facing issues in implementation | 
| 7 | Synchronous Counter |  ✅ Done  | Build a top module : synchronous counter, a clock divider  and then a binary to 7 seg module, generated bit file and implemented on basys 3 ( video available) | 
| 8 |  4 bit ALU |  ⏳ In Progress | |
| 9 | FSM |  ⏳ In Progress  | | 
| 10 | carry look ahead adder | 📋 Planned   | | 
| 11 |  4 bit binary ripple adder | 📋 Planned   | | 
