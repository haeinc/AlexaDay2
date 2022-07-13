## Input 
Input is the way the computer gets information from the user

Note: Python initially treats input as a `string` type

Ex: 
5 --> "5"
Today is Monday --> "Today is Monday"

## Formula:
`variableName = input("PROMPT")`

PROMPT - A question or statement that the computer asks the user

Python stores the __input__ in the __variableName__

## Operators
### Arithmetic Operators
Use to perfrom mathematical operations

1. Addition `+`
2. Subtraction `-`
3. Multiplication `*`
4. Division `/` (Exact Answer), `//` (Quotient Division)
5. Modulo `%` (Remainder)
6. Exponent `**`

Ex.
``` python # Code Block
print(5 / 2) # 2.5
print(5 // 2) # 2
print(5 % 2) # 1
print(4 ** 2) # 16
```

### Assignment Operators
1. `=` Simple Assignment
2. `+=` Addition Assignment
3. `-=` Subtraction Assignment
4. `*=`, `/=`, `//=`, `**=`, `%=`

Ex.
``` python
a = 2
a += 3 # 5 --> a = a + 3
a = 1 
a -= 5 # -4 
```

### Comparison Operators
1. `==` equal to
2. `>=` greater than or equal to
3. `>` greater than
4. `<=` less than or equal to
5. `<` less than
6. `!=` not equal to

### Boolean Operators
1. and (PRECEDENCE)
2. or
3. not

AND (BOTH NEED TO BE TRUE):
T AND T -> TRUE
F AND T -> FALSE
T AND F -> FALSE
F AND F -> FALSE

OR (AT LEAST ONE HAS TO BE TRUE):
T OR T -> TRUE
F OR T -> TRUE
T OR F -> TRUE
F OR F -> FALSE

NOT (OPPOSITE)
! T -> FALSE
! F -> TRUE

!(T OR F) -> !(T) -> FALSE
!F AND F -> T AND F -> FALSE


