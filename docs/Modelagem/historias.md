# História de Usuário

## O que é?
História de usuário é uma “breve declaração que descreve algo que o sistema deve fazer para o usuário." (Livro Engenharia de Requisitos. p. 214)
<br>

## Para que serve?
De acordo com Vazquez e Simões, a história de usuários serve para definir um escopo pouco detalhado, ou seja, não irá entrar no detalhamento dos passos a serem seguidos ou das regras de negócio aplicadas na tarefa do software.
<br>

## Metodologia
Para montarmos nossas histórias de usuários iremos utilizar a seguinte sintaxe: Como ____ eu quero ____ para que ____. O “Como” representa o tipo do usuário do aplicativo; o “eu quero” representa o objetivo, necessidade do cliente; finalmente, o "para que” representa o benefício adquirido ao final da história.
<br>

## Nossas Histórias de Usuário
| ID | História | Critérios de Aceitação |Rastreabilidade |
| -- | -- | -- | -- |
| HU01 | Eu, como um usuário, desejo visualizar notícias para que eu consiga me informar sobre o funcionamento do metrô | -Deve ter um botão no menu inicial que redireciona para a página de notícias <br> -Deve ter um botão que retorna para a página inicial |RF01 | 
| HU02 | Eu, como usuário, desejo poder visualizar o atual preço das passagens para que eu consiga saber quanto custa atualmente o bilhete do metrô | -Deve ter um botão no menu inicial que redireciona para a página que contém o preço da passagem <br> -Deve ter um botão que retorna para a página inicial | RF17 | 
| HU03 | Eu, como usuário, desejo visualizar o mapa da linha do metrô para que eu consiga ver todas as linhas de metrô existentes | -Deve ter um botão no menu inicial que redireciona para o mapa do metrô <br> -Deve ter um botão que retorna para a página inicial | RF06 |
| HU04 | Eu, como usuário, desejo receber mensagens com notificações sobre o Metrô-DF para que eu saiba se o metrô está funcionando normalmente | -Deve ter um botão no menu inicial que redireciona para a página de mensagens <br> -Deve ter um botão que retorna para a página inicial <br> -Deve pedir permissão para exibir notificações na tela do celular do usuário, fora do app |RF 22|
| HU05 | Eu, como usuario, desejo poder visualizar as estações para que eu consiga saber quais são as estações existentes | -Deve ter um botão no menu inicial que redireciona para a página de estações <br> -Deve ter, dentro da página de estações, um botão para selecionar a estação do DF desejada <br> -Deve ter um botão que retorna para a página inicial | RF09 |
| HU06 | Eu, como usuario, desejo poder visualizar o horário de funcionamento das estações para que eu consiga saber quando elas funcionam | -Deve ter um botão no menu inicial que redireciona para a página do horário dos trens <br> -Deve ter um botão que retorna para a página inicial | RF10 |
| HU07 | Eu, como usuário, desejo visualizar os serviços disponíveis em cada estação  para que eu saiba mais sobre as estações | -Deve ter um botão no menu inicial que redireciona para a página de informações das estações <br> -Deve ter, dentro da página de informações uma parte dedicada aos serviços disponíveis <br> -Deve ter um botão que retorna para a página inicia | RF14 | 
| HU08 | Eu, como usuário, desejo filtrar estações de acordo com os serviços disponibilizados para que eu consiga saber quais estações apresentam um determinado serviço | -Deve ter um botão no menu inicial que redireciona para a página de informações das estações <br> -Deve ter, dentro da página de informações uma opção de filtro <br> -Deve ter um botão que retorna para a página inicia  | RF15 |
| HU09 | Eu, como usuário, desejo visualizar a distância até as estações para que eu saiba quais são as estações mais próximas de onde estou | -Deve ter um botão no menu inicial que redireciona para a página de estações mais próximas <br> -Deve pedir permissão para ativar a localização para que o app encontre qual é a estação mais próxima <br> -Deve ter um botão que retorna para a página inicial  | RF12|
| HU10 | Eu, como usuário, desejo visualizar a localização das estações para que eu consiga saber como chegar até as estações | -Deve ter um botão no menu inicial que redireciona para a página de conhecer uma estação <br> -Deve ter, dentro da página de conhecer as estações, um mapa marcando o local da estação <br> -Deve ter um botão que ao clicar peça permissão para trocar para um aplicativo de GPS (Wase, Google Maps, entre outros) que irá guiar o usuário até a estação  <br> -Deve ter um botão que retorna para a página inicial | RF19 |
| HU11 | Eu, como usuário, desejo visualizar horários de trens para que eu consiga saber o tempo de chegada de um trem até uma estação específica | -Deve ter um botão no menu inicial que redireciona para a página de horários dos trens <br> -Deve ter, dentro da página de horário dos tren, dois botões para selecionar a “em qual estação você está?” e “para qual estação você vai?” <br> -Deve disponibilizar o tempo de chegada dos trens de uma estação para a outra  <br> -Deve ter um botão que retorna para a página inicial | RF02 |
| HU12 | Eu, como usuario desejo atualizar horários dos trens para que eu consiga saber se o tempo de chegada de um trem até uma estação específica mudou | -Deve ter um botão no menu inicial que redireciona para a página de horários dos trens <br> -Deve ter, dentro da página de horário dos trens, dois botões para selecionar a “em qual estação você está?” e “para qual estação você vai?” <br> -Deve disponibilizar o tempo de chegada dos trens de uma estação para a outra  <br> -Deve ter um botão de atualizar os horários <br> -Deve ter um botão que retorna para a página inicial  | RF03 |
| HU13 | Eu, como usuário, desejo favoritar horário dos trens para que eu saiba se o tempo de chegada de um trem até uma estação específica mudou| -Deve ter um botão no menu inicial que redireciona para a página de horários dos trens <br> -Deve ter, dentro da página de horário dos trens, dois botões para selecionar a “em qual estação em que está?” e “para qual estação você vai?” <br> -Deve disponibilizar o tempo de chegada dos trens de uma estação para a outra  <br> -Deve ter um botão para marcar como favorito <br> -Deve ter um botão que retorna para a página inicial  | RF03|
| HU14 | Eu, como usuario, desejo visualizar detalhes de um trajeto para que eu consiga saber como chegar ao meu destino | -Deve ter um botão no menu inicial que redireciona para a página de “vai pra onde?” <br> -Deve ter, dentro da página de “vai pra onde?”, dois botões para selecionar a “em qual estação em que está?” e “para qual estação você vai?” <br> -Deve disponibilizar detalhes do trajeto <br> -Deve ter um botão que retorna para a página inicial  | RF16 |
| HU15 | Eu, como usuario, desejo selecionar a estação de partida para que eu consiga planejar um trajeto | -Deve ter um botão no menu inicial que redireciona para a página de “vai pra onde?” <br> -Deve ter, dentro da página de “vai pra onde?”, dois botões e um deles deve ser o botão “em qual estação em que está?” para selecionar a estação de partida <br> -Deve ter um botão que retorna para a página inicial | RF20 |
| HU16 | Eu, como usuário, desejo selecionar a estação de destino para que eu consiga planejar um trajeto | -Deve ter um botão no menu inicial que redireciona para a página de “vai pra onde?” <br> -Deve ter, dentro da página de “vai pra onde?”, dois botões e um deles deve ser o botão “para qual estação você vai?” para selecionar a estação de destino <br> -Deve ter um botão que retorna para a página inicial | RF21 |
| HU17 | Eu, como usuario, desejo que o sistema responda rapidamente para que eu me mantenha informado o mais rápido possível | -Deve atualizar as notícias do metrô com frequencia | RNF07 |
| HU18 | Eu, como usuario, desejo executar a maioria das ações no app sem me cadastrar ou fazer login para que eu consiga simplificar a utilização do aplicativo | -Deve ter acesso, sem precisar de login, às funcionalidades de: “situação do metrô”, “horário dos trens”, “conheça as estações”, “vai para onde”e “informações” <br> -Deve ser capaz de falar com a ouvidoria apenas no modo anônimo | RF18 |
| HU19 | Eu, como usuário, desejo realizar cadastro na plataforma para que eu tenha acesso à ouvidoria | -Deve apresentar uma tela para criação da conta no Metro-DF <br> -Deve ter um botão que irá abrir a página de fazer o cadastro <br> -Deve concluir o cadastro salvando os dados do usuário <br> -Deve ser possível entrar em contato com a ouvidoria utilizando o cadastro do Metro-DF <br> -Deve ter um botão que retorna para a página inicial | RF07 |
| HU20 | Eu, como usuário cadastrado, desejo fazer login para que eu consiga usufruir dos privilégios de usuário logado | -Deve possuir cadastro no Metro-DF <br> -Deve possuir um botão na tela inicial para realizar login <br> -Deve ser capaz de realizar login <br> -Deve ser capaz de usufruir dos privilégios de usuário logado | RF08 |
| HU21 | Eu, como usuário cadastrado, desejo falar com a ouvidoria para que eu consiga fazer um elogio, denúncia, sugestão, solicitação, reclamação ou pedir informação | -Deve possuir cadastro no Metro-DF <br> -Deve ser capaz de realizar login <br> -Deve ser capaz de realizar um elogio, denúncia, sugestão, solicitação, reclamação ou pedir informação | RF04 |
| HU22 |  Eu, como usuário cadastrado, desejo recarregar o cartão do metrô para que eu não necessite ir fisicamente ao local, facilitando o processo de recarga | -Deve possuir cadastro no Metro-DF <br> -Deve possuir um botão na tela inicial para realizar login <br> -Deve ser capaz de realizar login <br> -Deve ser capaz de inserir os dados do método de pagamento <br> -Deve ser capaz de fazer a recarga do cartão  <br> -Deve ter um botão que retorna para a página inicial| RF05 |
| HU23 | Eu, como usuario, desejo que meus dados sejam mantidos de forma segura para que eu tenha minha privacidade mantida em segurança | -Deve ser capaz de pedir uma senha <br> -Deve ser capaz de habilitar a verificação em dois fatores <br> -Deve ter um botão que retorna para a página inicial | RNF02 |
<br>

## Referências
* Livro Engenharia de Requisitos: VAZQUEZ, Carlos Eduardo, SIMÕES, Guilherme Siqueira - Engenharia de Requisitos: Software Orientado ao Negócio. Disponível em: <https://plataforma.bvirtual.com.br/Acervo/Publicacao/160193> Acesso em: 2021 set. 08

* Link: Disponível em <https://www.youtube.com/watch?v=yG6GUqrje1k> Acesso em: 2021 set. 08
<br>

## Histórico de Versões
| Data     | Versão | Descrição                                        | Autores    | Revisor        |
| ---------- | --------- | ------------------------------------------ | ---------------- |-------- |
| 08/09/2021 | 1.0 | Criação do documento                   | Rafael e Felipe  |               |  
| 08/09/2021 | 2.0 | Detalhamento sobre histórioa de Usuários |Rafael| Felipe|
| 08/09/2021 | 2.1 | Criação das Histórias de Usuários    | Rafael e Felipe  |               |  
| 08/09/2021 | 2.2 | Adicionou Critérios de Aceitação| Rafael |      |
| 12/10/2021 | 2.3 | Fazendo algumas correções | Felipe Correia |      |
