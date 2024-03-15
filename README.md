# Ex03 Time Table
## Date:14/03/24

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
        <title>My Time Table</title>
    </head>
    <body>
        <img src="logo.png"  height="100" width="">
	<table  border="2" cellspacing="8" cellpadding="8" width="40" height="50">
		    <caption>SLOT TIMETABLE-MOHAN.S(212223240094)</caption>
            <tr>
			<th bgcolor="skyblue">Day/Time</th>
			<th bgcolor="red">Monday</th>
            <th bgcolor="red">Tuesday</th>
            <th bgcolor="red">Wednesday</th>
            <th bgcolor="red">Thursday</th>
            <th bgcolor="red">Friday</th>
            <th bgcolor="red">Saturday</th>
	           
		</tr>
		<tr>
			<td align="center" bgcolor="yellow">8-10</td>
			<td bgcolor="orange">FREE TIME</td>
			<td bgcolor="orange">ADV.C </td>
			<td bgcolor="orange">FREE TIME</td>
            <td bgcolor="orange">FREE TIME</td>
            <td bgcolor="orange">FWAD</td>
            <td bgcolor="orange">PYTHON</td>
		</tr>
		<tr>
			<td align="center" bgcolor="yellow">10-12</td>
			<td bgcolor="orange">FREE TIME</td>
			<td bgcolor="orange">PYTHON</td>
			<td bgcolor="orange">COMP.NET</td>
            <td bgcolor="orange">ADV.C</td>
            <td bgcolor="orange">EDM</td>
            <td bgcolor="orange">COMP.NET</td>
		
		</tr>
		<tr>

			<td align="center" bgcolor="yellow">12-1</td>
			<td COLSPAN="6" ALIGN="center" bgcolor="Spearmint">LUNCH</td>
		
		</tr>
        <tr>

			<td align="center" bgcolor="yellow">1-3</td>
			<td bgcolor="orange">FREE TIME</td>
			<td bgcolor="orange">FWAD</td>
            <td bgcolor="orange">FREE TIME</td>
            <tD bgcolor="orange">FWAD</tD>
            <td bgcolor="orange">PYTHON</td>
            <td bgcolor="orange">SOFTSKILL</td>
        </tr>
        <tr>

			<td align="center" bgcolor="yellow">3-5</td>
			<td bgcolor="orange">FREE TIME</td>
			<td bgcolor="orange">FREE TIME</td>
            <td bgcolor="orange">PYTHON</td>
            <td bgcolor="orange">EDM</td>
            <td bgcolor="orange">FREE TIME</td>
            <td bgcolor="orange">FREE TIME</td>
		</tr>

	</table> 
	</br>
	<table  border="2" cellspacing="8" cellpadding="8" width="700" height="50">
		<tr>
			<th>S.No</th>
			<th>Subject Code</th>
			<th>Subject Name</th>
		</tr>
		<tr>
			<td align="center">1.</td>
			<td>19AI414</td>
			<td>Fundamentals Of Web Application Development(FWAD)</td>
		</tr>
		<tr>
			<td align="center">2.</td>
			<td>19AI301C</td>
			<td>Python and Linear Algebra</td>
			
		
		</tr>
		<tr>

			<td align="center">3.</td>
			<td>19AI305</td>
			<td>Advanced C Programming</td>
		</tr>
		<tr>

			<td align="center">4.</td>
			<td>19AI302</td>
			<td>Engineering Design And Modelling</td>
		</tr>
		<tr>

			<td align="center">5.</td>
			<td>19CS406</td>
			<td>Computer Network</td>
		</tr>
		<tr>

			<td align="center">6.</td>
			<td>19EY701</td>
			<td>Soft Skills</td>
		</tr>

	</body>

```

## OUTPUT
![Screenshot 2024-03-15 102952](https://github.com/Mohansithaiya/slot/assets/154211682/09ae267d-a610-41c1-9ce5-e600f34303da)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
