This Maze solver read a maze from the input text.
The format is:
1st row is the algo to apply (a*/greedyBestFirst),
The 2nd row is size (the maze should be NxN)
and next should be the maze with the next format:
A=starting point
D=dirt (cost 4)
R=road (cost 1)
W=wall (can't move there)
B=end point

The output should be in the format of: Path cost.
Ex: D-D-R-D-R-R-U-U-U 11