<?php
	
	include_once("db.php");
	
	$sql = "INSERT INTO book(name,noofppl,datefrom,dateto,tripint,email,phone,notes) VALUES ('$_POST[name]', '$_POST[noofppl]', '$_POST[datefrom]', '$_POST[dateto]', '$_POST[tripint]'. '$_POST[email]', '$_POST[phone]', '$_POST[notes]')";

	if(!mysqli_query($con,$sql))
	{
		die('Error : '.mysqli_error($con));
	}
	else
	{
		echo "<script>alert('Submitted successfully !!!');</script>";
		echo "<script>window.location = 'index.html';</script>";
	}
	mysqli_close($con);
?>