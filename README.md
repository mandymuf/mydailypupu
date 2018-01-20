# mydailypupu
<!DOCTYPE html>
<html>
	<head>
		<title>Calculator</title>
		<link rel="stylesheet" type="text/css"href="calculator.css" />
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
		
		
	</head>
<body>


 
  
<div class="container">
	<h2>Calculator</h2>
	
    <table>
        <tr>
            <td colspan="4" id="display">0</td>
        </tr>
        <tr>
            <td colspan="3"><button onclick="inputBtn(this);" id="clear">C</button></td>
            <td><button onclick="inputBtn(this);">/</button></td>
        </tr>
        <tr>
            <td><button onclick="inputBtn(this);" class="btn">7</button></td>
            <td><button onclick="inputBtn(this);" class="btn">8</button></td>
            <td><button onclick="inputBtn(this);" class="btn">9</button></td>
            <td><button onclick="inputBtn(this);" class="btn">*</button></td>
        </tr>
        <tr>
            <td><button onclick="inputBtn(this);" class="btn">4</button></td>
            <td><button onclick="inputBtn(this);" class="btn">5</button></td>
            <td><button onclick="inputBtn(this);" class="btn">6</button></td>
            <td><button onclick="inputBtn(this);" class="btn">-</button></td>
        </tr>
        <tr>
            <td><button onclick="inputBtn(this);" class="btn">1</button></td>
            <td><button onclick="inputBtn(this);" class="btn">2</button></td>
            <td><button onclick="inputBtn(this);" class="btn">3</button></td>
            <td><button onclick="inputBtn(this);" class="btn">+</button></td>
        </tr>
        <tr>
            <td><button onclick="inputBtn(this);" class="btn">0</button></td>
            <td><button onclick="inputBtn(this);" class="btn">.</button></td>
            <td colspan="2"><button onclick="inputBtn(this);" id="equals">=</button></td>
        </tr>
    </table>

<script type="text/javascript" src="calculator.js"> 

</script>

</div>

</body>

</html>
