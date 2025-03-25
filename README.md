# CHECKLIST DE ACESSIBILIDADE DO PROTÓTIPO DE PP:

# ELEMENTOS NÃO TEXTUAIS
## Todas as imagens têm um texto alternativo (alt) 
Atendido. No protótipo, a única imagem utilizada é da logo do aplicativo. Nela, há um (alt= “Logo Mamãe a Bordo”), considerado essencial já que a imagem transmite algo relevante para o conteúdo. 

## Os itens não textuais têm uma versão alternativa em texto
Atendido. A imagem utilizada no código possui o atributo alt, garantindo que tecnologias assistivas possam interpretar o conteúdo das imagens. Isso é essencial para garantir que usuários com deficiência visual possam entender a presença da imagem, seja através de leitores de tela ou outras ferramentas assistivas.

## Não são usadas imagens que contêm blocos de texto
Atendido. Nenhum bloco de texto está dentro de imagens.

# FORMULÁRIOS
## Todos os campos dos formulários têm uma <label> associada
Parcialmente atendido. Embora existam label associadas aos campos de entrada, elas não utilizam o atributo for, que melhora a acessibilidade associando corretamente os rótulos aos campos.

## São usados <fieldset> e <legend> para agrupar os vários campos nos formulários
Não atendido. O formulário não usa fieldset para organizar os campos. O uso dessa estrutura ajudaria na acessibilidade ao agrupar campos relacionados.

## O envio dos formulários é feito via input/button e não através de links e JavaScript
Atendido. O formulário usa button, garantindo funcionamento sem depender de JavaScript. É essencial já que algumas usuárias podem ter dispositivos ou navegadores com suporte limitado a JavaScript, então garantir um envio nativo torna o site mais acessível e funcional.

## Os erros nos formulários são indicados em texto e junto do campo que contém o erro
Não atendido. O código não apresenta mensagens de erro associadas aos campos em caso de preenchimento incorreto. Seria importante pois se um campo for preenchido incorretamente, a usuária precisa saber onde está o erro e como corrigi-lo. 

# USO DA COR DE ELEMENTOS QUE PISCAM
## Não é usada apenas a cor para transmitir informação
Não atendido. Não há indicação alternativa (ícone ou texto) para mensagens de erro. Seria essencial já que pessoas com daltonismo podem não perceber mudanças de cor. Se um erro for indicado apenas por cor vermelha, essas usuárias não entenderão a mensagem. Adicionar ícones ou texto evitaria esse problema.

## Não há elementos que piscam ou mudam de cores repetidamente
Atendido. O código não contém elementos piscantes ou mudanças bruscas de cor. Algumas usuárias podem ter epilepsia fotossensível, e elementos piscantes podem causar crises. Além disso, animações excessivas podem ser desconfortáveis para gestantes que sofrem de enjoos ou tonturas.

# NAVEGAÇÃO
## São fornecidos atalhos para saltar links repetitivos
Não atendido. O código não possui um link de "Pular para o conteúdo".

## O <title> das páginas é claro, direto e percetível e está intimamente relacionado com o conteúdo da mesma
Atendido. As páginas possuem title adequados e é essencial para a navegação.

## O site é navegável usando apenas o teclado
Atendido. É possível realizar o login e cadastro utilizando somente o teclado. 

# SEMÂNTICA E LEGIBILIDADE
## O conteúdo está estruturado de forma semântica
Atendido. As tags h2, p, label, e button são usadas corretamente.

## O idioma da página está indicado no HTML
Atendido. O código contém lang="pt-BR", permitindo que leitores de tela reconheçam o idioma.

## As tabelas têm headings <th> definidos
Não atendido. Não contêm tabelas, então esse critério não se aplica.

## O site funciona com as imagens desativadas
Atendido. Como todas as imagens possuem alt, o site continua funcional sem imagens.

## O site é legível e navegável com o CSS desativado
Parcialmente atendido. O HTML é estruturado, mas não há garantia de boa legibilidade sem CSS.

## O site é legível aumentando o texto 2 vezes
Parcialmente atendido. Não há garantia de que o layout não será quebrado ao aumentar a fonte, mas seria essencial já que algumas usuárias podem ter dificuldades visuais e precisarão aumentar o zoom da página.



