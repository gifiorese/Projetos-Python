Hi! Here you'll find the solutions to "Python Basic" exercises from Hacker Rank 😁 <br>
Click on the titles to be directed to the full question 😁 <br>
The challenges are solved in Python3 💻<br>
**Reminder:** Never ignore the indentations, they do make a huge difference in Python. The code portion here is only the solution, some exercises have pre-programmed bits.
<br>
<br>
Olá! Aqui você irá encontrar a resolução dos exercícios "Python Basic" do Hacker Rank 😁 <br>
Clique nos títulos para ser direcionado(a) ao enunciado completo 😁<br>
Os desafios são resolvidos em Python3 💻<br>
**Lembrete:** nunca ignore as identações, elas fazem uma diferença significativa em Python. A parte do código postada aqui é apenas a resolução, alguns exercícios possuem pedaços pré-programados.
<br>
<br>
<br>

[Say "Hello, World!" with Python](https://www.hackerrank.com/challenges/py-hello-world)

**Question -** Print "Hello, World!" on your screen.

**Solution** 
```python
print("Hello, World!")
```

<br>
<br>
<br>

[Python If-Else](https://www.hackerrank.com/challenges/py-if-else)

**Question -** Given an integer, n, perform the following conditional actions:

- If n is odd, print Weird
- If n is even and in the inclusive range of 2 to 5, print Not Weird
- If n is even and in the inclusive range of 6 to 20, print Weird
- If n is even and greater than 20, print Not Weird

Reminder: range() does not count the last value --> range(0,5) would give 0, 1, 2, 3, 4

**Solution** 
```python
    if n%2 != 0:
        print('Weird')
    else:
        if n in range(2,6):
            print('Not Weird')
        else:
            if n in range(6,21):
                print('Weird')
            else:
                if n > 20:
                    print('Not Weird')
```

<br>
<br>
<br>

[Arithmetic Operators](https://www.hackerrank.com/challenges/python-arithmetic-operators)

**Question -** The provided code stub reads two integers from STDIN, a and b. Add code to print three lines where:

- The first line contains the sum of the two numbers.
- The second line contains the difference of the two numbers (first - second).
- The third line contains the product of the two numbers.

**Solution** 
```python
    print(a + b)
    print(a - b)
    print(a * b)
```

<br>
<br>
<br>

[Loops](https://www.hackerrank.com/challenges/python-loops)

**Question -** The provided code stub reads and integer, n, from STDIN. For all non-negative integers i < n, print i².

**Solution** 
```python
    for i in range(n):
        print(i**2)
```

<br>
<br>
<br>

[Write a function](https://www.hackerrank.com/challenges/write-a-function) - MEDIUM

**Question -** An extra day is added to the calendar almost every four years as February 29, and the day is called a leap day. It corrects the calendar for the fact that our planet takes approximately 365.25 days to orbit the sun. A leap year contains a leap day.

In the Gregorian calendar, three conditions are used to identify leap years:

- The year can be evenly divided by 4, is a leap year, unless:
    - The year can be evenly divided by 100, it is NOT a leap year, unless:
        - The year is also evenly divisible by 400. Then it is a leap year.

This means that in the Gregorian calendar, the years 2000 and 2400 are leap years, while 1800, 1900, 2100, 2200, 2300 and 2500 are NOT leap years.

**Solution** 
```python
    if year%400 == 0:
        return True
    elif year%100 == 0:
        return False
    elif year%4 == 0:
        return True
```

<br>
<br>
<br>

[Print function](https://www.hackerrank.com/challenges/python-print)

**Question -** The included code stub will read an integer, n, from STDIN.

Without using any string methods, try to print the following:<br>
123...n<br>
Note that "..." represents the consecutive values in between.

**Solution** 
```python
    for i in range(1, n+1):
        print(i, end="")
```

<br>
<br>
<br>
