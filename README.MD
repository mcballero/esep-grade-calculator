# ESEP Grade Calculator

Overview:

This library is a simple utility to calculate your grades. It works with
assignment, exam, and essay grades, it calculates each individual weighted grade,
and a weighted sum. The program also converts the final grade into a letter grade.

This ESEP Grade Calculator uses the following weights:

    - Assignments: 50%
    
    - Exams: 35%
    
    - Essays: 15%
    
    
The final grade is converted based on this scale:

    - A: 90 and above
    
    - B: 80–89
    
    - C: 70–79
    
    - D: 60–69
    
    - F: below 60
    
    
File Descriptions:

    - go.mod: Contains the Go module and the Go version used by the project.
    
    - grade_calculator.go: Implements the necessary grade calculator functions.
    
    - grade_calculator_test.go: Contains the unit tests for the calculator.
    

Runtime requirements:

Golang 1.24+

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```
