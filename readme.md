Redactor
========

Visit author website: http://imperavi.com/redactor

1) Installing
--------------

First clone this repo with:
	
	git clone https://github.com/AlexLeonVader/redactor.git .

Add jquery.min.js, redactor.css and redactor.js to your html:
	
	...
		<script src="jquery.min.js"></script>
		<script src="redactor.js"></script>
		<link rel="stylesheet" href="redactor.css">
	</body>

Initialize with: 

	<script type="text/javascript">
		$(function(){
	  		$('#example').redactor();
		});
	</script>

Add your textarea:

	<textarea id="example" cols="30" rows="10"></textarea>

Finaly you'll have some like this: 

	<head>
		<script src="jquery.min.js"></script>
		<script src="redactor.js"></script>
		<link rel="stylesheet" href="redactor.css">
		<script type="text/javascript">
			$(function(){
		  		$('#example').redactor();
			});
		</script>
	</head>
	<body>
		<textarea id="example" cols="30" rows="10"></textarea>
	</body>

Final result:

![alt tag](https://raw.githubusercontent.com/AlexLeonVader/redactor/master/preview.png)
