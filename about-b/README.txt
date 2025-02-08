	
/* extensão no VS-Code: live server, para abrir uma pagína de navegador ao lado*/

css:

	:root {
	--branco-principal: #FFFFFF;
	--cinza-secundario: #C0C0C0;
	--botao-zul: #167bf7;
	--cor-de-fundo: #00030;
	}

	body {
	background-color: var(--cor-de-fundo);
	color: var(--branco-principal);
	}

	* {
	margin: 0;
	padding: 0;
	}

	/*No css adicione uma imagem de fundo, apenas decorativa vai no css, que não afeta o usuário*/
	
	/*Obs. se for uma imagem só decorativa utilize no "css background-image" */
	/*mas se for image com relevancio para o usuário utilize "img" */

	.principal {
	background-image: url("img/imagem-fundo.png");
	background-repeat: no-repeat;
	background-size:container;   /*Tamanho da imagem de fundo/espaçamento da esquerda */
	
	}

	.container {
	height:100vh;        /* altura, para ocupar a tela inteira o vh detecta a altura da tela do dispositivo, qual altura da pagina*/
	}

	
	HTML:

	<section class=" container principal">
	<h1>Trabalhando com imagem...</h1>
	<figure>
		<figcaption>
     <h3>Para inserir uma image, você deve digitar: <img src="image-aqui.png" alt="descriçao-image"</h3>
		</figcaption>

	<img src"img/foto.logo.png" alt="logo marca da empresa...">
	</figure>
	</section>

	Mais informções sobre o que é HTML e suas tags?

	https://www.alura.com.br/artigos/o-que-e-html-suas-tags-parte-1-estrutura-basica

	------------------------------------------------------------------------------------------------------

css:

	  <link rel="stylesheet" href="style.css">

	--------------------------------------------

	   :root {
       --branco-principal: #FFFFFF;
       --cinza-secundario: #C0C0C0;
       --botao-azul: #167BF7;
   }

   /* Exemplo de aplicação */
   h1 {
       color: var(--branco-principal);
   }
   p {
       color: var(--cinza-secundario);
   }
   .botao {
       background-color: var(--botao-azul);
   }

	   * {
       margin: 0;
       padding: 0;
   }

  /*utilizando imagem de fundo no css:*/
	     .main-section {
         background-image: url("img/Background.png");
         background-size: cover;
         background-repeat: no-repeat;
     }


   /* Restante do arquivo CSS */
--------------------------------------

html:  

	Inserindo imagem na tag img:

	<img src="img/Promo.png" alt="Descrição da imagem promocional">	
	
	-------------------------Fim-do-primeira-aula----------------------

	02. A dupla HTML e CSS:

	Botão quando se usa? 

	Um botão se usa quando vai dar uma preferência que vai chamar alguma função no clique do botão, quando
	a questão de querer clicar em um link para ir para outra pagína do mesmo site ou para outra <section>,
	preferivel usar uma ancora <a href=""></a> por impressões de SEO.

	use o botão quando ativar alguma coisa.
	
	O uso da ãncora? Ela vai ser utilizada no css e vai ficar ingual ao botão.

	É uma questão de estética esse botão.
	Parece um botão então chamo de botão...

	Utilizando a ancora <a href="www.alura.com.br" target="_black"  class="container__botao">alura</a>

css:

	.container__botao {
	background-color: var(--botao-azul);
	border-radius: 5px;
	padding: 1rem;		 /*ou 1em;*/
	}

	===============REVISANDO=ALGUMAS=INFORMAÇÕES=============

		<meta charset="utf-8"> <!--resolver problemas com acentuação -->
         <meta name="author" content="Antônio Cezar de Oliveira"><!-- Define o autor da pagina -->
         <meta name="keywords" content="posicionamento, css, avançado"> <!--Palavras chaves do site -->
         <meta name="description" content="cursos"><!--descrição do site -->
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="shortcut icon" href="about-b/ico/favicon-2.ico" type="image/x-icon"><!--Linkando o ico -->
	<link rel="stylesheet" href="estilo3.css">	<!--Adicionando o estilo css na pagína -->	

	=============display:grid;===================diferente=de=display:flex;

	https://www.alura.com.br/artigos/criando-layouts-com-css-grid-layout

	---------------------------------------------------------------------------------------------------

	3) Ajustando o layout com grid CSS
	Suponha que você está trabalhando no desenvolvimento front-end de um site e se depara com um
	 problema de layout: um botão que está ocupando mais espaço do que deveria. Sua tarefa é corrigir
	 esse problema utilizando CSS Grid. Para isso, você deve modificar a classe .container no arquivo
	 styles.css, definindo display: grid e ajustando o grid-template-columns para que o botão ocupe 
	apenas o espaço necessário. Além disso, experimente com diferentes configurações de colunas, 
	como 50% 50% e 33% 33% 33%, para observar as mudanças no layout.

-------------------------------------------------------------------------------------------------------

			Trabalhando com botões:


	1) Criando um botão estilizado com CSS
Você trabalha com desenvolvimento web e está seguindo um projeto para criar uma página
 com base em um design do Figma. Sua tarefa agora é estilizar um botão que, na verdade, é uma
 tag <a> transformada visualmente em botão. Use o CSS para dar a esta âncora a aparência
 desejada, baseando-se nas instruções do vídeo.

2) Ajustando o layout do botão
Agora que o botão está estilizado, você percebe que ele está alinhado ao lado de uma
 imagem, mas no design do Figma, ele deve estar abaixo dela. Seu desafio é ajustar 
o layout para que o botão apareça na posição correta.

Examine a estrutura HTML para entender como a imagem e o botão estão organizados.
Use o CSS para alterar o comportamento de exibição dos elementos, se necessário.
Considere a possibilidade de ajustar a propriedade display da imagem ou do contêiner 
que envolve tanto a imagem quanto o botão.
Faça os ajustes necessários para que o botão apareça abaixo da imagem, conforme o design.
3) Ajustando o layout com grid CSS
Suponha que você está trabalhando no desenvolvimento front-end de um site e se depara 
com um problema de layout: um botão que está ocupando mais espaço do que deveria. 


Sua tarefa é corrigir esse problema utilizando CSS Grid. Para isso, você deve modificar a classe
 .container no arquivo styles.css, definindo display: grid e ajustando o grid-template-columns para 
que o botão ocupe apenas o espaço necessário. Além disso, experimente com diferentes configurações
 de colunas, como 50% 50% e 33% 33% 33%, para observar

 as mudanças no layout.

4) Criando um botão secundário com CSS
Você precisa criar um segundo botão para o site que está trabalhando, o qual deve ter características
 visuais distintas do botão principal. No arquivo index.html, adicione um novo elemento âncora (<a>)
 com a classe botao_secundario. No arquivo styles.css, defina o estilo para .botao_secundario, alterando

 o background-color para transparente e adicionando uma borda com 2px solid var(--branco-principal).
 Ajuste também outros atributos conforme necessário para que este botão secundário tenha uma aparência


 única, mas mantenha a consistência com o design geral do site.

5) Personalizando fontes e estilos no CSS
Imagine que você está trabalhando em um projeto de website e recebeu o design final do cliente 


através do Figma. Sua tarefa é replicar o design no HTML e CSS. Primeiro, você precisa lidar com
 as fontes. No Figma, você observa que o projeto utiliza a fonte "Inter" com pesos 400 e 700. 
Você precisa importar essa fonte do Google Fonts e aplicá-la ao seu projeto, definindo-a como
 a fonte padrão. Além disso, você deve definir um font-size padrão de 16px e um font-weight 
de 400 para o corpo do texto. Por fim, você deve criar uma classe .container__aviso com um font-size
 de 12px e uma cor cinza. Como você faria isso?

6) Estilizando títulos e botões
Continuando o trabalho no mesmo projeto, agora você precisa ajustar os estilos de elementos específicos.
 Primeiro, ajuste o estilo do título principal. No Figma, você vê que o título (marcado com a tag <h1>)
 tem um font-size de 28px e um font-weight de 700. Crie uma classe .container__titulo para aplicar esses estilos.
 Em seguida, personalize os botões removendo o sublinhado padrão (usando text-decoration: none;)
 e ajuste outras propriedades conforme necessário. Como você implementaria esses estilos específicos?

	

	1) Criando um botão estilizado com CSS
Para criar um botão estilizado com CSS, siga estes passos:

Adicione a classe container__botao à tag <a> no HTML:

	<a href="www.alura.com.br" class="container__botao">Assine por 12x de R$ 120,00</a>

	No arquivo CSS, selecione a classe container__botao e aplique as seguintes propriedades:

	.container__botao {
    background-color: var(--botao-azul);
    border-radius: 5px;
    padding: 1em;
    color: var(--branco-principal);
    display: block;
  }

	sEste código muda a cor de fundo para azul, arredonda as bordas, adiciona um 
espaçamento interno, altera a cor do texto para branco e define o botão para ocupar uma linha inteira.

2) Ajustando o layout do botão
Para ajustar o layout do botão para que ele fique abaixo da imagem:

Verifique o código HTML para entender a estrutura atual.
Modifique o CSS para ajustar o display dos elementos. Por exemplo, se a imagem está usando display:
 inline ou inline-block, altere para display: block ou ajuste o contêiner que envolve a imagem e o botão.
Teste e ajuste conforme necessário até que o botão apareça abaixo da imagem, como no design do Figma.

	3) Ajustando o layout com grid CSS
Abra o arquivo styles.css.
Localize a classe .container.
Defina a propriedade display para grid.
Experimente com diferentes configurações de grid-template-columns, como 50% 50% e 33% 33% 33%, 
para entender como isso afeta a disposição dos elementos na página.
Observe como a mudança na distribuição das colunas afeta o layout, especialmente o espaço ocupado pelo botão.




	.container {
       display: grid;
       grid-template-columns: 50% 50%; /* Ou 33% 33% 33% para experimentar */
   }

	4) Criando um botão secundário com CSS
No arquivo index.html, adicione um novo elemento âncora (<a>) com a classe botao_secundario.
No arquivo styles.css, crie a regra para .botao_secundario.
Defina background-color: transparent.
Adicione border: 2px solid var(--branco-principal) para criar uma borda sólida branca.
Ajuste outros atributos de estilo conforme necessário, mantendo a harmonia com o design do site.
Código:

	.botao_secundario {
       background-color: transparent;
       border: 2px solid var(--branco-principal);
       /* Adicione mais estilos se necessário */
   }


	5) Personalizando fontes e estilos no CSS
Acesse o site "fonts.google.com" e busque pela fonte "Inter". Selecione os estilos 400 e 700.
No arquivo index.html, adicione o link importado do Google Fonts abaixo do link do CSS.
No arquivo styles.css, crie uma variável no :root para a fonte principal: --fonte-principal: 'Inter';.
Aplique a fonte principal e o font-size padrão ao body:


	body {
    font-family: var(--fonte-principal);
    font-size: 16px;
    font-weight: 400;
  }


	Para a classe .container__aviso, adicione um font-size de 12px e a cor cinza:


	.container__aviso {
    font-size: 12px;
    color: var(--cinza-secundario);
  }

	6) Estilizando títulos e botões
Para o título principal, crie a classe .container__titulo e aplique o font-size e font-weight necessários:

	.container__titulo {
    font-size: 28px;
    font-weight: 700;
  }

	Nos botões, remova o sublinhado padrão e faça ajustes adicionais conforme necessário:

	.container__botao {
    text-decoration: none;
    /* outros estilos conforme necessário */
  }

	================Separando=os=elementos=====================


	text-align, porque ele consegue alinhar todos elementos dentro do bloco.

	O código começa com um elemento de bloco (a div), ou seja, que tem "display block", e há elementos
 dentro dele que são inline. Dessa maneira, usar a propriedade text-align na div permitirá alinhar
 para qualquer lado que você desejar os elementos filhos da div.



	Pesquizar: text-align:center; | align-items:

	A propriedade align-items não tem o poder de alinhar todos os elementos da página.
 Ela alinha de acordo com o display do elemento pai, como o flexbox e grid.

	
		Centralizar:

	align:items;


========================================================================

	<section class="container__secundario">

	  <img src="img/plataformas.png" alt="monitor e um celular com o alura plus aberto">
	
	   <div class="conteiner__descricao">

		<h2 class="descricao__titulo"> Assita do seu geito </h2>
		<p class="descricao__titulo">Aproveite a tela grande da TV ou assista no tablet.</p> 
	   </div>

	</section>

====================================================================
	HTML5:

	</section>

    <section class="container__secundario">
        <img src="img/Plataformas.png" alt="Um monitor e um celular com a alura plus aberta" class="secundario__imagem">
        <div class="container__descricao">
            <h2 class="descricao__titulo">Assista do seu jeito</h2>
            <p class="descricao__texto">Aproveite a tela grande da TV ou assista no tablet, laptop, celular e outros
                aparelhos. Nossa seleção de cursos não para de crescer.</p>
        </div>
    </section>

----------------------------------------------------------------------------------------------------------------

	CSS3:

	==================================================

	Obs. Sempre que precisar reutilize os códigos das classes ou reutilize as mesmas classes
	utilizadas nas pagínas para ter o mesmo resultados...

	-------------

	Utilize o (display:inline-block; ) vai deixar os elementos em linhas..

	---------------------------------------

	https://medium.com/collabcode/pare-de-chutar-e-aprenda-como-funciona-o-display-inline-block-4e6cba2f19d4

	

















