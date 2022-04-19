# Grading-on-marks

## Aim:
To write a C# program to grade the marks



## Algorithm:
Step1:
Start

Step2:
Create a class and declare one variable with integer datatype

Step3:
Get marks from the User.

Step4:
Use if and elif condition to check the grade

Step5:
print the grade for the given mark

Step6:
stop

## Program:
```c#
using System;
namespace Pras
{
    class program
    {
            static void Main(string[] args)
            {
            int marks;
            Console.WriteLine("ENTER THE MARK:");
            marks = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("\nYOUR GRADE IS:");
            if (marks>90)
                Console.WriteLine("O GRADE");
            else if (marks > 80)
                Console.WriteLine("A+ GRADE");
            else if (marks > 70)
                Console.WriteLine("A GRADE");
            else if (marks > 60)
                Console.WriteLine("B+ GRADE");
            else if (marks > 50)
                Console.WriteLine("B GRADE");
            else if (marks >= 40)
                Console.WriteLine("C GRADE");
            else
                Console.WriteLine("FAIL");
        }
    }
}
```
## Output:
![GRADE](https://user-images.githubusercontent.com/75234942/163851777-cceee437-1546-4232-9283-bc284220b2e4.png)


## Result:
