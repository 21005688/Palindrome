# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:

## step 1:
Import the 'system' namespace to use the classes present in the 'system' namespace.

## step 2:
Declare the main method.

## step 3:
Declare name variable in the string format.

## step 4:
And declare an empty string to reverse the string input.

## step 5:
Using for loop reverse the input string and store it in rev.

## step 6:
Using if else loop check whether the input string and the reversed string are same.

## step 7:
Print the result.
## Program:
```
using System;
namespace palindrome
{
    public class Program
    {
        static void Main(string[] args)
        {
            string str1;
            string rev = "";
            Console.Write("Enter a string : ");
            str1 = Convert.ToString(Console.ReadLine());


            for (int i = str1.Length - 1; i >= 0; i--)
            {
                rev += str1[i];
            }

            if (str1 == rev)
            {
                Console.WriteLine("{0} is Palindrome.", str1);
            }
            else
            {
                Console.WriteLine("{0} is not Palindrome", str1);
            }
        }
    }
}
```

## Output:
![c #](https://user-images.githubusercontent.com/94747031/225877616-ce91a19b-6b39-48e0-8866-a48f777acb75.png)
![c # 2](https://user-images.githubusercontent.com/94747031/225877651-5e48a104-55fd-4ef2-8e46-fe8644460fdb.png)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
