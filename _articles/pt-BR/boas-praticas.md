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

Rules can be nerve-wracking to write down. Sometimes you might feel like you're policing other people's behavior or killing all the fun.

Written and enforced fairly, however, good rules empower maintainers. They prevent you from getting dragged into doing things you don't want to do.

Most people who come across your project don't know anything about you or your circumstances. They may assume you get paid to work on it, especially if it's something they regularly use and depend on. Maybe at one point you put a lot of time into your project, but now you're busy with a new job or family member.

All of this is perfectly okay! Just make sure other people know about it.

If maintaining your project is part-time or purely volunteered, be honest about how much time you have. This is not the same as how much time you think the project requires, or how much time others want you to spend.

Here are a few rules that are worth writing down:

* How a contribution is reviewed and accepted (_Do they need tests? An issue template?_)
* The types of contributions you'll accept (_Do you only want help with a certain part of your code?_)
* When it's appropriate to follow up (_ex. "You can expect a response from a maintainer within 7 days. If you haven't heard anything by then, feel free to ping the thread."_)
* How much time you spend on the project (_ex. "We only spend about 5 hours per week on this project"_)

[Jekyll](https://github.com/jekyll/jekyll/tree/master/docs), [CocoaPods](https://github.com/CocoaPods/CocoaPods/wiki/Communication-&-Design-Rules), and [Homebrew](https://github.com/Homebrew/brew/blob/bbed7246bc5c5b7acb8c1d427d10b43e090dfd39/docs/Maintainers-Avoiding-Burnout.md) are several examples of projects with ground rules for maintainers and contributors.

### Keep communication public

Don't forget to document your interactions, too. Wherever you can, keep communication about your project public. If somebody tries to contact you privately to discuss a feature request or support need, politely direct them to a public communication channel, such as a mailing list or issue tracker.

If you meet with other maintainers, or make a major decision in private, document these conversations in public, even if it's just posting your notes.

That way, anybody who joins your community will have access to the same information as someone who's been there for years.

## Aprendendo a dizer não

You've written things down. Ideally, everybody would read your documentation, but in reality, you'll have to remind others that this knowledge exists.

Having everything written down, however, helps depersonalize situations when you do need to enforce your rules.

Saying no isn't fun, but  _"Your contribution doesn't match this project's criteria"_ feels less personal than _"I don't like your contribution"_.

Saying no applies to many situations you'll come across as a maintainer: feature requests that don't fit the scope, someone derailing a discussion, doing unnecessary work for others.

### Keep the conversation friendly

One of the most important places you'll practice saying no is on your issue and pull request queue. As a project maintainer, you'll inevitably receive suggestions that you don't want to accept.

Maybe the contribution changes your project's scope or doesn't match your vision. Maybe the idea is good, but the implementation is poor.

Regardless of the reason, it is possible to tactfully handle contributions that don't meet your project's standards.

If you receive a contribution you don't want to accept, your first reaction might be to ignore it or pretend you didn't see it. Doing so could hurt the other person's feelings and even demotivate other potential contributors in your community.

<aside markdown="1" class="pquote">
  <img src="https://avatars3.githubusercontent.com/u/869950?v=3&s=400" class="pquote-avatar" alt="avatar" alt="@KrauseFx avatar">
  The key to handle support for large-scale open source projects is to keep issues moving. Try to avoid having issues stall. If you're an iOS developer you know how frustrating it can be to submit radars. You might hear back 2 years later, and are told to try again with the latest version of iOS.
  <p markdown="1" class="pquote-credit">
— @KrauseFx, ["Scaling open source communities"](https://krausefx.com/blog/scaling-open-source-communities)
  </p>
</aside>

Don't leave an unwanted contribution open because you feel guilty or want to be nice. Over time, your unanswered issues and PRs will make working on your project feel that much more stressful and intimidating.

It's better to immediately close the contributions you know you don't want to accept. If your project already suffers from a large backlog, @steveklabnik has suggestions for [how to triage issues efficiently](http://words.steveklabnik.com/how-to-be-an-open-source-gardener).

Secondly, ignoring contributions sends a negative signal to your community. Contributing to a project can be intimidating, especially if it's someone's first time. Even if you don't accept their contribution, acknowledge the person behind it and thank them for their interest. It's a big compliment!

If you don't want to accept a contribution:

* **Thank them** for their contribution
* **Explain why it doesn't fit** into the scope of the project, and offer clear suggestions for improvement, if you're able. Be kind, but firm.
* **Link to relevant documentation**, if you have it. If you notice repeated requests for things you don't want to accept, add them into your documentation to avoid repeating yourself.
* **Close the request**

You shouldn't need more than 1-2 sentences to respond. For example, when a user of [celery](https://github.com/celery/celery/) reported a Windows-related error, @berkerpeksag [responded with](https://github.com/celery/celery/issues/3383):

![celery screenshot](/assets/images/best-practices/celery.png)

If the thought of saying no terrifies you, you're not alone. As @jessfraz [put it](https://blog.jessfraz.com/post/the-art-of-closing/):

> I've talked to maintainers from several different open source projects, Mesos, Kubernetes, Chromium, and they all agree one of the hardest parts of being a maintainer is saying "No" to patches you don't want.

Don't feel guilty about not wanting to accept someone's contribution. The first rule of open source, [according to](https://twitter.com/solomonstre/status/715277134978113536) @shykes: _"No is temporary, yes is forever."_ While empathizing with another person's enthusiasm is a good thing, rejecting a contribution is not the same as rejecting the person behind it.

Ultimately, if a contribution isn't good enough, you're under no obligation to accept it. Be kind and responsive when people contribute to your project, but only accept changes that you truly believe will make your project better. The more often you practice saying no, the easier it becomes. Promise.

### Be proactive

To reduce the volume of unwanted contributions in the first place, explain your project's process for submitting and accepting contributions in your contributing guide.

If you're receiving too many low-quality contributions, require that contributors do a bit of work beforehand, for example:

* Fill out a issue or PR template/checklist
* Open an issue before submitting a PR

If they don't follow your rules, close the issue immediately and point to your documentation.

While this approach may feel unkind at first, being proactive is actually good for both parties. It reduces the chance that someone will put in many wasted hours of work into a pull request that you aren't going to accept. And it makes your workload easier to manage.

<aside markdown="1" class="pquote">
  <img src="https://avatars0.githubusercontent.com/u/125011" class="pquote-avatar" alt="avatar">
  Ideally, explain to them and in a CONTRIBUTING.md file how they can get a better indication in the future on what would or would not be accepted before they begin the work.
  <p markdown="1" class="pquote-credit">
— @mikemcquaid, ["Kindly Closing Pull Requests"](https://github.com/blog/2124-kindly-closing-pull-requests)
  </p>
</aside>

Sometimes, when you say no, your potential contributor may get upset or criticize your decision. If their behavior becomes hostile, [take steps to defuse the situation](https://github.com/jonschlinkert/maintainers-guide-to-staying-positive#action-items) or even remove them from your community, if they're not willing to collaborate constructively.

### Embrace mentorship

Maybe someone in your community regularly submits contributions that don't meet your project's standards. It can be frustrating for both parties to repeatedly go through rejections.

If you see that someone is enthusiastic about your project, but needs a bit of polish, be patient. Explain clearly in each situation why their contributions don't meet the expectations of the project. Try pointing them to an easier or less ambiguous task, like an issue marked _"good first bug,"_ to get their feet wet. If you have time, consider mentoring them through their first contribution, or find someone else in your community who might be willing to mentor them.

## Alavancando sua comunidade

You don't have to do everything yourself. Your project's community exists for a reason! Even if you don't yet have an active contributor community, if you have a lot of users, put them to work.

### Share the workload

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

### Let others build the solutions they need

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

### Require tests and other checks to improve the quality of your code

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

### Use tools to automate basic maintenance tasks

The good news about maintaining a popular project is that other maintainers have probably faced similar issues and built a solution for it.

There are a [variety of tools available](https://github.com/integrations) to help automate some aspects of maintenance work. A few examples:

* [semantic-release](https://github.com/semantic-release/semantic-release) automates your releases
* [mention-bot](https://github.com/facebook/mention-bot) mentions potential reviewers for pull requests
* [Danger](https://github.com/danger/danger) helps automate code review

For bug reports and other common contributions, GitHub has [Issue Templates and Pull Request Templates](https://github.com/blog/2111-issue-and-pull-request-templates), which you can create to streamline the communication you receive. You can also set up [email filters](https://github.com/blog/2203-email-updates-about-your-own-activity) to manage your email notifications.

If you want to get a little more advanced, style guides and linters can standardize project contributions and make them easier to review and accept.

However, if your standards are too complicated, they can increase the barriers to contribution. Make sure you're only adding enough rules to make everyone's lives easier.

If you're not sure which tools to use, look at what other popular projects do, especially those in your ecosystem. For example, what does the contribution process look like for other Node modules? Using similar tools and approaches will also make your process more familiar to your target contributors.

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
