menuPanda
=========

Um menu animado em CSS3 e jQuery que funciona como o 
menu do app do Facebook, no lugar da estrutura do menu
aparece um ícone, esse ícone chama uma barra lateral.

Como Usa?
=========

É bem simples veja:

	$(document).ready(function(){
		$("#menu").pandfy();
	});

mas atenção! É importante que todos os Plugins sejam chamados depois do pandfy();
você pode colocá-los na mesma chamada tipo:

	$(document).ready(function(){
		//pandfy() vem primeiro!:
		$("#menu").pandfy();
		
		//aqui vc põe todas as outras chamadas
		$('#shuffle').cycle({ 
			fx:     'shuffle', 
			easing: 'easeOutBack', 
			delay:  -4000 
		});
	});

lembrando que a estrutura deve ser

	<nav id="nomeDoMenu">
		<ul data-title="Aba Principal">
			<li><a href="#">link interno ou externo</a></li>
			<ul data-title="titulo do submenu">
				<li><a href="#">e assim suscetivamente...</a></li>	
			</ul>
		</ul>
	</nav>


Como Instala?
=========

1 - adicione o jquery
snippet: <script src="//ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>

2 - Baixe a pasta JS para seu servidor e adicione o menuPanda a sua página
snippet: <script src="js/menuPanda.min.js"></script>

3 - Copie a pasta CSS no mesmo diretório da pasta "js"

4 - Copie as imagens para a pasta "img" na mesma localização da pasta "js"
você pode modifica-las para adaptarem-se ao seu layout

Quem Fez/tá fazendo?
=========

Luan Cittá
https://www.facebook.com/luan.citta
