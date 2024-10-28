# My Clock

My Clock is a simple Java application that displays the current time in a GUI window. It was developed using Java Swing and provides a real-time clock that updates every second.

## Features

- Displays current time in hours, minutes, and seconds (AM/PM format).
- Simple, user-friendly graphical interface using Java Swing.
- Updates every second to display the current time.

## Project Structure

The project consists of two main Java files:

1. `Main.java`: This is the entry point of the application. It initializes and displays the clock window.
2. `MyWindow.java`: This file contains the core GUI setup and logic for updating the clock every second.

## Code Overview

- `Main.java`: Initializes the application by creating an instance of the `MyWindow` class.
- `MyWindow.java`: Contains the Swing components (`JLabel`, `JFrame`) to display the clock interface. It uses a `Timer` to update the clock label every second.

## Getting Started

### Prerequisites

- Java JDK (version 8 or later recommended)
- A Java IDE (e.g., IntelliJ IDEA, Eclipse) or a text editor and command-line access

### Installation

1. Clone this repository or download the project files.
2. Open the project in your preferred IDE or navigate to the project directory in your terminal.

### Running the Project

1. Compile the Java files by running:
   ```bash
   javac -d . Main.java MyWindow.java

2. Run the application
   ```bash
   java com.clock.Main
