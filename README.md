# Neumorphism Working Keyboard - Soft UI Virtual Keyboard

Um componente de teclado virtual interativo, funcional e totalmente responsivo desenvolvido com HTML5, CSS3 e JavaScript. O projeto explora a fundo a estética do Neumorfismo (Neumorphism / Soft UI), utilizando um jogo avançado de múltiplas sombras para esculpir teclas táteis em relevo que reagem fisicamente ao clique, integrando-se a um visor de texto funcional.

## Tecnologias Utilizadas

* HTML5: Estruturação semântica do contêiner do teclado, área do visor de texto e mapeamento de cada tecla do layout QWERTY.
* CSS3: Estilização completa, uso de cantos suavizados, paleta de cores monocromática fosca e gerenciamento complexo de sombras projetadas.
* JavaScript: Captação de eventos de clique nas teclas, lógica de inserção/renderização de caracteres no visor e mapeamento de interatividades de estados.

## Funcionalidades e Técnicas Aplicadas

* Interface Soft UI de Alto Nível: Uso preciso da propriedade `box-shadow` combinando sombras claras e escuras opostas para criar o efeito de relevo extrudado nas teclas e relevo em profundidade (*inset*) na tela de texto superior.
* Layout QWERTY Funcional: Organização sistemática das linhas de caracteres alfabéticos e inclusão de uma barra de espaço ("SPACE") customizada e ampliada na base inferior.
* Microinterações Mecânicas Realistas: Configuração de transições dinâmicas via JavaScript e CSS que alteram as sombras no momento do clique (evento *active* ou classe de estado), simulando o afundamento físico de uma tecla mecânica real.
* Visor de Texto Integrado: Área superior responsiva mapeada para exibir os caracteres digitados em tempo real à medida que o utilizador interage com o painel de teclas.
* Alinhamento Perfeito com Grid/Flexbox: Distribuição simétrica e centralizada de todas as linhas de teclas dentro do painel estrutural principal.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone 
