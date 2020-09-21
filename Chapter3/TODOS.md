# Tasks
1. Create a assembly program that sets 3 variables myvar1, myvar2, and myvar3 to 1,2,3 and then adds them together.

## Details

Task 1:
    I highly suggest reading the book and doing the practice before doing this. 
    The final program will look like a combination of load01.s and store01.s.
    You need to initally start with the three variables with the value zero.
    Your main should,
        1. load the addresses of the variables into a register.
        2. Set the registers to the correct values.
        3. Then add all three of the registers together.
        4. Finally, return the sum
    You will also need to create a makefile to build your ARM code as well.
    Name your file cp3.s.


## Gradding
    Task 1:
        I will first run your makefile.
        Your makfile should create files specified in the chapter. (1 point)
        I will run your code useing this command `./cp3 ; echo $?`.
        The output should be `6`. (2 points)
        When I run `make clean` the files created by your make should be deleted. (1 point)
        Loading memory from variables will be worth 2 points.
        Storing value into variables is worth 2 points.
        I will also be looking at the code carefully to see if you actualy store and load variables.
        If you add 3 numbers together without using variables that will result in a zero.

