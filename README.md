# ToStudy
About Virtual Hotels.

O jogo "Habbinfo" é um jogo de aventura em que o jogador controla um personagem que viaja pelo mundo, enfrentando inimigos e desafiando os monstros que o rodeiam. O jogo é baseado em fatos reais e tem o objetivo de ser um jogo educativo para crianças e adolescentes.

Para criar este jogo, você precisará de um editor de texto, um navegador web e um pouco de conhecimento em JavaScript.

O jogo consiste em:

1. Cena inicial: A cena inicial do jogo contém o personagem, que começa na cidade de Habbinfo. O jogador pode escolher entre iniciar uma nova partida ou carregar uma partida salva.

2. Cena de jogo: A cena de jogo é onde o jogador interage com o mundo. O jogador pode andar pelas ruas, atravessar os caminhos, atacar inimigos e derrotar monstros.

3. Cena de fim de jogo: A cena de fim de jogo aparece quando o jogador venceu o jogo. Ela contém uma mensagem de vitória e as opções de iniciar uma nova partida ou carregar uma partida salva.

4. Cena de opções: A cena de opções contém as configurações do jogo, como a dificuldade do jogo, o volume do som e a fonte do texto.

5. Cena de créditos: A cena de créditos mostra os desenvolvedores do jogo e as fontes dos textos.

6. Cena de salvar jogo: A cena de salvar jogo permite que o jogador salve o progresso do jogo.

7. Cena de carregar jogo: A cena de carregar jogo permite que o jogador carregue uma partida salva.

Abaixo, você pode ver um exemplo de como criar o jogo "Habbinfo" em JavaScript:

HTML:

html
<!DOCTYPE html>
<html>
<head>
	<title>Habbinfo</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" type="text/css" href="style.css">
	<script src="script.js"></script>
</head>
<body>
	<div id="game"></div>
	<div id="menu">
		<button id="new-game">Novo Jogo</button>
		<button id="load-game">Carregar Jogo</button>
		<button id="options">Opções</button>
		<button id="credits">Créditos</button>
	</div>
</body>
</html>

CSS:

css
body {
	margin: 0;
	padding: 0;
	font-family: Arial, sans-serif;
	background-color: #f2f2f2;
}

#game {
	position: absolute;
	top: 50px;
	left: 50px;
	width: 800px;
	height: 600px;
	background-color: #fff;
	border: 1px solid #ccc;
	box-shadow: 0px 0px 10px #ccc;
}

#menu {
	position: absolute;
	top: 50px;
	left: 50px;
	width: 300px;
	height: 50px;
	background-color: #fff;
	border: 1px solid #ccc;
	box-shadow: 0px 0px 10px #ccc;
	display: none;
}

#new-game, #load-game, #options, #credits {
	position: absolute;
	top: 5px;
	left: 5px;
	width: 100px;
	height: 30px;
	background-color: #4CAF50;
	color: #fff;
	border: none;
	border-radius: 5
