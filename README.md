# Ex03 Time Table
## Date:21/04/2025

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
'''
<html >
    <head>
        <title>Timetable </title>
    </head>
    <body >
        <center>
            <img src="sec-logo-01as.png" height = "130" width="500>">
        </center>
        <table align="Center" border="3">
            <caption><b>My Time Table (Sibhiraaj R - 24010177)</b></caption>
            <tr  bgcolor="white" cellspacing="10" cellpadding="20">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <th  bgcolor="blue">8-10</th>
                <td  bgcolor="sky blue">Free </td>
                <td  bgcolor="sky blue">FWAD</td>
                <td  bgcolor="sky blue">Python & Math</td>
                <td  bgcolor="sky blue">Free</td>
                <td  bgcolor="sky blue">Free</td>
                <td  bgcolor="sky blue">English</td>
            </tr>
            <tr>
                <th  bgcolor="blue">10-12</th>
                <td  bgcolor="sky blue">Free</td>
                <td  bgcolor="sky blue">Free</td>
                <td  bgcolor="sky blue">English</td>
                <td  bgcolor="sky blue">Python</td>
                <td  bgcolor="sky blue">Soft Skills</td>
                <td  bgcolor="sky blue">Python & Math</td>
            </tr>
            <tr>
                <th  bgcolor="blue">12-1</th>
                <td    bgcolor="white"colspan="6" align="center">LUNCH BREAK</td>
            </tr>

            <tr>
                <th  bgcolor="blue">1-3</th>
                <td  bgcolor="sky blue">Chemistry</td>
                <td  bgcolor="sky blue">Python</td>
                <td  bgcolor="sky blue">Mentor Meet</td>
                <td  bgcolor="sky blue">Chemistry</td>
                <td  bgcolor="sky blue">FWAD</td>
                <td  bgcolor="sky blue">FWAD</td>
            </tr>
            <tr>
                <th  bgcolor="blue">3-5</th>
                <td  bgcolor="white" colspan="6" align="center">FREE SLOT</td>

        </table>    

    </body>
</html>
<br>
<hr>
<br>

<html>
    <head>
        <title>courses</title>
    </head>
    <body>
        <table align="Center" border="3" >
        <caption><b>My courses</b></caption>

            <tr bgcolor=" white">
                <th>S.NO</th>
                <th>Course Code</th>
                <th>Course Name</th>
            </tr>
            <tr>
                <th bgcolor="blue">1</th>
                <td bgcolor=" sky blue">19A13414</td>
                <td bgcolor=" sky blue">Fundamentals of web application development (FWAD)</td>
            </tr>
            <tr>
                <th bgcolor="blue">2</th>
                <td  bgcolor=" sky blue">19AI301C</td>
                <td  bgcolor=" sky blue">Python adn Linear Algebra</td>
            </tr>
            <tr>
                <th bgcolor="blue">3</th>
                <td  bgcolor=" sky blue">19EN101</td>
                <td  bgcolor=" sky blue">Communicative English</td>
            </tr>
            <tr>
                <th bgcolor="blue">4</th>
                <td  bgcolor=" sky blue">19CY205</td>
                <td  bgcolor=" sky blue">Principle of Chemistry in Engineeing </td>
            </tr>
            <tr>
                <th bgcolor="blue">6</th>
                <td  bgcolor=" sky blue">ECA-M-SCOFT</td>
                <td  bgcolor=" sky blue">Mentor Meet</td>
            </tr>
            <tr>
                <th bgcolor="blue">8</th>
                <td  bgcolor=" sky blue">19EY708</td>
                <td  bgcolor=" sky blue">Carrer development skill(Soft skill)</td>
            </tr>
        </table>
    </body>
</html>
'''

## OUTPUT
![WhatsApp Image 2025-04-21 at 09 53 10_c1160f0d](https://github.com/user-attachments/assets/371e0e9a-60f2-4a56-bdd8-ea15d2a58f59)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
