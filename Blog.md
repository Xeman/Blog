# Blog

<html>
<head>
	<link rel="stylesheet" type="text/css" href="css/style.css">
	<script type="text/javascript" src="js/javascript.js"></script>
	<title>BLOG</title>
</head>
<body>
	<div><center id="head">Create Blog</center></div>
	<article id="main">
		<div>
			<label>TITLE: </label>
			<input type="textbox" name="TITLE" size="66" id="title" autofocus>
			<br><br>
		</div>
		<div>
			<label>AUTHOR: </label><br> 
			<pre id="name">Firstname:         <input type="textbox" name="firstname" size="55" id="fname" autofocus></pre>
			<pre id="name">Middlename:    <input type="textbox" name="middlename" size="55" id="mname" autofocus></pre>
			<pre id="name">Lastname:         <input type="textbox" name="lastname" size="55" id="lname" autofocus></pre>
		</div>
		<div>
			<label>CONTENT: </label><br>
			<textarea id="content" cols="48" rows="10" placeholder="type text here....." autofocus></textarea>
		</div>
		<div>
			<br>
			<button onclick="postBlog();"> SUBMIT </button><br><br>
		</div>
		<div>
			<article id="result">
				<h1 id="input_title"> </h1>
				<h3 id="input_author"> </h3>
				<p id="input_content"> </p>
			</article>
		</div>
		
	</article>
</body>
</html>
