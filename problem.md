# Pseudocode Solutions for Lab 03 Problems

## 1. Display Student Information Using Different Data Types

START
    SET student_id = 101
    SET student_gpa = 3.75
    SET student_grade = 'A'
    
    PRINT "Student ID: ", student_id
    PRINT "GPA: ", student_gpa
    PRINT "Grade: ", student_grade
END


## 2. Read and Display a Character Using getchar() and putchar()

START
    PRINT "Enter a single character: "
    READ character USING getchar()
    
    PRINT "You entered: "
    WRITE character USING putchar()
END


## 3. Display a Floating-Point Value Using Different Precision Settings

START
    SET pi_val = 3.14159265
    
    PRINT "Default: ", pi_val
    PRINT "2 Decimal Places: ", FORMAT(pi_val, 2)
    PRINT "4 Decimal Places: ", FORMAT(pi_val, 4)
END
