# Title : Objects and Classes

# Tools : VS Code ( C++ Program)

# Aim :To study and implement Classes and Objects 

# Theory :
•	Object-oriented programming (OOP) is a way of thinking about and organizing code for maximum reusability. 

•With this type of programming, a program comprises objects that can interact with the user, other objects, or other programs. 
This makes programs more efficient and easier to understand.

•	Programs made with object-oriented programming are well-organized. 

•	Since relative data and functions are grouped in the same object, it is simple to find what you're looking for and understand the code's fundamental purpose. 

•	Developers new to the project or those revisiting code they have not seen in a while can adapt much faster. 

# Procedure :
Step 1: Start

Step 2: Define a class named cube Inside the class:

Declare three integer data members: height, width, and length.

Assign them default values:

height = 4

width = 5

length = 3

Step 3: Define a member function named volume() This function:

Calculates the volume using the formula:

volume
height × width × length volume=height×width×length Returns the calculated volume as an int.

Step 4: In the main() function Create an object d1 of class cube.

Call the volume() function using the object d1, and store the result in an integer variable vol.

Step 5: Display the result Use cout to print:

CODE2:

Step 1: Start Step 2: Define a class named cube Declare three integer data members:

height

width

length

Initialize the values:

height = 4

width = 5

length = 3

Step 3: Inside main() function Create an object d1 of class cube.

Step 4: Calculate volume Use the formula:

volume
𝑑 1. ℎ 𝑒 𝑖 𝑔 ℎ 𝑡 × 𝑑 1. 𝑤 𝑖 𝑑 𝑡 ℎ × 𝑑 1. 𝑙 𝑒 𝑛 𝑔 𝑡 ℎ volume=d1.height×d1.width×d1.length Store the result in a variable named vol.

Step 5: Display the result Output the value of vol using cout.

Step 6: End the program Use return 0; to exit main() properly

CODE4: Step 1: Start Step 2: Define a class named cube Declare three public integer variables:

height

width

length

Step 3: Define the input() method Prompt the user to enter values:

Ask for height → store in height

Ask for width → store in width

Ask for length → store in length

Step 4: Define the vol() method Calculate volume using the formula:

volume
height × width × length volume=height×width×length Return the calculated volume

Step 5: Define the display() method Call the vol() method to get the volume

Print the volume using cout

Step 6: In the main() function Create an object v1 of the class cube

Call v1.input() to accept dimensions from the user

Call v1.display() to show the volume on the screen

Step 7: End

CODE3: Step 1: Start Step 2: Define a class named cube Mark three attributes as private:

height ← 4

width ← 5

length ← 3

Step 3: Inside the class, define a public method volume() Multiply height, width, and length.

Store the result in a local variable v.

Return v (which represents the volume).

Step 4: In the main() function Create an object d1 of class cube.

Call the volume() method using object d1.

Store the returned volume in a variable vol.

Step 5: Print the volume Use cout to print:

# Conclusion :
A class acts as a blueprint, defining attributes and behaviors. An object is an instance created from that blueprint.

This approach allows you to write organized, reusable, and maintainable code by bundling data and functions together. It is fundamental for building complex applications that model real-world problems
