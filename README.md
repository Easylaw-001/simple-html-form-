<!DOCTYPE html>
<html>
<head>
	<title>Simple Form Example</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>

	<h2>Simple Form</h2>

	<form action="#" method="POST">
		<label for="name">Name:</label>
		<input type="text" id="name" name="name" required><br><br>

		<label for="email">Email address:</label>
		<input type="email" id="email" name="email" required><br><br>

		<label for="phone">Phone number:</label>
		<input type="tel" id="phone" name="phone" required><br><br>
		
		<label for="gender">Gender:</label>
		<br>
		<br>
		
		<div class="gender">
		<label for="male">Male</label>
		<input type="radio" id="male" name="gender" value="male" required>
		</div>
		
		<div class="gender">
		<label for="female">Female</label>
		<input type="radio" id="female" name="gender" value="female">
		</div>
		
		<div class="gender">
		<label for="other">Other</label>
		<input type="radio" id="other" name="gender" value="other">
		</div>
 
 
                 <label for="password">Password:</label>
		<input type="password" id="password" name="password" required><br><br>

		<input type="submit" value="Submit">
	</form>

</body>
</html>
