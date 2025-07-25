# skill-HTML
this is my skill html code
<br>
AUTHOR-Rushi
<!DOCTYPE html>
<html>
<head>
<script>
function formSubmit() {
    document.forms["myForm"].submit();
}
</script>
</head>
<body>

<h1>The form name attribute</h1>

<form name="myForm" action="" method="get">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <input type="button" onclick="formSubmit()" value="Send form data">
</form>


</body>
</html>
