# <!DOCTYPE html>

<!-- Nome
Leticia Barros lourenço 3A-->
<html lang="pt-BR">
<head>

<meta charset="UTF-8">

<title>Conferir quais números são primos</title>

<script>








function Primos() {
var N1 = parseInt(document.getElementById("numero1").value, 10);
var canvas = document.getElementById("MeuCanvas");
var ctx = canvas.getContext("2d");
ctx.clearRect(0, 0, canvas.width, canvas.height);
ctx.font = "40px Helvetica";
ctx.fillStyle = "yellow”;
var resultado = '';
if (N12) {
resultado = N1 +" não é primo";
else {
var primo = true;
for (var contador = 2; contador <= Math.sqrt(N1); contador++) {
if (N1 % contador === 0) {
primo = false;
break;

}   }


if (primo){

resultado N1+"é primo";

}

else{

resultado = N1 +" não é primo";
}

}


 }
  </head>
ctx.fillText(resultado,70, 110);
</script>
 <body>

<label for="numero1">É primo?</label>

<input type="numero" id="numero1"><br><br>


<button onclick="Primos()">Calcular</button><br><br>

<canvas id="MeuCanvas" width="400" height="400”style="border:2px solid #808080; background-color: blue;"></canvas>
</body>
 </html>