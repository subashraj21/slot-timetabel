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
<!DOCTYPE html>
<meta name="viewport">
<img src="http://training.saveetha.in/pluginfile.php/1/core_admin/logo/0x150/1623542614/logo_1.png" width="500" >

<html>
<head>
    <title>Time Table</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="background-color: cyan  (173, 230, 221);">
    <p>Slot Time Table - subash raj B (212221040164) </p>

<table border="1">
    <tr>
        <th style="background-color: violet;">Day/Time</th>
        <th style="background-color: violet;">Monday</th>
        <th style="background-color: violet;">Tuesday</th>
        <th style="background-color: violet;">Wednesday</th>
        <th style="background-color: violet;">Thursday</th>
        <th style="background-color: violet;">Friday</th>
        <th style="background-color: violet;">Saturday</th>
    </tr>
    
    <tr>
        <td style="background-color: blue ;">8-10</td>
        <td style="background-color: rgb(0, 255, 128);"> Free</td>
        <td style="background-color: rgb(0, 255, 128);">crypto</td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
        <td style="background-color: rgb(0, 255, 128);" >Toc</td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
    </tr>
    <tr>
        <td style="background-color: blue;">10-12</td>
        <td style="background-color: rgb(0, 255, 128);">Mern</td>
       <td style="background-color: rgb(0, 255, 128);">Free</td>
       <td style="background-color: rgb(0, 255, 128);">Mern</td>
       <td style="background-color: rgb(0, 255, 128);">TOC</td>
       <td style="background-color: rgb(0, 255, 128);">Mern</td>
       <td style="background-color: rgb(0, 255, 128);">Crypto</td>
    </tr>
    <tr>
        <td style="background-color: blue;">1-3 </td>
        <td style="background-color: rgb(0, 255, 128) (0, 255, 128);">Free</td>
        <td style="background-color: rgb(0, 255, 128);">java</td>
        <td style="background-color: rgb(0, 255, 128);">Game</td>
        <td style="background-color: rgb(0, 255, 128);">Game</td>
        <td style="background-color: rgb(0, 255, 128);">Compiler</td>
        <td style="background-color: rgb(0, 255, 128);">Free</td>
    </tr>
    <tr>
        <td style="background-color: blue;">3-5 </td>
        <td style="background-color: rgb(0, 255, 128);">Crypto</td>
        <td style="background-color: rgb(0, 255, 128);">Compiler</td>
        <td style="background-color: rgb(0, 255, 128);">Compiler</td>
        <td style="background-color: rgb(0, 255, 128);">Web</td>
        <td style="background-color: rgb(0, 255, 128);">Trainning</td>
        <td style="background-color: rgb(0, 255, 128);">Web</td>
    </tr>
    
</table>
<table border="1" class="table2">
    <tr>
        <th>S.No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>
    <tr>
        <td>1.</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Applications Development (WEB)</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>19CS409</td>
        <td>Compiler Design (CD)</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>19CS521</td>
        <td>Cryptography and Network Security (CNS)</td>
    </tr>
    <tr>
        <td>4.</td>
        <td>19CS512</td>
        <td>MERN</td>
    </tr>
    
   
    <tr>
        <td>5.</td>
        <td>19CS407</td>
        <td>Theory of Computation (TOC)</td>
    </tr>
    <tr>
        <td>6.</td>
        <td>19CS403</td>
        <td>Programming Paradigms(java)</td>
</table>
</body>
</html>


## OUTPUT
![image](https://github.com/subashraj21/slot-timetabel/assets/143729815/3fb10a8a-25cc-45f3-9ac7-67f15b477e5f)


## HTML VALIDATOR


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
