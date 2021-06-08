# registration-form
this is a registration form using html. it is created in html
it consist of student's name,email,phone_no,photo,city,address  etc.


<!DOCTYPE html>
<html>
<center>
<head>
	<title>Student Registration Form</title>
</head>
<body bgcolor="#FF7F50">
	<form method="get">
		<h2><u>Student Registration Form</u></h2>
		<table bgcolor="#FFDAB9">
			<tr>
				<td>First Name :- </td>
				<td><input type="text" name="fname" placeholder="first name"> (max 30 character a-z or A-Z)</td>
			</tr>
			<tr>
				<td>Last Name :- </td>
				<td><input type="text" name="lname" placeholder="last name"> (max 30 character a-z or A-Z)</td>
			</tr>
			<tr>
				<td>Date of Birth :- </td>
				<td><input type="date" name="date"></td>
			</tr>
			<tr>
				<td>Email :- </td>
				<td><input type="email" name="email_id"></td>
			</tr>
			<tr>
				<td>Phone Number :- </td>
				<td><input type="text" name="phone_no" placeholder="10 digit number"></td>
			</tr>
			<tr>
				<td>Gender :- </td>
				<td><input type="radio" name="gender" value="male">Male</td>
				<td><input type="radio" name="gender" value="female">Female</td>
			</tr>
			<tr>
				<td>Upload Photo :- </td>
				<td><input type="file" name="photo"></td>
			</tr>
			<tr>
				<td>Address :- </td>
				<td><textarea cols="60" rows="5"></textarea></td>
			</tr>
			<tr>
				<td>City :- </td>
				<td><input type="text" name="city"></td>
			</tr>
			<tr>
				<td>Pin Code :- </td>
				<td><input type="text" name="pin_code"></td>
			</tr>
			<tr>
				<td>State :- </td>
				<td><select name="state">
				    <option>Select</option>
				    <option>Andhra Pradesh </option>
				    <option>Arunachal Pradesh</option>
				    <option>Assam</option>
				    <option>Bihar</option>
				    <option>Chhatisgarh</option>
				    <option>Goa</option>
				    <option>Haryana</option>
				    <option>Himachal Pradesh</option>
				    <option>Jharkhand</option>
				    <option>Bihar</option>
				    <option>Karnataka</option>
				    <option>Kerela</option>
				    <option>Madhya Pradesh</option>
				    <option>Maharashtra</option>
				    <option>Manipur</option>
				    <option>Meghalaya</option>
				    <option>Mizoram</option>
				    <option>Nagaland</option>
				    <option>Odisha</option>
				    <option>Punjab</option>
				    <option>Rajasthan</option>
				    <option>Sikkim</option>
				    <option>Tamil Nadu</option>
				    <option>Telangana</option>
				    <option>Tripura</option>
				    <option>Uttarakhand</option>
				    <option>Uttar Pradesh</option>
				    <option>West Bengal</option>
				    </select></td>
			</tr>
			<tr>
				<td>Country :- </td>
				<td><input type="text" name="country" value="India"></td>
			</tr>
			<tr>
				<td>Qualifications :- </td>
				<td><table border="1" bgcolor="white">
					<tr>
						<th>S.no</th>
						<th>Examination</th>
						<th>Board</th>
						<th>Percentage</th>
						<th>Year of Passing</th>
					</tr>
					<tr>
						<td>1</td>
						<td>10th</td>
						<td><input type="text" name="qualification"></td>
						<td><input type="text" name="qualification"></td>
						<td><input type="text" name="qualification"></td>
					</tr>
					<tr>
						<td>2</td>
						<td>12th</td>
						<td><input type="text" name="qualification"></td>
						<td><input type="text" name="qualification"></td>
						<td><input type="text" name="qualification"></td>
					</tr>
				</table></td>
			</tr>
			<tr>
				<td>Courses applied for :-</td>
				<td><input type="radio" name="course"> Btech </td>
				<td><input type="radio" name="course"> Bcom </td>
				<td><input type="radio" name="course"> B.Sc </td>
				<td><input type="radio" name="course"> BCA </td>	
			</tr>
		</table><br>
		<div>
			<input type="Submit" name="Submit">
			<input type="Reset" name="Reset">
		</div>
	</form>
</body>
</center>
</html>
