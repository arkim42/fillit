# Fillit

`Fillit` is a project that assembles a given *Tetriminos* set altogether in the smallest possible square. *Tetriminos* is a 4-blocks geometric figure which you can see in the popular game *Tetris*

## Getting Started
```
git clone https://github.com/arkim42/fillit.git
```
Go to the directory where you just cloned and build:
```
make
```
Run
```
./fillit tetrimino_input_file
```

## Valid Input Files & Rules
- Precisely 4 lines of 4 characters (4 x 4 square), each followed by a new line
- A *Tetrimino* is a classic piece of *Tetris* composed of 4 blocks
- Each character must be either a block character `#` or an empty character `.`
- Each block of a *Tetrimino* must touch at least one block on any of his 4 sides (up, down, left and right)
- No rotation is possible, which means a rotated *Tetrimino* describes a different one
- Shift is possible 

Example:
```
####
....
....
....

.##.
##..
....
....

....
...#
.###
....
```
