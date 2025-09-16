# Calculator Web Application

A simple, responsive calculator built with HTML, CSS, and JavaScript. Features a clean dark theme interface with basic arithmetic operations.

![alt text](<images/calculator_screenshot.png>)

_Clean, dark-themed calculator interface_

## 🚀 Features

- **Basic Arithmetic Operations**: Addition (+), Subtraction (-), Multiplication (\*), Division (/)
- **Decimal Support**: Calculate with decimal numbers
- **Clear Function**: Reset the calculator with the 'C' button
- **Error Handling**: Displays "Error" for invalid expressions
- **Responsive Design**: Clean, dark-themed interface
- **Hover Effects**: Interactive button feedback
- **Keyboard-like Layout**: Familiar calculator button arrangement

## 📁 Project Structure

```
calculator/
│
├── images/
│   └── calculator_screenshot.png  # Calculator interface screenshot
├── index.html          # Main HTML structure
├── style.css           # Styling and layout
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic structure and layout
- **CSS3**: Styling, Grid layout, and responsive design
- **Vanilla JavaScript**: Calculator logic and DOM manipulation

## 📋 Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or frameworks required

## 🚀 Getting Started

### Installation

1. **Clone or download the project files**

   ```bash
   git clone <repository-url>
   cd calculator
   ```

2. **Open the project**

   - Simply open `index.html` in your web browser
   - Or use a local server for development:

     ```bash
     # Using Python 3
     python -m http.server 8000

     # Using Node.js (if you have http-server installed)
     npx http-server
     ```

3. **Start calculating!**
   - No build process required
   - Works offline once loaded

## 💻 Usage

### Basic Operations

1. **Numbers**: Click number buttons (0-9) to input values
2. **Operations**: Click operator buttons (+, -, \*, /) between numbers
3. **Calculate**: Press '=' to evaluate the expression
4. **Decimal**: Use '.' for decimal numbers
5. **Clear**: Press 'C' to clear the display

### Example Calculations

```
Input: 7 + 3 =
Output: 10

Input: 15.5 * 2 =
Output: 31

Input: 100 / 4 =
Output: 25
```

## 🏗️ Architecture

### HTML Structure

- Main container with `.calculator` class
- Display input field (disabled for display only)
- Button grid with 4-column layout
- Semantic button classes for styling

### CSS Design

- **Grid Layout**: 4-column button arrangement
- **Dark Theme**: Professional dark color scheme
- **Hover Effects**: Interactive feedback
- **Responsive**: Centered layout that works on different screen sizes

### JavaScript Functionality

- **Event Delegation**: Single event listener approach
- **Expression Evaluation**: Uses `eval()` for calculation
- **Error Handling**: Try-catch for invalid expressions
- **DOM Manipulation**: Updates display in real-time

**Happy Calculating!** 🧮
