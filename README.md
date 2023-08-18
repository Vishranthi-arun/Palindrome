# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.

## Algorithm:
### Step 1:
To start the C# program in visual Studio 2022.

### Step 2:
Create a class and declare two variable with string datatype.

### Step 3:
Loop over the entire string and reverse it.

### Step 4:
Use if condition to check whether the string and the reversed string is equal or not.

### Step 5:
print palindrome if it's equal else print not a palindrome.

### Step 6:
Save the program and run the program in visual studio 2022.

## Program:
```
Developed by : Vishranthi A
Reg No.: 212221230124
```
```
using System;
namespace PALINDROME
{
    public class Palindrome
    {
        static void Main(string[] args)
        {
            string word, reverse = "";
            Console.WriteLine("ENTER A STRING:");
            word = Convert.ToString(Console.ReadLine());
            Console.WriteLine("before reverse:" + word);
            for (int i = word.Length - 1; i >= 0; i--)
            {
                reverse += word[i];
            }
            Console.WriteLine("After reverse:" + reverse);
            if (reverse == word)
            {
                Console.WriteLine("It is palindrome");
            }
            else
            {
                Console.WriteLine("Its not palindrome");
            }
            Console.ReadLine();
        }
    }
}
```

## Output:
![image](https://github.com/Vishranthi-arun/Palindrome/assets/93427278/c9c95669-9f65-472c-98e0-6e4649ce2a98)

![image](https://github.com/Vishranthi-arun/Palindrome/assets/93427278/d5c3c46c-f28e-47f2-9f54-f576286dd04e)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
