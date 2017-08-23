# C
## Keyword
> คำที่ห้ามใช้ในการตั้งชื่อตัวแปร

|||||
| --- | --- | --- | --- |
| auto | double | int | struct |
| break | else | long | switch |
| case | enum | register | typedef |
| char | extern | return | union |
| continue | for | signed | void |
| do | if | static | while |
| default | goto | sizeof | volatile |
| const | float | short | unsigned |

## Data Type
| Type | Text Format |
| --- | --- |
| int | %d |
| float | %f |
| char | %c, %d (ascii) |

## Variable
- ประกอบด้วย ตัวอักษร ตัวเลข และ _ เท่านั้น
- ห้ามขึ้นต้นด้วยตัวเลข
### Syntax
```c
DataType VariableName = InitializeValue;
```
```c
int id = 0;
float accountBlance;
double bookPrice;

// A character constant is a constant which uses single quotation around characters. For example: 'a', 'l', 'm', 'F'
char test = 'h';

long double i;
```

## Escape Sequences
| Escape Sequences | Character |
| --- | --- |
|\b | Backspace |
|\f | Form feed |
|\n | Newline |
|\r | Return |
|\t | Horizontal tab |
|\v | Vertical tab |
|\\ | Backslash |
|\' | Single quotation mark |
|\" | Double quotation mark |
|\? | Question mark |
|\0 | Null character |

## printf()
```c
printf("C Programming\n");

int testInteger = 5;
printf("Number = %d\n", testInteger);

float f = 22.45;
printf("Value = %f\n", f);
printf("Value = %.2f\n", f);

char chr = 'T';
printf("ASCII value of %c is %d", chr, chr);
```
### Output
```
C Programming
Number = 5
Value = 22.450000
Value = 22.45
ASCII value of T is 84
```

## scanf()
```c
int testInteger;
printf("Enter an integer: ");
scanf("%d", &testInteger);
printf("Number = %d", testInteger);
```
### Output
```
Enter an integer: 4
Number = 4
```