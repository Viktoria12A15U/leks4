<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
    <style>
	    body{
	    background-color: #DDA0DD;
		color: 	#696969;
		font-size: 40px;
		text-align: center;
	    }
	</style>
</head>
<body>
</body>
<script>
for (let a = 1; a < 101; a++) {
    document.write('<p>');
	if (a % 3 == 0 && a % 5 == 0) {
        document.write("FizzBuzz ");
    }
    else if (a % 3 == 0) {
        document.write("Fizz");
		
    }
    else if (a % 5 == 0) {
        document.write("Buzz");
		
    }
    else {
        document.write(a);
    }
	document.write('</p>');
}
</script>
</html>
