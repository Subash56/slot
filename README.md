# Ex03 Time Table
## Date:14/04/2025

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
<!DOCTYPE html>
<html lang="en">
<head>
  
  <title>SEC WEEKLY SCHEDULE</title>
  <link rel="icon" href="images.jpg">
</head>
<body>
    <center><img src="logo.png" width="540" height="100"</center>
  <table border="5" cellpadding="20">
    <caption><h3>WEEKLY SCHEDULE 0CT 2024 - SUBASH (212224220108)</caption></h3>
    <tr bgcolor="sky blue" style="color: rgb(0, 7, 7);">
      <th>TIME</th><th>SUN</th><th>MON</th><th>TUES</th><th>WED</th><th>THURS</th><th>FRI</th><th>SAT</th>
    </tr>
    <tr>
      <td bgcolor="sky blue" style="color: rgb(0, 7, 7);">8am-9am</td><td bgcolor="red"></td><td bgcolor="red"></td><td bgcolor="yellow">career development</td><td bgcolor="red"></td><td bgcolor="red"></td><td bgcolor="pink">calculus algebra</td><td bgcolor="red"></td>
  
    </tr>
    <tr>
        <td bgcolor="sky blue" style="color: rgb(1, 14, 14);">10am-12pm</td><td bgcolor="red"></td><td bgcolor="grey">fundamentals of web development</td><td bgcolor="aqua">digital electronic</td><td bgcolor="grey">fundamentals of web development</td><td bgcolor="grey">fundamentals of
          web development</td><td bgcolor="#00FA9A">physics for quantum</td><td bgcolor="pink">calculus algebra</td>
    </tr>
    <tr>
      <td bgcolor="sky blue" style="color:rgb(0, 3, 3);">1pm-3pm</td><td bgcolor="red"></td><td bgcolor="lime">human values</td><td bgcolor="orange">fundamentals of c</td><td bgcolor="#98FB98">mentor meeting</td><td bgcolor="#00FA9A">physics for quantum</td><td bgcolor="aqua">digital electronic</td><td bgcolor="orange">fundamentals of c</td>
    </tr>

  </table>
  <!DOCTYPE html>
<html>
<head>
  <title>Subject List</title>
  <style>
    table {
      border-collapse: collapse;
      width: 50%;
    }

    th, td {
      border: 5px solid black;
      padding: 20px;
      text-align: left;
    }

    th {
      background-color: yellow;
    }
  </style>
</head>
<body>

<h2>Subject List</h2>

<table>
  <tr>
    <th>S. No.</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
  </tr>
  <tr>
    <td>1.</td>
    <td>19A1414</td>
    <td>Fundamentals of Web Application Development</td>
  </tr>
  <tr>
    <td>2.</td>
    <td>19AI403</td>
    <td>Fundamentals of C Programming</td>
  </tr>
  <tr>
    <td>3.</td>
    <td>19SH831</td>
    <td>Physics for Quantum computing</td>
  </tr>
  <tr>
    <td>4.</td>
    <td>19EE404</td>
    <td>Digital Electronics</td>
  </tr>
  <tr>
    <td>5.</td>
    <td>19MA201</td>
    <td>Calculus and Matrix Algebra (MAT)</td>
  </tr>
  <tr>
    <td>6.</td>
    <td>19EY701</td>
    <td>Career Skill Development</td>
  </tr>
</table>

</body>
</html>
  
</body>
</html>







```




## OUTPUT
![alt text](image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
