# ThaiBath
javascript แปลงค่าเงินจากตัวเลขเป็นตัวหนังสือ

ตัวอย่างโค้ด

<script src="thaibath.js" type="text/javascript" charset="utf-8"></script>
	<input type="text" id="number"  placeholder="">
	<button type="button" onclick="myFunction()">แปลง</button>
	<p id="text">ตัวอักษร</p>
	
	<script type="text/javascript">
		function myFunction(){
			var monney = document.getElementById("number").value;
			var thaibath = ThaiBaht(monney);
			document.getElementById("text").innerHTML  = thaibath;
		}
	</script>
