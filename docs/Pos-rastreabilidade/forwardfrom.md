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
| 1 | O usuário deve ser capaz de visualizar notícias | Cenário 7  | Léxico (Notícia) | - | HU1 | Gerencial, Desenvolvimento | Satisfação, Recurso | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R1.PNG"><img border="0" alt="Requisito 1" width="100" height="100"></a> |
| 2 | O usuário deve ser capaz de visualizar horário dos trens | Cenário 2 |Léxico (Horário)  | Caso 1 |  HU06 | Desenvolvimento, Organizacional, Ambiental | Satisfação, Agregação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R2.PNG"><img border="0" alt="Requisito 2" width="100" height="100"></a> |          
| 3 | O usuário deve ser capaz de atualizar horário dos trens | - | Léxico (Horário) | - | HU12 | Gerencial, Desenvolvimento, Organizacional| Satisfação  |  <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R3.PNG"><img border="0" alt="Requisito 3" width="100" height="100"></a>  |          
| 4 | O usuário deve ser capaz de falar com a ouvidoria | Cenário 6 | - | Caso 4 | HU18 |  Gerencial, Ambiental, Desenvolvimento  | Satisfação, Agregação  |  <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R2.PNG"><img border="0" alt="Requisito 4" width="100" height="100"></a> |          
| 5 | O usuário deve ser capaz de recarregar cartão do metrô | - | - | - |  | - | - | Não implementado|          
| 6 |O usuário deve ser capaz de visualizar o mapa da linha do metrô | Cenário 4 | - | Caso 2, Caso 3 | HU22 | Organizacional, Ambiental, Desenvolvimento |  Recurso, Representação |  <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R6.PNG"><img border="0" alt="Requisito 6" width="100" height="100"></a>  |          
| 7 | O usuário deve ser capaz de se cadastrar | Cenário 6 | Léxico (Cadastrar) | - | HU19 | Desenvolvimento  | Satisfação, Responsabilidade |  <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R7.PNG"><img border="0" alt="Requisito 7" width="100" height="100"></a> |          
| 8  | O usuário deve ser capaz de realizar login em sua conta cadastrada | - | Léxico (Entrar) | - | HU20 |  Desenvolvimento | Satisfação, Responsabilidade | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R8.PNG"><img border="0" alt="Requisito 8" width="100" height="100"></a> |
| 9 | O usuário deve ser capaz de ver todas as estações | Cenário 5 | - | Caso 1, Caso 3 | HU09 | Desenvolvimento, Ambiental, Organizacional | Satisfação, Agregação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R9.PNG"><img border="0" alt="Requisito 9" width="100" height="100"></a> |
| 10 |  O usuário deve ser capaz de visualizar o horário de funcionamento das estações | Cenário 7 | Léxico (Horário) | Caso 1 | HU04 | Organizacional, Desenvolvimento | Satisfação, Representação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R10.PNG"><img border="0" alt="Requisito 10" width="100" height="100"></a> |          
| 11 |O usuário deve ser capaz de visualizar o tempo de chegada dos trens até a estação| Cenário 5 | Léxico (Tempo real) | - | HU11 |Organizacional, Desenvolvimento, Ambiental | Satisfação, Agregação |  <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R11.PNG"><img border="0" alt="Requisito 11" width="100" height="100"></a>  |          
| 12 | O usuário deve ser capaz de visualizar a distância até as estações | - | - | - | HU09 | Desenvolvimento, Organizacional  | Satisfação, Responsabilidade | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R12.jpg"><img border="0" alt="Requisito 12" width="100" height="100"></a> |         
| 13 | O usuário deve ser capaz de favoritar horário dos trens | - | Léxico (Favoritar) | - | HU13 |  Desenvolvimento,Organizacional | Satisfação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R13.jpg"><img border="0" alt="Requisito 13" width="100" height="100"></a> |         
| 14 | O usuário deve ser capaz de visualizar os serviços disponíveis em cada estações |     - | Léxico (Serviços) | - | HU08 | Organizacional, Desenvolvimento | Satisfação, Responsabilidade | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R14.jpg"><img border="0" alt="Requisito 14" width="100" height="100"></a> |         
| 15 | O usuário deve ser capaz de filtrar estações de acordo com o serviços disponibilizados | Cenário 4 | Léxico (Serviços) | Caso 3 | HU07 | Ambiental, Desenvolvimento | Satisfação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R15.jpg"><img border="0" alt="Requisito 15" width="100" height="100"></a> |          
| 16 | O usuário deve ser capaz de visualizar detalhes de um trajeto | Cenário 5 | - | - | HU14 | Ambiental, Desenvolvimento | Satisfação | Não se aplica | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R16.jpg"><img border="0" alt="Requisito 16" width="100" height="100"></a> |          
| 17 | O usuário deve ser capaz de visualizar o atual preço da passagem | - | - | Caso 2 | HU02 | Gerencial, Desenvolvimento | Recurso | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R17.jpg"><img border="0" alt="Requisito 17" width="100" height="100"></a> |          
| 18 | O usuário deve ser capaz de executar a maioria das ações no app sem se cadastrar ou realizar login | - | Léxico (Cadastrar) | - | HU18 | Desenvolvimento, Organizacional | Satisfação, alocado | Não se aplica | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R18.jpg"><img border="0" alt="Requisito 18" width="100" height="100"></a> |          
| 19 | O usuário deve ser capaz de visualizar a localização das estações | - | - | - | HU10 | Organizacional, Desenvolvimento | Satisfação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R19.jpg"><img border="0" alt="Requisito 19" width="100" height="100"></a> |          
| 20 |  O usuário deve ser capaz de selecionar a estação em que está ao planejar um trajeto | Cenário 5 | - | - | HU15 | Ambiental, Desenvolvimento | Recurso | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R20.jpg"><img border="0" alt="Requisito 20" width="100" height="100"></a> |          
| 21 |  O usuário deve ser capaz de selecionar para qual estação deseja ir ao planejar um trajeto | Cenário 5 | - | - | HU16 | Ambiental, Desenvolvimento | Recurso | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R21.jpg"><img border="0" alt="Requisito 21" width="100" height="100"></a> |          
| 22 | O usuário deve ser capaz de poder receber mensagens com notificações sobre o Metrô-DF | Cenário 8 | Léxico (Mensagem) | - | HU04 | Organizacional, Desenvolvimento | Satisfação, Representação | <a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R22.jpg"><img border="0" alt="Requisito 22" width="100" height="100"></a> | 

### Requisitos Não Funcionais

| ID | Descrição | Cenários | Léxicos | Caso de Uso | História de Usuário | Nível | Elo | Telas |
| -- | --------- | ------ | ----- | --- | ----- | ---- | --- | --- | 
| 1   | O sistema deverá iniciar rapidamente | - | - | -  |  HU17 | Desenvolvimento |  Satisfação | Não se aplica |
| 2   | O sistema deverá manter os dados dos usuário de forma segura  | - |  - |  - | HU23 |Desenvolvimento | Recurso | Não se aplica |
| 3   | O sistema deverá apresentar opções de acessibilidade| - | - | - | HU18 |  Desenvolvimento    |   Recurso, Responsabilidade | Não se aplica |
| 4   | O sistema deverá apresentar um design simples e intuitivo | - | - | - | - | Desenvolvimento | Satisfação, Responsabilidade | Não se aplica |
| 5   | O sistema deverá executar em qualquer plataforma mobile | - | - | - | - |  Desenvolvimento | Satisfação, Agregação  | Não se aplica |
| 6   |O sistema deverá suportar grandes quantidades de usuários simultaneamente | - | - | - | -  | Desenvolvimento | Satisfação  | Não se aplica |  
| 7   | O sistema deverá responder rapidamente | - | - | - | HU17 | Desenvolvimento |     Satisfação |  Não se aplica|

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


