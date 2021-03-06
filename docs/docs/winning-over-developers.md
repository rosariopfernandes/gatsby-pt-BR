---
title: Conquistando Desenvolvedores
---

Desenvolvedores são geralmente os principais evangelistas do Gatsby porque eles são os principais usuários do framework. Se você é um desenvolvedor, é possível que descubra que uma simples conversa com outros desenvolvedores sobre o porquê _você_ gosta do Gatbsy é o suficiente para deixá-los interessados. Aqui estão alguns pontos de discussão para te ajudar a apoiar suas conversas com outros desenvolvedores. 

Algumas coisas com as quais desenvolvedores se importam incluem:

- **Performance do site**: Construir sites que são e que permanecem rápidos à medida que novas ferramentas e tecnologias são incorporadas.
- **Trabalhar com as melhores ferramentas e tecnologias**: Utilizar novas tecnologias e ter a flexibilidade de escolher as ferramentas certas para o trabalho.
- **Não ficar atolado em configuração**: Essas coisas geralmente consomem tempo, são frustrantes e impedem os desenvolvedores de focarem no trabalho que realmente importa.
- **Desenvolver da maneira mais eficiente e eficaz possível**: Quanto mais os processos puderem ser aperfeiçoados, automatizados e/ou simplificados melhor.

## Explicação básica

Aqui está um exemplo de uma explicação básica para desenvolvedores do que é o Gatsby:

> Gatsby é um framework gratuito, open source, baseado em React para construção de websites e aplicações velozes. Gatsby simplifica o processo de configuração do seu build, permitindo o consumo de dados a partir de quaisquer fontes para sua UI, além do excelente desempenho e das melhores práticas já embutidas nos sites Gatsby.

## Benefícios específicos

O Gatsby têm muitos benefícios que dão aos desenvolvedores a liberdade de construir excelentes websites e ainda utilizar as habilidades e ferramentas que eles amam. Alguns pontos de discussão específicos são listados a seguir.

### Velocidade do site

> O Gatsby foi desenvolvido pensando em desempenho desde o princípio, e sites Gatsby são consistentemente 2-3x mais rápidos do que sites similares construídos com outras ferramentas - páginas carregam em milissegundos ao invés de segundos. As otimizações de desempenho automatizadas do Gatsby incluem recursos de _pre-fetching_, _code splitting_, geração estática de HTML e [padrão PRPL](/docs/prpl-pattern/) da Google. Se quiser se aprofundar quanto aos recursos de desempenho do Gatsby, veja [Web Performance 101 – Além disso, por quê o Gatsby é tão rápido?](/blog/2017-09-13-why-is-gatsby-so-fast/).

### Ferramentas web modernas

> Sites Gatsby são construídos com React - atualmente o framework mais popular para desenvolvimento de aplicações web, e dados podem ser consumidos nos componentes React usando GraphQL. Gatsby também foi construído para consumir dados a partir de qualquer fonte e dá flexibilidade para que você escolha a melhor ferramenta para cada tarefa e função que o seu site precisa realizar. Consuma dados a partir das melhores ferramentas de gestão de conteúdo, das melhores ferramentas de _e-commerce_, de quaisquer bases de dados que estiver utilizando, e muito mais.

### Recursos e plugins

> Quase todos os recursos que você poderia desejar para construir um website ou aplicação web de última geração estão disponíveis através do Gatsby. Se o recurso ainda não estiver embutido, há uma extensa biblioteca de plugins disponível. Há uma lista de recursos, suas disponibilidades e comparações com outras opções de construção disponíveis na [página de Recursos](/features/). A lista completa de plugins atualmente disponíveis pode ser encontrada na [página de Plugins](/plugins/).

### Integração de dados

> O Gatsby suporta a integração de dados de fontes como CMSs, serviços SaaS, APIs, bancos de dados e outras fontes de dados de todos os tipos. O Gatsby também pode consumir dados não estruturados diretamente para páginas através de chamadas a API criadas especificamente para esse fim. Isso funciona muito bem em sites menores, que podem ser posteriormente escalados sem esforço, se necessário. Isso faz com que o Gatsby se destaque da maioria dos outros geradores de sites estáticos.

### Comunidade e documentação

> Seria difícil você encontrar uma comunidade open source mais ativa e acolhedora do que a do Gatsby. A documentação é completa, detalhada e não faz nenhuma suposição sobre o seu nível de experiência atual. O time do Gatsby é comprometido com a transparência e com trabalho aberto para que a comunidade possa acompanhar e participar do direcionamento e do desenvolvimento do Gatsby. Todos são estimulados a contribuir para o Gatsby e toda contribuição é valorizada.

### Traz o foco para o frontend

> Um benefício que surge com frequência nas discussões sobre o Gatsby é como ele ajuda a trazer mais foco para o desenvolvimento frontend e uma divisão mais clara entre tarefas de frontend e de backend. Ferramentas e configurações complicadas podem consumir muito do tempo de desenvolvimento e podem desviar os desenvolvedores frontend do que eles fazem de melhor. Como o Gatsby requer configurações e ferramentas mínimas, desenvolvedores frontend podem usar mais tempo construindo excelentes UI's e desenvolvedores backend podem focar em adicionar funcionalidades e integrações que tornam seu produto melhor.

## Preocupações comuns

Talvez você ache que muitos dos seus amigos e colegas desenvolvedores tenham dúvidas e preocupações sobre o Gatsby. Aqui estão alguns exemplos e respostas comuns que você pode dar para ajudar a amenizar essas preocupações.

### Nosso site usa muito conteúdo e componentes dinâmicos. Gatsby não é um gerador de site estático?

> É, mas ele é mais do que isso. Gatsby gera conteúdo HTML estaticamente usando React DOM e APIs server-side - é uma parte importante do como o Gatsby oferece velocidade excepcional e mais segurança. No entanto, este conteúdo estático HTML pode ser melhorado com Javascript do lado do cliente através do React hydration. Você pode aprender mais a respeito no post do blog de Dustin Schau [Beyond Static: Building Dynamic apps with Gatsby](/blog/2018-10-15-beyond-static-intro/).

### Tenho de aprender GraphQL para usar o Gatsby?

> GraphQL é usado para consumir conteúdo de diferentes fontes para dentro do Gatsby de uma maneira consistente e unificada. Você não tem de usar GraphQL para fazer isso, mas aprender a usá-lo te deixará preparado para criar novas integrações mais facilmente (e pode não ser tão desafiador quanto você pensa). Amberly Romo analisa alguns dos prós e contras no seu post em [Usando Gatsby sem GraphQL](/blog/2018-10-25-using-gatsby-without-graphql/).

### Nossa equipe de conteúdo precisa ser capaz de fazer atualizações no site, mas eles não são super técnicos. Eles conseguirão trabalhar com o site Gatsby?

> Gatsby pode consumir conteúdo de quaisquer fontes de dados, includindo os CMS all-in-one como WordPress e Drupal assim como os vários headless CMS disponíveis, de forma que sua equipe de conteúdo possa trabalhar com qualquer editor de conteúdo que atenda às suas necessidades e preferências, incluindo o CMS que eles já estão utilizando.

## Estudos de caso

Às vezes a forma mais eficiente de chamar a atenção dos desenvolvedores é mostrar-lhes exemplos de sites reais e times de desenvolvimento utilizando Gatsby. Aqui estão alguns estudos de caso que talvez você queira compartilhar:

- [Delicious Simplicity <3 Gatsby: Building Happily Ever After](/blog/2019-06-08-delicious-simplicity-case-study-part-1/)
- [Beyond Static: Haptic Media Uses Gatsby to Build a Dynamic Web App](/blog/2019-02-05-hapticmedia-case-study/)
- [IBM Uses Gatsby to Manage Enterprise-Level Content](/blog/2018-12-17-ibm-case-study/#big-company-big-website)

Para mais exemplos de sites Gatsby, [veja o Showcase](/showcase/).

## Conclusão

Muitos desenvolvedores gostam de ser pioneiros quando novas ferramentas interessantes surgem, mas eles também tendem a ser céticos quando a nova ferramenta parece ser apenas mais uma "modinha". Felizmente, o Gatsby resiste a essa análise. As informações fornecidas aqui são um excelente ponto de partida para conversas com desenvolvedores sobre o Gatsby. A partir daí, incentive os desenvolvedores a confirmarem as informações por conta própria. Pode ser tudo de que eles precisam.
