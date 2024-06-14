<html>
	<head>
		<title>스킨표</title>
	</head>
	<body>
		<img id="aa1" src="melly_1.png" width=100 height=150 
			align="left" border="3" alt="오류"/>
		<img id="aa1_" src="melly_01.png" width=100 height=150 
			align="left" border="3" alt="오류"/>
	</body>
	
	<script src="https://code.jquery.com/jquery-3.5.1.js" integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc=" crossorigin="anonymous"></script>
 
	<script>
    $(document).ready(function(){
            /*웹페이지 열었을 때*/
            $("#aa1").show();
            $("#aa1_").hide();
 
            /*img1을 클릭했을 때 img2를 보여줌*/
            $("#aa1").click(function(){
                $("#aa1").hide();
                $("#aa1_").show();
            });
 
            /*img2를 클릭했을 때 img1을 보여줌*/
            $("#aa1_").click(function(){
                $("#aa1").show();
                $("#aa1_").hide();
            });
        });
</script>
</html>
