# From-Orders-to-Shortest-Maps
This is a group project for our course 'Data Structures and Algorithm'. This code is capable of taking inputs from the user and provides a list according to the time the user placed the order, and in that specific order what will be the shortest path is also shown. Along with the path the item to be delivered is show and the price to be collected.

*Disclaimer*
This program takes the assumption, for e.g. there are limited number of places in city Karachi, and every places has its own coordinates. Input is not validated, hence the program might not work if the data might not sync with the program.

The code will run on computers with python idle installed either as a separate software, for e.g. 'IDLE', or as an extension on a parent software, for e.g. 'Visual Studio Code'.

However, ther might be an issue even when above mentioned software is installed. Since the code uses 'tkinter' library for GUI (Graphical User Interface). The user might first look online to add the specific library (if not) to run the code successfully.

As a feature of this project the code generates a file named as 'inputfile2.0'. This file is being generated as a proof for the user to refer, whenever there is an ambiguity with the orders delivered. The file also gets deleted once a new file is requested or the user wants to run the whole program again. This was made to make the code space efficient. A practical situation was integrated as a website owner might want to just refer the data at the end of the day and dont need the file again. The user who wants to save the file can simply remove the two line that incorporate 'os' (Miscellaneous operating system interfaces) library in the code. (this library is usually with the package of the sofware).

The number of input is dependent on a self counter. This can be controlled by the user where it can stop at a particular number of order. The code works fine with orders within 100. After this limit if the computer ios able to process the code in a particular time frame easily, its perfectly fine to work with it.

Steps to run the code:
1. Creat a file in your enviroment (for e.g. VS code in my case). And save it in the same location you want your input data to be stored.
2. Write the code provided.
3. Run the code.
4. There will be a window asking for details reagarding the orders.
5. The following cells should have specified data entered in the cell. 
6. 'Coordinate' cell as a tuple with two integer values (less than 1500). And 'address' cell should have location from the list of edges only. 
7. Fill all the cells and click submit. And remember to take enter locations with their cordiantes as wriiten in the commented data.
8. The shortest path will be automatically opened in a new window while the input window will be closed. 
9. And there you go, most optimum path to rach every customer on first come first basis.

By Ghufran And Bilwal.
