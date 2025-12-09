# Ex03 Time Table
## Date:09/12/2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>
   <h3 align="center">  SLOT TIME TABLE - M.HARI PRASAD ( 25013933 ) </h3>
        <table align="center" border="5" cellpadding="6" cellspacing="2" bgcolor="cyan">
        <tr>
          <th bgcolor="yellow">Day</th>    
          <th bgcolor="yellow">8-10</th>
          <th bgcolor="yellow">10-12</th>
          <th bgcolor="yellow">12-1</th>
          <th bgcolor="yellow">1-3</th>
          <th bgcolor="yellow">3-5</th>
        </tr>
        <tr>
           <th bgcolor="yellow">MONDAY </th>
           <td>PYTHON </td>
           <td>PYTHON</td>
           <td rowspan="6">L<br>U<br>N<br>C<br>H </td>
           <td>WEB APPLICATION </td>
           <td>COMMUNICATIVE ENGLISH </td>
        </tr>
        <tr>
            <th bgcolor="yellow">TUESDAY  </th>
            <td>WEB APPLICATION</td>
            <td>FREE SLOT</td>
            <td>PYTHON   </td>
            <td>WEB APPLICATION </td>
         </tr> 
         <tr>
            <th bgcolor="yellow">WEDNESDAY </th>
            <td>WEB APPLICATION </td>
            <td>FREE SLOT </td>
            <td>MENTOR    </td>
            <td>COMMUCATIVE ENGLISH </td>
         </tr> 
         <tr>
            <th bgcolor="yellow">THURSDAY  </th>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>WEB APPLICATION  </td>
            <td>FREE SLOT </td>
         </tr>
          <tr>
            <th bgcolor="yellow">FRIDAY    </th>
            <td>FREE SLOT </td>
            <td>PYTHON   </td>
            <td>PYTHON </td>
            <td>FREE SLOT </td>
         </tr>
         <tr>
            <th bgcolor="yellow">SATURDAY  </th>
            <td>FREE SLOT</td>
            <td>FREE SLOT  </td>
            <td>FREE SLOT </td>
            <td>COMMUNICATIVE ENGLISH </td>
         </tr>
        </table>
        <br> 
        <table border="5" cellpadding="7" cellspacing="2" align="center">
         <tr>
           <th><h4>S.NO</h4></th>    
           <th><h4>SUBJECT CODE </h4></th>
           <th><h4>SUBJECT NAME </h4></th>
         </tr>
         <tr>
            <th>1.</th>
            <td>19AI301</td>
            <td>PYTHON PROGRAMMING  </td>
         </tr>
         <tr>
             <th>2.</th>
             <td>19EN101</td>
             <td>COMMUNICATION ENGLISH  </td>
          </tr> 
          <tr>
             <th>3.</th>
             <td>19AI414</td>
             <td>FUNDAMENTALS OF WEB APPLICATION  </td>
          </tr> 
          
         </table>   
    </body>
</html>

    </table>
    
</body>
</html>
```

## OUTPUT
<img width="1911" height="906" alt="Screenshot 2025-12-09 203448" src="https://github.com/user-attachments/assets/c9cd5c08-710f-4b2f-a22d-7dac7e35877d" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
