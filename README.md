# CSS-Position
Membuat 3 kolom dengan CSS Position
<!DOCTYPE html>
<html>
<head>
	<title>Layout 3 kolom dengan CSS Position</title>
<style type="text/css">
	#halaman {
	width: 980px;
	margin: 0 auto;
}

#header {
	height: 100px;
	padding: 10px;
	background-color: #cccccc;   
}

#kiri {
	height: 100px;
	padding: 10px;
	background-color: #cccccc;
	float: left;
	width: 250px;
	margin-top: 10px;
}

#kanan {
	height: 100px;
	padding: 10px;
	background-color: #cccccc;
	float: right;
	width: 250px;
	margin-top: 10px;
}

#tengah {
	height: 100px;
	padding: 10px;
	background-color: #cccccc;
	margin: 10px 290px 0 290px;
}

#footer {
	clear: both;
	height: 50px;
	padding: 10px;
	background-color: #cccccc;
	margin-top: 10px;
}
</style>
</head>
<body>
<div id="halaman">
	<div id="header">HEADER</div>
	<div id="kiri">KIRI</div>
	<div id="kanan">KANAN</div>
	<div id="tengah">TENGAH</div>
	<div id="footer">FOOTER</div>	
</div>
</body>
</html>
