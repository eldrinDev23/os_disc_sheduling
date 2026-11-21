# OS Disk Scheduling Visualizer

## Description
This project is a simple Operating System Disk Scheduling Visualizer developed using HTML, CSS, and JavaScript.

It helps users understand how disk scheduling algorithms work by displaying the head movement in a graph.

## Features
- Simple and user-friendly interface.
- Supports multiple disk scheduling algorithms.
- Displays disk head movement graph.
- Shows request sequence.
- Calculates total head movement.
- Allows users to select disk direction.

## Algorithms Used
1. FCFS (First Come First Serve)
2. SSTF (Shortest Seek Time First)
3. SCAN
4. C-SCAN
5. LOOK

## Technologies Used
- HTML
- CSS
- JavaScript

## How to Run
1. Download or clone the project.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Enter disk size, initial head position, and request queue.
5. Select a scheduling algorithm.
6. Click the **Run Algorithm** button.

## Sample Input
- Disk Size: 200
- Initial Head: 50
- Request Queue: 82, 170, 43, 140, 24, 16, 190
- Algorithm: FCFS

## Output
- Disk head movement graph.
- Request service sequence.
- Total head movement.

## Project Structure

```text
OS-Scheduling-Visualizer/
│
├── disc_sheduling.html
└── README.md
```

## Theme Colors
- Primary Color: #7a1b39
- Background Color: #d9ced1

## Conclusion
This project provides a simple visual explanation of disk scheduling algorithms and helps students understand disk head movement in operating systems.
