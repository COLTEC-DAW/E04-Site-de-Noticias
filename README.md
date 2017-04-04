**OBS: É importante que você gere um commit para cada parte da atividade que você concluir.**

# Site de Notícias

Você foi designado para implementar um site que mostrará notícias acerca de eventos do COLTEC. Como inspiração, a diretoria do colégio lhe pediu para implementar uma página com layout similar ao do <a href="http://www.uol.com.br">Portal UOL</a>. Mais especificamente, a diretoria requisitou a implementação de acordo com as seguintes restrições:


## Layout Principal

A página deverá ser dividida verticalmente em 5 áreas principais, cada uma dedicada a um dos cursos técnicos ofertados pelo colégio. Os cursos deverão ser exibidos em ordem alfabética.

Cada área deverá conter, pelo menos para cada curso:
* Uma notícia principal, que conterá uma foto e irá ocupar toda a largura da página
* 4 notícias de médio impacto com foto, que irão ocupar 1/3 da página cada
* 2 notícias de médio impacto sem foto, que irão ocupar 1/3 da página cada
* 3 notícias de pequeno impacto com foto, que irão ocupar 1/6 da página cada
* 3 notícias de pequeno impacto sem foto, que irão ocupar 1/6 da página cada

*Dica: Utilizem lorem ipsum para gerar as notícias e [lorem pixel](http://www.lorempixel.com) para as fotos*


## Estrutura de Navegação

Um menu deverá ser posicionado no topo da página para que cada curso possa ser acessado diretamente. Esse menu deverá ser posicionado de forma fixa (deverá ser exibido sempre, independentemente do ponto em que o usuário estiver na página).

## Cores

Cada curso deverá ter um tema que o caracterize. Foi decidido pela direção que essa tema se dará pela escolha de cores que representem cada curso. Essas cores deverão ser utilizadas em pontos estratégicos da página, para que possa informar ao usuário de forma subjetiva em que seção da página ele está localizado.

Ao conversar com os designers do projeto foi decidido que as cores serão aplicadas na fonte do título das notícias. No espaçamento entre as seções, e em animações que serão executadas sobre uma interação que haverá ao passar o mouse sobre uma notícia qualquer.

No caso da animação, deverão mudar a cor da fonte do título para uma cor neutra, e a cor da fonte do subtítulo para a cor do referido tema.

*Dica: Utilize o Adobe Kuler para selecionar cores adequadas para os cursos*

## Tela de Login

Além disso, a direção pediu para você implementar uma área de login para que o pessoal da administração possa acessar o portal de notícias e atualizar seu conteúdo.

Você deverá implementar uma página de login que utilize os recursos de formulários disponíves no Bootstrap. O formulário deverá ser horizontal e contará com dois campos: usuário e senha.

Para fins de prototipação, a equipe de design requisitou que você implemente e deixe exibido uma mensagem de alerta caso não seja possível realizar o login.

A tela de login deverá ser acessível através do menu existente na página principal.
