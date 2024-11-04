<h1>Parte inicial do HTML5</h1>
<h2>1. Navegação (nav)</h2>
nav: Cria a área de navegação na página, onde fica o menu.
div class="menu": Agrupa o menu e aplica a classe menu, que será usada para estilização com CSS.
ul class="menu-ul": Cria uma lista não ordenada, que serve para organizar os itens do menu em uma lista vertical ou horizontal.
li class="menu-li": Cada item da lista. Cada li representa um item do menu.
a href="#": Link para cada item do menu. O # é um marcador de posição, que pode ser substituído por um link real para cada página.
<h2>2. Seção Principal (main) - Apresentação do Projeto</h2>
main: Define a seção principal da página, onde está o conteúdo principal.
section class="first-container": Agrupa a primeira seção da página, aplicando a classe first-container.
h1 class="main-title": Título principal da página, representando o nome do projeto.
h2 class="title-description": Subtítulo explicativo, descrevendo o propósito do projeto.
button class="btn-know-us": Botão com o texto “Conheça-nos”, usando a classe btn-know-us para estilização.
<h2>3. Seção de Projetos (div class="our-projects")</h2>
div class="our-projects": Contém a seção de projetos, com a classe our-projects para estilizar essa área específica.
h1 class="title": Título da seção de projetos, destacando “Nossos Projetos”.
3.1 Bloco de Projeto (div class="container")
div class="container": Bloco que organiza os projetos dentro da página.

Para cada projeto individual:

div class="container-img": Contêiner que agrupa as informações de cada projeto específico.

img class="image-principal" src="queimadas.png" alt="": Imagem que representa o projeto. A classe image-principal é usada para aplicar estilos à imagem.

h2 class="title-img": Subtítulo do projeto, destacando o nome específico do projeto.

p class="text-img": Parágrafo com uma breve descrição do projeto.

button class="btn-projects": Botão com o texto “Saiba mais”, que pode ser usado para redirecionar a uma página com mais informações.

Obs: O mesmo conjunto de elementos pode ser repetido para cada projeto.

<h2>4. Estrutura do HTML e Metadados (head)</h2>
!DOCTYPE html: Declara o uso do HTML5.
html lang="en": Define o idioma principal da página como inglês (en).
meta charset="UTF-8": Define a codificação de caracteres como UTF-8, que permite usar caracteres especiais.
meta name="viewport" content="width=device-width, initial-scale=1.0": Ajusta a largura da página para o tamanho da tela do dispositivo, tornando-a responsiva.
link rel="shortcut icon" href="favicon.ico" type="image/x-icon": Adiciona um ícone na aba do navegador.
link rel="stylesheet" href="style.css": Conecta o arquivo CSS externo, chamado style.css, para estilizar a página.
title: Define o título da página, exibido na aba do navegador (neste caso, "Home - Zero Fire").
<h2>5. Estrutura Básica (body e Fechamentos)</h2>
body: Contém todo o conteúdo visível da página, incluindo menus, seções e projetos.
Tags de fechamento:
div: Vários fechamentos de div para finalizar os blocos abertos anteriormente.
main e body: Fecham o conteúdo principal e o corpo da página.
html: Fecha o documento HTML.
CSS (Explicação das Classes e Estilização)

<h1>Parte do CSS3</h1>

<h2>1. Navegação (nav)</h2>
nav: Define o estilo geral da barra de navegação. Pode incluir cores de fundo, largura, altura e alinhamento do conteúdo.
menu: Estiliza o contêiner do menu. Geralmente define o layout do menu, alinhamento e espaçamento.
menu-ul: Aplica estilo à lista não ordenada do menu, como margens e preenchimentos para evitar espaçamento indesejado entre os itens.
menu-li: Estiliza cada item de lista no menu. Pode incluir configurações de display (como inline-block para alinhar os itens horizontalmente) e espaçamento entre os itens.
a: Estilo aplicado aos links do menu, como cor, tamanho da fonte, efeito de hover (passar o mouse) e remoção de sublinhado padrão.
<h2>2. Seção Principal (main) - Apresentação do Projeto</h2>
main: Define o layout da seção principal, como largura, alinhamento do conteúdo e cor de fundo.
first-container: Aplica estilos à primeira seção da página, como altura, largura e centralização do conteúdo.
main-title: Define o estilo do título principal, incluindo tamanho da fonte, cor e espaçamento.
title-description: Aplica estilo ao subtítulo, incluindo tamanho de fonte menor que o título principal, cor e espaçamento.
btn-know-us: Estiliza o botão de chamada para ação, com configurações de cor de fundo, bordas arredondadas, tamanho da fonte, cor do texto e efeito de hover.
<h2>3. Seção de Projetos (our-projects)</h2>
our-projects: Estiliza a seção geral dos projetos, incluindo largura da seção, alinhamento do conteúdo e espaçamento.
title: Define o estilo do título “Nossos Projetos”, aplicando tamanho de fonte maior, cor e espaçamento para destacar o título.
3.1 Bloco de Projeto (container)
container: Estiliza o bloco que contém todos os projetos, aplicando display flexível ou grid para organizar os projetos.

Para cada projeto individual:

container-img: Define o estilo do bloco de cada projeto individual, como borda, sombra, alinhamento e espaçamento interno (padding).
image-principal: Estiliza a imagem principal do projeto, definindo largura máxima, altura e borda para melhorar a apresentação.
title-img: Aplica estilo ao subtítulo de cada projeto, com configurações de tamanho de fonte e cor.
text-img: Estiliza o parágrafo de descrição do projeto, com um tamanho de fonte menor que o título e uma cor mais neutra.
btn-projects: Estiliza o botão de cada projeto, com cor de fundo, bordas arredondadas, tamanho da fonte e efeitos de hover.
<h2>4. Estrutura do CSS Básico e Estilização Global</h2>
html: Define estilos globais para a página inteira, como largura da página e propriedades de fonte padrão.
body: Aplica estilos básicos ao corpo da página, incluindo cor de fundo, fonte e espaçamento padrão.
* (universal selector): Remove margens e preenchimentos padrão de todos os elementos para manter a consistência no layout.
h1, h2, p, button: Estilos padrão para cabeçalhos, parágrafos e botões, aplicando tamanho de fonte, cor e espaçamento para uma aparência coerente.
<h2>5. Estrutura Responsiva e Configurações Específicas</h2>
@media (max-width: Xpx): Define estilos para dispositivos móveis, ajustando tamanhos e espaçamentos para melhor visualização em telas menores.
Configurações específicas para display: flex ou grid: Organizam elementos em layouts responsivos para alinhamento e espaçamento consistentes entre seções e itens.

