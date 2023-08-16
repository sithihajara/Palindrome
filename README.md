# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
1.Start the program.

2.Get the string value and read the string.

3.Use loop over the entire string and reverse it.

4.Use condional statement for checking the reversed string.

5.Print whether the string is palindrome or not a palindrome.

6.End the program.
## Program:
```
DEVELOPED BY : SITHI HAJARA I
REG NO : 212221230102
```
```python
using System;
namespace palindrome
{
    class stringl
    {
        public static void Main(string[] args)
        {
            string str, rev = "";
            int n;
            Console.WriteLine("Enter a String :");
            str = Console.ReadLine();
            n = str.Length - 1;
            for (int i = n; i >= 0; i--)
            {
                rev = rev + str[i];
            }
            if (rev == str)

                Console.WriteLine("{0} is Palindrome", str);
            else
                Console.WriteLine("{0} is not Palindrome", str);

        }
    }
}
```
## Output:
![ex2](https://github.com/sithihajara/Palindrome/assets/94219582/ecc3c345-9f01-45d4-80f6-2843ec8b2172)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
