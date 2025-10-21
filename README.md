# MODULE-1

# 1a : C program to find the ASCII character of the given value.

## AIM:
 To write a C program to find the ASCII character of the given value.
 
## ALGORITHM:
1. Start
2. Input an integer num1
3. Convert num1 to its ASCII character
4. Print the character
5. End

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int num1;
    scanf("%d",&num1);
    printf("Character of ASCII Value %d is %c",num1,num1);
    return 0;
}
```

## OUTPUT:

## RESULT:
Thus,the program has been executed successfully.

---

# 1b : C program to read X value and check whether that number is equal to 000 using an if-else

## AIM:
 To write a C program to read X value and check whether that number is equal to 000 using an if-else?

## ALGORITHM:
1. Start
2. Input a number → num1
3. If num1 == 0
→ Print "Number is equal to 000"
4. Else
→ Print "Number is NOT equal to 000"
5. End
   
## PROGRAM:
```
#include <stdio.h>
int main()
{
    int num1;
    scanf("%d",&num1);
    if (num1 == 000)
        printf("Number is equal to 000");
    else 
        printf("Number is NOT equal to 000");
}
```
## OUTPUT:

## RESULT:
Thus,the program has been executed successfully.

---

# 1c : C program to swap two values without using a third variable.

## AIM:
 To write a C program to swap two values without using a third variable.

## ALGORITHM:
1. Start
2. Input two numbers → num1, num2
3. Display values before swapping
4. Swap logic:
- num1 = num1 + num2
- num2 = num1 - num2
- num1 = num1 - num2
5. Display values after swapping
6. End


## PROGRAM:
```
#include <stdio.h>
int main()
{
    int num1, num2;
    scanf("%d %d", &num1, &num2);
    printf("Numbers before swapping: %d %d\n", num1, num2);
    num1 = num1 + num2;
    num2 = num1 - num2;
    num1 = num1 - num2;
    printf("Numbers after swapping: %d %d", num1, num2);
    return 0;
}
```
## OUTPUT:


## RESULT:
Thus,the program has been executed successfully.

---

# 1d : 
C program to read the age of a candidate and determine whether he/she is eligible for admission into pre-school( assume eligible age > 3).

## AIM:
To write a C program to read the age of a candidate and determine whether he/she is eligible for admission into pre-school( assume eligible age > 3).

## ALGORITHM:
1. Start
2. Input age
3. If age > 3
→ Print "Eligible for admission"
4. End

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int age;
    scanf("%d", &age);
    if (age > 3) 
        printf("Eligible for admission") ;
    return 0;   
}
```

## OUTPUT:


## RESULT:
Thus,the program has been executed successfully.

---

# 1e :
C program to read any digit(16-20), display in the word.

## AIM:
To write a program in C to read any digit(16-20), display in the word.

## ALGORITHM:
1. Start
2. Input an integer num
3. Switch on the value of num:
- If num == 16, print "Sixteen."
- If num == 17, print "Seventeen."
- If num == 18, print "Eighteen."
- If num == 19, print "Nineteen."
- If num == 20, print "Twenty."
- Else, print "invalid number."
4. End


## PROGRAM:
```
#include <stdio.h>
int main()  
{
    int num1;
    scanf("%d", &num1);
    switch (num1)
    {
        case 16:
            printf("Sixteen.");
            break;
        case 17:
            printf("Seventeen.");
            break;
        case 18:
            printf("Eighteen.");
            break;
        case 19:
            printf("Nineteen.");
            break;
        case 20:
            printf("Twenty.");
            break;
        default:
            printf("invalid number.");
    }
    return 0;
}
```

## OUTPUT:


## RESULT:
Thus,the program has been executed successfully.
