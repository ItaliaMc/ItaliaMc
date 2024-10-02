<!-- Documento HTML-->
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0" /><!-- Etiqueta para adaptar a @media -->
  <LINK REL="stylesheet" TYPE="text/css" HREF="estiloscalculadora.css"><!-- Enlace hoja estilos -->
</head>
<body>
<!-- Empieza codigo calculadora html-->
  <form name="calculator">
    <h3>Calculadora de Jesusmalave <a href="#">Manumelomama.com</a></h3>
    <p>Haz algun calculo para ver el resultado.</p>
    <input type="textfield" name="ans" value="">
    <br>
    <input type="button" value="1" onClick="document.calculator.ans.value+='1'">
    <input type="button" value="2" onClick="document.calculator.ans.value+='2'">
    <input type="button" value="3" onClick="document.calculator.ans.value+='3'">
    <input type="button" value="+" onClick="document.calculator.ans.value+='+'">
    <br>
    <input type="button" value="4" onClick="document.calculator.ans.value+='4'">
    <input type="button" value="5" onClick="document.calculator.ans.value+='5'">
    <input type="button" value="6" onClick="document.calculator.ans.value+='6'">
    <input type="button" value="-" onClick="document.calculator.ans.value+='-'">
    <br>
    <input type="button" value="7" onClick="document.calculator.ans.value+='7'">
    <input type="button" value="8" onClick="document.calculator.ans.value+='8'">
    <input type="button" value="9" onClick="document.calculator.ans.value+='9'">
    <input type="button" value="X" onClick="document.calculator.ans.value+='*'">
    <br>
    <input type="button" value="0" onClick="document.calculator.ans.value+='0'">
    <input type="reset" value="c">
    <input type="button" value="/" onClick="document.calculator.ans.value+='/'">
    <input type="button" value="=" onClick="document.calculator.ans.value=eval(document.calculator.ans.value)">
    </form>
</body>
</html>
<!-- Finaliza codigo calculadora html -->
 
 
<!-- Documento CSS-->
  <head>
    <style>
    
form {
  width: 100%;
  max-width: 400px;
  text-align: center;
  border: solid 1px #c2c2c2;
  padding-bottom: 10px;
  margin: auto;
  background: #fafafa;
}
input[type=textfield] {
    width: 75%;
    padding: 16px 32px;
    font-size: 16px;
    margin: 8px 0;
    border: 1px solid silver;
    border-radius: 1px;
    text-align: left;
    color: #333;
    background: #ccc;
}
input[type=button], input[type=submit], input[type=reset] {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 16px 32px;
    font-size: 16px;
    min-width: 21%;
    text-decoration: none;
    margin: 4px 2px;
    cursor: pointer;
}
input[type=button]:hover, input[type=submit]:hover, input[type=reset]:hover {
  background-color: #333;
}
<!-- Finaliza codigo calculadora CSS-->
