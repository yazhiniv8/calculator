# Ex.No:06 JavaScript Calculator
## Date: 23-11-2026
## AIM

To design and develop a simple calculator using HTML, CSS, and JavaScript to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## ALGORITHM

1. Create an HTML page to design the calculator interface.
2. Create a display field to show the numbers and calculation results.
3. Create buttons for digits from 0 to 9 and arithmetic operators.
4. Use CSS to arrange and style the calculator buttons and display.
5. Write JavaScript functions to handle button clicks.
6. Store the entered numbers and operators in the calculator display.
7. Use JavaScript to evaluate the arithmetic expression.
8. Display the calculated result on the calculator screen.
9. Provide a clear button to reset the calculator.
10. Test the calculator with different arithmetic operations.

## PROGRAM

# .html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Calculator</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="calculator">
        <h2>Calculator</h2>

        <input type="text" id="display"
        placeholder="0" readonly>

        <div class="buttons">
            <button class="clear">C</button>
            <button class="delete">DEL</button>
            <button class="operator">÷</button>
            <button class="operator">×</button>

            <button>7</button>
            <button>8</button>
            <button>9</button>
            <button class="operator">−</button>

            <button>4</button>
            <button>5</button>
            <button>6</button>
            <button class="operator">+</button>

            <button>1</button>
            <button>2</button>
            <button>3</button>
            <button class="equal">=</button>

            <button class="zero">0</button>
            <button>.</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
```

# style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #c9b6ff, #91d5ff);
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.calculator {
    width: 320px;
    padding: 25px;
    background: white;
    border-radius: 20px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.2);
}

h2 {
    text-align: center;
    margin-bottom: 20px;
    color: #333;
}

#display {
    width: 100%;
    height: 65px;
    margin-bottom: 20px;
    padding: 10px;
    font-size: 28px;
    text-align: right;
    border: 2px solid #ddd;
    border-radius: 10px;
    background: #f5f5f5;
    color: #222;
}

.buttons {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
}

button {
    height: 55px;
    border: none;
    border-radius: 10px;
    background: #e9e9f0;
    font-size: 20px;
    cursor: pointer;
}

button:hover {
    background: #d2d2df;
}

.operator {
    background: #b9a0ff;
    color: white;
}

.clear {
    background: #ff5555;
    color: white;
}

.delete {
    background: #ff9f43;
    color: white;
}

.equal {
    background: #28b463;
    color: white;
    grid-row: span 2;
    height: auto;
}

.zero {
    grid-column: span 2;
}

button:active {
    transform: scale(0.95);
}
```


## OUTPUT
![Output](<output.png>)

## RESULT

Thus, a JavaScript-based calculator was successfully designed and developed to perform basic arithmetic operations using HTML, CSS, and JavaScript.

## RESULT

Thus, a JavaScript-based calculator was successfully designed and developed to perform basic arithmetic operations using HTML, CSS, and JavaScript.
