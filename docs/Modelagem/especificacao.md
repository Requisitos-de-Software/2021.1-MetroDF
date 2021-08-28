# Especificação Suplementar

## Introdução
<p align="justify"> A especificação suplementar é um documento em linguagem natural que, quando aliado às outras técnicas de elicitação e modelagem, possibilita a obtenção de um conjunto mais completo dos requisitos do sistema, principalmente os requisitos não funcionais. </p>

### Propósito
<p align="justify">O propósito deste documento é tratar os requisitos não funcionais relacionados à aplicação Metrô-DF e, assim, obter um conjunto mais completo dos requisitos deste sistema.</p>

### Contexto
<p align="justify">O Metrô-DF é um aplicativo mobile que apresenta recursos como consulta a situação operacional do metrô, tempo de chegada dos trens as estações, distância entre o usuário e as estações, planejamento de trajetos, registro de  sugestões e visualização do mapa completo da rede de metrô do Distrito Federal.</p>

### Metodologia
<p align="justify">Para a elaboração deste documento, a equipe utilizou o método FURPS+ e o documento de <a href="http://www.metro.df.gov.br/?page_id=40565">Política de Privacidade do Aplicativo Metrô-DF</a>.</p>

## FURPS+
<p align="justify">O FURPS+ é um método de classificação de requisitos que pode ser utilizado para orientar o documento de especificação suplementar. O nome é um acrônimo para <i><b>F</b>unctionality, <b>U</b>sability, <b>R</b>eliability, <b>P</b>erformance e <b>S</b>upportability.</i></p>

* <i><b>F</b>unctionality</i> - Funcionalidade: refere-se aos aspectos funcionais do software, ou seja, seu  conjunto de recursos e capacidades, suas funções e a segurança geral do sistema.
* <i><b>U</b>sability </i> - Usabilidade: refere-se às questões humanas, a facilidade do usuário ao realizar suas demandas utilizando o sistema. Engloba fatores como estética, ajuda, documentação, consistência e padrões.
* <i><b>R</b>eliability </i> - Confiabilidade: refere-se a integridade, conformidade e interoperabilidade do software. É avaliada a partir da medição da frequência e gravidade das falhas, a precisão dos resultados de saída, a capacidade de recuperação de falhas e a previsibilidade do programa.
* <i><b>P</b>erformance</i> - Desempenho: refere-se a quantidade de trabalho útil realizado por um sistema. Pode ser estimado em termos de precisão, eficiência e velocidade de execução das instruções do sistema.
* <i><b>S</b>upportability </i> - Suportabilidade: refere-se a facilidade de suporte. Engloba características como estabilidade, adaptabilidade, manutenibilidade, compatibilidade, configurabilidade, instalabilidade, escalabilidade e localizabilidade.
<p align="justify">O "+" no acrônimo refere-se a outros aspectos que podem ser englobados, mas que não estão presentes nas outras letras do acrônimo.</p>

## Funcionalidade
<p align="justify">As características relacionadas às funcionalidades do aplicativo foram amplamente descritas em documentos anteriores. O levantamento e descrição de requisitos funcionais podem ser encontrados nos documentos de <a href="https://requisitos-de-software.github.io/2021.1-MetroDF/Elicitacao/brainstorming/">Brainstorming</a>, <a href="https://requisitos-de-software.github.io/2021.1-MetroDF/Elicitacao/introspeccao/">Introspecção</a>, <a href="https://requisitos-de-software.github.io/2021.1-MetroDF/Elicitacao/observacao/">Observação Participativa</a> e <a href="https://requisitos-de-software.github.io/2021.1-MetroDF/Elicitacao/resultados/">Resultados</a>. </p>


## Usabilidade
1.  O sistema deve utilizar palavras, expressões e conceitos que são familiares aos usuários
    * O vocabulário em todas as funcionalidades e telas deve ser compatível com os usuários que utilizam o aplicativo. Os usuários da aplicação englobam pessoas de diferentes idades, graus de escolaridade e localizações geográficas, assim, o sistema deve apresentar uma linguagem que seja facilmente compreendida pelos diferentes perfis de usuários. 

2. A interface deve ser simples, intuitiva e de fácil compreensão
    * Clareza e consistência no design de ícones: o usuário deve compreender facilmente quais funcionalidades os ícones representam, como favoritar, mensagens e voltar.
    * Consistência e padronização: ícones, botões, palavras, situações e ações devem ser padronizados para facilitar a compreensão, utilização e reconhecimento.
    * Projeto estético e minimalista : a interface não deve conter informações irrelevantes ou raramente necessárias.

3. Acessibilidade:
    * O usuário deve interagir com o sistema sem que a interface imponha obstáculos.
    * O aplicativo deve levar em consideração a existência de usuários com deficiências e limitações.

## Confiabilidade
1. As informações apresentadas pelo aplicativo devem ser concordantes com as informações em tempo real da situação do metrô
    * Informações disponibilizadas pelo aplicativo, como horários dos trens, situação do metrô, horário de funcionamento e tarifas devem ser consistentes com a realidade do serviço de metrô do Distrito Federal.

2. O sistema deve estar disponível a qualquer momento
    * O aplicativo deve estar disponível a qualquer horário, especialmente durante os horários de funcionamento das estações de metrô do Distrito Federal.
    * Caso  seja necessário realizar manutenção do sistema, ela deve ser realizada no período noturno, fora do horário de funcionamento das estações de metrô do Distrito Federal.

3. Prevenção e recuperação de erros
    * Mensagens de erro: caso o usuário cometa algum erro, ele deve ser informado por uma mensagem que seja  facilmente compreensível, indique precisamente o problema e faça a sugestão de uma solução.

4. Segurança dos dados
    * A aplicação deve armazenar as informações de seus usuários de forma segura: dados dos usuários devem ser armazenados da forma mais segura possível, mantendo sua integridade e privacidade e protegendo-os contra eventuais falhas que possam comprometê-los.
    * Política de privacidade: a <a href="http://www.metro.df.gov.br/?page_id=40565">Política de Privacidade</a> do aplicativo deve estar disponível aos usuários.</p>

## Desempenho
1. Tempo de resposta 
    * O tempo de resposta do aplicativo deve ser o menor possível.

2. Conexão
    * Caso o usuário perca a conexão com a internet, o sistema deverá alertá-lo.

3. Acessos simultâneos
    * O sistema deve suportar uma grande quantidade de acessos  simultâneos de usuários, evitando estabilidades e tempo de resposta elevado.

3. Consumo de recursos
    * O aplicativo deve consumir a menor quantidade possível de memória, processamento e bateria dos dispositivos.
    * No momento, o aplicativo necessita de 16 megabytes de armazenamento em sistemas Android e 30 megabytes em sistemas IOS.

## Suportabilidade
1. Compatibilidade 
    * O aplicativo deve ser compatível e suportado pelos  sistemas operacionais IOS e Android. 
    * O aplicativo deve levar em consideração versões mais antigas de sistemas operacionais.
    * O sistema deverá funcionar igualmente bem em dispositivos móveis mais simples e mais modernos.

2. Otimização
    * A interface do aplicativo deve se adaptar aos diferentes dispositivos móveis em que ele pode ser utilizado.

3.  Manutenibilidade
    * O sistema deve ser construído de forma que seja fácil escalona-lo pra situações de maior uso.
    * A aplicação deve ser construída seguindo padrões, de forma a facilitar a implementação de futuras funcionalidades necessárias.


## Referências
SERRANO, Milene, SERRANO, Maurício. Requisitos - Aula 13. Disponível em: <<a>https://aprender3.unb.br/pluginfile.php/993616/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf</a>>. Acesso em: 26 de agosto de 2021.

GOIS, Samily, SOBRINHO, Francisco. Projeto de Software Floricultura Beija-Flor, Especificação Suplementar. Versão 101.6. PHP SOFTWARE COMPANY, 2012.  Disponível em: <<a>https://aprender3.unb.br/pluginfile.php/993618/mod_resource/content/1/Especificacao_Suplementar_Exemplo.pdf </a>>. Acesso em: 26 de agosto de 2021. 

Política de Privacidade do Aplicativo Metrô-DF. Disponível em: <<a>http://www.metro.df.gov.br/?page_id=40565</a>>. Acesso em Acesso em: 26 de agosto de 2021. 


BARBOSA, Simone Diniz Junqueira; DA SILVA, Bruno Santana. Interação humano-computador. Elsevier, 2010.

## Versionamento

| Data       | Versão | Descrição                                       | Autores          | Revisor          |
| ---------- | ------ | ---------------------------------------------   | ---------------- | ---------------- |
| 26/08/2021 |  0.1   | Criação e elaboração do documento               | Hérya Rodrigues  |                  |
| 26/08/2021 |  0.2   | Correções                                       | Hérya Rodrigues  |                  |
