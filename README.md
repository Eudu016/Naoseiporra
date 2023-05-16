# Naoseiporra
Naosei
```html
<!DOCTYPE html">
<html>
<head>
	<title>Comprar Computador</title>
</head>
<body>
	<h1>Você vai comprar um computador para mim?</h1>
	<button onclick="nao()">Não</button>
	<button onclick>
<html>
<head>
	<title>Pergunta</title>
	<style type="text/css">
		body {
			display: flex; 
			flex-direction: column; 
			align-items: center;
			margin-top: 50px;
		}
		button {
			margin-top: 20px;
			padding: 10px 20px;
			font-size: 18px;
		}
	</style>
	<script type="text/javascript">
		function moverBotao() {
			var botao = document.getElementById("botao-nao");
			var novaPosicao = Math.floor(Math.random() * 3); // escolhe uma nova posição (0, 1 ou 2)
			var posicoes = ["left: 50px", "left: 200px", "left: 350px"]; // array com as posições possíveis

			botao.style = posicoes[novaPosicao]; // muda a posição do botão para a nova posição escolhida
		}
	</script>
</head>
<body>
	<h1>Vai comprar um computador para mim?</h1>
	<button>Sim</button>
	<button id="botao-nao" onclick="moverBotao()">Não</button>
</body>
</html>
```
