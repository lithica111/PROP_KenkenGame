# PROP Group 43.1
Programming Project, Group 43, subgroup 43.1. <br>Professor: ____ ([____]()).

## Group Members

- Caterina Moll ([caterina.moll@estudiantat.upc.edu]())
- David Vendrell ([david.vendrell.lopez@estudiantat.upc.edu]())
- Javier Sánchez ([javier.sanchez.zarate@estudiantat.upc.edu]())
- Marcos Roca ([marcos.roca@estudiantat.upc.edu]()).

## Directory Elements

### DOCS:
Contains all the documentation of the project: use case diagram with a description of each one, a complete static diagram of the conceptual data model in design version with a brief description of the attributes and methods of the classes, the list of classes implemented by each team member, description of the data structures and algorithms used to implement the functionalities of the delivery.

### EXE:
Executable files (*.class*) for all the classes that allow testing the main functionalities implemented. There are subdirectories for each of the types of classes: test, exceptions, functions, types, which follow the structure determined by the *packages*

### FONTS:
Code of the domain classes associated with the main functionalities implemented so far. It also includes the JUnit tests. All files are within subdirectories that follow the package structure, so the code can be directly recompiled. It also includes the *Makefile* file.

## Testing the Program

To execute the program, go to the `../src` directory, where the program's *Makefile* is located. Build the system by entering `make` in the console and you will be able to test all the classes individually through the drivers.


### Description Makefile

- `make compileG`

      Compiles DriverGame.java and creates the executable

- `make compileP`
    
        Compiles DriverPlayer.java and creates the executable

- `make exeG`
    
        Executes the executable of DriverGame. Here you will find a list with the main functionalities of the game.

- `make exeP`
        
        Executes the executable of DriverPlayer

- `make clean`

      Rule for cleaning the .class files