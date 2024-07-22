This is a program where you input a text file consisting of lines of characters.

- . -> this character means the starting points(default).

- x -> this character means targets(default).

- [:space:] -> whitespace means empty cells we can travel to

Any other character means obstacle.
The program will read in such file and draw the shortest paths from starting
points to targets. The shortest paths will be drawn with @ character(default).
You can specify the following options:
- -s <c>  ->  the starting point character will be <c>
- -t <c>  ->  the target character will be <c>
- -p <c>  ->  the paths will be drawn with <c> character
- -n <c>  ->  the neighbourhood: 4 for Von Neumann(default), 8 for Moore
- -o <file>  ->  the path to file where you want to store the results
- --maxlen <n>  ->  maximum path lengths to consider
- --highlight  ->  the paths will be highlighted
- -c <color>  ->  choose the color for highlighting