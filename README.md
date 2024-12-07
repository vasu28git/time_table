# Ex03 Time Table
# Date:04-11-2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Time Table</title>
    <style>
        table,tr,th,td{
            border: 1px solid black;
            margin: auto;
        }
        td{
            background-color: aqua;
        }
        th{
            background-color: yellow;
        }
        
    </style>
</head>
<body>
    {% load static %}
    <h1> <img src="{% static 'logo.png'%}" height= "100%" width="100%" class="center"></h1>
    <br>
    <h2 align="center">VASU VIGNESHWARAN  REF:24900796</h2>
    <table >
        <tr>
            <th>Day</th>
            <th>8 - 10</th>
            <th>10 - 12</th>
            <th>12 - 1</th>
            <th>1 - 3</th>
        </tr>
        <tr>
            <th>Monday</th>
            <td>Free</td>
            <td>Crypto</td>
            <td rowspan="6"> Lunch </td>
            <td>Web Application</td>
        </tr>
        <tr>
            <th>Tuesday</th>
            <td>Free</td>
            <td>Calculus</td>
            <td>Chemistry</td>
        </tr>
        <tr>
            <th>Wednesday</th>
            <td>Free</td>
            <td>C Programming</td>
            <td>Mentor Meet</td>
        </tr>
        <tr>
            <th>Thursday</th>
            <td>Human Values</td>
            <td>BEEE</td>
            <td>C Programming</td>
        </tr>
        <tr>
            <th>Friday</th>
            <td>Chemistry</td>
            <td>Web Application</td>
            <td>BEEE</td>
        </tr>
        <tr>
            <th>Saturday</th>
            <td>Web Application</td>
            <td>English</td>
            <td>Calculus</td>
        </tr>
    </table>
    <table style="margin-top: 5ch;">
        <tr>
            <th>S .NO</th>
            <th> SUBJECT CODE </th>
            <th> SUBJECT NAME </th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Devolopment</td>
    
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI304</td>
            <td>Fundamentals of C Programming</td>
            
        </tr>
        <tr>
            <td>3.</td>
            <td>19CS547</td>
            <td>Fundamentals of Cryptocurrency</td>
         
        </tr>
        <tr>
            <td>4.</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19EE305</td>
            <td>Basic Electrical, Electronics and Measurement Engineering</td>
            
        </tr>
        <tr>
            <td>6.</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra</td>
            
        </tr>
        <tr>
            <td>7.</td>
            <td>ECA-M-SCOFT</td>
            <td>Mentor Meet</td>
        </tr>
        <tr>
            <td>8.</td>
            <td>SH7801</td>
            <td>Human Values and Professional Ethics</td>
        </tr>
    </table>
    
</body>
</html>
~~~
# OUTPUT
![time](https://github.com/user-attachments/assets/c4c04ae1-37dd-4014-afaa-5cd699cbe9a3)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
