# Caso de uso

## O que são Casos de Uso?
De acordo com a apostila “Projeto de Software Usando a UML” de Andrey Ricardo Pimentel,  caso de uso é “é uma sequência de transações executadas por um sistema, que produz um resultado mensurável de valores para um ator em particular” (p, 14). Os substantivos são usados apenas para definir atributos. Deve-se tomar cuidado para responder às seguintes perguntas:

* “Quais são as tarefas de cada ator?”; 

* “Algum ator criará, armazenará, mudará, removerá ou lerá informação do sistema?”; 

* “Que casos de uso criarão, armazenarão, mudarão, removerão ou lerão esta informação?”; 

* “Algum ator precisará informar o sistema a respeito de mudanças externas repentinas?”;

* “Algum ator necessita ser informado a respeito de certas ocorrências no sistema?”; 

* “Que casos de uso suportarão ou manterão o sistema?”; 

* “Todas as necessidades funcionais podem ser executadas pelos dos casos de uso?” 
<br>

## Para que serve?
Casos de uso servem para fornecer algo de valor para um ator. Por exemplo: “a Secretaria deve incluir cursos, eliminar cursos e modificar cursos. Três casos de uso ou um único? Aqui novamente, deveria ser feito um caso de uso - a manutenção de currículo, já que a funcionalidade é iniciada pelo mesmo ator (a Secretaria) e trata com as mesmas entidades no sistema” (p. 15)
<br>

##Quem são os atores?
De acordo com os slides dos professores Milene Serrano e Maurício Serrano, os atores “podem ser atores humanos– pessoas; ou podem ser sistemas, subsistemas, componentes, chamados atores sistêmicos” (slide 13). Mas, deve-se tomar cuidado para escolher os atores, a identificação dos atores  é feita de uma maneira iterativa - a primeira lista de atores para um sistema raramente constitui a lista final” (apostila aula 11, p. 14).
<br>

## O que é um Diagrama de Casos de Uso?
Na linguagem de modelagem unificada (UML), o diagrama de caso de uso resume os detalhes dos usuários do seu sistema (também conhecidos como atores) e as interações deles com o sistema. Para criar um, use um conjunto de símbolos e conectores especializados. Um bom diagrama de caso de uso ajuda sua equipe a representar e discutir:
* Cenários em que o sistema ou aplicativo interage com pessoas, organizações ou sistemas externos
* Metas que o sistema ou aplicativo ajuda essas entidades (conhecidas como atores) a atingir
* O escopo do sistema
<br>

## Símbolos e notação no diagrama de caso de uso
A notação do diagrama de caso de uso é bastante objetiva e não envolve a mesma quantidade de símbolos de outros diagramas UML. Veja todas as formas que você encontra no Lucidchart:
* Caso de uso: formato oval na horizontal e que representam os diferentes usos que um usuário pode ter.

* Atores: bonecos palito, representando as pessoas que realmente implementam os casos de uso. Temos dois tipos de atores: o ator ativo que é quem inicia/dispara a ação do caso de uso e o ator passivo que é quem reage a uma provocação de um caso de uso

* Associações: uma linha entre atores e casos de uso. Nos diagramas complexos, é importante saber quais atores estão associados a quais casos de uso. Tendo 3 tipos de associação sendo elas: 
- include - Muitos casos de uso podem compartilhar pedaços de pequenas funcionalidades. Esta funcionalidade é colocada em separado em outro caso de uso ao invés de ser documentada em cada caso de uso que precisa dela. Relacionamentos de <> são criados entre um novo caso de uso e qualquer outro caso de uso que utilize esta funcionalidade.
- extend- Um relacionamento de "extend" é usado para mostrar: comportamento opcional, comportamento que somente é executado sobre determinadas condições, como o disparo de 20 um alarme, muitos diferentes caminhos que podem ser executados de acordo com uma seleção feita por um ator.
- generalização - Uma generalização entre um caso de uso C e um caso de uso D indica que C é uma especialização de D. Este relacionamento é representado por uma seta de generalização partindo de D para C. Pode ser representado, também, um tipo de relacionamento entre atores. Este relacionamento é o de generalização. Uma generalização de um ator A para um ator B indica que A pode se comunicar com os mesmos casos de uso que B.

* Caixa de limite do sistema: caixa que define um escopo do sistema para os casos de uso. Todos os casos de uso fora da caixa são considerados fora do escopo do sistema.
<br>

## Participantes
Rafael Berto Pereira e Felipe Correia
<br>

## Diagrama de Casos de Uso

<img alt = "Diagrama de caso de uso" src="../../imagens/casodeuso.jpeg"/>

(figura 1)

(Produzido por Rafael e Felipe no site < https://lucid.app>)

## Especificação dos Casos de Uso
De acordo com a apostila “Projeto de Software Usando a UML” de Andrey Ricardo Pimentel, Uma especificação dos casos de uso é uma forma de documentar cada caso de uso descrevendo o comportamento de cada um. Este comportamento é descrito em um fluxo que será apresentado abaixo.



### 1) Visualizar horário de funcionamento do metrô
<center>

||Informações|
|--|--|
|Descrição| O ator deve poder visualizar os horários de funcionamento|
|Ator| Usuário|
|Pré-condições| Acesso à internet e ao app |
|Ação| O usuário visualiza os horários de funcionamento dos metrôs|
|Fluxo Principal| Fluxo para visualizar horários de funcionamento<br/>1. O ator entra no aplicativo<br/>2. O ator clica em “horário dos trens”<br/>3. O ator seleciona as estações de saída e de chegada<br/>4. O sistema mostra os horários de funcionamento de acordo com as estações selecionadas<br/>
|Pós-condições| O ator poderá ter acesso aos horários disponibilizados|

</center>
<h6 align = "center">Tabela 1: Tabela de especialização dos horários de funcionamento.</h6>
<h6 align = "center">Fonte: Autores</h6>


### 2) Fornecer informações  sobre o Metro
<center>

||Informações|
|--|--|
|Descrição| O metrô deve fornecer as informações sobre o preço da passagem de trem, Dias e horários de funcionamento, mapa do metrô e Contatos e redes sociais|
|Ator| Usuário|
|Pré-condições| Acesso à internet|
|Ação| O usuário irá visualizar informações  genéricas sobre o metrô|
|Fluxo Principal| Fluxo para visualizar informações<br/>1. O ator entra no app<br/>2 O ator clica no botão de informações <br/>3. O ator visualiza a informação que desejar: preço da passagem, dia e horário de funcionamento, mapa do metrô e contatos e redes sociais do metrô.|
|Pós-condições| O ator se manterá informado|

</center>
<h6 align = "center">Tabela 2: Tabela de informações sobre o metrô.</h6>
<h6 align = "center">Fonte: Autores</h6>



### 3) Visualizar linhas de trens
<center>

||Informações|
|--|--|
|Descrição| Visualizar informações específicas sobre as linhas do metrô|
|Ator| Usuário|
|Pré-condições| Acesso à internet e ao app |
|Ação| O usuário visualiza as linhas de metrô|
|Fluxo Principal| Fluxo para visualizar linhas de metrô<br/>1. O ator entra no aplicativo.<br/>2. O ator clica no botão “conheça as estações”.<br/>3. O ator seleciona a estação que deseja conhecer.<br/>4. O ator visualiza as informações específicas da estação: O que tem próximo desta estação, serviços disponíveis e mapa dos arredores.|
|Pós-condições| O ator poderá ter acesso às informações específicas sobre todas as linhas de metrô|

</center>
<h6 align = "center">Tabela 3: Tabela de visualização de linhas de metrô.</h6>
<h6 align = "center">Fonte: Autores</h6>

### 4) Fazer reclamações ou tirar dúvidas
<center>

||Informações|
|--|--|
|Descrição| Fazer reclamações ou tirar dúvidas|
|Ator| Usuário|
|Pré-condições| Acesso à internet e ao app |
|Ação| O ator faz reclamações ou tira dúvidas|
|Fluxo Principal| Fluxo para responder reclamações ou dúvidas<br/>1. O ator entra no aplicativo<br/>2. O ator clica em “Fale com a ouvidoria”<br/>3. O ator seleciona a opção desejada: elogio, sugestão, solicitação, informação, reclamação ou denúncia<br/>4. O ator escolhe se quer falar como anônimo ou se vai se identificar<br/>5. O ator escolhe sobre o que vai ser a pergunta: Bilheterias do metrô, estações do metrô…<br/>6. O ator específica sobre o que foi escolhido anteriormente<br/>7. O ator escreve numa caixa de texto sobre o que foi selecionado.|
|Pós-condições| O ator consegue perguntar ou falar sobre algo com o metrô-df|

</center>
<h6 align = "center">Tabela 4: Tabela de fazer reclamações ou tirar dúvidas.</h6>
<h6 align = "center">Fonte: Autores</h6>

### 5) Definir um trajeto
<center>

||Informações|
|--|--|
|Descrição| Após definir um trajeto o app irá indicar quais estações o usuário deve seguir para alcançar o seu destino|
|Ator| Usuário|
|Pré-condições| Acesso à internet e ao app |
|Ação| O usuário irá consultar um trajeto|
|Fluxo Principal| Fluxo para visualizar linhas de metrô<br/>1. O ator entra no aplicativo.<br/>2. O ator clica no botão “vai pra onde?”.<br/>3. O ator seleciona em qual estação está e depois seleciona para onde quer ir.<br/>4. O aplicativo indica qual sentido da estação o usuário vai seguir e também por quais estações vai passar e se será necessário descer do trem|
|Pós-condições| O ator terá um roteiro que indica por quais estações ele vai passar até chegar ao destino|

</center>
<h6 align = "center">Tabela 5: Tabela de Definir um trajeto</h6>
<h6 align = "center">Fonte: Autores</h6>

<br>

## Referências
Apostila: Pimentel, Andrey. Projeto de Software Usando a UML: Apostila para Curso de Projeto de Sistemas Orientado a Objetos Usando a UML. Julho 2007.
Lucidchart: <https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml>. Acesso em 29/08/2021
Slide: Milene Serrano e Maurício Serrano. Requisitos – Aula 13

<br>

## Histórico de Versões

| Data     | Versão | Descrição                                          | Autores          | Revisor          |
| ---------- | --------- | --------------------------------------------- | ---------------- | ---------------- |
| 26/08/2021 | 1.0 | Criação do documento                                | Rafael           | Felipe           |     
| 27/08/2021 | 1.0 | Detalhamento de Casos de Uso                        | Rafael           | Felipe           |        
| 27/08/2021 | 1.1 | Inclusão do Diagrama de Casos de Uso                | Rafael           | Felipe           |
| 29/08/2021 | 1.2 | Inclusão dos significados das simbologias           | Felipe           |                  |
| 29/08/2021 | 1.2 | Explicação do que é um diagrama de casos de uso     | Felipe           |                  |
| 29/08/2021 | 1.3 | Especificação dos casos de uso                      | Felipe e Rafael  |                  |
