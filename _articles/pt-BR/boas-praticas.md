---
locale: pt-BR
title: Boas práticas para mantenedor
description: Fazendo sua vida como mantenedor de projetos open source mais fácil, do processo de documentação até o apoio à comunidade.
class: boas-praticas
toc:
  o-que-siginifica-ser-um-mantenedor: "O que significa ser um mantenedor?"
  documentando-seu-processo: "Documentando seu processo"
  aprendendendo-a-dizer-nao: "Aprendendo a dizer não"
  alavancando-sua-comunidade: "Alavancando sua comunidade"
  traga-os-robos: "Traga os robôs"
  e-ok-pausar: "É OK pausar"
order: 5
image: /assets/images/cards/best-practices.png
---

## O que significa ser um mantenedor?

Se você mantém um projeto open source que muitas pessoas usam, você deve ter percebido que está codificando menos e respondendo mais questões da comunidade.

Nos estágios iniciais do projeto você está experimentando novas ideias e fazendo decisões baseadas no que você quer. Enquanto seu projeto expande em popularidade, você vai se ver trabalhando mais com seus usuários e contribuintes.

Manter um projeto requer mais que códigos. Essas tarefas são inesperadas, apesar de serem tão importantes quanto para o crescimento do seu projeto. Nós juntamos algumas maneiras para fazer sua vida mais fácil, da documentação ao apoio da comunidade.

## Documentando seu processo

Escrever muitas coisas é um dos passos mais importantes como um mantenedor.

Documentar não somente clarifica suas próprias ideias, mas também ajuda outras pessoas a entenderem o que você precisa ou espera, antes mesmo delas perguntarem.

Escrever sobre o projeto facilita você dizer não quando algo não está dentro do escopo. Isso também ajuda outras pessoas a iniciarem as contribuições e te ajudarem. Nunca se sabe quem pode estar lendo ou usando seu projeto.

Mesmo que você não use parágrafos completos, separar em pequenos itens continua sendo melhor que não escrever nada.

### Escreva a visão do seu projeto

Comece escrevendo os objetivo do seu projeto. Adicione-os ao arquivo README, ou até crie um arquivo separado chamado VISION. Se tiver outros itens que possam ajudar, como um roadmap do projeto, torne-os públicos também.

Ter uma visão clara e bem documentada te mantém focado e evita que outros contribuidores saiam do escopo.

Por exemplo, @lord percebeu que ter uma visão do projeto o ajudou a descobrir em quais requisições gastar seu tempo. Como responsável pela manutenção, ele se arrependeu de não manter rígido no escopo do projeto quanto recebeu sua primeira requisição por um recurso novo no [Slate](https://github.com/lord/slate).

<aside markdown="1" class="pquote">
  <img src="https://avatars2.githubusercontent.com/u/1976330?v=3&s=460" class="pquote-avatar" alt="avatar" alt="@lord avatar">
  Eu tentei. Eu não fiz o esforço necessário para trazer uma solução completa. Ao invés de uma solução meia-boca eu queria ter dito "Não tenho tempo para isso agora, mas irei adicionar à lista de longo prazo de itens que seriam importante termos."
  <p markdown="1" class="pquote-credit">
— @lord, ["Dicas para novos mantenedores de projetos open source"](https://lord.io/blog/2014/oss-tips/)
  </p>
</aside>

### Comunique suas expectativas

Pode ser estressante escrever regras. Às vezes pode parecer que você está privando o comportamento de outras pessoas ou acabando com a diversão.

Enquanto escritas e aplicadas de forma justa, boas regras ajudam os mantenedores. Elas evitam que você seja arrastado para coisas que não quer fazer.

A maioria das pessoas que acaba cruzando seu projeto não sabem nada sobre você ou suas circunstâncias. Pode ser que assumam que você foi pago pra trabalhar nisso, especialmente se é algo que usam regularmente e dependem disso. Talvez em certo ponto você gastou muitas horas no projeto, mas agora está ocupado com um novo trabalho ou com a família.

Nada disso tem problema! Somente tenha certeza que as outras pessoas saibam sobre isso.

Se manter seu projeto é algo de meio período ou foi puramente voluntário, seja honesto sobre quanto tempo tem. Esse não é o mesmo tempo que acha que seu projeto necessita ou quanto tempo os outros querem que você gaste.

Eis algumas regras que valem a pena escrever sobre:

* Como a contribuição é avaliada e aceita (_Elas precisam de testes? Um template de Issue?_)
* Os tipos de contribuição que você vai aceitar (_Você só precisa de ajuda com certa parte do código?_)
* Quando é OK te cobrar por uma resposta (_ex. "Espere uma resposta do mantenedor em até 7 dias. Se você não obteve resposta, sinta-se a vontade para comentar na thread."_)
* Quanto tempo você gasta no projeto (_ex. "Nós gastamos somente 5 horas por semana trabalhando neste projeto"_)

[Jekyll](https://github.com/jekyll/jekyll/tree/master/docs), [CocoaPods](https://github.com/CocoaPods/CocoaPods/wiki/Communication-&-Design-Rules), e [Homebrew](https://github.com/Homebrew/brew/blob/bbed7246bc5c5b7acb8c1d427d10b43e090dfd39/docs/Maintainers-Avoiding-Burnout.md) são vários examples de projetos com regras básicas para mantenedores e contribuidores.

### Mantenha a comunição pública

Não se esqueça de documentar suas interações também. Sempre que puder, mantenha a comunicação sobre o projeto pública. Se alguém tentar te contatar de forma privada para discutir algum recurso novo ou ajuda requerida, educadamente direcione para um canal público, como uma lista de discussão ou uma thread de Issue.

Se você se encontrar com outros mantenedores ou tomar uma grande decisão de forma privada, documente essas discussões publicamente, mesmo que seja somente postar algumas notas rápidas.

Dessa forma, qualquer um que se juntar à sua comunidade vai ter acesso às mesmas informações que alguém que esteve lá por anos.

## Aprendendo a dizer não

Você escreveu coisas. Idealmente, todo mundo vai ler sua documentação, mas na realidade, você vai ter que lembrar os outros que ela existe.

Ter tudo escrito, entretando, ajuda a tornar menos pessoal as situações em quando você precisar impor alguma regra.

Dizer não pode ser chato, mas _"Sua contribuição não bate com os critérios do projeto"_ é menos pessoal que _"Eu não gostei da sua contribuição"_.

Dizer não se aplica a várias situações que você vai cruzar como um mantenedor: pedidos de novas funcionalidades que não entram no escopo, perda de rumo em discussões, fazer trabalho desnecessário para outros.

### Mantenha a discussão amigável

Um dos lugares mais importantes que você vai aprender a dizer não é em filas de Issues e Pull requests. Como um responsável pelo projeto, você vai acabar recebendo sugestões que não quer aceitar.

Talvez a contribuição mude o escopo do seu projeto ou não bate com sua visão. Talvez a ideia seja boa, mas a implementação é fraca.

Independente da razão, é possível lidar taticamente com as contribuições que não tem o padrão do seu projeto.

Se você receber uma contribuição que não quer aceitar, sua primeira reação pode ser de ignorá-la e fingir que não viu. Fazer isso pode machucar os sentimentos de outras pessoas e até desmotivar outros potenciais contribuintes na sua comunidade.

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/869950?v=3&s=400" class="pquote-avatar" alt="avatar" alt="@KrauseFx avatar">
  A chave para lidar com o suporte de projetos open source de grande escala é manter os Issues rodando. Tente evitar que os Issues fiquem estagnados. Se você é um desenvolvedor iOS sabe como é frustrante enviar radares. Você pode ter um retorno 2 anos depois e ouvir para tentar com a nova versão do iOS.
  <p markdown="1" class="pquote-credit">
— @KrauseFx, ["Escalando comunidades open source"](https://krausefx.com/blog/scaling-open-source-communities)
  </p>
</aside>

Não deixe uma contribuição despercebida em aberto porque você se sente culpado ou quer ser legal. Com o tempo, seus Issues e Pull requests não respondidas vão fazer o trabalho no seu projeto parecer muito mais estressante e intimidante.

É melhor imediatamente fechar as contribuições que você sabe que não quer aceitar. Se seu projeto já sofre com um backlog muito grande, @steveklabnik tem sugestões para [triar Issues de forma eficiente](http://words.steveklabnik.com/how-to-be-an-open-source-gardener).

Além disso, ignorar contribuições envia um sinal negativo para sua comunidade. Contribuir para um projeto pode ser intimidante, especialmente se é a primeira vez de alguém. Mesmo que você não aceite suas contribuições, reconheça a pessoa por trás dela e agradeça o interese. Isso é um grande elogio!

Se você não quer aceitar a contribuição:

* **Agradeça** pela contribuição
* **Explique porque ela não se aplica** no escopo do seu projeto, e ofereça sugestões para melhorias, se você puder. Seja gentil, mas firme.
* **Link para documentações relevantes**, se você tiver. Se você perceber muitas requisições por coisas  que você não quer aceitar, adicione-as na sua documentação para evitar que você se repita muito.
* **Feche a requisição**

Você não deve precisar de mais que 1-2 sentenças para responder. Por exemplo, quando um usuário do [celery](https://github.com/celery/celery/) reportou um erro relacionado ao Windows, @berkerpeksag [respondeu com](https://github.com/celery/celery/issues/3383):

![celery screenshot](/assets/images/best-practices/celery.png)

Se a dificuldade em dizer não te assusta, você não está sozinho. Assim como @jessfraz [colocou](https://blog.jessfraz.com/post/the-art-of-closing/):

> Eu falei com mantenedores de diferentes projetos open source, Mesos, Kubernetes, Chromium, e todos eles concordam que a parte mais díficil de ser um mantenedor é dizer "Não" para patches que você não quer.

Não se sinta culpado sobre não querer aceitar a contribuição de alguém. A primeira regra para o open source, [de acordo com](https://twitter.com/solomonstre/status/715277134978113536) @shykes: _"O não é temporário, o sim é para sempre"_ Enquanto empatizar com o entusiasmo de outras pessoas é uma coisa boa, rejeitar uma contribuição não é o mesmo que rejeitar a pessoa por trás dela.

Por fim, se uma contribuição não é boa o suficiente, você não tem obrigação de aceitá-la. Seja gentil e responsivo quando as pessoas contribuirem para seu projeto, mas só aceite mudanças que você realmente acredita que farão seu projeto melhorar. Quanto mais praticar dizer não, mais fácil fica. Prometo.

### Seja proativo

Para reduzir o volume de contribuições indesejadas, em primeiro lugar explique o processo do seu projeto para envio e aceitação de contribuições no seu guia de contribuição.

Se você estiver recebendo muitas contribuições de baixa qualidade, peça aos contribuintes que façam um trabalho em antemão, como por exemplo:

* Preencha um template ou checklist para Issues e Pull requests
* Abra um novo Issue ante de enviar um Pull request

Se eles não seguirem as regras, feche imediatamente o Issue e aponte para sua documentação.

Enquanto essa abordagem pode parecer rude no começo, ser proativo é na verdade bom para as duas partes. Isso reduz as chances de que alguém vai colocar muitas horas perdidas de trabalho em um Pull request que você não vai aceitar. E isso faz sua carga de trabalho mais fácil de gerenciar.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/125011" class="pquote-avatar" alt="avatar">
  Idealmente, explique a eles no arquivo CONTRIBUTING.md como podem ter uma indicação melhor no futuro de que coisas seriam ou não seriam aceitas antes de começarem o trabalho.
  <p markdown="1" class="pquote-credit">
— @mikemcquaid, ["Gentilmente fechando Pull requests"](https://github.com/blog/2124-kindly-closing-pull-requests)
  </p>
</aside>

Às vezes, quando você diz não, seu potencial contribuidor pode se sentir chateado ou criticar sua decisão. Se o comportamento se tornar hostil, [siga esses passos para contornar a situação](https://github.com/jonschlinkert/maintainers-guide-to-staying-positive#action-items) ou até retire-os de sua comunidade, se eles não estiverem dispostos a colaborar construtivamente.

### Adote mentoria

Talvez alguém na sua comunidade regularmete envie contribuições que não preenchem os padrões do seu projeto. Pode ser frustrante para ambas as partes repetidamente passarem por rejeições.

Se você vir que alguém está empolgado com seu projeto, mas precisa de um pouco de polimento, seja paciente. Explique claramente em cada situação por que suas contribuições não passam pelas expectativas do projeto. Tente mostrá-los uma tarefa mais fácil ou menos ambígua, como um Issue com a tag _"bom primeiro bug"_ para que iniciem. Se você tiver tempo, considere dar mentoria durante a primeira contribuição ou achar alguém na sua comunidade que esteja disposto a fazê-lo.

## Alavancando sua comunidade

Você não tem que fazer tudo sozinho. A comunidade do seu projeto existe por uma razão! Mesmo que você ainda não tenha uma comunidade contribuinte ativa, se tiver muitos usuários, coloque-os para trabalhar.

### Distribua a carga de trabalho

If you're looking for others to pitch in, start by asking around.

When you see new contributors making repeated contributions, recognize their work by offering more responsibility. Document how others can grow into leadership roles if they wish.

Encouraging others to [share ownership of the project](../building-community/#share-ownership-of-your-project) can greatly reduce your own workload, as @lmccart discovered on her project, [p5.js](https://github.com/processing/p5.js?files=1).

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/191056?v=3&s=460" class="pquote-avatar" alt="avatar">
  I’d been saying, “Yeah, anyone can be involved, you don’t have to have a lot of coding expertise [...].” We had people sign up to come [to an event] and that’s when I was really wondering: is this true, what I’ve been saying? There are gonna be 40 people who show up, and it’s not like I can sit with each of them...But people came together, and it just sort of worked. As soon as one person got it, they could teach their neighbor.
  <p markdown="1" class="pquote-credit">
—  @lmccart, ["What Does “Open Source” Even Mean? p5.js Edition"](https://medium.com/@kenjagan/what-does-open-source-even-mean-p5-js-edition-98c02d354b39#.chnjlag7p)
  </p>
</aside>

If you need to step away from your project, either on hiatus or permanently, there's no shame in asking someone else to take over for you.

If other people are enthusiastic about its direction, give them commit access or formally hand over control to someone else. If someone forked your project and is actively maintaining it elsewhere, consider linking to the fork from your original project. It's great that so many people want your project to live on!

@progrium [found that](http://progrium.com/blog/2015/12/04/leadership-guilt-and-pull-requests/) documenting the vision for his project, [Dokku](https://github.com/dokku/dokku), helped those goals live on even after he stepped away from the project:

> I wrote a wiki page describing what I wanted and why I wanted it. For some reason it came as a surprise to me that the maintainers started moving the project in that direction! Did it happen exactly how I'd do it? Not always. But it still brought the project closer to what I wrote down.

### Deixe outros construirem as soluções que precisam

If a potential contributor has a different opinion on what your project should do, you may want to gently encourage them to work on their own fork.

Forking a project doesn't have to be a bad thing. Being able to copy and modify projects is one of the best things about open source. Encouraging your community members to work on their own fork can provide the creative outlet they need, without conflicting with your project's vision.

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/481677?v=3&s=400" class="pquote-avatar" alt="avatar">
  I cater to the 80% use case. If you are one of the unicorns, please fork my work. I won't get offended! My public projects are almost always meant to solve the most common problems; I try to make it easy to go deeper by either forking my work or extending it.
  <p markdown="1" class="pquote-credit">
— @geerlingguy, ["Why I Close PRs"](https://www.jeffgeerling.com/blog/2016/why-i-close-prs-oss-project-maintainer-notes)
  </p>
</aside>

The same applies to a user who really wants a solution that you simply don't have the bandwidth to build. Offering APIs and customization hooks can help others meet their own needs, without having to modify the source directly. @orta [found that](http://artsy.github.io/blog/2016/07/03/handling-big-projects/) encouraging plugins for CocoaPods led to "some of the most interesting ideas":

> It's almost inevitable that once a project becomes big, maintainers have to become a lot more conservative about how they introduce new code. You become good at saying "no", but a lot of people have legitimate needs. So, instead you end up converting your tool into a platform.

## Traga os robôs

Just as there are tasks that other people can help you with, there are also tasks that no human should ever have to do. Robots are your friend. Use them to make your life as a maintainer easier.

### Exija testes e outros checks para melhorar a qualidade do seu código

One of the most important ways you can automate your project is by adding tests.

Tests help contributors feel confident that they won't break anything. They also make it easier for you to review and accept contributions quickly. The more responsive you are, the more engaged your community can be.

Set up automatic tests that will run on all incoming contributions, and ensure that your tests can easily be run locally by contributors. Require that all code contributions pass your tests before they can be submitted. You'll help set a minimum standard of quality for all submissions. [Required status checks](https://help.github.com/articles/about-required-status-checks/) on GitHub can help ensure no change gets merged without your tests passing.

If you add tests, make sure to explain how they work in your CONTRIBUTING file.

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/812892?v=3&s=460" class="pquote-avatar" alt="avatar">
  I believe that tests are necessary for all code that people work on. If the code was fully and perfectly correct, it wouldn't need changes – we only write code when something is wrong, whether that's "It crashes" or "It lacks such-and-such a feature". And regardless of the changes you're making, tests are essential for catching any regressions you might accidentally introduce.
  <p markdown="1" class="pquote-credit">
— @edunham, ["Rust's Community Automation"](http://edunham.net/2016/09/27/rust_s_community_automation.html)
  </p>
</aside>

### Use ferramentas para automatizar tarefas básicas de manutenção

A boa notícia sobre manter projetos populares é que outros mantenedores provavelmente já encontraram problemas parecidos e criaram soluções para isso.

Existe uma [grande variedade de ferramentas disponíveis](https://github.com/integrations) para ajudar a automação de alguns aspectos do trabalho de manutenção. Alguns exemplos:

* [semantic-release](https://github.com/semantic-release/semantic-release) automatiza seus novos releases
* [mention-bot](https://github.com/facebook/mention-bot) menciona potenciais pessoas para revisarem os Pull requests
* [Danger](https://github.com/danger/danger) ajuda a automatização de revisão de código

Para informar bugs e outras contribuições comuns, o GitHub tem [templates de Issues e Pull requests](https://github.com/blog/2111-issue-and-pull-request-templates), os quais você pode criar para agilizar a comunicação que você receber. Você também pode configurar [filtros de email](https://github.com/blog/2203-email-updates-about-your-own-activity) para gerenciar as notificações de email.

Se você quiser avançar mais um passo, guias de estilo para o código e "linters" podem padronizar suas contribuições e torná-las mais fáceis de revisar e aceitar.

Contudo, se seus padrões forem muito complicados, pode ser que aumentem as barreiras para novas contribuições. Garanta que você só está adicionando regras o suficiente para facilitar a vida de todos.

Se você não tiver certeza que ferramentas usar, veja o que outros projetos populares usam, especialmente no seu ecossistemas. Por exemplo, como funciona o processo de contribuição para outros módulos em Node? Usar ferramentas e métodos similares vai tornar seu processo mais familiar para seus contribuidores alvo.

## É OK pausar

Trabalhar com open source já te trouxe alegrias. Talvez agora esteja começando a fazer você se sentir culpado ou evasivo.

Talvez você esteja pressionado ou com um sentimento de pavor quando pensa sobre seus projetos. E enquanto isso, os Issues e Pull requests continuam crescendo.

Exaustão é um problema real e sutil em trabalhos open source, especialmente entre mantenedor. Como responsável pela manutenção, sua felicidade é uma exigência não negociável para a sobrevivência de qualquer de seus projetos open source.

Pode parecer óbvio mas: dê um tempo! Você não precisa esperar a exaustão para tirar um tempo de folga. @brettcannon, um desenvolvedore core do Python, decidiu tirar [um mês de férias](http://www.snarky.ca/why-i-took-october-off-from-oss-volunteering) depois de 14 anos de trabalho voluntário em OSS.

Assim como qualquer tipo de trabalho, tirar folgas regulares vai te ajudar a se manter renovado, feliz e empolgado com seu trabalho.

<aside markdown="1" class="pquote">
  <img src="https://avatars1.githubusercontent.com/u/36432?v=3&s=400" class="pquote-avatar" alt="avatar">
  Mantendo o projeto WP-CLI, descobri que preciso me manter feliz em primeiro lugar, e definir fronteiras claras no meu envolvimento. O melhor balanceametno que encontrei foi 2-5 por semana como uma parte da minha rotina de trabalho. Isso mantém meu envolvimento uma paixão e um sentimento de não tanto quanto um trabalho exatamente. Como eu priorizo as tarefas que estou trabalhando, consigo fazer um progresso constante no que acho que é mais importante.
  <p markdown="1" class="pquote-credit">
— @danielbachhuber, ["Meus pesâmes, agora você é mantenedor de um projeto open source popular"](https://runcommand.io/2016/06/26/my-condolences-youre-now-the-maintainer-of-a-popular-open-source-project/)
  </p>
</aside>

Às vezes pode ser díficil tirar uma folga de um projeto open source quando parece que todos dependem de você. Há pessoas que podem até tentar fazer você se sentir culpado pela ausência.

Faça seu melhor para achar o apoio para seus usuários e para a comunidade enquanto estiver ausente do seu projeto. Se não puder encontrar o suporte necessário, tire a folga mesmo assim. Lembre-se de comunicar enquanto não estiver disponível de forma que as pessoas não se sintam confusas quando à falta de respostas.

Tirar folgas se aplica a mais que tirar férias. Se você não quer trabalhar em open source nos fins de semana ou durante o horário comercial, comunique essas expectativas para os outros, de forma que não te incomodem.

## Cuide primeiro de você!

Manter um projeto popular requer diferentes competências que nos estágios iniciais do crescimento, mas não deixa de ser menos gratificante. Como responsável pela manutenção do projeto, você vai aprender liderança e competências pessoais em um nível que poucas pessoas chegam à experimentar.Enquanto não é sempre fácil gerenciar, colocar limites claros e se manter num limite do que te deixa confortável te ajudará a se manter feliz, renovado e produtivo.
