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
| 1   | O usuário deve ser capaz de visualizar notícias | Cenário 7  | Léxico (Notícia) | - | HU1 | Gerencial, Desenvolvimento | Satisfação, Recurso | <ahref="https://raw.githubusercontent.com/Requisitos-de-Software/2021.1-MetroDF/main/docs/imagens/fowardform/R1.PNG"><img border="0" alt="Requisito 1" width="100" height="100"></a> |

        

### Requisitos Não Funcionais

| ID | Descrição | Cenários | Léxicos | Caso de Uso | História de Usuário | Nível | Elo | Telas |
| -- | --------- | ------ | ----- | --- | ----- | ---- | --- | --- | 
| 1   | O sistema deverá iniciar rapidamente | - | - | -  |  HU17 | Desenvolvimento |  Satisfação | Não se aplica |
| 2   | O sistema deverá manter os dados dos usuário de forma segura  | - |  - |  - | HU23 |Desenvolvimento | Recurso | Não se aplica |
| 3   | O sistema deverá apresentar opções de acessibilidade| - | - | - | HU18 |  Desenvolvimento    |   Recurso, Responsabilidade | Não se aplica |
| 4   | O sistema deverá apresentar um design simples e intuitivo | - | - | - | - | Desenvolvimento | Satisfação, Responsabilidade | Não se aplica |
| 5   | O sistema deverá executar em qualquer plataforma mobile | - | - | - | - |  Desenvolvimento | Satisfação, Agregação  | Não se aplica |
| 6   |O sistema deverá suportar grandes quantidades de usuários simultaneamente | - | - | - | -  | Desenvolvimento | Satisfação  | Não se aplica |  
| 7   | O sistema deverá responder rapidamente | - | - | - | HU17 | Desenvolvimento |     Satisfação |  Não se aplica |

## Referências 
SERRANO, Milene, SERRANO, Maurício. Requisitos - Aula 26. Disponível em: <https://aprender3.unb.br/pluginfile.php/993676/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 05 de outubro de 2021.

## Histórico de Versões

| Data       | Versão | Descrição                                     | Autores          | Revisor          |
| ---------- | ------ | --------------------------------------------- | ---------------- | ---------------- |
| 05/10/2021 | 0.1    | Adição de introdução e metodologia | Hérya Rodrigues   |    |
| 06/10/2021 | 1.0    | Montagem das matrizes         | Felipe Correia, Rafael Berto  |     |
| 08/10/2021 | 1.1    | Adição das imagens            | Felipe Correia, Rafael Berto  |     |
| 10/10/2021 | 2.0    | Correção da matriz de requisitos funcionais | Rafael |     |


