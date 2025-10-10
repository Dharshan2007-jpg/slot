# Ex03 Time Table
## Date:28/09/2025

## AIM
To write a html webpage to display your slot timetable.

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
~~~

</head>
<body>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>
    <table border="2" cellpadding="10" cellspacing="1" row="1">
        <tr>
            <th>day</th>
            <th>8-10</th>
            <th>10-12</th>
            <th>1-3</th>
            <th>3-5</th>
        </tr>
        <tr>
            <td>MONDAY</td>
            <td></td>
            <td></td>
            <td>fundamental of c programing</td>
            <td>fundamentals of web application devolopment</td>
        </tr>
        <tr>
            <td>TUESDAY</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            
        </tr>
        <tr>
            <td>WEDNESDAY</td>
            <td></td>
            <td></td>
            <td>mentor meet</td>
            <td>fundamental of c programing</td>
        </tr>
        <tr>
            <td>THURSDAY</td>
            <td></td>
            <td>fundamental of c programing</td>
            <td>fundamentals of web application devolopment</td>
            <td>fundamental of c programing</td>
        </tr> 
        
        <tr>
            <td>FRIDAY</td>
            <td>fundamental of c programing</td>
            <td>fundamentals of web application devolopment</td>
            <td></td>
            <td rowspan="2">fundamentals of web application devolopment</td>
        </tr>
        <tr>
            <td>SATURDAY</td>
            <td></td>
            <td></td>
            <td></td>
            
        </tr>
         
    </table>
 </body>

~~~

## OUTPUT
![alt text](<Screenshot 2025-09-28 031154.png>)
![alt text](<Screenshot 2025-09-28 031444.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
