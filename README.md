# 8-Bit-Arithmetic-Operations-using-8085
## Aim:
To perform 8-bit arithmetic operations such as addition, subtraction, multiplication, and division using the 8085 microprocessor.

## Apparatus Required:
•	Laptop with internet connection

## Algorithm:

### For Addition (With Carry Consideration):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Add the contents of registers A and B.
4.	If carry is generated, store carry in 4301H.
5.	Store the sum in memory location 4300H.
   
### Program:
![MPMC](https://github.com/user-attachments/assets/b7c0db6b-1b51-4865-b347-cc08693cc9d7)



### Output:
![MPMC EXP 1g](https://github.com/user-attachments/assets/16443cfd-0b42-47a6-af44-d2f6555c9124)
![MPMC EXP1h](https://github.com/user-attachments/assets/efa04cca-fcdf-4e2c-b893-57d353063cae)




### For Subtraction (Considering Greater Number):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Compare A and B.
4.	If A < B, swap the values of A and B to ensure positive result.
5.	Subtract the content of B from A.
6.	Store the result in memory location 4300H.

### Program :
![MPMC1](https://github.com/user-attachments/assets/3fe1edea-4a82-4f41-9e45-e4a3e6ad0285)



### Output:
![MPMC EXP 1b](https://github.com/user-attachments/assets/75f15ce5-5e23-41d0-a2da-70253e353934)

![MPMC EXP 1a](https://github.com/user-attachments/assets/ec0aa8f9-1e94-47ed-b011-89cb02e6a67c)


### For Multiplication:
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Multiply A and B using repeated addition.
4.	Store the result in memory locations 4300H and 4301H (if required for higher bits).

### Program:
 ![MPMC2](https://github.com/user-attachments/assets/04e9c5aa-89b7-4233-b8d3-b2eed49096d1)


### Output:
![MPMC EXP 1d](https://github.com/user-attachments/assets/e4a7cf0b-1e9e-4c58-9a8d-db5552b96da4)


![MPMC EXP 1c](https://github.com/user-attachments/assets/c1ea6c61-6149-4ef8-87b3-09eda8125f85)




### For Division:
1.	Load the dividend from memory location 4200H into register A.
2.	Load the divisor from memory location 4201H into register B.
3.	Perform division using repeated subtraction.
4.	Store the quotient in 4300H and remainder in 4301H.

### Program:
![MPMC3](https://github.com/user-attachments/assets/9784a0d8-b69b-4e53-a238-158a559a816a)



### Output:
![MPMC EXP 1e](https://github.com/user-attachments/assets/2634b231-d73f-4bb3-b1c4-8e3299ccaba1)
![MPMC EXP 1f](https://github.com/user-attachments/assets/6820ce10-cd27-44db-9ab3-e0fdb5f2acb5)




## Result:
The 8-bit arithmetic operations using the 8085 microprocessor have been successfully executed and verified using memory access for input and output.

