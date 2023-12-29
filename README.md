# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
DEVELOPED BY : PRAVEENKUMAR R
REGISTERNUMBER: 212223050037

HALF ADDER:

/*![293147651-f4b7a5f8-0622-40ac-820c-b29559be88d3](https://github.com/yogeshwaran72/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153492924/678564c4-1a4c-47d9-ac3f-055a427f6b0d)
FULL ADDER:
![293147737-2a459e13-5abc-4e0a-9c4c-60068a7339d4](https://github.com/yogeshwaran72/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153492924/e973295a-53e1-4d70-bd75-01c0b2b30ffe)

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/
Logic symbol & Truthtable
RTL realization

### Output:
### RTL:
HALF ADDER:
![293147956-0bf5dc49-7257-4b3e-937a-f80065c75438](https://github.com/yogeshwaran72/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153492924/6400aa48-2d85-469f-9a1d-7152a4efadb0)
FULL ADDER:
![293148169-5dc7dd46-3910-4096-9a56-f165228e110a](https://github.com/yogeshwaran72/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153492924/79cfb04d-e522-482a-af4c-0cbc68de0f8b)

### TIMING DIAGRAM
HALF ADDER:

![293148850-e6f0f168-454b-4b3b-9853-1e4c77b72192](https://github.com/yogeshwaran72/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153492924/f57f930f-c803-469c-b81e-92ced25d9bd9)
FULL ADDER:

![293149007-103f1c1f-238a-4b87-8add-852129284c02](https://github.com/yogeshwaran72/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153492924/74f7a6eb-ba0d-43c6-80ea-ef34f94f4421)

### TRUTH TABLE 
HALF ADDER :
![293148487-796c6edd-90f2-4f83-8607-bf76f87dce4f](https://github.com/yogeshwaran72/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153492924/352053ca-0f13-49f0-8697-da5917a7ee1f)
FULL ADDER:
![293148652-4650726b-772f-46e4-95e5-f36da3cea1b2](https://github.com/yogeshwaran72/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153492924/1aac17fe-4ac4-44e2-bf69-57380959ae3d)


### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog programming.

