<b>HW 2 Question 6:</b> Shape display via object-oriented approach (Java)

<b>Due:</b> 15 February 2019

<b>Team member(s):</b> Dieu My Nguyen

<b>Assignment description:</b> Revisit your Shape Program from Homework 1. Write this program again (with the same requirements as the original) in a different OO language than you used the first time. Consider anything from an OOAD perspective that you’ve learned or thought about that you should change in this version. Include those changes in your code’s comments and your README file.

<b>Changes from Homework 1 Question 4 Python version of program:</b>

(These comments are also included in the respective sections of the code.)

- In the Python version, my abstract class Shape was very simple with one method display(). Here, inheritance is made use of more. More fields/attributes and methods that should be inherited by the subclasses are included in this abstract superclass. This increases code reuse for more concise code.

- While I displayed graphics in Python, the shape display here will simply be printing shapes and their attributes to the screen, for simplicity and because it is my first Java programming experience.

- In the Python version, I had a Display class to be passed into the Collection class to display all the shapes. Here, I have Collection take as argument the "shapes" object array that holds the database of shapes and simply display them without another class. Like before, Collection also sorts shapes based on ascending z-order before displaying.

- While in Python, I could easily make actual graphics to display the shapes, here, my database is an array of objects of the derived classes of Shape (i.e. Circle, Square, Triangle). Similar to before, each object has a name to indicate its shape type, and attributes regarding its location (x, y, z) and measurements (e.g. height).

- Before, the shape database was created more manually. Here, this makeDatabase class makes use of aggregation with the Shape subclasses to make the shape objects for the database.

- As before, the main program is concise, with object instantiations of the above classes to create a shape display program. First, the program create a database object of the makeDatabase class to make an array of shape objects. Then, a Collection is also instantiated to contain all the shapes from the database, sort them, and display them via printing to screen their name and attributes.

<b>Instructions to run code:</b> Simply run the Java code cells in the Jupyter Notebook. Cells are pre-run to show sample outputs.
