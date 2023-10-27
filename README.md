# Ex03 Time Table

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

## CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
    <style>
        .table1{
            background-color: cyan;
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px;
        }
        .table2{
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px; 
        }
        .name{
            padding-left: 185px;
        }
        .row1{
            background-color: yellow;
        }
        .c1{
            background-color: yellow;
        }
    </style>
</head>
<body>
    <img src = "http://training.saveetha.in/pluginfile.php/1/core_admin/logo/0x150/1623542614/logo_1.png" width = "800" height="150">
    <h3 class = "name">SLOT TIMETABLE - <b> B Subash Raj(212221040164)</b></h3>
    <table border="1" class = "table1">
        <tr class = "row1">
            <th class="c1">Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td class="c1">8-10</td>
            <td>DAA</td>
            <td>MC</td>
            <td>AQT</td>
            <td>FWAD</td>
            <td>FS</td>
            <td>FWAD</td>
        </tr>
        <tr>
            <td class="c1">10-12</td>
            <th colspan="4">FS</th>
            <td>DAA/DW</td>
            <td>CNS</td>
            
        </tr>
        <tr>
            <td class="c1">12-1</td>
            <th colspan="6">LUNCH BREAK</th>
        </tr>
        <tr>
            <td class="c1">1-3</td>
            <th colspan="2">FS</th>
            <td>DW</td>
            <td>TOC</td>
            <td>TOC</td>
            <td>FS</td>
            
        </tr>
        <tr>
            <td class="c1">3-5</td>
            <td>CNS</td>
            <td>FWAD</td>
            <th colspan="2">FS</th> 
            <td>MC</td>
            <td>FS</td>
        </tr>
        <tr>
            <td class="c1">5-7</td>
            <th colspan="2">FS</th>
            <td>GP</td>
            <td>GP</td>
            <th colspan="2">FS</th>
        </tr>
    </table>
    <br>
    <br>
    <table border="1" class="table2">
        <tr>
            <th>S.No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Applications Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19CS402</td>
            <td>Design Analysis and Algorithm (DAA)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CS521</td>
            <td>Cryptography and Network Security (CNS)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CS517</td>
            <td>Mobile Computing (MC)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19AI513</td>
            <td>Game Programming (GP)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY704</td>
            <td>Advance Quantitative and Logical Reasoning (AQT)</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19EY704</td>
            <td>Theory of Computation (TOC)</td>
        </tr>
    </table>
</body>
</html>
```
## OUTPUT
![image](https://github.com/subashraj21/slot-timetabel/assets/143729815/cc49ff6a-6fba-48a4-9939-8233f61f0b07)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
