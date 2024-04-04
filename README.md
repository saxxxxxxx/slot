# Ex03 Time Table
## Date:04/04/2024

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
```C
<html>
    <head>
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="C:\Users\screenshot\Pictures\screenshot.png"height="100" width="500">
        </center>
        <br>
        <table border="2" cellspacing="5" cellpadding="7" align="center" bgcolor="black">
            <caption><b>SLOT TIMETABLE DHINESH (212222043001)</b></caption> 
            <tr align="center">
                <th bgcolor="lightblue">Day/Time</th>
                <th bgcolor="lightblue">Monday</th>
                <th bgcolor="lightblue">Tuesday</th>
                <th bgcolor="lightblue">Wednesday</th>
                <th bgcolor="lightblue">Thursday</th>
                <th bgcolor="lightblue">Friday</th>
            </tr>
            <tr align="center">
                <th bgcolor="red">8-10</th>
                <td bgcolor="lightgreen">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="lightgreen">ETHICAL HACKING TECHNIQUES</td>
                <td bgcolor="lightgreen">INTRODUCTION TO IOT</td>
                <td bgcolor="lightgreen">FREE SLOT</td>
                <td bgcolor="lightgreen">INTRODUCTION TO IOT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="red">10-12</th>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="lightgreen">COMPUTER NETWORKS</td>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="lightgreen">COMPUTER NETWORKS</td>
                <td bgcolor="pink">FREE SLOT</td>
            </tr>
            <tr bgcolor="cyan" align="center">
                <th bgcolor="orange">12-1</th>
                <td colspan="5" align="center"> L U N C H </td>
            <tr align="centre">
                <th bgcolor="red">1-3</th>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="lightgreen">Programming in C</td>
                <td bgcolor="lightgreen">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="lightgreen">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="red">1-3</th>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="lightgreen">SOFT SILLS</td>
                <td bgcolor="pink">FREE SLOT</td>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr> 
            <tr>
                <td align="center">1.</td>
                <td align="center"><b><font color = orange>19AI414</font></b></td>
                <td><b><font color = orange>Fundamentals of Web Application Development (FWAD)</font></b></td>
                </tr>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AM508</td>
                <td>INTRODUCTION TO IOT(IOT)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19CS417</td>
                <td>ETHICAL HACKING TECHNIQUES(EHT)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19CS406</td>
                <td>COMPUTER NETWORKS(CN)</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19CS302</td>
                <td>C PROGRAMMING(C)</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19EY701</td>
                <td>SOFT SKILLS (SS)</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![Screenshot (33)](https://github.com/dhinesh00406/slot/assets/147149471/14be7cdb-d257-4cf0-a926-4b0fb340e8ff)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
