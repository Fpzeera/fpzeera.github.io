<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Planos de música</title>
        <style>
            body {
                text-align: center;
            }
            h1 {
                margin-top: 30px;
            }
            .titulo {
                font-size: 26px;
                color: black;
                text-align: center;
                background-color: rgb(255, 255, 255);
                padding: 20px;
                border: 2px solid black;
                border-radius: 25px;
                max-width: 1200px;
                margin: auto;
                margin-top: 30px;
                margin-bottom: 30px;
            }
            .margem {
                display: flex;
                flex-wrap: wrap;
                justify-content: center;
                max-width: 1200px;
                margin: auto;
            }
            .plano {
                background-color: #f8f8f8;
                border: 1px solid #ccc;
                border-radius: 5px;
                box-shadow: 0 0 5px rgba(0, 0, 0, 0.3);
                margin: 10px;
                width: 30%;
                min-width: 300px;
            }
            .plano-basico .plano-geral {
                background-color: #4CAF50;
                color: #fff;
            }
            .plano-normal .plano-geral {
                background-color: #800080;
                color: #fff;
            }
            .plano-avancado .plano-geral {
                background-color: #1E90FF;
                color: #fff;
            }
            .plano-geral {
                font-weight: bold;
                padding: 10px;
                text-align: center;
                border-top-left-radius: 5px;
                border-top-right-radius: 5px;
            }
            .plano-gerall {
                padding: 20px;
                text-align: center;
            }
            .plano-valores {
                font-size: 32px;
                margin: 10px 0;
            }
            .plano-informativo {
                text-align: left;
                margin-top: 20px;
            }
            .plano-informativo li {
                margin: 10px 0;
            }
            .plano-botoes {
                display: inline-block;
                padding: 10px 20px;
                background-color: #4CAF50;
                color: #fff;
                text-align: center;
                text-decoration: none;
                font-size: 16px;
                border-radius: 10px;
                box-shadow: 0 0 7px rgba(0, 0, 0, 0.3);
                margin-top: 10px;
            }
        </style>
</head>
<body>
    <h1 class="titulo">Planos de Música</h1>
	<div class="margem">
		<div class="plano plano-basico">
			<div class="plano-geral">Básico</div>
			<div class="plano-gerall">
				<div class="plano-valores">R$ 25,00</div>
				<ul class="plano-informativo">
					<li>1 dispositivo</li>
					<li>Sem propaganda</li>
					<li>Acesso a 10 milhões de músicas</li>
					<li>Reprodução em qualidade padrão</li>
					<li>Streaming online</li>
				</ul>
				<a href="#" class="plano-botoes">Comprar</a>
			</div>
		</div>
		<div class="plano plano-normal">
			<div class="plano-geral">Normal</div>
			<div class="plano-gerall">
				<div class="plano-valores">R$ 55,00</div>
				<ul class="plano-informativo">
					<li>3 dispositivos</li>
					<li>Sem propaganda</li>
					<li>Acesso a 50 milhões de músicas</li>
					<li>Reprodução em qualidade padrão</li>
					<li>Streaming online</li>
				</ul>
				<a href="#" class="plano-botoes">Comprar</a>
			</div>
		</div>
		<div class="plano plano-avancado">
			<div class="plano-geral">Avançado</div>
			<div class="plano-gerall">
				<div class="plano-valores">R$ 100,00</div>
				<ul class="plano-informativo">
					<li>5 dispositivos</li>
					<li>Sem propaganda</li>
					<li>Acesso a mais de 100 milhões de músicas</li>
					<li>Reprodução em alta qualidade</li>
					<li>Streaming online e offline</li>
				</ul>
				<a href="#" class="plano-botoes">Comprar</a>
			</div>
		</div>
	</div>
</body>
</html>
