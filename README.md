# 2D Graphics Editor in C

A simple console-based 2D Graphics Editor developed in C that allows users to draw basic geometric shapes on an ASCII canvas.

## Features

* Draw Lines
* Draw Rectangles
* Draw Circles
* Draw Triangles
* Display the Canvas
* Boundary Checking for Pixels
* ASCII-based Graphics Rendering

## Canvas Specifications

| Property    | Value |
| ----------- | ----- |
| Width       | 80    |
| Height      | 24    |
| Empty Pixel | `_`   |
| Draw Pixel  | `*`   |

## Menu Options

```text
1. Draw Line
2. Draw Rectangle
3. Draw Circle
4. Draw Triangle
5. Display Picture
0. Exit
```

## Shape Drawing

### Line

Draws a line between two points using Bresenham's Line Algorithm.

### Rectangle

Draws a rectangle using four connected lines.

### Circle

Draws a circle using the Midpoint Circle Algorithm.

### Triangle

Draws a triangle by connecting three given vertices.

## Compilation

Using GCC:

```bash
gcc graphics.c -o graphics
```

## Execution

```bash
./graphics
```

## Example

```text
_____________________*____________________
___________________*___*__________________
__________________*_____*_________________
___________________*___*__________________
_____________________*____________________
```

## Project Structure

```text
graphics.c
README.md
```

## Learning Outcomes

This project demonstrates:

* 2D Array Manipulation
* Functions in C
* Graphics Rendering using ASCII Characters
* Bresenham's Line Algorithm
* Midpoint Circle Algorithm
* Coordinate Systems
* Boundary Validation

## Author

Raghav K M

## License

This project is open-source and available for educational purposes.
