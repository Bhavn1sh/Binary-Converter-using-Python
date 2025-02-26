
<body>
    <h1>Binary Converter Program</h1>
    <p>Welcome to the <strong>Binary Converter</strong> program! This Python application allows you to easily convert digits, letters, and binary numbers in various formats.</p>
    <h2>Features</h2>
    <ul>
        <li>Convert a digit (0-9) to its binary representation and two's complement.</li>
        <li>Convert a single letter (a-z, A-Z) to its binary representation and two's complement.</li>
        <li>Convert an 8-bit binary number to its corresponding letter (ASCII character).</li>
        <li>Convert an 8-bit binary number to a digit (if it's a valid binary number).</li>
        <li>Calculate the two's complement of any binary number.</li>
    </ul>
    <h2>How It Works</h2>
    <p>The program continuously prompts the user for input, allowing them to choose from different options to convert between digits, letters, and binary numbers. It processes each option accordingly and outputs the corresponding result.</p>
    <h3>Menu Options</h3>
    <pre>
    Choose an option:
    1. Convert a digit to binary and two's complement.
    2. Convert a letter to binary and two's complement.
    3. Convert an 8-bit binary to a letter (ASCII character).
    4. Convert an 8-bit binary to a digit.
    5. Convert a binary number to its two's complement.
    </pre>
    <h2>Program Workflow</h2>
    <p>Upon running the program, it presents a menu with the following options:</p>
    <ul>
        <li><strong>Option 1:</strong> Converts a digit (0-9) into binary and computes its two's complement.</li>
        <li><strong>Option 2:</strong> Accepts a string of letters (a-z, A-Z), converts each letter into its binary representation, and computes the two's complement for each letter.</li>
        <li><strong>Option 3:</strong> Converts a valid 8-bit binary number into its corresponding letter (ASCII character).</li>
        <li><strong>Option 4:</strong> Converts a valid 8-bit binary number into its corresponding digit.</li>
        <li><strong>Option 5:</strong> Computes and displays the two's complement of any binary number input by the user.</li>
    </ul>
    <h2>Exit Program</h2>
    <p>The program will continue to run until the <strong>ESC key</strong> is pressed. This provides a quick way to exit the program at any point.</p>
    <h2>Important Functions</h2>
    <p>Here are the key functions used within the program:</p>
    <ul>
        <li><code>to_binary(number)</code>: Converts an integer or a single letter to its binary representation.</li>
        <li><code>to_twos_complement(binary)</code>: Computes the two's complement of a binary string.</li>
        <li><code>binary_to_letter(binary)</code>: Converts an 8-bit binary number to its corresponding ASCII character (letter).</li>
        <li><code>binary_to_digit(binary)</code>: Converts an 8-bit binary number to its corresponding digit (if valid).</li>
    </ul>
    <h2>Exit the Program</h2>
    <p>The user can press the <strong>ESC key</strong> at any time to terminate the program.</p>
    <h2>Requirements</h2>
    <ul>
        <li><strong>Python 3.x</strong> (For running the Python program)</li>
        <li><strong>keyboard module</strong> (For detecting key presses, such as ESC to exit the program). Install it with: <code>pip install keyboard</code></li>
    </ul>
    <h2>Sample Output</h2>
    <p>Here’s an example of how the program works:</p>
    <pre>
    Hello there,
    Welcome to Binary converter!
    Press ESC anytime to exit.
    Choose an option:
    1. Convert a digit to binary and two's complement.
    2. Convert a letter to binary and two's complement.
    3. Convert an 8-bit binary to a letter (ASCII character).
    4. Convert an 8-bit binary to a digit.
    5. Convert a binary number to its two's complement.
    Enter option (1, 2, 3, 4, or 5): 2
    Enter a string of letters (a-z or A-Z): Hello
    Letter: H
      Binary: 01001000
      Two's complement: 10111000
    Letter: e
      Binary: 01100101
      Two's complement: 10011011
    Letter: l
      Binary: 01101100
      Two's complement: 10010011
    Letter: l
      Binary: 01101100
      Two's complement: 10010011
    Letter: o
      Binary: 01101111
      Two's complement: 10010001
    </pre>
    <p>You can press the ESC key to exit the program anytime.</p>

