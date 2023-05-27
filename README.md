# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
<head>
<title>JavaScript program to display the result of a student</title>
<script type="text/javascript">
function student()
{
    var mark1, mark2, mark3, mark4, mark5, total, percentage;
    mark1 = parseInt(prompt("Enter Subject-1 Marks"));
    mark2 = parseInt(prompt("Enter Subject 2 Marks"));
    mark3 = parseInt(prompt("Enter Subject 3 Marks"));
    mark4 = parseInt(prompt("Enter Subject 4 Marks"));
    mark5 = parseInt(prompt("Enter Subject 5 Marks"));
    total = mark1 + mark2 + mark3 + mark4 + mark5;
    percentage = total / 5;

    if (percentage >= 91 && percentage <= 100)
    {
        alert("O Grade");
    }
    else if (percentage >= 81 && percentage <= 90)
    {
        alert("A+ Grade");
    }
    else if (percentage >= 71 && percentage <= 80)
    {
        alert("A Grade");
    }
    else if (percentage >= 61 && percentage <= 70)
    {
        alert("B+ Grade");
    }
    else if (percentage >= 51 && percentage <= 60)
    {
        alert("B Grade"); 
    }
    else
    {
        alert("RA Grade");
    }
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>

## OUTPUT

![Screenshot from 2023-05-27 08-57-14](https://github.com/esanjaye/Ex06_Web-Design/assets/127818044/a43e76ab-4f65-423b-b44b-f4ff5eea6d70)
![Screenshot from 2023-05-27 08-57-26](https://github.com/esanjaye/Ex06_Web-Design/assets/127818044/3b144c4b-28cf-4da5-a5b8-bd24db93e0ad)
![Screenshot from 2023-05-27 08-57-48](https://github.com/esanjaye/Ex06_Web-Design/assets/127818044/57e44835-8a43-4297-9c42-95d349e10de3)
![Screenshot from 2023-05-27 08-57-53](https://github.com/esanjaye/Ex06_Web-Design/assets/127818044/932aa870-38fe-4c08-bae7-a87939fe825e)
![Screenshot from 2023-05-27 08-57-56](https://github.com/esanjaye/Ex06_Web-Design/assets/127818044/1f410d89-072d-49b7-b329-b212350f8eba)
![Screenshot from 2023-05-27 08-57-59](https://github.com/esanjaye/Ex06_Web-Design/assets/127818044/7e1e6fb9-9fdf-4837-9691-f5c521090c7f)
![Screenshot from 2023-05-27 08-58-03](https://github.com/esanjaye/Ex06_Web-Design/assets/127818044/ac2d9143-4ad4-4196-b8e1-a7ec6d6a1b06)

## RESULT
  Student result using JavaScript is created successfully.
