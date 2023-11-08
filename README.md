# Ex03 Time Table
## Date:5-11-2023

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
	<title> SLOT TIMETABLE-NISHA.D (23012927) </title>
	<body>
		<table align="center" width="540" border="10" bgcolor="cyan" cellspacing="10" cellpadding="10">
			<caption>SLOT TIMETABLE-NISHA.D (23012927)</caption>
			<tr align="center">
				<th bgcolor="yellow"> Day/Time</th>
				<th bgcolor="yellow">8-10</th>
				<th bgcolor="yellow">10-12</th>
				<th bgcolor="yellow">12-1</th>
				<th bgcolor="yellow">1-3</th>
				<th bgcolor="yellow">3-5</th>
			</tr>
			<tr>
				<th bgcolor="yellow">MONDAY</th>
				<td>freeslot</td>
				<td>freeslot</td>
				<td>LUNCH</td>
				<td>CHEM</td>
				<td>freeslot</td>
			</tr>
			<tr>
				<th bgcolor="yellow">TUESDAY</th>
				<td>ENG</td>
				<td>MATH</td>
				<td>LIUNCH</td>
				<td>freeslot</td>
				<td>freeslot</td>
			</tr>
			<tr>
				<th bgcolor="yellow">WEDNESDAY</th>
                                <td>FWAD</td>
				<td>freeslot</td>
				<td>LUNCH</td>
				<td>CHEM</td>
				<td>PYTHON</td>
			</tr>
			<tr>
				<th bgcolor="yellow">THURSDAY</th>
				<td>SOFTSKILL</td>
				<td>FWAD</td>
				<td>LUNCH</td>
				<td>ENG</td>
				<td>MATH</td>
			</tr>
			<tr>
				<th bgcolor="yellow">FRIDAY</th>
				<td>PYTHON</td>
				<td>freeslot</td>
				<td>LUNCH</td>
				<td>FWAD</td>
				<td>freeslot</td>
			</tr>
		</table>
	</body>
</html>




<html>
	<title>COURSE</title>
	<body>
		<table align="center" width="540" border="10" cellspacing="10" cellpadding="6">
			<tr align="center">
				<th>S.NO</th>
				<th>SUBJECT CODE</th>
				<th>SUBJECT NAME</th>
			</tr>
			<tr>
				<th>1</th>
				<td>19AI301C</td>
				<td>Python and linear algebra</td>
			</tr>
			<tr>
				<th>2</th>
				<td>19AI414</td>
				<td>Fundamentals of web application development</td>
			</tr>
			<tr>
                                <th>3</th>
				<td>19CY205</td>
				<td>Principles of chemistry in engineering</td>
			</tr>
			<tr>
				<th>4</th>
				<td>19EN101</td>
				<td>Communicative English</td>

			</tr>
			<tr>
				<th>5</th>
				<td>19EY701</td>
				<td>Softskills</td>

			</tr>
		</table>
	</body>
</html>
    
```


## OUTPUT
![Alt text](<Screenshot (18).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
