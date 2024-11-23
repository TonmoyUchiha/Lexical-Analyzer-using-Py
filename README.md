# Lexical-Analyzer-using-Py
This is a lexical analyzer built using raw python. I have tried to minimize the code as much as possible using Regular Expressions to split the statements into lexemes. In this iteration of the code you can input your statement for analyzing.

The reason for using RegEx is we can easily separate the lexemes.

**Regular Expression (re)**:
►  r"[a-zA-Z_]\w*": Matches keywords and identifiers (letters or _ followed by alphanumerics).
►  r"\d+": Matches numbers.
►  r"[+\-*/=<>!]+": Matches operators.
►  r"[;(){}]": Matches delimiters.

**Token Matching**:
The re.findall function extracts all tokens matching the patterns from the source code.

This is how the code looks in my IDE:
![image](https://github.com/user-attachments/assets/38b47282-3512-40f5-a813-7c6c80d2cc66)

<br>And this is my Output:
![image](https://github.com/user-attachments/assets/3e5c0998-542e-4154-8a5b-a63299fc7a7a)<br>

This is how the parsing works in my program: (Using x=x+1 as an example)
![output](https://github.com/user-attachments/assets/3812bedb-9d23-4867-b602-b47244dd9d3c)<br>

In short, it makes the whole process of understanding and running a program faster and simpler by organizing the code into meaningful pieces.
