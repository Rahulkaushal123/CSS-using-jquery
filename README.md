# CSS-using-jquery
<!DOCTYPE html>
<html>
<head>
<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script>
$(document).ready(function(){
$("input").focus(function(){
$(this).css("background-color","blue");
});
$("input").blur(function(){
$(this).css("background-color","red");
});
});
</script>
</head>
<body>
name: <input type="text" name="full name"><br>
email: <input type="text" name="email">
</body>
</html>
