# Informações do Projeto
`TÍTULO DO PROJETO`  

......  AVICEE: A vida como ela é ......

`CURSO` 

...... Engenharia de Software ......

## Participantes

......  
> Os membros do grupo são: 
> - Tito Chen
> - Thales Mattos
> - André Rodrigues
> - Vítor de Figueiredo
> - André Rodrigues
> - Vítor Fernandes
> - Arthur Felipe
>  ......

> Inclua a lista dos membros da equipe com seus nomes completos.
>
> Os membros do grupo são: 
> - Fulano da Silva
> - Ciclano Albuquerque

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

## Problema

......  Na sociedade atual, uma etapa essencial para o desenvolvimento de cada ser humano são os estudos e a aprendizagem. Desde pequeno os seres humanos são condicionados a aprender e aprender cada vez mais, num ciclo infinito. Durante nossas pesquisas, percebemos que uma grande parte das pessoas enfrentam problemas quando se trata de estudos, especialmente aqueles que estão em escolas, cursinhos e faculdades. Muitos acabam se perdendo nos prazos, não sabem o que realmente precisam focar quando começa a acumular matéria e até mesmo não sabem por onde começar quando se trata de um novo tema ou uma nova matéria. ......

> Nesse momento você deve apresentar o problema que a sua aplicação deve
> resolver. No entanto, não é a hora de comentar sobre a aplicação.
> Descreva também o contexto em que essa aplicação será usada, se
> houver: empresa, tecnologias, etc. Novamente, descreva apenas o que de
> fato existir, pois ainda não é a hora de apresentar requisitos
> detalhados ou projetos.
>
> Nesse momento, o grupo pode optar por fazer uso
> de ferramentas como Design Thinking, que permite um olhar de ponta a
> ponta para o problema.
>
> **Links Úteis**:
> - [Objetivos, Problema de pesquisa e Justificativa](https://medium.com/@versioparole/objetivos-problema-de-pesquisa-e-justificativa-c98c8233b9c3)
> - [Matriz Certezas, Suposições e Dúvidas](https://medium.com/educa%C3%A7%C3%A3o-fora-da-caixa/matriz-certezas-suposi%C3%A7%C3%B5es-e-d%C3%BAvidas-fa2263633655)
> - [Brainstorming](https://www.euax.com.br/2018/09/brainstorming/)

## Objetivos

......  Este projeto tem por objetivo facilitar a vida de todos os estudantes, independente de sua área, foco, objetivo com os estudos e entregar uma solução que agregue no trabalho dos docentes. com ferramentas de gestão de prazos e de estudos(individuais e em grupo), planejamento de estudos, dinâmicas e metodologias de estudos variadas, de acordo com cada um dos usuários, além de possibilitar uma melhor organização por parte dos professores em relação às suas aulas e prazos, de forma simples e prática para seus alunos. ......

> Aqui você deve descrever os objetivos do trabalho indicando que o
> objetivo geral é desenvolver um software para solucionar o problema
> apresentado acima. Apresente também alguns (pelo menos 2) objetivos
> específicos dependendo de onde você vai querer concentrar a sua
> prática investigativa, ou como você vai aprofundar no seu trabalho.
> 
> **Links Úteis**:
> - [Objetivo geral e objetivo específico: como fazer e quais verbos utilizar](https://blog.mettzer.com/diferenca-entre-objetivo-geral-e-objetivo-especifico/)

## Justificativa

......  Muitas pessoas sofrem constantemente com o despreparo para a realização de projetos já programados, isso se deve, em grande parte, por conta da falta de organização destes indivíduos. Como os integrantes do grupo são bem familiarizados com o ambiente escolar e muitos passaram pelas dificuldades explicitadas pelos entrevistados, o tratamento escolhido para este tema foi com base nas entrevistas e análise de qual será a solução mais otimizada. ......

> Descreva a importância ou a motivação para trabalhar com esta aplicação
> que você escolheu. Indique as razões pelas quais você escolheu seus
> objetivos específicos ou as razões para aprofundar em certos aspectos
> do software.
> 
> O grupo de trabalho pode fazer uso de questionários, entrevistas e
> dados estatísticos, que podem ser apresentados, com o objetivo de
> esclarecer detalhes do problema que será abordado pelo grupo.
>
> **Links Úteis**:
> - [Como montar a justificativa](https://guiadamonografia.com.br/como-montar-justificativa-do-tcc/)

## Público-Alvo

......  Temos por base na seleção de público alvo as seguintes características:
Pessoas imersas no mundo acadêmico, faixa etária entre 16 e 40 anos, usuários de celulares e mobiles, que tenham interesse em melhorar sua rotina de estudos e agilizar o processo de aprendizagem.
 ......

> Descreva quem serão as pessoas que usarão a sua aplicação indicando os
> diferentes perfis. O objetivo aqui não é definir quem serão os
> clientes ou quais serão os papéis dos usuários na aplicação. A ideia
> é, dentro do possível, conhecer um pouco mais sobre o perfil dos
> usuários: conhecimentos prévios, relação com a tecnologia, relações
> hierárquicas, etc.
>
> Adicione informações sobre o público-alvo por meio de uma descrição
> textual, ou diagramas de personas, mapa de stakeholders, ou como o
> grupo achar mais conveniente.
> 
> **Links Úteis**:
> - [Público-alvo: o que é, tipos, como definir seu público e exemplos](https://klickpages.com.br/blog/publico-alvo-o-que-e/)
> - [Qual a diferença entre público-alvo e persona?](https://rockcontent.com/blog/diferenca-publico-alvo-e-persona/)
 
# Especificações do Projeto

......  Este documento tem por objetivo o registro de todo o projeto AVICEE, desde as suas pesquisas e análises de mercado quanto à sua execução e decorrer de seu desenvolvimento, deixando claro cada ação e seus objetivos.  ......

> Apresente uma visão geral do que será abordado nesta parte do
> documento, enumerando as técnicas e/ou ferramentas utilizadas para
> realizar a especificações do projeto

## Personas e Mapas de Empatia

......  
1- Cleiton é um homem de estatura média, cabelos ondulados, 24 anos e está na faculdade. Ele tem o costume de utilizar bastante seu celular para as suas atividades diárias e também seu notebook, é uma pessoa muito alegre e extrovertida, porém prioriza sair para o bar ao invés dos estudos. Seu sonho é ser um grande historiador que viaja mundo a fora, ser famoso na sua área e financeiramente independente. Ele, muitas vezes está mais preocupado com os jogos online do que com a faculdade e apesar de querer ser um grande historiador, é desfocado com relação aos estudos e faculdade. Cleiton é uma pessoa relativamente tímida que precisa beber para socializar, seus amigos dizem que apesar de desfocado ele é extremamente inteligente.

2- Carlos é um jovem de 21 anos, baixo e cabelo cacheado e castanho. Ele usa muito celular, durante sua caminhada, escutando música. Ele joga bastante, tem uma carteira digital e sempre confere ela por não saber quanto está sobrando nela. Seu sonho é ser um médico rico com 2 filhos e comprar um computador de 5 mil reais. Ele gosta de pessoas bem humoradas e relaxadas. Sempre que alguém o ajuda ele fica contente. Ele é uma pessoa bem ansiosa pois medicina é um curso bem concorrido e praticava muitos esportes na época da escola.

3- Soraya é uma professora de escola particular de 35 anos, estatura média, cabelo ondulado e castanho que adora ler e ouvir podcast. Ela utiliza o notebook para a preparação das aulas em casa, além de utilizar o telefone para manter contato com os alunos e tirar suas duvidas basicas. Seu sonho é igualdade no ensino para todos e para isso, ela mantém paciência com os alunos e se preocupada se estão ou não aprendendo, além disso, ela se preocupa sobre a falta de interesse de alguns alunos junto da procrastinação e têm dificuldade em incentivar seus alunos nos estudos.
......


> Relacione as personas identificadas no seu projeto e os respectivos mapas de empatia. Lembre-se que 
> você deve ser enumerar e descrever precisamente e de forma
> personalizada todos os principais envolvidos com a solução almeja. 
> 
> Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina
> e/ou nos seguintes links:
>
> **Links Úteis**:
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Como fazer um mapa de empatia - Vídeo](https://www.youtube.com/watch?v=JlKHGpVoA2Y)
> 
> 
> **Exemplo de Persona**
> 
> ![Exemplo de Persona](imaages/../images/persona.png)
> 
> Fonte: [Como criar uma persona para o seu negócio](https://raissaviegas.com.br/como-criar-uma-persona/)


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

A maioria dos usuários vê necessidade em ter um app para os ajudar a se organizar, visto que a maioria tem problemas com relação a isso. Tanto na parte de saber o que priorizar nos estudos, quanto na parte de saber dividir o que estudar no dia. A maioria dos usuários já utiliza dos meios tecnológicos para estudar o que irá facilitar o uso do software em desenvolvimento.

“ Eu como ex professora de faculdade, sinto a necessidade em um app que listasse as minhas atividade da mais importante para a menos importante.”

" Eu como pessoa com TDAH quero um aplicativo que me notifique meus prazos, pois esqueço, diariamente, os prazos que eu possuo para entregar minhas atividades."

" Eu como trabalhador e estudante quero um aplicativo que me ajude a me organizar, pois possuo dificuldade em organizar meu tempo para ambas atividades."

" Eu como professor quero um aplicativo para recomendar meus alunos uma maneira de organizar os estudos, eles estão com dificuldades em se organizar para dar atenção para suas matérias."

" Eu como estudante, desejo uma plataforma para manter minhas notas e metas bem visíveis."


> Apresente aqui as histórias de usuário que são relevantes para o
> projeto de sua solução. As Histórias de Usuário consistem em uma
> ferramenta poderosa para a compreensão e elicitação dos requisitos
> funcionais e não funcionais da sua aplicação. Se possível, agrupe as
> histórias de usuário por contexto, para facilitar consultas
> recorrentes à essa parte do documento.
>
> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

Login
Cada usuário, uma vez que possa ser cadastrado por instituição, precisa realizar o login 
para que os calendários e atividades possam ser sincronizados com cada um de seus docentes.
Calendário
Área de calendário, no qual cada usuário possa acessar de forma rápida suas entregas pendentes e seus planejamentos de estudo, de forma sincronizada com sua instituição ou plano de estudo escolhido.
Kanban
Uma aba para kanban personalizável, no qual pode ser incluído vários usuários para trabalhos e projetos em grupo, ou pode ser usado de forma individual para planejamento pessoal. Recomendações de kanban populares
Boletim
Área restrita para usuários inscritos em alguma instituição ou curso didático, mostrando suas notas, de projetos entregues, corrigidos, em correção e pendentes. Sistema de notas e repescagens específicas para cada modalidade.
Plano de estudos
Área no qual podem ser apresentados, criados e escolhidos planos de estudos. Cada plano de estudo deve sincronizar com o calendário e com o kanban. Nele deverá ser possível a publicação de planos pessoais para o público, e a busca por planos específicos.
Q&A
Um pequeno FAQ, de simples perguntas e respostas. Inspiração: brainly.
Anotações
Um bloco de notas para cada usuário, dividido em categorias, matérias e outras classificações escolhidas pelo usuário. Possível integração com o calendário.
Complementares
Área de conhecimentos complementares. Local onde será possível pesquisar por tópicos/matérias, para poder encontrar videoaulas, documentos e outras fontes de estudos para qualquer assunto, sem o compromisso de um plano de estudo estruturado.
Utilitários de estudos
Áreas com ferramentas e utilitários para estudos, como documentos formatados para download, Playlists de músicas, modelos de apresentação, etc
Notificações
Área de notificações para saber sobre menções, tarefas pendentes e lançamento de notas e trabalhos



### Requisitos não Funcionais

Modo escuro e alto contraste
Temas e templates do próprio app para personalização do usuário, incluindo música de fundos e notificações personalizadas
Integração com o discord
Integração com o discord para sincronizar menções, chats, chamadas, agendamentos e salas de estudo.
Integração com deezer/spotify
Integração com deezer e spotify para selecionar músicas para os estudos, importação de playlists e outros.
Mudança de contas e segurança
Sistema para fácil mudança de contas, para melhor organização dentro do app. Sistema de MFA para garantir a segurança de cada conta, especialmente as cadastradas por instituições.


> Com base nas Histórias de Usuário, enumere os requisitos da sua
> solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.
> 
> **Links Úteis**:
> 
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


> Enumere as restrições à sua solução. Lembre-se de que as restrições
> geralmente limitam a solução candidata.
> 
> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


# Projeto de Interface

......  COLOQUE AQUI O SEU TEXTO DE INTRODUÇÃO ......

> Apresente as principais interfaces da solução. Discuta como 
> foram elaboradas de forma a atender os requisitos funcionais, não
> funcionais e histórias de usuário abordados nas [Especificações do
> Projeto](#especificações-do-projeto).

## User Flow

......  INCLUA AQUI O DIAGRAMA COM O FLUXO DO USUÁRIO NA APLICAÇÃO ......

> Fluxo de usuário (User Flow) é uma técnica que permite ao desenvolvedor
> mapear todo fluxo de telas do site ou app. Essa técnica funciona
> para alinhar os caminhos e as possíveis ações que o usuário pode
> fazer junto com os membros de sua equipe.
>
> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)
>
> **Exemplo**:
> 
> ![Exemplo de UserFlow](images/userflow.jpg)


## Wireframes

......   ......

> Wireframes são protótipos das telas da aplicação usados em design de interface para sugerir a
> estrutura de um site web e seu relacionamentos entre suas
> páginas. Um wireframe web é uma ilustração semelhante ao
> layout de elementos fundamentais na interface.
> 
> **Links Úteis**:
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> 
> **Exemplo**:
> 
> ![Exemplo de Wireframe](images/wireframe-example.png)


# Metodologia

...... 
 A metodologia aplicada pelo grupo foi a metodolgia SCRUM, onde a tentativa de reunir o grupo era feita diariamente. Cada membro escolhia com o que iria trabalhar e foi utilizado o Trello para a organização e o replit para a junção do código. O GitHub foi preenchido ao final das sprints.
 O Design Thinking foi feito em apenas um dia, já com a divisão de papeis feito nela, tendo o trello para acompanhar o andamento das tarefas.
......

> Nesta parte do documento, você deve apresentar a metodologia 
> adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, 
> a divisão de papéis e tarefas, as ferramentas empregadas e como foi realizada a
> gestão de configuração do projeto via GitHub.
>
> Coloque detalhes sobre o processo de Design Thinking e a implementação do Framework Scrum seguido
> pelo grupo. O grupo poderá fazer uso de ferramentas on-line para acompanhar
> o andamento do projeto, a execução das tarefas e o status de desenvolvimento
> da solução.
> 
> **Links Úteis**:
> - [Tutorial Trello](https://trello.com/b/8AygzjUA/tutorial-trello)
> - [Gestão ágil de projetos com o Trello](https://www.youtube.com/watch?v=1o9BOMAKBRE)
> - [Gerência de projetos - Trello com Scrum](https://www.youtube.com/watch?v=DHLA8X_ujwo)
> - [Tutorial Slack](https://slack.com/intl/en-br/)

## Divisão de Papéis

> - Vítor de Figueiredo - Designer
> - Augusto Baldiotti - Desenvolvedor
> - Vítor Fernandes - Desenvolvedor
> - Thales Mattos - Desenvolvedor
> - André Rodrigues - Desenvolvedor
> - Tito Chen - Desenvolvedor
> - Arthur Felipe - Desenvolvedor

......  A equipe será organizada em 6 desenvolvedores e um designer, sendo estes sem nenhuma parte pré definida. Com a organização do backlog, cada um realizará o processo que mais lhe for conveniente. ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
>
> **Links Úteis**:
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)


## Ferramentas

......  Replit, VisualStudio Code  ......

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/app/board/uXjVOBMZXB4=/ | 
|Repositório de código | GitHub | https://github.com/ICEI-PUC-Minas-PPLES-TI/plf-es-2022-1-ti1-7924100-t1-g9-dific-na-organizacao-de-estudos | 
|Hospedagem do site | Heroku |  https://XXXXXXX.herokuapp.com | 
|Protótipo Interativo | MavelApp ou Figma | https://figma.com/XXXXXXX | 

>
> Liste as ferramentas empregadas no desenvolvimento do
> projeto, justificando a escolha delas, sempre que possível.
> 
> As ferramentas empregadas no projeto são:
> 
> - Editor de código.
> - Ferramentas de comunicação
> - Ferramentas de diagramação
> - Plataforma de hospedagem
> 
> O editor de código foi escolhido porque ele possui uma integração com o
> sistema de versão. As ferramentas de comunicação utilizadas possuem
> integração semelhante e por isso foram selecionadas. Por fim, para criar
> diagramas utilizamos essa ferramenta por melhor captar as
> necessidades da nossa solução.
> 
> **Links Úteis - Hospedagem**:
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Crie seu Site com o HostGator](https://www.hostgator.com.br/como-publicar-seu-site)
> - [GoDady](https://br.godaddy.com/how-to)
> - [GitHub Pages](https://pages.github.com/)

## Controle de Versão

......  COLOQUE AQUI O SEU TEXTO ......

> Discuta como a configuração do projeto foi feita na ferramenta de
> versionamento escolhida. Exponha como a gerência de tags, merges,
> commits e branchs é realizada. Discuta como a gerência de issues foi
> realizada.
> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
> 
> O projeto segue a seguinte convenção para o nome de branchs:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> Quanto à gerência de issues, o projeto adota a seguinte convenção para
> etiquetas:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida
>
> **Links Úteis**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
> - [5 Git Workflows & Branching Strategy to deliver better code](https://zepel.io/blog/5-git-workflows-to-improve-development/)
>
> **Exemplo - GitHub Feature Branch Workflow**:
>
> ![Exemplo de Wireframe](images/Github-Workflow.png)

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  Uma aplicação web para resolver problemas de falta de organização através de um calendário interativo ......

## Tecnologias Utilizadas

......  HTML para produzir o visual
CSS para otimizar
Javascript para a interação
replit para rodar o software .....

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  A solução encontrada pelo grupo foi um calendário simples com uma aba de tarefas para digitação......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  A lista de tarefas é dinâmica possibilitando ao usuário adicionar novas tarefas, apagá-las e sinalizar quais tarefas já foram concluídas. Testes foram realizados, e as tarefas realmente ficam salvas no local storage.
O boletim foi criado para que o aluno possa colocar as suas notas e se organizar, ele foi testado em todos os aspectos, apresentando responsividade, todos os botões tinham suas funções funcionando corretamente e o processo principal que é o de adicionar as notas também estava funcionando perfeitamente, juntamente com a barra de pesquisa de notas.
O template e os campos de login e cadastro, o que foi testado foi a interatividade e responsividade da página. O botão de logar e cadastrar, são bloqueados, fazendo com que o seja liberado, apenas após a completude dos campos do formulário.
 ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  Foram selecionados foram testes manuais para seguir o plano do usuário ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......   ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  Os testes foram feitos manualmente, descobrindo erros e os pontos que deveria ser consertados ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  [COLOQUE AQUI O SEU TEXTO](https://css-tricks.com)
https://fontawesome.com
https://www.w3schools.com......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
