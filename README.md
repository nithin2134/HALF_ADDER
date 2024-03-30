AIM: 

To simulate and synthesis half adder using vivado 2023.2 

APPARATUS REQUIRED: 

vivado 2023 

PROCEDURE: 

STEP:1 Start the vivado software, Select and Name the New project. 

STEP:2 Select the device family, device, package and speed. 

STEP:3 Select new source in the New Project and select Verilog Module as the Source type. 

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it. 

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax. 

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table. 

STEP:7 compare the output with truth table. 

 
# HALF_ADDER# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/fe672c28-5c6a-4355-b70f-b40bce63880d)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/5f1a79a7-73c2-4b99-a40d-afa2a20c74ac)
# Sum = A XOR B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/020e1531-1c11-42e5-9f27-f09ba459984d)
# Carry = A AND B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/988ae131-0822-4d23-941b-eaafad349a72)

**Verilog code**

module HalfAdder(a,b,sum,carry); 

input a,b; 

output sum,carry; 

xor (sum,a,b); 

and (carry,a,b); 

endmodule 

**output**

![hagit](https://github.com/nithin2134/HALF_ADDER/assets/160302970/9fcd6267-a087-4ff6-ad2b-2b9532087ee7)

**Result**

Thus the simulatation and synthesis of half adder using vivado was successfully executed and verified.

