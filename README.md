# BIM_3rd_Sem
<!-- <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>

	<table border="1" cellspacing="0">
		<tr>
			<th>Actor</th>
			<th>Movies</th>
		</tr>
		<tr>
		<td rowspan="3">Tom Hanks</td>
		<td>Ne</td>
	</tr>
	<tr>
		
		<td>pa</td>
	</tr>
	<tr>
		<td>li</td>
	</tr>
			</table>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>
	<div>
		<label>Username:</label>
		<input type="text" name="Username">
	</div>
		<div>
		<label>Password:</label>
		<input type="Password" name="pass">
	</div>
		<div>
		<label>Gender:</label>
		<input type="radio" name="Gender" value="male">
		<label>Male</label>
		<input type="radio" name="Gender" value="Female">
		<label>Female</label>
	</div>
		<div>
		<label>Intrest:</label>
		<input type="radio" name="Intrest" value="Singing">
		<label>Singing</label>
		<input type="radio" name="Intrest" value="Travelling">
		<label>Traveling</label>
	</div>
		<div>
		<label>Photo Upload</label>
		<input type="file" name="photo">
	</div>
	<button type="btn">Submit</button>
	<button type="btn">Reset</button>
<script type="text/javascript">
	let x = parseInt(prompt("Enter first number"));
	let y =parseInt(prompt("Enter second number"));
	sum = x+y;
	document.write("\nThe sum is"+sum);
</script>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>
<form>
	
		<label>Username:</label>
		<input type="text" id="user">
		<label>Password:</label>
		<input type="password" id="pass">
		<label>Phone</label>
		<input type="number" id="phone">
	<input type="Submit" value="Log in" onclick="valid()">
</form>
	<script type="text/javascript">
	function  valid()
	{
		const user = document.getElementById("user").value;
		const Password = document.getElementById("pass").value;
		const Phone = document.getElementById("phone").value;
		if(user == "" || Password == "" || Phone == ""){
			alert("Insert the Data");
		}
		if(Password.length<6){
			alert("Password is too short");
		}
		if(Phone.length!== 10){
			alert("Please Insert Valid Number");
		}

	}
	</script>

</body>
</html> -->
<!-- 2016 -->
<!-- <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>
<form>
	Trim Number <input type="number" id="num"><br>
	Form Prepared By <input type="text" id="preparedby">
	<br><hr>
	Dept/Division<input type="text" id="dept"><br>
	Email <input type="email" id="mail"><br><hr>
	Visa Required
	Yes <input type="radio" id="Visa Required" value="Yes">
	No <input type="radio" id="Visa Required" value="No">
	<br>
	Visitor Visa type 
	<select value="Please select">
		<optgroup>Working</optgroup>
		<optgroup>Student</optgroup>
	</select>
	<hr>
	<input type="checkbox" id="email">Send Email<br>
	<button type="btn">SEND</button>
	<button type="btn">CLEAR</button>
	<script type="text/javascript">
		document.write(5+"5");
	</script>
</form>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>
	<form>
		<div>
			<label>Send To</label>
			<input type="email" name="Sendto">
		</div>
		<div>
			<label>CC</label>
			<input type="email" name="cc">
		</div>
		<div>
			<label>Subject</label>
			<input type="text" name="subject">
		</div>
		<div>
			<label>Attachment</label>
			<input type="file" name="attach">
		</div>
		<div>
			<label>Message</label>
			<textarea style="height: 30px; width:150px;"></textarea>
		</div>
		<button type="btn">Submit</button>
	</form>
</body>
</html> -->
<!-- Orchid Pre-Board Questions --> 
<!-- <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>3 no </title>
</head>
<body>
<table border="1" cellspacing="0">
	<tr>
		<th colspan="6">Table</th>
	</tr>
	<tr>
			<td rowspan="6">Hours</td>
			<td>Mon</td>
			<td>Tue</td>
			<td>Wed</td>
			<td>Thru</td>
			<td>Fri</td>
		
	</tr>
	<tr>
			
			<td>Science</td>
			<td>Math</td>
			<td>Science</td>
			<td>Math</td>
			<td>Arts</td>
	</tr>
		<tr>
			
			<td>Social</td>
			<td>History</td>
			<td>English</td>
			<td>Social</td>
			<td>Sports</td>
	</tr>
	<tr>
		<th colspan="5">Lunch</th>
	</tr>
	<tr>
		<td>Science</td>
		<td>Math</td>
		<td>Science</td>
		<td>Math</td>
		<td rowspan="2">Project</td>
	</tr>
	<tr>
		<td>Social</td>
		<td>History</td>
		<td>English</td>
		<td>Socail</td>
	</tr>
</table>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>4no question</title>
	<style type="text/css">
		.whole{
			background: grey;
			border: 1px solid ;
			height: 100vh;
			width: 100%;
		}
		.left60{
			background: gold;
			border: 1px;
			height: 100vh;
			width: 80%;
		}
		.red{
			height: 33vh;
			border: 1px;
			background: red;
			width: 50%;
			display: flex;
			float: left;
		}
		.green{
			height: 33vh;
			border: 1px;
			background: green;
			width: 50%;
			display: flex;
			float: left;

		}
		.blue{
			height: 33vh;
			border: 1px;
			background: blue;
			width: 100%;
			display: flex;
			float: left;
		}
			.orange{
			height: 34vh;
			border: 1px;
			background: orange;
			width: 50%;
			display: flex;
			float: left;
		}
		.purple{
			height: 34vh;
			border: 1px;
			background: purple;
			width: 50%;
			display: flex;
			float: left;

		}


	</style>
</head>
<body>
<div class="whole">
	<div class="left60">
		<div class="stline">
			<div class="red"></div>
			<div class="green"></div>
		</div>
		<div class="blue"></div>
		<div class="third">
			<div class="orange"></div>
			<div class="purple"></div>
		</div>
	</div>
	<div class="right40"></div>
</div>
</body>
</html> -->
<!--  <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>
<form>
	
		<label>Username:</label>
		<input type="text" id="user">
		<label>Password:</label>
		<input type="password" id="pass">
		<label>Confirm Password:</label>
		<input type="password" id="confi">
		<label>Phone</label>
		<input type="number" id="phone">
	<input type="Submit" value="Log in" onclick="valid()">
</form>
	<script type="text/javascript">
	function  valid()
	{
		const user = document.getElementById("user").value;
		const Password = document.getElementById("pass").value;
		const PasswordOne = document.getElementById("confi").value; 
		const Phone = document.getElementById("phone").value;
		if(user == "" || Password == "" || PasswordOne== "" || Phone == ""){
			alert("Insert the Data");
		}
		if(Password !== PasswordOne){
			alert("Confirm your password")
		}
		if(Password.length<8){
			alert("Password is too short");
		}
		if(Phone.startsWith("98") && Phone.length!== 10){
			alert("Please Insert Valid Number");
		}

	}
	</script>

</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Nagarjuna</title>
	<style type="text/css">
		.all{
			background: grey;
			border: 1px;
			height: 100vh;
			width: 100%;
		}
		.header{
			background: red;
			border: 1px;
			height: 10vh;
			width: 100%;
		}
		.nmenu{
			background: deepskyblue;
			border: 1px;
			height: 10vh;
			width: 100%;
		}
		.lcontent{
			background: yellow;
			border: 1px;
			height: 70vh;
			width: 20%;
			display: flex;
			float: left;
		}
		.mcontent{
			background: green;
			border: 1px;
			height: 70vh;
			width: 60%;
			display: flex;
			float: left;
		}
		.rcontent{
			background: brown;
			border: 1px;
			height: 70vh;
			width: 20%;
			display: flex;
			float: left;
		}
		.footer{
			background: red;
			border: 1px;
			height: 10vh;
			width: 100%;
		}


	</style>
</head>
<body>
<div class="all">
	<div class="header"></div>
	<div class="nmenu"></div>
	<div>
		<div class="lcontent"></div>
		<div class="mcontent"></div>
		<div class="rcontent"></div>
	</div>
	<div class="footer"></div>
</div>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>
<script type="text/javascript">

	let x = parseInt(prompt("Enter first number"));
	square = x*x;
	cube = square*x;
	final = (5++square);
	Finala = (6++cube);
	result = final+Finala;
	document.write("\nThe sum is"+result);

</script>

</body>
</html> -->
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>
<div>
	<label>Username:</label>
	<input type="text" id="name">
</div>
<div>
	<label>Password:</label>
	<input type="password" id="pass">
</div>
<input type="Submit" value="Log in" onclick="valid()">
<script type="text/javascript">
	function valid(){
	const user = document.getElementById("name").valid;
	const pass = document.getElementById("pass").valid;
	if(user == 'admin' && pass == 'nepal'){
		alert("User Authorized");
		break;
	}
	else{
		alert("Unauthorized User");
	}
}


</script>
</body>
</html>
