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
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100"width="540">
        </center>
        <br>
        <table align="center" width="540">
            <caption><b>SLOT TIMETABLE MADHUVATHANI.V(212223040107)</b></caption>
            <tr align="center">
                <th bgcolor="green">Day/Time</th>
                <th bgcolor="green">Monday</th>
                <th bgcolor="green">Tuesday</th>
                <th bgcolor="green">Wednesday</th>
                <th bgcolor="green">Thursday</th>
                <th bgcolor="green">Friday</th>
            </tr>
            <tr align="center">
                <th bgcolor="green">8-10</th>
                <td bgcolor="red">FREE SLOCT</td>
                <td bgcolor="red">COMMUNICATIVE ENGLISH</td>
                <td bgcolor="red">PHYSICS FOR QUANTUM COMPUTATION</td>
                <td bgcolor="red">STATISTICS AND NUMERICAL METHODS</td>
                <td bgcolor="red">PROGRAMMING MICROCONTROLLER</td>
            </tr>
            <tr align="centre">
                <th bgcolor="green">10-12</th>
                <td bgcolor="red">PROGRAMMING MICROCONTROLLER</td>
                <td bgcolor="red">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="red">PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
                <td bgcolor="red">FREE SLOT</td>
                <td bgcolor="red">STATISTICS AND NUMERICAL METHODS</td>
            </tr>
            <tr align="centre">
                <th bgcolor="green">1-3</th>
                <td bgcolor="red">COMMUNICATIVE ENGLISH</td>
                <td bgcolor="red">FREE SLOT</td>
                <td bgcolor="red">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="red">PHYSICS FOR QUANTUM COMPUTATION</td>
                <td bgcolor="red">PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
            </tr>
            <tr align="centre">
                <th bgcolor="green">3-5</th>
                <td bgcolor="red">STATISTICS AND NUMERICAL METHODS</td>
                <td bgcolor="red">SOFT SKILLS</td>
                <td bgcolor="red">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="red">PHYSICS FOR QUANTUM COMPUTATION</td>
                <td bgcolor="red">PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
            </tr>
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
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AI304</td>
                <td>FUNDAMENTALS OF C PROGRAMMING (C PROGRAM)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19EN101</td>
                <td>COMMUNICATIVE ENGLISH(ENG)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19CY205</td>
                <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING (CHE)</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19MA211</td>
                <td>STATISTICS AND NUMERICAL METHODS (MAT)</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19PH214</td>
                <td>PHYSICS FOR QUANTUM COMPUTATION(PHY)</td>
            </tr>
            <tr>
                <td align="center">7.</td>
                <td align="center">19EE309</td>
                <td>PROGRAMMING MICROCONTROLLER(PM)</td>
            <tr>
        </table>
    </body>
</html>
```

## OUTPUT
![Screenshot 2024-03-26 110403](https://github.com/Suji-90/slot/assets/150884148/32670723-9864-4378-ae04-e56702975758)
![Ex-03](https://github.com/Suji-90/slot/assets/150884148/f94e17aa-f82a-455e-bc36-ee1eca48ed33)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
