# RT_11_Tonenchuk
<!DOCTYPE html>
<html>
<head>

<script src="http://code.jquery.com/jquery-latest.js"></script>

<script>	 		
	$(document).ready(function () {
		$("button").click(function () {
		var i=0;
		
             do{
		$('#div1').delay(150);
		$('#div2').delay(150);
		$('#div3').delay(150);
		$('#div4').delay(150);
		$('#div5').delay(150);
		
                if(i==0){
		$("#div1").fadeIn();}
		i++;		
		
                if(i==4){
		$("#div2").fadeIn();}
		
                if(i==8){
		$("#div3").fadeIn();}
		
                if(i==12){
		$("#div4").fadeIn();}
		
                if(i==16){
		$("#div5").fadeIn();}
		
                if(i==20){
		$("#div5").fadeOut();}
		
                if(i==24){
		$("#div4").fadeOut();}
		
                if(i==28){
		$("#div3").fadeOut();}
		
                if(i==32){
		$("#div2").fadeOut();}
		
                if(i==36){
		$("#div1").fadeOut();
		i=0;}
}
		while(i<37)
		});
});
</script>

</head>
<body>
<div id="div1" style="width:40px;height:40px;float:left;display:none;background-color:blue;"></div>
<div id="div2" style="width:40px;height:40px;float:left;display:none;background-color:green;"></div>
<div id="div3" style="width:40px;height:40px;float:left;display:none;background-color:black;"></div>
<div id="div4" style="width:40px;height:40px;float:left;display:none;background-color:fuchsia;"></div>
<div id="div5" style="width:40px;height:40px;float:left;display:none;background-color:red;"></div>
</body>
<br><br>
<button>Запуск</button>
</html>
