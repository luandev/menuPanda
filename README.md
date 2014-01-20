menuPanda
=========

<<<<<<< .mine
simple one page menu jquery plugin
Um plugin simples para adicionar um menu em sua p·gina.

O que È?
=========
Um menu animado em css3 e jquery que funciona como o 
menu do app do facebook, no lugar da estrutura do menu
aparece um Ìcone, esse Ìcone chama uma barra lateral.

Como Usa?
=========
$(document).ready(function(){
	$("#menu").pandfy();
});

ATEN«¬O: … importante que todos os plugins sejam chamados depois do pandfy();
vocÍ pode coloc·-los na mesma chamada tipo:

$(document).ready(function(){
	//padfy() vem primeiro!:
	$("#menu").pandfy();
	
	//aqui vc pıe todas as outras chamadas
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
			<li><a href="#">e assim sucetivamente...</a></li>	
		</ul>
	</ul>
</nav>


Como Instala?
=========
1 - adicione o jquery
snippet: <script src="//ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>

2 - Baixe a pasta JS para seu servidor e adicione o menuPanda a sua p·gina
snippet: <script src="js/menuPanda.min.js"></script>

3 - Copie a pasta css no mesmo direitorio da pasta JS

4 - Copie as imagens para a pasta img na mesma localizaÁ„o da pasta JS
vocÍ pode modifica-las para adaptarem-se ao seu layout=======
Um menu animado em CSS3 e jQuery que funciona como o 
menu do app do Facebook, no lugar da estrutura do menu
aparece um √≠cone, esse √≠cone chama uma barra lateral.

Como Usa?
=========
√â facil, veja:

	$(document).ready(function(){
		$("#menu").pandfy();
	});

mas ATEN√á√ÉO: √â importante que todos os Plugins sejam chamados depois do pandfy();
voc√™ pode coloc√°-los na mesma chamada tipo:

	$(document).ready(function(){
	
		//pandfy() vem primeiro!:
		$("#menu").pandfy();
		
		//aqui vc p√µe todas as outras chamadas
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

2 - Baixe a pasta JS para seu servidor e adicione o menuPanda a sua p√°gina
snippet: <script src="js/menuPanda.min.js"></script>

3 - Copie a pasta CSS no mesmo diret√≥rio da pasta "js"

4 - Copie as imagens para a pasta "img" na mesma localiza√ß√£o da pasta "js"
voc√™ pode modifica-las para adaptarem-se ao seu layout


Quem Fez?
=========

Luan Citt√°
https://www.facebook.com/luan.citta
>>>>>>> .r4
