# Ex03 Time Table
## Date:17/11/24

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
    <body>
        <img src="logo.png">
        <table border="1" cellspacing="5" cellpadding="1">
            <caption>Timetable-M.krishna kumaran(24004032)</caption>
            <tr bgcolor="cyan">
                <td>Day/Time</td>
                <td>Monday</td>
                <td>Tuesday</td>
                <td>wednesday</td>
                <td>Thursday</td>
                <td>Friday</td>
                <td>saturday</td>
            </tr>
            <tr>
                <td bgcolor="red">8-10</td>
                <th>mat</th>
                <th>edm</th>
                <th>edm</th>
                <th>c</th>
                <th>web</th>
                <th>free</th>
            </tr>
            <tr>
                <td bgcolor="red">10-12</td>
                <th>beee</th>
                <th>beee</th>
                <th>maths</th>
                <th>chem</th>
                <th>free</th>
                <th>chem</th>
            <tr>
            <tr>
                <td bgcolor="red">12-1</td>
                <th colspan="6">lunch</th>
            </tr>
            <tr>
                <td bgcolor="red">1-3</td>
                <th>web</th>
                <th>web</th>
                <th>mentor</th>
                <th>free</th>
                <th>cds</th>
                <th>c</th>
            </tr>
            <tr>
                <td bgcolor="red">3-5</td>
                <th colspan="5">free</th>
                <th>yoga</th>
            </tr>
        </table>
        <table border="2" cellspacing="5" cellpadding="1">
            <tr>
                <td>S.NO</td>
                <td>Subject code</td>
                <td>Subject Name</td>
            </tr>
            <tr>
                <th>1.</th>
                <th>19AI302</th>
                <th>Engineering Design and Modelling(edm)</th>

            </tr>
            <tr>
                <th>2.</th>
                <th>19AI302</th>
                <th>Fundamentals of c programming(c)</th>
            </tr>
            <tr>
                <th>3.</th>
                <th>19AI414</th>
                <th>Fundamentals of web application(web)</th>
            </tr>
            <tr>
                <th>4.</th>
                <th>19CY205</th>
                <th>Principles of chemistry in Engineering(chem)</th>
            </tr>
            <tr>
                <th>5.</th>
                <th>19EE305</th>
                <th>Basics of electical,electronics and mesurement engineering(beee)</th>
            </tr>
            <tr>
                <th>6.</th>
                <th>19EY708</th>
                <th>Career development skills(cds)</th>
            </tr>
            <tr>
                <th>7.</th>
                <th>19MA222</th>
                <th>Proabliltyand queueing models(mat)</th>
            </tr>
            <tr>
                <th>8.</th>
                <th>ECA-M-SCOFT</th>
                <th>Mentor meeting</th>
            </tr>
            <tr>
                <th>9.</th>
                <th>SH5616</th>
                <th>Yoga</th>
            </tr>
        </table>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot (15).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
