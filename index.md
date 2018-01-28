<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<link rel="stylesheet" type="text/css" href="css/style.css">
<title>搜索框1-3</title>
<style type="text/css">
	header,#sidebar{display:none}
	#main-content {
	    float: none;
	    width: auto;
	}
	
	body{background:#333;}
	.bg-div{background-image: url(river.jpg);
		width:1228px;height:690px;
		margin:0 auto;
		position: relative;}
	.logo{background-image: url(logo.png);
		width:107px;height:53px;float: left;
		margin: -4px 18px 0 0}
	form{float: left; background-color: #fff;padding: 5px;}
	.search-input-text{border:0;float: left;
		height: 25px;line-height: 25px;
		outline: none; width: 350px;}
	.search-input-button{border:0;float: left;
		background-image: url(search-button.png);
		width: 29px;height: 29px;}
	.search-box{position: absolute; top: 200px; left: 300px;}
</style>
</head>

<body>
	<div class="bg-div">
		<div class="search-box">
			<div class="logo"></div>
			<form>
				<input type="text" class="search-input-text">
				<input type="submit" class="search-input-button" value="">
			</form>
		</div>
	</div>
	
	<script type="text/javascript">
	    let mainContent = document.getElementById('main-content');
	    document.body.appendChild(mainContent);
	</script>
</body>
</html>
