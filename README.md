# React Calculator App

A modern, functional calculator built with React featuring a clean UI and intuitive operation.

## Features

- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division
- **Advanced Functions**: Percentage, sign toggle, and decimal support
- **Clear Button**: Reset calculator to initial state
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Beautiful gradient design with smooth animations

## Operations

- **Numbers (0-9)**: Click to input numbers
- **+/-**: Toggle between positive and negative values
- **%**: Convert number to percentage
- **÷**: Division operation
- **×**: Multiplication operation
- **-**: Subtraction operation
- **+**: Addition operation
- **.**: Decimal point for floating-point numbers
- **=**: Calculate the result
- **AC**: Clear all and reset calculator

## Installation

1. Make sure you have Node.js and npm installed
2. Clone this repository
3. Install dependencies:
   ```bash
   npm install
   ```

## Running the App

Start the development server:

```bash
npm run dev
```

The app will open in your browser at `http://localhost:5173`

## Building for Production

Create an optimized production build:

```bash
npm run build
```

## Project Structure

```
src/
├── Calculator.jsx      # Main calculator component
├── Calculator.css      # Calculator styling
├── App.jsx            # Root component
├── App.css            # App styling
└── main.jsx           # Entry point
```

## Technologies Used

- React 18
- CSS3 with Flexbox and Grid
- Vite (build tool)

## How It Works

The calculator maintains state for:
- **display**: Current number being shown
- **previousValue**: The first operand
- **operation**: The selected operation (+, -, *, /)
- **waitingForNewValue**: Flag to track if ready for new input

When you perform an operation, it stores the current value and waits for the next number. When you press equals, it calculates the result using the stored operation.

## License

This project is open source and available for personal and commercial use.
