---
revisão: 2024-01-28
conteúdo: Autoconhecimento
status:
  - Concluído
tags:
  - Memorização
---
# O que é

Este é um aplicativo com a função de criar cartões para revisão de conteúdos. Esses cartões possuem algumas regras de revisão para ajudar na memorização.

# Regras dos cartões

### Resposta

Todo cartão tem sua pergunta e você deve responder mentalmente a ela. Em seguida, você deve virar o cartão para validar se sua resposta estava correta. Então, o app vai perguntar como você avaliaria a dificuldade de responder à questão com os seguintes níveis:

- **Again** - Significa que você precisa que esse cartão se repita, pois errou.
- **Hard** - Você acertou, mas esqueceu de algum detalhe importante.
- **Good** - Acertou, mas deixou algo não muito relevante passar.
- **Easy** - Acertou tudo que estava no cartão. Cada dificuldade vai colocar uma data no cartão e deixá-lo em um [[#Estados do cartão]]. Isso fará com que o cartão só seja "**Finalizado**" após você considerar **Easy** responder à pergunta.

### Estados do cartão

Todo cartão sempre está em um estado, que representa como está seu conhecimento no tema. São eles:

- **New** - Quando o cartão é criado, ele vai para esse estado, indicando que o conteúdo deve ser respondido.
- **Learn** - Você ainda não conseguiu acertar o conteúdo e deve aprendê-lo.
- **Due** - Significa que você deve revisar o conteúdo.
- **Archived** - Se você acertou o conteúdo com um **Easy**, ele vai para esse estado até que a validade acabe. Quando isso ocorre, esse conteúdo volta para **Due** e você deve confirmar que ainda lembra.