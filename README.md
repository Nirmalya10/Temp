# Temp
Create a numeric vector and perform arithmetic operations
Task:
Create a vector of 5 numbers. Add 10 to each element, then multiply all elements by 2.
Solution:
r
CopyEdit
v <- c(1, 2, 3, 4, 5)
v <- v + 10
v <- v * 2
print(v)
________________________________________
Program 2: Find the maximum, minimum, and mean of a vector
Task:
Create a vector of 6 elements and find its maximum, minimum, and mean values.
Solution:
r
CopyEdit
v <- c(12, 45, 23, 67, 89, 34)
print(max(v))
print(min(v))
print(mean(v))
________________________________________
Program 3: Access and modify vector elements
Task:
Create a vector and change the third element to 100.
Solution:
r
CopyEdit
v <- c(5, 10, 15, 20)
v[3] <- 100

Program 4:Create a matrix and Add a new row to a matrix
Create a 2x3 matrix and add a new row c(7,8,9) to it.

Solution:
r
CopyEdit
m <- matrix(1:6, nrow=2, byrow=TRUE)
new_row <- c(7, 8, 9)
m <- rbind(m, new_row)
print(m)
________________________________________
Program 3: Remove a column from a matrix
Task:
Create a 3x3 matrix and remove the second column.
Solution:
r
CopyEdit
m <- matrix(1:9, nrow=3)
m <- m[, -2]  # Remove second column
print(m)

Program 4: Create a list and access its elements
Task:
Create a list with a name, age, and marks vector. Print each item separately.
Solution:
r
CopyEdit
student <- list(name="Alice", age=22, marks=c(80, 85, 90))
print(student$name)
print(student$age)
print(student$marks)
Program 5: Add a new element to a list
Task:
Add a new element "grade" to the existing list.
Solution:
r
CopyEdit
student$grade <- "A"
print(student)
Modify an element inside a list
Task:
Change the student's age to 23.
Solution:
r
CopyEdit
student$age <- 23
print(student$age)

Basic arithmetic operations
Task:
Take two numbers and perform addition, subtraction, multiplication, and division.
Solution:
r
CopyEdit
a <- 15
b <- 5
print(a + b)
print(a - b)
print(a * b)
print(a / b)
________________________________________
Program : Find remainder and quotient
Task:
Calculate remainder and quotient when 27 is divided by 4.
Solution:
r
CopyEdit
print(27 %% 4)  # Remainder
print(27 %/% 4) # Quotient

Program : Create a data frame and display specific columns
Task:
Create a data frame with name, age, and marks of 3 students. Display only names.
Solution:
r
CopyEdit
df <- data.frame(name=c("John", "Mary", "Tom"), age=c(20, 21, 19), marks=c(85, 90, 75))
print(df$name)
________________________________________
Program : Add a new column to a data frame
Task:
Add a "grade" column to the existing student data frame.
Solution:
r
CopyEdit
df$grade <- c("A", "A+", "B")
print(df)
________________________________________
Program : Access specific row and column
Task:
Print the marks of the second student.
Solution:
r
CopyEdit
print(df[2, "marks"])

Program : Line plot of x and y values
Task:
Plot a line graph for x = 1 to 5 and y = x²
Solution:
r
CopyEdit
x <- 1:5
y <- x^2
plot(x, y, type="l", main="Line Plot", xlab="X", ylab="Y = X^2")
________________________________________
Program : Bar chart of student marks
Task:
Create a bar chart for marks of 3 students.
Solution:
r
CopyEdit
students <- c("John", "Mary", "Tom")
marks <- c(85, 90, 75)
barplot(marks, names.arg=students, col="blue", main="Student Marks")
________________________________________
Program : Histogram of random scores
Task:
Plot a histogram for a given vector of scores.
Solution:
r
CopyEdit
scores <- c(55, 60, 65, 70, 75, 80, 85, 90)
hist(scores, col="green", main="Score Histogram")





