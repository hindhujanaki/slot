# Ex03 Time Table
## Date:

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
<title> MT TIMETABLE </title>
<caption>SLOT TIME TABLE G.HINDHU(212223230079)</caption>
<center><img src="logo.png" height="180" width="600"></center>
<body bgcolor="lavender" align="center">
<table border="8" align="center"
<tr>
<th bgcolor="pink">DAY/TIME</th>
<th bgcolor="pink">MONDAY</th>
<th bgcolor="pink">TUESDAY</th>
<th bgcolor="pink">WEDNESDAY</th>
<th bgcolor="pink">THURSDAY</th>
<th bgcolor="pink">FRIDAY</th>
<th bgcolor="pink">SATURDAY</th>
</tr>


<tr>
<th bgcolor="pink">8-10</th>
<th bgcolor="skyblue">Digital Electronics</th>
<th bgcolor="skyblue">Free Slot</th>
<th bgcolor="skyblue">Fundamentals Of Web Application</th>
<th bgcolor="skyblue">Free Slot</th>
<th bgcolor="skyblue">Computer Network</th>
<th bgcolor="skyblue">Probability</th>
</tr>


<tr>
<th bgcolor="pink">10-12</th>
<th bgcolor="skyblue">Free Slot</th>
<th bgcolor="skyblue">Fundamentals Of Web Application</th>
<th bgcolor="skyblue">Computer Network</th>
<th bgcolor="skyblue">Probability</th>
<th bgcolor="skyblue">Fundamentals Of C Programming</th>
<th bgcolor="skyblue">Introduction Of Data Science</th>
</tr>


<tr>
<th bgcolor="pink">12-1</th>
<th bgcolor="skyblue">LUNCH BREAK</th>
</tr>

<tr>
<th bgcolor="pink">1-3</th>
<th bgcolor="skyblue">Fundamentals Of Web Application</th>
<th bgcolor="skyblue">Free Slot</th>
<th bgcolor="skyblue">Statistics</th>
<th bgcolor="skyblue">Free Slot</th>
<th bgcolor="skyblue">Free Slot</th>
<th bgcolor="skyblue">Statistics</th>
</tr>

<tr>
<th bgcolor="pink">3-5</th>
<th bgcolor="skyblue>Fundamentals Of Web Application</th>
<th bgcolor="skyblue>Introduction Of Data Science</th>
<th bgcolor="skyblue>Free Slot</th>
<th bgcolor="skyblue>Digital Electronics</th>
<th bgcolor="skyblue>Free Slot</th>
<th bgcolor="skyblue>Free Slot</th>
</tr>
</table>

<table border="10" align="center">
<tr>
<th>S.NO</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>

<tr>
<th>01</th>
<th>19EE404</th>
<th>Digital Electronics</th>
</tr>

<tr>
<th>02</th>
<th>19AI414</th>
<th>Fundamentals Of Web Application</th>
</tr>

<tr>
<th>03</th>
<th>19AI304</th>
<th>Fundamentals Of C Programming</th>
</tr>

<tr>
<th>04</th>
<th>19AI403</th>
<th>Introduction Of Data Science</th>
</tr>

<tr>
<th>05</th>
<th>19CS406</th>
<th>Computer Network</th>
</tr>

<tr>
<th>06</th>
<th>19MA222</th>
<th>Probability</th>
</tr>

<tr>
<th>07</th>
<th>19MA211</th>
<th>Statistics</th>
</tr>
</table>
</head>
</body>
</html>
```
## OUTPUT
![alt text](image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
