# Ex03 Time Table
## Date:22.09.2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```

<html>
<head>
    <title>Slot Time Table - ESWAR</title>
</head>
<body>
    <IMG SRC= "C:\Users\acer\Gitclone\slot\exp3\tt\static\logo.png" height="150" width="500" border=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - ESWAR (25017992)</h3>

    <table border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr BGCOLOR="CYAN" ALIGN="CENTER">
            <td BGCOLOR="YELLOW">8-10</td>
            <td>DS</td>
            <td>DS</td>
            <td>DS</td>
            <td COLSPAN=2 ALIGN="CENTER">FREE SLOT</td>
            <td>PY</td>
        </tr>
        <tr BGCOLOR="CYAN" ALIGN="CENTER">
            <td BGCOLOR="YELLOW">10-12</td>
            <td>FWAD</td>
            <td>PY</td>
            <td>FWAD</td>
            <td>DS</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW" ALIGN='CENTER'>12-1</td>
            <td COLSPAN=6 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN" ALIGN="CENTER">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>FREE SLOT</td>
            <td>PY</td>
            <td>MM</td>
            <td COLSPAN="2" ALIGN="CENTER">FREE SLOT</td>
            
            <td>FWAD</td>
        </tr>
        <tr BGCOLOR="CYAN" ALIGN="CENTER">
            <td BGCOLOR="YELLOW">3-5</td>
            <td COLSPAN="2" ALIGN="CENTER">FREE SLOT</td>
            
            <td>FWAD</td>
            <td>PY</td>
            <td>DS</td>
            <td>PY</td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr ALIGN="CENTER">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td ALIGN="CENTER">1.</td>
            <td ALIGN="CENTER">19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td ALIGN="CENTER">2.</td>
            <td ALIGN="CENTER">19AI403</td>
            <td>Introduction to Data Science (DS)</td>
        </tr>
        <tr>
            <td ALIGN="CENTER">3.</td>
            <td ALIGN="CENTER">19AI301</td>
            <td>Python Programing (PY)</td>
        </tr>
        <tr>
            <td ALIGN="CENTER">4.</td>
            <td ALIGN="CENTER">ECA-M</td>
            <td>Mentor Meet (MM)</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2025-09-22 093523.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
