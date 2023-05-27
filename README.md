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
![Screenshot (12)](https://github.com/DSREWINJAYASAMSHAJIN/Ex06_Web-Design/assets/127816515/6b057403-b2ae-4df8-8ad7-0ba6abacd0c5)
![Screenshot (13)](https://github.com/DSREWINJAYASAMSHAJIN/Ex06_Web-Design/assets/127816515/0f1a764d-9bbc-4784-9b4e-08f4ecc9787e)
![Screenshot (14)](https://github.com/DSREWINJAYASAMSHAJIN/Ex06_Web-Design/assets/127816515/822fc72a-8962-4cd7-8d00-f28652e257ff)
![Screenshot (15)](https://github.com/DSREWINJAYASAMSHAJIN/Ex06_Web-Design/assets/127816515/2f3cc8b6-2e39-414d-90da-909392d993a1)
![Screenshot (16)](https://github.com/DSREWINJAYASAMSHAJIN/Ex06_Web-Design/assets/127816515/65b59f3c-cf4e-49f6-baab-985f3baed386)
![Screenshot (17)](https://github.com/DSREWINJAYASAMSHAJIN/Ex06_Web-Design/assets/127816515/a6b0a65d-b813-4e1f-ac71-8e58cff48e87)
![Screenshot (11)](https://github.com/DSREWINJAYASAMSHAJIN/Ex06_Web-Design/assets/127816515/91636225-fa03-4b61-b522-8e52d3328189)


## RESULT
  Student result using JavaScript is created successfully.
