# Age-Calculator


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <h1>Age Calculator</h1>
    
    <p id="result"> </p>
    
<script>
    var age = prompt("Enter your age!");
    var calculation = age * 365;
 if(isNaN(age)){
     alert('Pleaase enter a valid number');
     document.getElementById("result").innerHTML = age + " is not a number " ;
     
 } else{
    document.getElementById("result").innerHTML = age + " years is " + calculation + " days ";
    }
</script>
</body>
</html>
