# Ex03-Time-Table
-AADHITHAN B 212224040001
REGNO:212224040001

# AIM:
To write a html webpage page to display your slot timetable

# ALGORITHM

STEP 1
Create a static folder and inert HTML code.

STEP 2
Create a simple table using <table> tag in html.

STEP 3
Add header row using <th> tag.

STEP 4
Add your timetable using <td> tag.

STEP 5
Execute the program using runserver command.

# PROGRAM
```

<html>
<head>
<title>Slot Timetable</title>
<style>
	.free-slot{
		background-color:bisque;
	}
</style>
</head>
<body>
<center>
<h1><b>SLOT TIMETABLE</b></h1>


</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" border="5" bgcolor="aqua">
<caption><b>SLOT TIMETABLE - AADHITHAN B-(212224040001)</b></caption>
<tr align="center">
	<th bgcolor="yellow">Day/Time</th>
	<th bgcolor="yellow">Monday</th>
	<th bgcolor="yellow">Tuesday</th>
	<th bgcolor="yellow">Wednesday</th>
	<th bgcolor="yellow">Thursday</th>
	<th bgcolor="yellow">Friday</th>
    <th bgcolor="yellow">Saturday</th>
</tr>
<tr align="center">
	<th bgcolor="yellow">8-10</th>
	<td>Training</td>
	<td>Employement Enrichment Skills</td>
	<td>Training</td>
	<td>Company Specific</td>
	<td>Training</td>
    <td>Fundamentals of Web Application</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">10-12</th>
	<td>Training</td>
	<td>Training</td>
	<td>Training</td>
	<td>Fundamentals of Web Application</td>
	<td>Training</td>
    <td>Training</td>
</tr>
<tr>
	<th bgcolor="yellow">12-1</th>
	<td colspan="5" align="center">L U N C H   B R E A K</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">1-3</th>
	<td>cyber law and compliance</td>
	<td>Software Project Management</td>
	<td>Mentor Meet</td>
	<td>cyber law and compliance</td>
	<td>training</td>
    <td>Training</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">3-5</th>
	<td>Fundamentals of Web Application</td>
	<td class = 'free-slot'>Free</td>
	<td class = 'free-slot'>Free</td>
	<td>Software Project Management</td>
	<td class = 'free-slot'>Free</td>
    <td class = 'free-slot'>Free</td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19EY712</td>
<td>Employement Enrichment Skills</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19CS504</td>
<td>Software Project Management</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EY706</td>
<td>Company Specific</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS418</td>
<td>Cyber law and compliance</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">ECA-M</td>
<td>Mentor Meet</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application</td>
</tr>
</table>
</body>
</html>

```

# OUTPUT
<img width="916" height="906" alt="image" src="https://github.com/user-attachments/assets/a0dc6814-76b9-49aa-9259-d58b18800c3d" />
