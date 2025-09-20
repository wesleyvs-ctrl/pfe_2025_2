# pfe_2025_2
<!DOCTYPE html>
<html lang="pt-br">
<head>https://code.visualstudio.com/download
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Front-end</title>
</head>
<body>
   <h1>Front-end - 19/09/25</h1>
   <div id="saida"></div>
   <div id="saida1">Saida1 e </div>
   <div class="azul">Texto na cor azul</div>
   <script>
    let saida = document.getElementById("saida");
    let calc;
    let num1 = parseInt(prompt("Digite o primeiro numero:"));//2.5
    let num2 = parseInt(prompt("Digite o segundo numero:"));//3.5
    calc=num1+num2;
    saida.innerHTML="<br>Num1"+num1
    saida.innerHTML="<br>Num2"+num2
    saida.innerHTML="<br>Calc:"+num1;
    saida.innerHTML+="<br>Soma: "+(num1+num2);
    

   </script>

   <script>
    document.getElementById("saida").innerHTML="Agora vai<br>";
    document.getElementById("saida").innerHTML+="Já foi<br>";
    document.getElementById("saida").innerHTML+="E foi mesmo!!";

    document.querySelector("h1").innerHTML+=" - Javascript";
    document.querySelector("div").innerHTML+=" - Javascript";
    document.querySelector("#saida1").innerHTML+=" - Javascript";

    document.querySelector(".azul").innerHTML+=", será??";

    document.querySelector(".azul").style.color="blue";
    document.querySelector("#saida1").style.color="red";
    document.querySelector("#saida").style.color="green";
    document.querySelector("h1").style.color="orange";

   </script>
</body>
</html>