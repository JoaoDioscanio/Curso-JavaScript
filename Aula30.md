# Aula 30

### 	Eventos

Eventos são acontecimentos específicos em nossa página, toda ação do usuário em uma página gera um evento, por exemplo, quando movemos o mouse, quando clicamos com o botão do mouse, quando a página é carregada, quando selecionamos um item, etc.

##### 	Eventos de mouse

| Evento        | Descrição                                                    |
| ------------- | ------------------------------------------------------------ |
| onclick       | Evento disparado quando se clica em um elemento.             |
| oncontextmenu | Evento disparado quando se clica com o botão direito do mouse sobre um elemento. |
| ondblclick    | Evento disparado quando é aplicado um clique duplo sobre um elemento. |
| onmousedown   | Evento disparado quando o botão do mouse é pressionado sobre um elemento. |
| onmouseenter  | Evento disparado quando o ponteiro do mouse se move para cima de um elemento. |
| onmouseleave  | Evento disparado quando o ponteiro do mouse se move para fora de um elemento. |
| onmousemove   | Evento disparado quando o ponteiro do mouse se move sobre um elemento. |
| onmouseover   | Evento disparado quando o ponteiro do mouse é movido para dentro de um elemento ou um de seus filhos. |
| onmouseout    | Evento disparado quando o ponteiro do mouse é movido para fora de um elemento ou um de seus filhos. |
| onmouseup     | Evento disparado quando o botão do mouse é liberado, despreciando, sobre um elemento. |

##### 	Eventos de teclado

| Evento     | Descrição                                                    |
| ---------- | ------------------------------------------------------------ |
| onkeydown  | Evento disparado quando o usuário pressiona uma tecla.       |
| onkeypress | Evento disparado quando o usuário mantém uma tecla pressionada. |
| onkeyup    | Evento disparado quando o usuário libera uma tecla pressionada. |

##### 	Eventos de objetos/frames/body

| Evento         | Descrição                                                    |
| -------------- | ------------------------------------------------------------ |
| onabort        | Evento disparado quando o carregamento do elemento é abortado. |
| onbeforeunload | Evento disparado antes do documento ser descarregado/fechado. |
| onerror        | Evento disparado quando ocorre algum erro no carregamento de arquivos externos. |
| onhashchange   | Evento disparado quando ocorre alguma alteração da âncora da URL. |
| onload         | Evento disparado quando um elemento é carregado.             |
| onpageshow     | Evento disparado quando uma página é mostrada.               |
| onpagehide     | Evento disparado quando uma página deixa de ser mostrada.    |
| onresize       | Evento disparado quando o elemento é redimensionado.         |
| onscroll       | Evento disparado quando a página é rolada.                   |
| onunload       | Evento disparado quando a página é fechada/descarregada.     |

##### 	Eventos de formulários

| Evento     | Descrição                                                    |
| ---------- | ------------------------------------------------------------ |
| onblur     | Evento disparado quando o elemento perde o foco, perde a seleção. |
| onchange   | Evento disparado quando o conteúdo do elemento é alterado, input, keygen, select, textarea. |
| onfocus    | Evento disparado quando o elemento recebe o foco, é selecionado. |
| onfocusin  | Evento disparado quando o elemento está prestes a receber o foco. |
| onfocusout | Evento disparado quando o elemento está prestes a perder o foco. |
| oninput    | Evento disparado quando o usuário clica para entrar ou selecionar o elemento. |
| onivalid   | Evento disparado quando um elemento é inválido.              |
| onreset    | Evento disparado quando o botão reset é pressionado.         |
| onsearch   | Evento disparado quando é escrito algo em um campo <input type=“search”> |
| onselect   | Evento disparado logo após a seleção de um texto <text> e <textarea> |
| onsubmit   | Evento disparado quando o botão submit é clicado para enviar os dados do formulário. |

##### 	Eventos de Arrastar

| Evento      | Descrição                                                    |
| ----------- | ------------------------------------------------------------ |
| ondrag      | Evento disparado quando um elemento é arrastado.             |
| ondragend   | Evento disparado quando um elemento deixa de ser arrastado.  |
| ondragenter | Evento disparado quando o elemento arrastado entra no elemento alvo. |
| ondragleave | Evento disparado quando o elemento arrastado deixa o elemento alvo. |
| ondragover  | Evento disparado quando o elemento arrastado está sobre o elemento alvo. |
| ondragstart | Evento disparado quando o elemento começa a ser arrastado.   |
| ondrop      | Evento disparado quando o elemento arrastado é solto.        |

##### 	Eventos de Área de transferência / clipboard	

| Evento  | Descrição                                                    |
| ------- | ------------------------------------------------------------ |
| oncopy  | Evento disparado quando o usuário copia o conteúdo de um elemento. |
| oncut   | Evento disparado quando o usuário recorta o conteúdo de um elemento. |
| onpaste | Evento disparado quando o usuário cola um conteúdo em um elemento. |

##### 	Eventos de impressão

| Evento        | Descrição                                                    |
| ------------- | ------------------------------------------------------------ |
| onafterprint  | Evento disparado quando a página termina de ser impressa.    |
| onbeforeprint | Evento disparado quando a página está prestes a ser impressa. |

##### 	Eventos de mídia

| Evento           | Descrição                                                    |
| ---------------- | ------------------------------------------------------------ |
| onabort          | Evento disparado quando o carregamento de uma mídia é interrompido. |
| oncanplay        | Evento disparado quando a página está prestes a ser impressa. |
| oncanplaythrough | Evento disparado quando o navegador pode começar a rodas a mídia (quando se tem cach suficiente para começar) |
| ondurationchange | Evento disparado quando a duração da mídia é alterada.       |
| onemptied        | Evento disparado quando algum problema acontece e o arquivo de mídia fica subitamente indisponível (quando a conexão é inesperadamente interrompida) |
| onended          | Evento disparado quando a mídia chegou ao fim (útil para mensagens como "Obrigado por escutar") |
| onerror          | Evento disparado quando ocorreu um erro durante o carregamento de um arquivo de mídia. |
| onloadeddata     | Evento disparado quando os dados de mídia são carregados.    |
| onloadedmetada   | Evento disparado quando dados de meta (como tamanho e duração) são carregados |
| onloadstart      | Evento disparado quando o navegador começa a carregar a mídia especificada |
| onpause          | Evento disparado quando a mídia é pausada pelo usuário.      |
| onplay           | Evento disparado quando a mídia é iniciada ou não está pausada. |
| onplaying        | Evento disparado quando a mídia está sendo tocada.           |
| onprogress       | Evento disparado quando o navegador baixando a mídia.        |
| onratechange     | Evento disparado quando a velocidade de reprodução da mídia é alterada. |
| onseeked         | Evento disparado quando o usuário termina de mover o ponteiro de reprodução para uma nova posição da mídia. |
| onseeking        | Evento disparado quando o usuário começa a mover o ponteiro de reprodução para uma nova posição da mídia. |
| onstalled        | Evento disparado quando o navegador está tentando obter dados de mídia, mas os dados não estão disponíveis. |
| onsuspend        | Evento disparado quando a reprodução da mídia é suspenso, quando o navegador não está recebendo dados da mídia. |
| ontimeupdate     | Evento disparado quando a posição de reprodução mudar (como quando o usuário avança para um ponto diferente na mídia) |
| onvolumechange   | Evento disparado quando o volume é alterado.                 |
| onwaiting        | Evento disparado quando a mídia fez uma pausa, mas é esperado para retomar (quando a mídia faz uma pausa para o bufferrizar mais dados) |

##### 	Eventos de animação

| Evento             | Descrição                                              |
| ------------------ | ------------------------------------------------------ |
| animationend       | Evento disparado quando uma animação CSS é completada. |
| animationiteration | Evento disparado quando uma animação CSS é repetida.   |
| animationstart     | Evento disparado quando uma animação CSS é iniciada.   |

##### 	Evento de transição

| Evento        | Descrição                                               |
| ------------- | ------------------------------------------------------- |
| transitionend | Evento disparado quando uma transição CSS é completada. |

##### 	Eventos enviados pelo servidor

| Evento    | Descrição                                                    |
| --------- | ------------------------------------------------------------ |
| onerror   | Evento disparado quando um erro ocorre.                      |
| onmessage | Evento disparado quando uma mensagem é recebida através da fonte de eventos. |
| onopen    | Evento disparado quando a conexão com o servidor é iniciada. |

##### 	Eventos diversos

| Evento     | Descrição                                                    |
| ---------- | ------------------------------------------------------------ |
| onmessage  | Evento disparado quando uma mensagem é recebida através ou a partir de um objeto. |
| ononline   | Evento disparado quando o browser inicia o trabalho online.  |
| onoffline  | Evento disparado quando o browser inicia o trabalho off-line. |
| onpopstate | Evento disparado quando a janela de histórico muda.          |
| onshow     | Evento disparado quando um elemento de <menu> é mostrado.    |
| onstorage  | Evento disparado quando a área de armazenamento web é atualizada. |
| ontoggle   | Evento disparado quando o usuário abre ou fecha um elemento de <details> |
| onwheel    | Evento disparado quando a roda do mouse é usada.             |

##### 	Eventos de toque na tela

| Evento        | Descrição                                                   |
| ------------- | ----------------------------------------------------------- |
| ontouchcancel | Evento disparado quando o toque é finalizado.               |
| ontouchend    | Evento disparado quando o dedo é retirado na tela de toque. |
| ontouchmove   | Evento disparado quando o dedo é movido na tela de toque.   |
| ontouchstart  | Evento disparado quando o dedo toca a tela.                 |

##### 	Event

| Evento           | Descrição                                                    |
| ---------------- | ------------------------------------------------------------ |
| DOMContentLoaded | Acionado quando o documento inicial HTML foi completamente carregado e analisado. |

##### 	MouseEvent

| Evento        | Descrição                                                    |
| ------------- | ------------------------------------------------------------ |
| altKey        | Retorna se a tecla ALT foi pressionada.                      |
| button        | Retorna qual botão do mouse foi pressionado.                 |
| buttons       | Retorna quais botões do mouse foram pressionados.            |
| clientX       | Retorna a coordenada horizontal do mouse.                    |
| clientY       | Retorna a coordenada vertical do mouse.                      |
| ctrlKey       | Retorna se a tecla CTRL foi pressionada.                     |
| detail        | Retorna um número que indica quantas vezes o mouse foi clicado. |
| metaKey       | Retorna se a tecla "META" foi pressionada.                   |
| retaledTarget | Retorna o elemento relacionado com o elemento que disparou o evento do mouse. |
| screenX       | Retorna a coordenada horizontal do ponteiro do mouse, em relação à tela. |
| screenY       | Retorna a coordenada vertical do ponteiro do mouse, em relação à tela. |
| shiftKey      | Retorna se a tecla SHIFT foi pressionada.                    |
| which         | Retorna qual botão do mouse foi pressionado.                 |

##### 	KeyboardEvent

| Evento   | Descrição                                            |
| -------- | ---------------------------------------------------- |
| altKey   | Retorna se a tecla ALT foi pressionada.              |
| crtlKey  | Retorna se a tecla CTRL foi pressionada.             |
| charCode | Retorna o código do caracteres da tecla pressionada. |
| key      | Retorna o valor da tecla pressionada.                |
| keyCode  | Retorna o código da tecla pressionada.               |
| location | Retorna a localização da tecla pressionada.          |
| metaKey  | Retorna se a tecla "META" foi pressionada.           |
| shiftKey | Retorna se a tecla SHIFT foi pressionada.            |
| which    | Retorna qual botão do mouse foi pressionado.         |

##### 	HashChangeEvent

| Evento | Descrição                                       |
| ------ | ----------------------------------------------- |
| newURL | Retorna a URL do documento após uma alteração.  |
| oldURL | Retorna a URL do documento antes uma alteração. |

##### 	PageTransitionEvent

| Evento    | Descrição                                                    |
| --------- | ------------------------------------------------------------ |
| persisted | Retorna se a página da Web foi armazenada em cache pelo navegador. |

##### 	FocusEvent

| Evento        | Descrição                                                    |
| ------------- | ------------------------------------------------------------ |
| relatedTarget | Retorna o elemento relacionado com o elemento que disparou o evento. |

##### 	AnimationEvent

| Evento        | Descrição                                                  |
| ------------- | ---------------------------------------------------------- |
| animationName | Retorna o nome da animação.                                |
| elapsedTime   | Retorna o tempo em segundos que uma animação está rodando. |

##### 	TransitionEvent

| Evento       | Descrição                                                    |
| ------------ | ------------------------------------------------------------ |
| propertyName | Retorna o nome da propriedade CSS associada com a transição. |
| elapsedTime  | Retorna o tempo em segundos que uma transição está rodando.  |

##### 	WheelEvent

| Evento    | Descrição                                                    |
| --------- | ------------------------------------------------------------ |
| deltaX    | Retorna a quantidade de rolagem horizontal de uma roda do mouse (eixo x). |
| deltaY    | Retorna a quantidade de rolagem vertical de uma roda do mouse (eixo y). |
| deltaZ    | Retorna a quantidade de deslocamento de uma roda do mouse para o eixo z. |
| deltaMode | Retorna um número que representa a unidade de medição para valores delta (pixels, linhas ou páginas). |