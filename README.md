<!DOCTYPE html>
<html>
<head>
	<title>Javascript 기초</title>

</head>
<body>
	<h5>[변수 연습]</h5>
	<script type="text/javascript">
		var num=3;
		num+=5;
		document.write(num);

		var str="파랑색";
		document.write("<p>"+str+"</p>");		
	</script>

	<h5>[배열 및 반복문 연습]</h5>
	<script type="text/javascript">
		var strDrink = new Array();
		strDrink[0]="커피";
		strDrink[1]="홍차";
		strDrink[2]="녹차";
		var i=0;
		for(i=0; i<=2; i++){
			document.write(i+". "+strDrink[i]+"<br>");
		}
	</script>
	
	<h5>[조건문 연습]</h5>
	<script type="text/javascript">
		var dtDate=new Date();
		var dtHour=dtDate.getHours();
		document.write(dtHour+"시 현재 ");
		if(dtHour>=6 && dtHour<=10){
			document.write("<b>Good Morning!</b>");
		} else {
			document.write("<b>How are you?</b>");
		}
	</script>

</body>
</html>
