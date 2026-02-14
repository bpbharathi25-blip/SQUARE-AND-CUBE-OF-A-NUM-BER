# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 00H
MOV R0, #50H
MOV A, @R0
MOV B, @R0
MUL AB
INC R0
MOV @R0, A
END

```

## OUTPUT
![WhatsApp Image 2026-02-11 at 11 19 11 AM](https://github.com/user-attachments/assets/7bd35aa1-71e3-4cee-a2b2-66c8c2f75eb6)

![WhatsApp Image 2026-02-14 at 11 14 14 AM](https://github.com/user-attachments/assets/66e7dc38-1243-4510-9766-8068b3ee973e)


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END
```


## OUTPUT

![WhatsApp Image 2026-02-14 at 11 19 56 AM](https://github.com/user-attachments/assets/3fef56e5-c347-491d-8a9a-1bf07f2e8500)


![WhatsApp Image 2026-02-14 at 11 28 46 AM](https://github.com/user-attachments/assets/de5c4e1f-484e-4bbb-86ea-73d98e250e19)

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
