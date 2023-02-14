# CardIAC
Implementations of "Computers" based on the CardIAC and similar machines

## "Paper" Version

![Screen Shot](/CardIAC_at_Startup.png?raw=true "Startup Screen")

## Simple Programming Example 1 - Add two numbers

Start by picking two numbers to add. We'll use 14 and 28 (following the example by Ben Eater).

Click on the word "INPUT" in the lower left corner of the screen and a pop-up box should appear. The pop-up box will ask for all input values separated by spaces. Enter "14 28" and click OK. Those two numbers should appear at the bottom of the "INPUT" slider. The input numbers may be partially obscured, but you can click and drag on the slider (above the input area) to see both numbers in the INPUT window. Leave it set to showing card 1 (which should be 14).

Next begin entering a program. The program will need storage space (addresses) for our two input values. We can pick almost any of the 100 available memory cell addresses. It's sometimes convenient to start with 51 since that's half-way through the available memory and happens to start with a "1" and is in the top row. So let's assign the first input value to 51 and the second to 52.

Now that we have our addresses we can write our first line of code. We will want to load the first input card into memory cell 51. The instruction to do that is "IN 51". In "machine code" that will be "051" (where 0 is the input instruction, and 51 is the memory cell to get the value. Let's put that instruction in Memory Cell 00. Click on the yellow rectangle at cell 51 and you will get a prompt "Enter a value for memory cell 0". Type in "051" and click OK.
