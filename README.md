# HSMathProject
High School Math Project "Activity 2" (Mrs. Yuen)

By Bosco Lo
11th December 2002
Mathematics: Sequences, Summation, and Special (feat. Fibonacci) Calculator

05 September 2020
       C++ to Python (all formulae unchanged) at 231 total lines (proper required spacing AND this Readme paragraphs)
       the big update: ordinal calculation (one-liner return function) automatically find its relative representation


This project includes learning about the following topics:
Arithmetic Sequence, Geometric Sequence, Summation for Arithmetic Series, Summation for Geometric Series, Summation for Triangular Numbers,
and finally also Fibonacci


Original Filename in the Project folder where I was "SHOWING MY WORK" for each topic: Evidence of working.doc

Line 28 starts teaching about Arithmetic Sequence:
Line 55 starts teaching about Geometric Sequence:
Line 83 starts teaching about Summation of Arithmetic Series:
Line 117 starts teaching about Summation of Geometric Series:
Line 152 starts teaching about Summation of Triangular Numbers:
Line 162 starts teaching about Fibonacci:

---------------------------------------
Arithmetic Sequence
Input two terms (a, b) given their values (x, y), input any term (n) that you would like to figure out.

Example: a=3, b=5, x=6, y=10

To calculate the first term:
a1 = (x × b – a × y + y – x) ÷ (b – a);

a1 = (6 × 5 – 3 × 10 + 10 – 6) ÷ (5 – 3)
a1 = (30 – 30 + 4) ÷ (2)
a1 = 2

To calculate the difference of given example:
d = (y – x) ÷ (b – a);

d = (10 – 6) ÷ (5 – 3)
d = 2

To find the term you desired, example: [n=8]:
an = a1 + (n – 1) × d;

a8 = 2 + (8 – 1) × 2
a8 = 16



---------------------------------------
Geometric Sequence
Input two terms (a, b) given their values (x, y), input any term (n) that you would like to figure out.

Example: a=4, b=6, x=81, y=729

To calculate the ratio of given example:

r = pow (y ÷ x, 1.0 ÷ (b – a));

r = (729 ÷ 81)^1 / (6 – 4)
r = (9)^1 / 2
r = 3

a1 = x × pow (r, 1 – a);

a1 = 81 × (3)^(1 – 4)
a1 = 3

To find the term you desired, example: [n=7]:
an = a1 × pow(r, (n – 1));

a7 = 3 × (3)^(7 – 1)
a7 = 3 × (729)
a7 = 2187



---------------------------------------
Summation of Arithmetic Series
Input two terms (a, b) given their values (x, y), input any term (n) that you would like to figure out the sum of the first (n) numbers.

Example: a=3, b=5, x=6, y=10

To calculate the first term:
a1 = (x × b – a × y + y – x) ÷ (b – a);

a1 = (6 × 5 – 3 × 10 + 10 – 6) ÷ (5 – 3)
a1 = (30 – 30 + 4) ÷ (2)
a1 = 2

To calculate the difference of given example:
d = (y – x) ÷ (b – a);

d = (10 – 6) ÷ (5 – 3)
d = 2

To find the term you desired, example: [n=8]:
an = a1 + (n – 1) × d;

a8 = 2 + (8 – 1) × 2
a8 = 16

To find the sum of the first (n) numbers:
sum = (a1 + an) × n ÷ 2;

sum = (2 + 16) × 8 ÷ 2
sum = 18 × 4
sum = 72



---------------------------------------
Summation of Geometric Series
Input two terms (a, b) given their values (x, y), input any term (n) that you would like to figure out.

Example: a=4, b=6, x=81, y=729

To calculate the ratio of given example:

r = pow (y ÷ x, 1.0 ÷ (b – a));

r = (729 ÷ 81)^1 / (6 – 4)
r = (9)^1 / 2
r = 3

a1 = x × pow (r,1 – a);

a1 = 81 × (3)^(1 – 4)
a1 = 3

To find the term you desired, example: [n=7]:
an = a1 × pow(r, (n – 1));

a7 = 3 × (3)^(7 – 1)
a7 = 3 × (729)
a7 = 2187

To find the sum of the first (n) numbers:
sn = a1 × (1 – pow(r, n)) ÷ (1 – r);

sn = 3 × ( 1 – (3^7) ) ÷ ( 1 – 3 )
sn = 3 × -2186 ÷ -2
sn = 3279



---------------------------------------
Triangular numbers

To find the term you desired, example: [a=10]:
sum = (a × a + a) ÷ 2;

sum = (10 × 10 + 10) ÷ 2
sum = 55


---------------------------------------
Fibonacci
a = 1
b = 1

To find the term you desired, example: [n=6]:

	for(int i=3;i<=n; i++)
	{
		c=a+b;
		// line to display the value at position term
		a=b;
		b=c;
	}

3rd term
c=a + b
c=2

a=1
b=2

4th term
c=a + b
c=3


a=2
b=3

5th term
c=a + b
c=5

a=3
b=5

6th term
c=a + b
c=8

So the 6th term of the fibonacci is 8.
