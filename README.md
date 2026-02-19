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
        SET Total = m1 + m2 + m3
        SET Average = Total / 3
            PRINT Total 
            PRINT Average
END

Flowchart


3. Display Multiplication Table
Create an algorithm and flowchart that input a number and display its multiplication table from 1 to 10 using a loop.

Pseudocode

START
    INPUT number n
        counter i = 1
            WHILE i <= 10
                Product P = i x n
                    PRINT "i x n = P"
                i = i + 1
            END WHILE
END

Flowchart

4. Positive, Negative, or Zero Check
Write the algorithm and flowchart to input a number and display whether it is positive, negative, or zero.

Pseudocode

START
    INPUT number n
        iF n > 0
            PRINT "Number is Positive"
        ELSE IF n < 0
            PRINT "Number is Negative"
        ELSE
            PRINT "Number is equal to zero"
        END IF
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
    SET sum_temp = 0.0
    SET avg_temp = 0.0
    SET num_days = 7
        FOR 1 TO 7
            PRINT "Enter temp of day" + day
                READ current_temp
                sum_temp = current_temp + sum_temp
        END FOR

                avg_temp = sum_temp / num_days
            PRINT "Average temperature of the week" + avg_temp
END

Flowchart

7. Calculate Area of a Rectangle
Create an algorithm and flowchart to input length and width, calculate the area (Area = Length × Width), and display the result.

Pseudocode

START
    INPUT length l
    INPUT width w
        Area a = l x w
    PRINT Area
END

Flowchart

8. Determine Pass or Fail
Write the algorithm and draw the flowchart for a program that takes a student's average marks and displays "Pass" if average ≥ 50, otherwise "Fail".

Pseudocode

START
    INPUT avg_mark
        IF avg_mark >= 50
            PRINT "Pass"
        ELSE
            PRINT "Fail"
        END IF
END

Flowchart

9. Calculate Factorial of a Number
Write the algorithm and draw the flowchart that input a number and calculate its factorial using a loop.

Pseudocode

START
    INPUT Positive number n
        fact = 1
        i = 1
    For i FROM 1 TO n
        fact = fact x i
        i = i + 1
    END FOR
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
        END IF
        PRINT Discount
END

Flowchart
