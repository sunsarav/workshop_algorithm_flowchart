# Workshop: Algorithm and Flowchart

## 1. Check even or odd number
Design an algorithm and flowchart that take a number as input and determine whether it is even or odd.

### Pseudocode

    START
        INPUT number
        IF number % 2 == 0 THEN
            PRINT Even
        ELSE
            PRINT Odd
        ENDIF
    END

### Flowchart

![evenodd](https://github.com/user-attachments/assets/faebf47c-6bc5-4ede-a5a5-ed90f26c00a5)


## 2. Calculate Total and Average Marks
Write the algorithm and draw the flowchart for a program that inputs marks for 3 subjects, calculates the total and average, and displays both.

### Pseudocode
   
    START
        INPUT m1
        INPUT m2
        INPUT m3
        Total = m1 + m2 + m3
        Average = Total / 3
            PRINT Total 
            PRINT Average
    END

### Flowchart

![totalavg](https://github.com/user-attachments/assets/d399d0e5-e403-48ed-ac2f-4934de468ebb)


## 3. Display Multiplication Table
Create an algorithm and flowchart that input a number and display its multiplication table from 1 to 10 using a loop.

### Pseudocode
   
    START
        INPUT number n
        i = 1
        WHILE i <= 10 DO
            Product P = n * i
            PRINT n, "x", i, "=", P
            i = i + 1
        ENDWHILE
    END

### Flowchart

![multable](https://github.com/user-attachments/assets/5351db3a-ea90-4772-abca-452d80bf58e7)


## 4. Positive, Negative, or Zero Check
Write the algorithm and flowchart to input a number and display whether it is positive, negative, or zero.

### Pseudocode
    
    START
        INPUT number n
        IF n > 0
            PRINT "Number is Positive"
        ELSEIF n < 0
            PRINT "Number is Negative"
        ELSE
            PRINT "Number is equal to zero"
        ENDIF
    END

### Flowchart

![posnegativ](https://github.com/user-attachments/assets/f12b626d-8f27-4bd2-b534-a57be59d1f94)


## 5. Simple Interest Calculator
Create an algorithm and flowchart for a program that calculates simple interest using the formula:

SI = (P × R × T) / 100

P = Principle → original amount of money
R = Rate of Interest → percentage per year
T = Time → number of years

### Pseudocode
    
    START
        INPUT Principle P
        INPUT Rate of Interest R
        INPUT Time T
            SI = (P x R x T) / 100
        PRINT SI
    END
        
### Flowchart

![siminterest](https://github.com/user-attachments/assets/a144151e-09c5-4c7d-a971-2e5b906a6795)

## 6. Average Temperature Calculation
Write the algorithm and draw the flowchart for a program that takes the temperature of 7 days, finds the average temperature, and displays it.

### Pseudocode
    
    START
        sum = 0
        day = 1
        WHILE day <= 7 DO
            INPUT temp
            sum = sum + temp
            day = day + 1
        ENDWHILE
        avg = sum / 7
            PRINT avg
    END

### Flowchart

![avgtemp](https://github.com/user-attachments/assets/1f4cfec1-591b-43a3-ac8b-ca71087a5ff1)


## 7. Calculate Area of a Rectangle
Create an algorithm and flowchart to input length and width, calculate the area (Area = Length × Width), and display the result.

### Pseudocode
    
    START
        INPUT length l
        INPUT width w
            area = l * w
        PRINT area
    END

### Flowchart

![rectarea](https://github.com/user-attachments/assets/42943de7-41eb-43dc-88fc-9e469f67b6a5)


## 8. Determine Pass or Fail
Write the algorithm and draw the flowchart for a program that takes a student's average marks and displays "Pass" if average ≥ 50, otherwise "Fail".

### Pseudocode

    START
        INPUT avg_mark
        IF avg_mark >= 50 THEN
            PRINT "Pass"
        ELSE
            PRINT "Fail"
        ENDIF
    END

### Flowchart

![passfail](https://github.com/user-attachments/assets/5931b330-6e85-48d4-a33a-47a1b8bbf054)

## 9. Calculate Factorial of a Number
Write the algorithm and draw the flowchart that input a number and calculate its factorial using a loop.

### Pseudocode
   
    START
        INPUT n
        fact = 1
        i = 1
        WHILE i <= n DO
            fact = fact * i
            i = i + 1
        ENDWHILE
        PRINT fact
    END

### Flowchart

![factorial](https://github.com/user-attachments/assets/a3c4cbc3-8857-43bb-b526-d7f2e89e81dd)


## 10. Calculate Discount on Purchase
Write the algorithm and draw the flowchart for a program that inputs the purchase amount and gives a 10% discount if the amount is greater than 1000.

### Pseudocode
    
    START
        INPUT amount a
            IF a >= 1000 THEN
                discount = a * 0.10
            ELSE 
                discount = 0
            ENDIF
            finalAmount = a - discount
                PRINT discount
                PRINT finalAmount
    END

### Flowchart

![discount](https://github.com/user-attachments/assets/52b929ed-f141-4dee-b9a9-88e509294b4c)


