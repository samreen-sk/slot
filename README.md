# Ex03 Time Table
## Date:16-03-2024

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
<title> My Time Table </title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
<table border="2" cellspacing="5" cellpading="5">
<caption>SLOT TIMETABLE - SHAIK SAMREEN(212223110047)</caption>
<tr>
<th bgcolor="pink">Day/Time</th>
<th bgcolor="pink">Monday</th>
<th bgcolor="pink">Tuesday</th>
<th bgcolor="pink">Wednesday</th>
<th bgcolor="pink">Thursday</th>
<th bgcolor="pink">Friday</th>
</tr>
<tr>
<td bgcolor="pink">8-10</td>
<td rowspan="2" bgcolor="lightblue">free</td>
<td bgcolor="lightblue">C.E</td>
<td bgcolor="lightblue">PQM</td>
<td bgcolor="lightblue">free</td>
<td bgcolor="lightblue">web</td>
</tr>
<tr>
<td bgcolor="pink">10-12</td>
<td bgcolor="lightblue">C</td>
<td bgcolor="lightblue">BEEE</td>
<td bgcolor="lightblue">C</td>
<td bgcolor="lightblue">Empd</td>
</tr>
<tr>
<td bgcolor="pink">12-1</td>
<td colspan="5" bgcolor="lightblue">----------------LUNCH TIME----------------</td>
</tr>
<tr>
<td bgcolor="pink">1-3</td>
<td bgcolor="lightblue">BEEE</td>
<td bgcolor="lightblue">web</td>
<td bgcolor="lightblue">Empd</td>
<td bgcolor="lightblue">web</td>
<td rowspan="2" bgcolor="lightblue">free</td>
</tr>
<tr>
<td bgcolor="pink">3-5</td>
<td bgcolor="lightblue">PQM</td>
<td colspan="2" bgcolor="lightblue">free</td>
<td bgcolor="lightblue">C.S</td>
</tr>
</table>
<table border="2" cellspacing="5" cellpading="5">
<tr>
<th>S.NO</th>
<th>SUBJECT CODE</th>
<th>SUBJECT NAME</th>
</tr>
<tr>
<td>1.</td>
<td>19AI303</td>
<td>Engineering mechanics and product development(Empd)</td>
</tr>
<tr>
<td>2.</td>
<td>19AI304</td>
<td>Fundamentals of C programming(C)</td>
</tr>
<tr>
<td>3.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Development(web)</td>
</tr>
<tr>
<td>4.</td>
<td>19EE305</td>
<td>Basic Electrical Electronics and Measurement Engineering(BEEE)</td>
<tr>
<td>5.</td>
<td>19EN101</td>
<td>Communicative English(C.E)</td>
</tr>
<tr>
<td>6.</td>
<td>19EY702</td>
<td>Creative Skills for Communication(C.S)</td>
</tr>
<tr>
<td>7.</td>
<td>19MA222</td>
<td>Probability and Queuing Models(PQM)</td>
</tr>
</table>
</center>
</body>
</html>
```
## OUTPUT
![output](./Screenshot%202024-03-16%20091943.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
