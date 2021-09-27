# familyTree

## Assignment

Create a new directory in your local Git repository called familyTree. As a general rule, do not use spaces or special characters in directory or file names.

Create objects to represents 3 generations of the British Royal Family. A person in the family tree should have the following properties:

name of type String
parents of type Array
childOf of type Function
The childOf property should return a string of the parent's names.

Use a combination of objects arranged in arrays to represent different generations. Use the this keyword to create a childOf function that references the parents array of itself.

Once constructed you should be able to traverse from an individual to their grand-parents. You should be able to call childOf on any person and that function should return a string i.e. 'Elizabeth Windsor & Philip Windsor'.

To run your code execute node name_of_file.js

Commit your code into Github and share the link with your coach for review.

Assignment extension tasks
Research the difference between Object.create({}) and Object.create(null).