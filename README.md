Workshop: Algorithm and Flowchart

1. Check even or odd number
Design an algorithm and flowchart that take a number as input and determine whether it is even or odd.

Pseudocode

START
    INPUT number
    IF number % 2 == 0 THEN
        PRINT Even
    ELSE
        PRINT Odd
    ENDIF
END

Flowchart

2. Calculate Total and Average Marks
Write the algorithm and draw the flowchart for a program that inputs marks for 3 subjects, calculates the total and average, and displays both.

Pseudocode

START
    INPUT m1
    INPUT m2
    INPUT m3
        Total = m1 + m2 + m3
        Average = Total / 3
            PRINT Total 
            PRINT Average
END

Flowchart


3. Display Multiplication Table
Create an algorithm and flowchart that input a number and display its multiplication table from 1 to 10 using a loop.

Pseudocode

START
    INPUT number n
        i = 1
            WHILE i <= 10 DO
                Product P = n * i
                    PRINT n, "x", i "=" P
                i = i + 1
            ENDWHILE
END

Flowchart

4. Positive, Negative, or Zero Check
Write the algorithm and flowchart to input a number and display whether it is positive, negative, or zero.

Pseudocode

START
    INPUT number n
        IF n > 0 THEN
            PRINT "Number is Positive"
        ELSE IF n < 0 THEN
            PRINT "Number is Negative"
        ELSE
            PRINT "Number is equal to zero"
        ENDIF
END

Flowchart

5. Simple Interest Calculator
Create an algorithm and flowchart for a program that calculates simple interest using the formula:

SI = (P × R × T) / 100

P = Principle → original amount of money
R = Rate of Interest → percentage per year
T = Time → number of years

Pseudocode

START
    INPUT Principle P
    INPUT Rate of Interest R
    INPUT Time T
        SI = (P x R x T) / 100
    PRINT SI
END

Flowchart

6. Average Temperature Calculation
Write the algorithm and draw the flowchart for a program that takes the temperature of 7 days, finds the average temperature, and displays it.

Pseudocode

START
    sum = 0
    day = 1
        WHILE day <= 7 DO
            INPUT temp
                sum = sum + temp
                day = day + 1
        ENDWHILE
                avg = sum / 7
            PRINT average
END

Flowchart

7. Calculate Area of a Rectangle
Create an algorithm and flowchart to input length and width, calculate the area (Area = Length × Width), and display the result.

Pseudocode

START
    INPUT length l
    INPUT width w
        Area a = l * w
    PRINT Area
END

Flowchart

8. Determine Pass or Fail
Write the algorithm and draw the flowchart for a program that takes a student's average marks and displays "Pass" if average ≥ 50, otherwise "Fail".

Pseudocode

START
    INPUT avg_mark
        IF avg_mark >= 50 THEN
            PRINT "Pass"
        ELSE
            PRINT "Fail"
        ENDIF
END

Flowchart

9. Calculate Factorial of a Number
Write the algorithm and draw the flowchart that input a number and calculate its factorial using a loop.

Pseudocode

START
    INPUT Positive number n
        fact = 1
        i = 1
    WHILE i <= n DO
        fact = fact * i
        i = i + 1
    ENDWHILE
        PRINT fact
END

Flowchart

10. Calculate Discount on Purchase
Write the algorithm and draw the flowchart for a program that inputs the purchase amount and gives a 10% discount if the amount is greater than 1000.

Pseudocode

START
    INPUT amount a
        IF a >= 1000 THEN
            Discount = a x 0.10
        ELSE 
            Discount = 0
        ENDIF
            Final amount = a - Discount
        PRINT Discount
        PRINT Final amount
END

Flowchart
