# Ex03 Time Table

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

## CODE

```
<!DOCTYPE html>
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/images/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b> TIME TABLE - SRINITHI V [212222110046] </b></caption>
<tr align="center" bgcolor="pink">
<th >Day/Time</th>
<th >8-10</th>
<th >10-12</th>
<th >1-3</th>
<th >3-5</th>
<th >5-7</th>
</tr>
<tr align="center">
<th bgcolor="pink">MONDAY</th>
<td>PM</td>
<td colspan="2">-</td>
<td>DBMS</td>
<td>-</td>
</tr>
<tr align="center">
<th bgcolor="pink">TUESDAY</th>
<td>PQM</td>
<td>DBMS</td>
<td>EDM</td>
<td>-</td>
<td>EMPD</td>
</tr>
<tr align="center">
<th bgcolor="pink">WEDNESDAY</th>
<td>-</td>
<td>EDM</td>
<td>FWAD</td>
<td>PQM</td>
<td>-</td>
</tr>
<tr align="center">
<th bgcolor="pink">THURSDAY</th>
<td>FWAD</td>
<td colspan="2">-</td>
<td>PM</td>
<td>EMPD</td>
</tr>
<tr align="center">
<th bgcolor="pink">FRIDAY</th>
<td>FWAD</td>
<td colspan="2">-</td>
<td>CSC</td>
<td>-</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19EY702</td>
<td>Creative Skills for Communication (CSC)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19MA222</td>
<td>Probability and Queueing Models (PQM)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EE309</td>
<td>Programming Microcontroller (PM)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19CS404</td>
<td>Database Management System and its Application (DBMS)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AI302</td>
<td>Engineering Design and Modelling (EDM)</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19AI303</td>
<td>Engineerind Mechanics and Product Development (EMPD)</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![OUTPUT](https://user-images.githubusercontent.com/118722030/233800623-45d13d8d-7e9d-436e-90f0-d3a8c23dcb28.png)


## HTML VALIDATOR
![HTML VALIDATOR](https://user-images.githubusercontent.com/118722030/233800641-26e21482-c158-451f-845c-923dc46c2067.png)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
