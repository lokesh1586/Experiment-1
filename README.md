# Experiment-1

# Name: lokesh M
# Reg no:212223030173

##  Write a C programs  to demonstrate the working of following constructs with possible test cases:
a) do…while b) while…do c) if …else d) switch e) for
## a) Aim
To demonstrate the working of the do...while loop, which ensures the loop body is executed at least once, even if the condition is false initially.

## Algorithm
1.	Initialize the loop variable.
2.	Execute the statements inside the loop body.
3.	After executing the loop body, check the condition.
4.	If the condition is true, repeat the loop; otherwise, exit the loop.

## Program
~~~
#include <stdio.h>

int main() {
    int i = 0;
    do {
        printf("Number: %d\n", i);
        i++;
    } while(i < 5); // condition to stop after 5 iterations
}
~~~

## Output
![Screenshot 2025-03-06 105004](https://github.com/user-attachments/assets/f09a9acf-d237-4b09-aab9-9d5b7dc495da)

## Result
Program succcessfully executed using do while loop.

## b) Aim
To demonstrate the working of the while...do loop, where the loop will execute the body of the loop as long as the condition is true.

## Algorithm
1.	Initialize the loop variable.
2.	Check the condition before executing the loop body.
3.	If the condition is true, execute the statements inside the loop.
4.	Repeat steps 2 and 3 until the condition becomes false.

## Program
~~~
#include <stdio.h>

int main() {
    int i = 0;

    // while loop to print numbers from 0 to 4
    while(i < 5) {
        printf("Number: %d\n", i);
        i++;
    }

}
~~~

## Output
![Screenshot 2025-03-06 105112](https://github.com/user-attachments/assets/baa9abbd-b2fb-4a7e-9da8-758cd585f42a)

## Result
Program succcessfully executed using while loop.

## c) Aim
To demonstrate the working of the if...else conditional statement, which allows for decision-making based on a condition.

## Algorithm
1.	Evaluate the condition.
2.	If the condition is true, execute the block of code inside the if statement.
3.	If the condition is false, execute the block of code inside the else statement.

## Program
~~~
#include <stdio.h>

int main() {
    int num;

    // Get user input
    printf("Enter a number: ");
    scanf("%d", &num);

    // if...else to check if the number is even or odd
    if(num % 2 == 0) {
        printf("The number %d is even.\n", num);
    } else {
        printf("The number %d is odd.\n", num);
    }

}
~~~

## Output
![Screenshot 2025-03-06 105201](https://github.com/user-attachments/assets/eae38325-79fd-413f-8530-02903a4f5a92)

![Screenshot 2025-03-06 105216](https://github.com/user-attachments/assets/439bb43f-808a-4582-b72c-b2a51627045d)

## Result
Program succcessfully executed using if...else.

## d) Aim
To demonstrate the working of the switch statement, which is used to select one of many code blocks to be executed.

## Algorithm
1.	Evaluate the expression in the switch statement.
2.	Compare the expression's value with each case value.
3.	If a match is found, execute the associated block of code.
4.	If no match is found, execute the default case (if defined).

## Program
~~~
#include <stdio.h>

int main() {
    int choice;

    printf("Enter a number (1-3): ");
    scanf("%d", &choice);

    switch (choice) {
        case 1:
            printf("You selected option 1.\n");
            break;
        case 2:
            printf("You selected option 2.\n");
            break;
        case 3:
            printf("You selected option 3.\n");
            break;
        default:
            printf("Invalid choice. Please enter a number between 1 and 3.\n");
    }

    return 0;
}
~~~

## Output
![Screenshot 2025-03-06 110228](https://github.com/user-attachments/assets/981002f5-540d-4b1f-8153-2b8102d6c710)

![Screenshot 2025-03-06 110247](https://github.com/user-attachments/assets/f04999f6-1af7-4cbd-a13a-1df019de20bd)

## Result
Program succcessfully executed using switch case.

# e) Aim
To demonstrate the working of the for loop, which is used to iterate a fixed number of times.

## Algorithm
1.	Initialize the loop variable.
2.	Set the loop condition.
3.	Execute the loop body.
4.	After each iteration, increment/decrement the loop variable and repeat until the condition becomes false.

## Program
~~~
#include <stdio.h>

int main() {
    int i, n;

    printf("Enter the number of iterations: ");
    scanf("%d", &n);

    // Using a for loop to iterate 'n' times
    for (i = 1; i <= n; i++) {
        printf("Iteration %d\n", i);
    }

    return 0;
}
~~~


## Output
![Screenshot 2025-03-06 110452](https://github.com/user-attachments/assets/2a1dff95-4fe2-4864-a74d-afb4d8e05f21)

## Result
Program succcessfully executed using for loop.
