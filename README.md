# Tower of Hanoi

The Tower of Hanoi is a puzzle game conceived by the French mathematician Édouard Lucas.

▪  The game involves moving n disks of different diameters from an initial tower (rod) to a final tower, passing through an intermediate tower.

▪  Initially, all the disks are stacked on the initial tower, from largest to smallest.

▪ The rules for moving are as follows:

  -You can only move one disk at a time.
  
  -You can only move a disk onto an empty tower or onto a disk that is larger.

## Materials
- Java Programming Language
- Java Swing Library
- Java StdDraw Library
- IDE: IntelliJ / Eclipse
  
For this project, Java programming and IDE: IntelliJ / Eclipse are used for coding. Swing and StdDraw libraries are used for GUI and visualization.

Note: Make sure the libraries are installed.

## UI and GUI

The first GUI we encounter in the project is the screen where we will select the number of disks and the solution method.

![Ekran görüntüsü 2024-03-16 140211](https://github.com/OzgunGultekin/Tower-of-Hanoi-/assets/153070257/9a7040b6-f308-43f6-9c7c-f0c078787650)

This frame was created using the Java Swing Library. "JSpinner" was used to select the number of disks and "JOptionPane" was used for the solution.

## Visualization 
Java StdDraw library was used to visualize the project.

![Ekran görüntüsü 2024-03-16 140504](https://github.com/OzgunGultekin/Tower-of-Hanoi-/assets/153070257/7143cca8-c687-4648-8dbe-10c5d3a10827)

![Ekran görüntüsü 2024-03-16 140504](https://github.com/OzgunGultekin/Tower-of-Hanoi-/assets/153070257/3b78e72e-af1f-4af4-b29e-cf10c103ab3a)

Thanks to StdDraw, onto the frame;

- Towers
- Discs
- Number of steps
- Colors
  
We were able to add.

## Algorithms 

In this project there are four solution algorithms, a recursive algorithm and three iterative algorithms.

- Recursive Algorithm
- Bitwise Algorithm
- Stack Algorithm
- Tree Algorithm

## Results

According to the tests, all algorithms showed time complexity in accordance with the O(2n) graph.

The Tree algorithm showed the worst performance. The fact that it has the biggest time complexity and keeps giving errors when a large number of disks are written makes it the worst algorithm.

The second worst algorithm is the Stack algorithm. Because it is the algorithm with the highest time complexity.

The best algorithms were Recursive and Bitwise algorithms.

Note: Test results may vary depending on processor and RAM type.



