# shuyuwang123.github.io
<!DOCTYPE html>
<html>
<head>
<title>Purchase a book</title>
</head>
<body>


	<form name="loginForm" method="get" action="Servlet">
		<label for="email"> Email address:</label><br> <input
			type="email" id=" email" name="email" required
			placeholder="@usc.edu"><br>
		<br> <label for="month"> Birthmonth:</label><br> <input
			type="month" id=" month" name="month"><br>
		<br> <label for="text"> Your name:</label><br> <input
			type="text" id="name" name="name" required><br>
		<br> <label for="text"> Your phone number:</label><br> <input
			type="tel" id=" phone" name=" phone" pattern="[0-9]{3}"><br>
		<br> <label for="book">How many do you want:</label> <select
			name="book" id="book">
			<option value="1">1</option>
			<option value="2">2</option>
			<option value="3">3</option>
			<option value="4">4</option>
		</select><br>
		<br> <label for="points">How do your friend like about
			the book (between 0 and 10):</label> <input type="range" id="points"
			name="points" min="0" max="10"> <br>
		<br> <label for="points">What is your gender :</label><br> <input
			type="radio" id="male" name="gender" value="male"> <label
			for="html">male</label><br> <input type="radio" id="female"
			name="gender" value="female"> <label for="css">female</label><br>
		<br>
		<br>



		<fieldset>
			<label for="story">Why you like the book?:</label><br>

			<textarea id="book" name="book" rows="5" cols="33">

</textarea>
			<br>
			<br>
		</fieldset>
		<input type="submit" value="Submit"> <input type="reset"
			value="Reset">

	</form>
</body>
</html>

