# Cenários

## Introdução

Abordagem utilizada para descrever as situações de uso do sistema pelos seus <a href="../lexico#usuario">usuários</a> e os relacionamentos. Na técnica, utiliza-se de abstrações para compreender as interações que ocorrem no sistema e elicitar a parte comportamental do mesmo.

<span id="c1"></span> 

## Cenário 1

| Título | <a href="../lexico#situacao">Situação</a> do metrô |
| ------ | ----------------- |
| Objetivo | Saber a atual <a href="../lexico#situacao">situação</a> do Metrô DF |
| Contexto | Ocorre em página vinculada à página inicial do <a href="../lexico#aplicativo">Aplicativo</a> |
| Atores | <a href="../lexico#usuario">Usuário</a> |
| Recursos | <a href="../lexico#aplicativo">Aplicativo</a>  instalado e acesso à internet |
| Episódios | <a href="../lexico#usuario">Usuário</a> deseja saber se a <a href="../lexico#circulacao">circulação</a> dos <a href="../lexico#trem">trens</a> está normal no <a href="../lexico#sentido">sentido</a> Samambaia-Central<br> <a href="../lexico#usuario">Usuário</a> deseja saber se a <a href="../lexico#circulacao">circulação</a> dos <a href="../lexico#trem">trens</a> está normal no <a href="../lexico#sentido">sentido</a> Ceilândia-Central |
| Exceção | Sem conexão com a internet<br>Sistema fora do ar |

<span id="c2"></span> 

## Cenário 2

| Título | <a href="../lexico#horario">Horário</a>  dos <a href="../lexico#trem">tre</a> |
| ------ | ----------------- |
| Objetivo | Saber quando o próximo <a href="../lexico#trem">trem</a> passará na <a href="../lexico#estacao">estação</a> de partida rumo à <a href="../lexico#estacao">estação</a> de destino |
| Contexto | Ocorre em página vinculada à página inicial do <a href="../lexico#aplicativo">Aplicativo</a>, o <a href="../lexico#usuario">Usuário</a> deve fornecer <a href="../lexico#estacao">estações</a> de partida e destino |
| Atores | <a href="../lexico#usuario">Usuário</a> |
| Recursos | <a href="../lexico#aplicativo">Aplicativo</a> instalado e acesso à internet |
| Episódios | <a href="../lexico#usuario">Usuário</a> na <a href="../lexico#estacao">estação</a> de partida ou à caminho da mesma, deseja saber o <a href="../lexico#horario">horário</a>  do próximo <a href="../lexico#trem">trem</a> para seu destino |
| Exceção | Sem conexão com a internet<br>Sistema fora do ar |

<span id="c3"></span> 

## Cenário 3

| Título | Ver notícias |
| ------ | ------------ |
| Objetivo | Se atualizar quanto à novidades relativas ao Metrô DF |
| Contexto | Ocorre na página inicial do <a href="../lexico#aplicativo">Aplicativo</a> |
| Atores | <a href="../lexico#usuario">Usuário</a> |
| Recursos | <a href="../lexico#aplicativo">Aplicativo</a> instalado e acesso à internet |
| Episódios | <a href="../lexico#usuario">Usuário</a> navega pelas notícias no <a href="../lexico#aplicativo">Aplicativo</a><br><a href="../lexico#usuario">Usuário</a> se interessa por uma notícia e à selecionou para entrar em seu contexto |
| Exceção | Sem conexão com a internet<br>Sistema fora do ar |

<span id="c4"></span> 

## Cenário 4

| Título | Conhecer estações |
| ------ | ----------------- |
| Objetivo | Visualizar informações relativas à <a href="../lexico#estacao">estação</a> específica |
| Contexto | Ocorre em página vinculada à página inicial do <a href="../lexico#aplicativo">Aplicativo</a> |
| Atores | <a href="../lexico#usuario">Usuário</a> |
| Recursos | <a href="../lexico#aplicativo">Aplicativo</a> instalado e acesso à internet |
| Episódios | <a href="../lexico#usuario">Usuário</a> deseja visualizar estabelecimentos e locais próximos à <a href="../lexico#estacao">estação</a> <br><a href="../lexico#usuario">Usuário</a> deseja visualizar <a href="../lexico#servicos">serviços</a> disponíveis na <a href="../lexico#estacao">estação</a> <br><a href="../lexico#usuario">Usuário</a> deseja visualizar  <a href="../lexico#mapa">mapa</a> dos arredores da <a href="../lexico#estacao">estação</a> |
| Exceção | Sem conexão com a internet<br>Sistema fora do ar |

<span id="c5"></span> 

## Cenário 5

| Título | Planejar <a href="../lexico#trajeto">trajeto</a> |
| ------ | ----------------- |
| Objetivo | Fazer planejamento do <a href="../lexico#trajeto">trajeto</a> a ser percorrido |
| Contexto | Ocorre em página vinculada à página inicial do <a href="../lexico#aplicativo">Aplicativo</a>, o <a href="../lexico#usuario">Usuário</a> deve fornecer <a href="../lexico#estacao">estações</a> de partida e destino |
| Atores | <a href="../lexico#usuario">Usuário</a> |
| Recursos | <a href="../lexico#aplicativo">Aplicativo</a> instalado e acesso à internet |
| Episódios | <a href="../lexico#usuario">Usuário</a> deseja saber quanto tempo levará o <a href="../lexico#trajeto">trajeto</a><br><a href="../lexico#usuario">Usuário</a> deseja se haverá transferência de <a href="../lexico#trem">trem</a> no <a href="../lexico#trajeto">trajeto</a><br><a href="../lexico#usuario">Usuário</a> deseja visualizar detalhamento do <a href="../lexico#trajeto">trajeto</a> |
| Exceção | Sem conexão com a internet<br>Sistema fora do ar |

<span id="c6"></span> 

## Cenário 6

| Título | Falar com a <a href="../lexico#ouvidoria">ouvidoria</a> |
| ------ | --------------------- |
| Objetivo | Reportar algo à <a href="../lexico#ouvidoria">ouvidoria</a> |
| Contexto | Ocorre em página vinculada à página inicial do <a href="../lexico#aplicativo">Aplicativo</a>, dependedo do que deseja reportar, é necessário que <a href="../lexico#usuario">Usuário</a> tenha  <a href="../lexico#cadastrar">cadastro</a>, para os casos de reclamação e denúncia pode-se manter o anonimato |
| Atores | <a href="../lexico#usuario">Usuário</a> e <a href="../lexico#ouvidoria">ouvidoria</a> do Metrô DF |
| Recursos | <a href="../lexico#aplicativo">Aplicativo</a> instalado e acesso à internet |
| Episódios | <a href="../lexico#usuario">Usuário</a> deseja fazer elogio ao Metrô DF<br><a href="../lexico#usuario">Usuário</a> deseja fazer sugestão ao Metrô DF<br><a href="../lexico#usuario">Usuário</a> deseja fazer solicitação ao Metrô DF<br><a href="../lexico#usuario">Usuário</a> deseja pedir informação ao Metrô DF<br><a href="../lexico#usuario">Usuário</a> deseja fazer reclamação ao Metrô DF<br><a href="../lexico#usuario">Usuário</a> deseja fazer denúncia ao Metrô DF<br> |
| Exceção | Sem conexão com a internet<br>Sistema fora do ar |

<span id="c7"></span> 

## Cenário 7

| Título | Visualizar informações |
| ------ | ---------------------- |
| Objetivo | Consultar informações relativas ao Metrô DF |
| Contexto | Ocorre em página vinculada à página inicial do <a href="../lexico#aplicativo">Aplicativo</a> |
| Atores | <a href="../lexico#usuario">Usuário</a> |
| Recursos | <a href="../lexico#aplicativo">Aplicativo</a> instalado e acesso à internet |
| Episódios | <a href="../lexico#usuario">Usuário</a> deseja consultar valor da passagem<br><a href="../lexico#usuario">Usuário</a> deseja visualizar <a href="../lexico#mapa">mapa</a><br><a href="../lexico#usuario">Usuário</a> deseja visualizar <a href="../lexico#horario">horários</a> de funcionamento<br><a href="../lexico#usuario">Usuário</a> deseja entrar em <a href="../lexico#contato">contato</a><br><a href="../lexico#usuario">Usuário</a> deseja alertar perda de objeto |
| Exceção | Sem conexão com a internet<br>Sistema fora do ar |

## Cenário 8

| Título | Visualizar mensagens |
| ------ | -------------------- |
| Objetivo | Visualizar <a href="../lexico#mensagem">mensagens</a> sobre informações pertinentes em relação à <a href="../lexico#situacao">situação</a> do Metrô DF |
| Contexto | Ocorre em página vinculada à pagina inicial do <a href="../lexico#aplicativo">Aplicativo</a> |
| Atores | <a href="../lexico#usuario">Usuário</a> |
| Recursos | <a href="../lexico#aplicativo">Aplicativo</a> instalado e acesso à internet |
| Episódios | <a href="../lexico#usuario">Usuário</a> deseja visualizar <a href="../lexico#mensagem">mensagens</a> |
| Exceção | Sem conexão com a internet<br>Sistema fora do ar |

## Referências 
SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10;

## Histórico de Versões
| Data       | Versão | Descrição                                       | Autores          | Revisor          |
| ---------- | ------ | ---------------------------------------------   | ---------------- | ---------------- |
| 19/08/2021 |  0.1   | Criação e desenvolvimento do documento | João Victor, Pedro Daniel |                  |
| 15/10/2021 |  0.2   | Linkagem com léxicos e criação dos links | Hérya|                  |
