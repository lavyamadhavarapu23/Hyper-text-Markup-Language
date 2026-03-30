# Hyper-text-Markup-Language
HTML Code
<!DOCTYPE html>
<html>
<head>
    <title>Student Profile Page</title>
</head>
<body>

    <h1>Student Profile Page</h1>
    <h2>Created by Lavya</h2>

    <p>Name: Lavya</p>
    <p>Course: B.Tech</p>
    <p>Learning: HTML</p>

</body>
</html>
Output (how it looks in browser)

Student Profile Page
Created by Lavya

Name: Lavya
Course: B.Tech
Learning: HTML


ORDERED LIST
HTML code to print student details in an ordered list:
<!DOCTYPE html>
<html>
<head>
    <title>Student Details</title>
</head>
<body>

    <h2>Student Details</h2>

    <ol>
        <li>Name: Lavya</li>
        <li>Roll No: 101</li>
        <li>Course: B.Tech</li>
        <li>Department: CSE</li>
        <li>Year: 3rd Year</li>
    </ol>

</body>
</html>
Output:

Name: Lavya
Roll No: 24P32A4210
Course: B.Tech
Department: CSE(AI&ML)
Year: 2nd Year


UNORDERED LIST
CODE:
<!DOCTYPE html>
<html>
<head>
    <title>Unordered List Example</title>
</head>
<body>

    <h1>My Hobbies</h1>

    <ul>
        <li>Reading</li>
        <li>Coding</li>
        <li>Music</li>
        <li>Traveling</li>
    </ul>

</body>
</html>
OUTPUT:

My Hobbies
• Reading
• Coding
• Music
• Traveling

HTML CODE FOR A WORKING TABLE
<!DOCTYPE html>
<html>
<head>
    <title>Student Table</title>
    <style>
        table {
            border-collapse: collapse;
            width: 50%;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: lightgray;
        }
    </style>
</head>
<body>

<h2>Student Details Table</h2>

<table>
    <tr>
        <th>ID</th>
        <th>Name</th>
        <th>Course</th>
    </tr>
    <tr>
        <td>101</td>
        <td>Lavya</td>
        <td>CSE</td>
    </tr>
    <tr>
        <td>102</td>
        <td>Rahul</td>
        <td>ECE</td>
    </tr>
    <tr>
        <td>103</td>
        <td>Anjali</td>
        <td>IT</td>
    </tr>
</table>

</body>
</html>
OUTPUT:
Student Details Table

+-----+--------+--------+
| ID  | Name   | Course |
+-----+--------+--------+
| 101 | Lavya  | CSE    |
| 102 | Rahul  | ECE    |
| 103 | Anjali | IT     |
+-----+--------+--------+
