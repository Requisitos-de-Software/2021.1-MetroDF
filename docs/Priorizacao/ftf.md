# First Things First

## Introdução
<p align="justify">First Things First é uma técnica de priorização de requisitos baseada no custo, risco e valor de cada requisito. A equipe optou pelo First Things First por se uma técnica que apresenta uma abordagem formal e fornece valores de prioridade quantitativos.</p>

## Metodologia
<p align="justify">De acordo com Wiegers (1999), a técnica apresenta oito passos: </p>

1. Lista-se todos os requisitos, recursos ou casos de uso que devem ser priorizados em uma planilha. Se certos requisitos estão logicamente vinculados, deve-se incluir apenas o requisito principal.
2. O benefício relativo que cada requisito oferece deve ser estimado em uma escala de 1 a 9, com 1 indicando muito pouco benefício e 9 sendo o benefício máximo possível.
3. Deve-se estimar a penalidade relativa se o requisito não for entregue. Novamente, deve ser utilizada uma escala de 1 (sem penalidade) a 9 (penalidade muito alta).
4. O valor do benefício e da penalidade relativa devem ser somados. Por padrão, benefício e penalidade têm o mesmo peso, mas podem ser ajustados.
5. Deve-se estimar o custo de implementação de cada requisito, de 1 (custo mínimo) a 9 (alto custo máximo).
6. O grau relativo de risco técnico do requisito deve ser estimado, novamente de 1 (facilmente programável) a 9 (alto grau de dificuldade técnica).
7. A prioridade de cada requisito deve ser calculada utilizando a fórmula: prioridade = valor percentual %  / (custo percentual * peso custo + riscos percentual * peso risco).
8. Os requisitos devem ser ordenados em ordem crescente quanto à prioridade. Os requisitos no topo da lista têm o equilíbrio mais favorável de valor, custo, e risco e, portanto, devem ter maior prioridade de implementação.

## Resultados

| Tipo | Requisito | Benefício Relativo | Penalidade Relativa | Valor Relativo | Valor Percentual (%) | Custo Relativo | Custo Percentual (%) | Risco Relativo | Risco Percentual (%) | Prioridade |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
|Funcional    | 18 | 6 | 6 | 12 | 3.31 | 1 | 1.05 | 1 | 1.12 | 1.53
|Funcional    | 20 | 8 | 8 | 16 | 4.41 | 2 | 2.11 | 2 | 2.25 | 1.01
|Funcional    | 21 | 8 | 8 | 16 | 4.41 | 2 | 2.11 | 2 | 2.25 | 1.01
|Funcional    | 9  | 9 | 8 | 17 | 4.68 | 3 | 3.16 | 2 | 2.25 | 0.87
|Funcional    | 1  | 7 | 6 | 13 | 3.58 | 2 | 2.11 | 2 | 2.25 | 0.82
|Funcional    | 10 | 7 | 6 | 13 | 3.58 | 2 | 2.11 | 2 | 2.25 | 0.82
|Funcional    | 19 | 7 | 6 | 13 | 3.58 | 2 | 2.11 | 2 | 2.25 | 0.82
|Funcional    | 7  | 7 | 5 | 12 |3.31  | 2 | 2.11 | 2 | 2.25 | 0.76 
|Funcional    | 8  | 7 | 5 | 12 |3.31  | 2 | 2.11 | 2 | 2.25 | 0.76 
|Funcional    | 2  | 9 | 9 | 18 | 4.96 | 3 | 3.16 | 3 | 3.37 | 0.76
|Funcional    | 3  | 9 | 9 | 18 | 4.96 | 3 | 3.16 | 3 | 3.37 | 0.76
|Funcional    | 14 | 6 | 5 | 11 | 3.03 | 2 | 2.11 | 2 | 2.25 | 0.69
|Funcional    | 15 | 6 | 5 | 11 | 3.03 | 2 | 2.11 | 2 | 2.25 | 0.69
|Funcional    | 17 | 6 | 4 | 10 | 2.75 | 2 | 2.11 | 2 | 2.25 | 0.63
|Funcional    | 6  | 5 | 4 | 9  | 2.48 | 2 | 2.11 | 2 | 2.25 | 0.57 
|Funcional    | 16 | 8 | 8 | 16 | 4.41 | 4 | 4.21 | 4 | 4.49 | 0.51
|Funcional    | 22 | 5 | 5 | 10 | 2.75 | 3 | 3.16 | 2 | 2.25 | 0.51
|Não funcional| 5  | 8 | 9 | 17 | 4.68 | 5 | 5.26 | 4 | 4.49 | 0.48
|Não funcional| 3  | 7 | 8 | 15 | 4.13 | 5 | 5.26 | 4 | 4.49 | 0.42
|Não funcional| 2  | 8 | 8 | 16 | 4.41 | 5 | 5.26 | 5 | 5.62 | 0.41
|Funcional    | 11 | 7 | 7 | 14 | 3.86 | 5 | 5.26 | 4 | 4.49 | 0.40
|Não funcional| 6  | 8 | 9 | 17 | 4.68 | 6 | 6.32 | 5 | 5.62 | 0.39
|Não funcional| 7  | 7 | 8 | 15 | 4.13 | 6 | 6.32 | 5 | 5.62 | 0.35
|Não funcional| 4  | 5 | 6 | 11 | 3.03 | 5 | 5.26 | 4 | 4.49 | 0.31
|Funcional    | 12 | 4 | 4 | 8  | 2.20 | 4 | 4.21 | 4 | 4.49 | 0.25
|Funcional    | 13 | 1 | 1 | 2  | 0.55 | 1 | 1.05 | 1 | 1.12 | 0.25
|Não funcional| 1  | 5 | 5 | 10 | 2.75 | 5 | 5.26 | 5 | 5.62 | 0.25
|Funcional    | 4  | 4 | 2 | 6  | 1.65 | 3 | 3.16 | 4 | 4.49 | 0.21
|Funcional    | 5  | 3 | 2 | 5  | 1.38 | 6 | 6.32 | 7 | 7.87 | 0.10


### Considerações para realização dos cálculos
* Peso do Benefício Relativo: 1
* Peso da Penalidade Relativa: 1
* Peso do Custo Relativo: 1
* Peso do Risco Relativo: 1
* Precisão: 2 casas decimais


## Referências
<p align="justify">WIEGERS, Karl. <b>First Things First: Prioritizing Requirements</b>. Process Impact, 1999. Disponível em: <<a>http://www.processimpact.com/articles/prioritizing.html</a>>. Acesso em 18 agos. 2021.</p>

## Versionamento

| Data       | Versão | Descrição                                       | Autores          | Revisor          |
| ---------- | ------ | ---------------------------------------------   | ---------------- | ---------------- |
| 18/08/2021 |  0.1   | Criação do documento, introdução e metodologia  | Hérya Rodrigues  |                  |
| 20/08/2021 |  0.2   | Realização dos cálculos e ordenação da tabela   | Hérya Rodrigues  |                  |
