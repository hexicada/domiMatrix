# domiMatrix

A tiny grid-based dungeon game written in R.

## What It Is

`domiMatrix` is a simple 5x5 text adventure where you move a player around a map, avoid rocks, find treasure, and reach the exit.

## Map Legend

- `@` player
- `.` empty tile
- `#` rock (blocked)
- `T` treasure
- `X` exit

## How To Play

1. Open `matrix_meandering.Rmd`.
2. Run the first R code chunk to initialize the map and `move()` function.
3. Use these commands in the R console:

```r
move("up")
move("down")
move("left")
move("right")
```

Each move prints the updated map and messages such as blocked paths, treasure found, or exit reached.

## Current Status

- Prototype / silly fun project
- Single static level (5x5)
- Console output gameplay

## Ideas For Next Steps

- Add win/lose conditions and score tracking
-Add lore 
- Add random map generation
- Track collected treasure count
- Add enemies or traps
