# PyramidPattern
Program to print Pyramid pattern of numbers and Stars.
## Explanation

The code declares a class named Pyramid.

The pattern method is declared as private. It is responsible for printing a pyramid pattern using asterisks.

Inside the pattern method, a nested loop structure is used to generate the pyramid pattern, similar to the previous code example we discussed.

The outer loop, controlled by the variable i, iterates from 1 to 5. This loop determines the number of rows in the pyramid.

Within the outer loop, the first inner loop, controlled by the variable j, prints the spaces before the asterisks, similar to the previous code example.

The second inner loop, controlled by the variable k, prints the asterisks. The number of asterisks in each row is determined by (i*2) - 1.

After the inner loops complete, a line break is added using System.out.println() to move to the next line and create a new row in the pyramid.

The num method is declared as private. It is responsible for printing a pyramid pattern using numbers instead of asterisks.

Inside the num method, a similar nested loop structure is used to generate the pyramid pattern, but instead of printing asterisks, it prints numbers.

The innermost loop, controlled by the variable k, prints the numbers k in each row. The numbers increase from 1 to (i*2)-1.

The main method is declared as public static void and serves as the entry point of the program.

Within the main method, an instance of the Pyramid class named info is created.

The pattern method is invoked on the info object using the dot operator (info.pattern()), which generates and prints the asterisk pyramid pattern.

The num method is also invoked on the info object using the dot operator (info.num()), which generates and prints the number pyramid pattern.
===>  It generates and prints two pyramid patterns: one using asterisks and another using numbers. <===
