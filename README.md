<h1>Rectangle Area Calculator CMD Tool</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This Python command-line tool calculates the area of a rectangle based on user-provided length and width dimensions. It provides a simple and efficient way to compute the area of a rectangle without the need for complex mathematical calculations. This tool is useful for educational purposes, quick calculations, and as a demonstration of basic Python programming concepts.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>CMD</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through with images :</h2>

<p align="center">
 
- <b>Import Necessary Module: This line imports the 'sys' module, which provides access to some variables used or maintained by the Python interpreter and functions that interact strongly with the interpreter. </b>
<img src="https://i.imgur.com/VT6SYj5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

- <b>Define the Function to Calculate Area: This function, 'calculate_rectangle_area', takes two parameters: 'length' and 'width', and returns their product, which represents the area of a rectangle. </b>
<img src="https://i.imgur.com/iPSXazi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

- <b>Define the Main Function: This is the entry point of the script. It defines the 'main()' function where the execution of the script begins. </b>
<img src="https://i.imgur.com/m1wBYOp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

- <b>Handle Command-Line Arguments: This block of code checks if the number of command-line arguments is not equal to 3 (including the script name). If not, it prints a usage message and exits the script with a non-zero exit status. <br/>
<img src="https://i.imgur.com/m1wBYOp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

- <b>Convert Command-Line Arguments to Numbers: Here, the script attempts to convert the command-line arguments ('sys.argv[1]' and 'sys.argv[2]') to floating-point numbers ('float()' function). If the conversion fails (e.g., if the arguments are not numeric), it prints an error message and exits the script.  <br/>
<img src="https://i.imgur.com/MEyCtO2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

- <b>Validate Length and Width: This block of code checks if the provided length and width are positive numbers. If either value is less than or equal to zero, it prints an error message and exits the script.  <br/>
<img src="https://i.imgur.com/FmfiMoI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

- <b>Calculate and Print the Area: Finally, the script calls the 'calculate_rectangle_area()' function with the provided length and width, assigns the result to the 'area' variable, and then prints the calculated area of the rectangle.  <br/>
<img src="https://i.imgur.com/nLSCRsh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

- <b>Call the Main Function: This conditional statement checks if the script is being run as the main program (not imported as a module). If true, it calls the main() function to start the execution of the script. <br/>
<img src="https://i.imgur.com/tbruBYf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Final image:</h2>

- <b> Running CMD Tool <br/>
<img src="https://i.imgur.com/8kyKIRN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
