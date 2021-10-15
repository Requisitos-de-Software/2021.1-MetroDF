# Forward-From

## Introdução
<p align="justify">A rastreabilidade é uma característica de sistemas relacionada à habilidade de rastrear os requisitos ao longo de todo o ciclo de vida. A rastreabilidade permite ligar os requisitos às suas fontes e aos artefatos criados a partir deles.</p>

<p align="justify"> A rastreabilidade <i>forward-from</i> liga os requisitos aos artefatos a eles vinculados.</p>

## Metodologia
### Meta-Modelo de Toranzo
De acordo com o Meta-Modelo de Toranzo, as informações a serem rastreadas devem ser classificadas em quatro níveis:

1. Ambiental: informações oriundas do contexto no qual a organização está inserida;

2. Organizacional: informações pertencentes à organização;

3. Gerencial: informações que auxiliam a gerência do projeto;

4. Desenvolvimento: informações relacionadas aos artefatos gerados ao longo do processo de desenvolvimento.

Neste modelo, os principais elos de rastreabilidade definidos são:

* Satisfação: classe origem tem dependência de satisfação com classe destino;

* Recurso: classe origem tem dependência de recurso com classe destino; 

* Responsabilidade: registra a participação, responsabilidade e ação de pessoas sobre artefatos;

* Representação: captura a representação ou modelagem dos requisitos em outras linguagens;

* Alocado: classe origem está relacionada à classe destino, que representa um subsistema;

* Agregação: indica "composição" de elementos.


## Matrizes
### Requisitos Funcionais

| ID | Descrição | Cenários | Léxicos | Caso de Uso | História de Usuário | Nível | Elo | Telas |
| -- | --------- | ------ | ----- | --- | ----- | ---- | --- | --- |  
| 1 | O usuário deve ser capaz de visualizar notícias | <a href="../../Modelagem/cenarios#c7">Cenário 7</a>  | <a href="../../Modelagem/lexico#noticia">notícia</a> | - | <a href="../../Modelagem/historias#HU01">HU01 </a> | Gerencial, Desenvolvimento | Satisfação, Recurso | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R1.PNG"><img border="0" alt="Requisito 1" width="100" height="100"></a> |
| 2 | O usuário deve ser capaz de visualizar horário dos trens | <a href="../../Modelagem/cenarios#c2">Cenário 2</a>  |<a href="../../Modelagem/lexico#horario">horário</a>  | <a href="../../Modelagem/casodeuso#caso1">Caso 1</a> |  <a href="../../Modelagem/historias#HU06">HU06 </a> | Desenvolvimento, Organizacional, Ambiental | Satisfação, Agregação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R2.PNG"><img border="0" alt="Requisito 2" width="100" height="100"></a> |          
| 3 | O usuário deve ser capaz de atualizar horário dos trens | - | <a href="../../Modelagem/lexico#horario">horário</a> | - | <a href="../../Modelagem/historias#HU12">HU12 </a> | Gerencial, Desenvolvimento, Organizacional| Satisfação  |  <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R3.PNG"><img border="0" alt="Requisito 3" width="100" height="100"></a>  |          
| 4 | O usuário deve ser capaz de falar com a ouvidoria | <a href="../../Modelagem/cenarios#c6">Cenário 6</a>  | - | <a href="../../Modelagem/casodeuso#caso4">Caso 4</a> | <a href="../../Modelagem/historias#HU18">HU18 </a> |  Gerencial, Ambiental, Desenvolvimento  | Satisfação, Agregação  |  <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R2.PNG"><img border="0" alt="Requisito 4" width="100" height="100"></a> |          
| 5 | O usuário deve ser capaz de recarregar cartão do metrô | - | - | - |  | - | - | Não implementado|          
| 6 |O usuário deve ser capaz de visualizar o mapa da linha do metrô | <a href="../../Modelagem/cenarios#c4">Cenário 4</a> | - | <a href="../../Modelagem/casodeuso#caso2">Caso 2</a>, <a href="../../Modelagem/casodeuso#caso3">Caso 3</a> | <a href="../../Modelagem/historias#HU22">HU22 </a>  | Organizacional, Ambiental, Desenvolvimento |  Recurso, Representação |  <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R6.PNG"><img border="0" alt="Requisito 6" width="100" height="100"></a>  |          
| 7 | O usuário deve ser capaz de se cadastrar | <a href="../../Modelagem/cenarios#c6">Cenário 6</a>  | <a href="../../Modelagem/lexico#cadastrar">cadastrar</a> | - | <a href="../../Modelagem/historias#HU19">HU19 </a>  | Desenvolvimento  | Satisfação, Responsabilidade |  <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R7.PNG"><img border="0" alt="Requisito 7" width="100" height="100"></a> |          
| 8  | O usuário deve ser capaz de realizar login em sua conta cadastrada | - | <a href="../../Modelagem/lexico#entrar">entrar</a> | - | <a href="../../Modelagem/historias#HU20">HU20 </a>  |  Desenvolvimento | Satisfação, Responsabilidade | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R8.PNG"><img border="0" alt="Requisito 8" width="100" height="100"></a> |
| 9 | O usuário deve ser capaz de ver todas as estações | <a href="../../Modelagem/cenarios#c5">Cenário 5</a>  | - | <a href="../../Modelagem/casodeuso#caso1">Caso 1</a>, <a href="../../Modelagem/casodeuso#caso3">Caso 3</a> | <a href="../../Modelagem/historias#HU09">HU09 </a>   | Desenvolvimento, Ambiental, Organizacional | Satisfação, Agregação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R9.PNG"><img border="0" alt="Requisito 9" width="100" height="100"></a> |
| 10 |  O usuário deve ser capaz de visualizar o horário de funcionamento das estações | <a href="../../Modelagem/cenarios#c7">Cenário 7</a>  | <a href="../../Modelagem/lexico#horario">horário</a> | <a href="../../Modelagem/casodeuso#caso1">Caso 1</a> | <a href="../../Modelagem/historias#HU04">HU04 </a>   | Organizacional, Desenvolvimento | Satisfação, Representação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R10.PNG"><img border="0" alt="Requisito 10" width="100" height="100"></a> |          
| 11 |O usuário deve ser capaz de visualizar o tempo de chegada dos trens até a estação| <a href="../../Modelagem/cenarios#c5">Cenário 5</a> | <a href="../../Modelagem/lexico#temporeal">tempo real</a> | - | <a href="../../Modelagem/historias#HU11">HU11 </a>   |Organizacional, Desenvolvimento, Ambiental | Satisfação, Agregação |  <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R11.PNG"><img border="0" alt="Requisito 11" width="100" height="100"></a>  |          
| 12 | O usuário deve ser capaz de visualizar a distância até as estações | - | - | - | <a href="../../Modelagem/historias#HU09">HU09 </a>  | Desenvolvimento, Organizacional  | Satisfação, Responsabilidade | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R12.jpg"><img border="0" alt="Requisito 12" width="100" height="100"></a> |         
| 13 | O usuário deve ser capaz de favoritar horários dos trens | - | <a href="../../Modelagem/lexico#favoritar">favoritar</a> | - | <a href="../../Modelagem/historias#HU13">HU13 </a>   |  Desenvolvimento,Organizacional | Satisfação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R13.jpg"><img border="0" alt="Requisito 13" width="100" height="100"></a> |         
| 14 | O usuário deve ser capaz de visualizar os serviços disponíveis em cada estações |     - | <a href="../../Modelagem/lexico#servicos">serviços</a> | - | <a href="../../Modelagem/historias#HU08">HU08 </a>   | Organizacional, Desenvolvimento | Satisfação, Responsabilidade | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R14.jpg"><img border="0" alt="Requisito 14" width="100" height="100"></a> |         
| 15 | O usuário deve ser capaz de filtrar estações de acordo com os serviços disponibilizados | <a href="../../Modelagem/cenarios#c4">Cenário 4</a>  | <a href="../../Modelagem/lexico#servicos">serviços</a> | <a href="../../Modelagem/casodeuso#caso3">Caso 3</a> | <a href="../../Modelagem/historias#HU07">HU07 </a>   | Ambiental, Desenvolvimento | Satisfação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R15.jpg"><img border="0" alt="Requisito 15" width="100" height="100"></a> |          
| 16 | O usuário deve ser capaz de visualizar detalhes de um trajeto | <a href="../../Modelagem/cenarios#c5">Cenário 5</a>  | - | - | <a href="../../Modelagem/historias#HU14">HU14 </a>   | Ambiental, Desenvolvimento | Satisfação | Não se aplica | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R16.jpg"><img border="0" alt="Requisito 16" width="100" height="100"></a> |          
| 17 | O usuário deve ser capaz de visualizar o atual preço da passagem | - | - | <a href="../../Modelagem/casodeuso#caso2">Caso 2</a> | <a href="../../Modelagem/historias#HU02">HU02 </a>   | Gerencial, Desenvolvimento | Recurso | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R17.jpg"><img border="0" alt="Requisito 17" width="100" height="100"></a> |          
| 18 | O usuário deve ser capaz de executar a maioria das ações no app sem se cadastrar ou realizar login | - | <a href="../../Modelagem/lexico#cadastrar">cadastrar</a> | - | <a href="../../Modelagem/historias#HU18">HU18 </a>  | Desenvolvimento, Organizacional | Satisfação, alocado | Não se aplica | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R18.jpg"><img border="0" alt="Requisito 18" width="100" height="100"></a> |          
| 19 | O usuário deve ser capaz de visualizar a localização das estações | - | - | - | <a href="../../Modelagem/historias#HU10">HU10 </a>   | Organizacional, Desenvolvimento | Satisfação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R19.jpg"><img border="0" alt="Requisito 19" width="100" height="100"></a> |          
| 20 |  O usuário deve ser capaz de selecionar a estação em que está ao planejar um trajeto | <a href="../../Modelagem/cenarios#c5">Cenário 5</a> | - | - | <a href="../../Modelagem/historias#HU15">HU15 </a>   | Ambiental, Desenvolvimento | Recurso | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R20.jpg"><img border="0" alt="Requisito 20" width="100" height="100"></a> |          
| 21 |  O usuário deve ser capaz de selecionar para qual estação deseja ir ao planejar um trajeto | <a href="../../Modelagem/cenarios#c5">Cenário 5</a> | - | - | <a href="../../Modelagem/historias#HU16">HU16 </a>   | Ambiental, Desenvolvimento | Recurso | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R21.jpg"><img border="0" alt="Requisito 21" width="100" height="100"></a> |          
| 22 | O usuário deve ser capaz de poder receber mensagens com notificações sobre o Metrô-DF | <a href="../../Modelagem/cenarios#c8">Cenário 8</a> | <a href="../../Modelagem/lexico#mensagem">mensagem</a> | - | <a href="../../Modelagem/historias#HU04">HU04 </a>   | Organizacional, Desenvolvimento | Satisfação, Representação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R22.jpg"><img border="0" alt="Requisito 22" width="100" height="100"></a> | 

### Requisitos Não Funcionais

| ID | Descrição | Cenários | Léxicos | Caso de Uso | História de Usuário | Nível | Elo | Telas |
| -- | --------- | ------ | ----- | --- | ----- | ---- | --- | --- | 
| 1   | O sistema deverá iniciar rapidamente | - | - | -  |  <a href="../../Modelagem/historias#HU17">HU17 </a>  | Desenvolvimento |  Satisfação | Não se aplica |
| 2   | O sistema deverá manter os dados dos usuário de forma segura  | - |  - |  - | <a href="../../Modelagem/historias#HU23">HU23 </a>  |Desenvolvimento | Recurso | Não se aplica |
| 3   | O sistema deverá apresentar opções de acessibilidade| - | - | - | <a href="../../Modelagem/historias#HU18">HU18 </a>  |  Desenvolvimento    |   Recurso, Responsabilidade | Não se aplica |
| 4   | O sistema deverá apresentar um design simples e intuitivo | - | - | - | - | Desenvolvimento | Satisfação, Responsabilidade | Não se aplica |
| 5   | O sistema deverá executar em qualquer plataforma mobile | - | - | - | - |  Desenvolvimento | Satisfação, Agregação  | Não se aplica |
| 6   |O sistema deverá suportar grandes quantidades de usuários simultaneamente | - | - | - | -  | Desenvolvimento | Satisfação  | Não se aplica |  
| 7   | O sistema deverá responder rapidamente | - | - | - | <a href="../../Modelagem/historias#HU17">HU17 </a>  | Desenvolvimento |     Satisfação |  Não se aplica|

## Referências 
SERRANO, Milene, SERRANO, Maurício. Requisitos - Aula 26. Disponível em: <https://aprender3.unb.br/pluginfile.php/993676/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 05 de outubro de 2021.

## Histórico de Versões

| Data       | Versão | Descrição                                     | Autores          | Revisor          |
| ---------- | ------ | --------------------------------------------- | ---------------- | ---------------- |
| 05/10/2021 | 0.1    | Adição de introdução e metodologia            | Hérya Rodrigues  |  Felip Correia   |
| 06/10/2021 | 1.0    | Montagem das matrizes                         | Felipe Correia, Rafael Berto  |     |
| 08/10/2021 | 1.1    | Adição das imagens                            | Felipe Correia, Rafael Berto  |     |
| 10/10/2021 | 2.0    | Correção da matriz de requisitos funcionais   | Rafael Berto     |  Felipe Correia  |
| 12/10/2021 | 2.1    | Correção das matrizes                         | Rafael e Felipe Correia |           |
| 15/10/2021 | 2.2    | Linkagem com léxicos, cenários, casos de uso e histórias de usuário | Hérya|                  |

