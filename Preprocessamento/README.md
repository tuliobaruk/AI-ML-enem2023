# Pré-processamento de Dados e Visão Geral do Dataset

Este repositório contém os passos de pré-processamento aplicados ao dataset original, bem como o dataset resultante após o processamento. O Jupyter Notebook incluído nesta pasta detalha o processo de transformação e mapeamento dos dados.

## Estrutura dos Arquivos

- **preProcessamento.ipynb**: Jupyter Notebook que contém todos os passos de pré-processamento aplicados ao dataset.
- **PreprocessedDataframe.csv**: O dataset após o pré-processamento, pronto para análise.

## Mapeamento e Transformação dos Dados

Abaixo está um resumo das transformações e mapeamentos aplicados ao dataset:

### 1. TP_ST_CONCLUSAO: Situação de Conclusão do Ensino Médio

| Valor | Descrição                                            |
| ----- | ---------------------------------------------------- |
| 1     | Já concluí o Ensino Médio                            |
| 2     | Estou cursando e concluirei o Ensino Médio em 2023   |
| 3     | Estou cursando e concluirei o Ensino Médio após 2023 |
| 4     | Não concluí e não estou cursando o Ensino Médio      |

### 2. SG_UF_PROVA_NUM: Unidade da Federação da Aplicação da Prova

| Valor | Unidade da Federação (UF) |
| ----- | ------------------------- |
| 1     | AC                        |
| 2     | AL                        |
| 3     | AM                        |
| 4     | AP                        |
| 5     | BA                        |
| 6     | CE                        |
| 7     | DF                        |
| 8     | ES                        |
| 9     | GO                        |
| 10    | MA                        |
| 11    | MG                        |
| 12    | MS                        |
| 13    | MT                        |
| 14    | PA                        |
| 15    | PB                        |
| 16    | PE                        |
| 17    | PI                        |
| 18    | PR                        |
| 19    | RJ                        |
| 20    | RN                        |
| 21    | RO                        |
| 22    | RR                        |
| 23    | RS                        |
| 24    | SC                        |
| 25    | SE                        |
| 26    | SP                        |
| 27    | TO                        |

### 3. Q006: Renda Mensal da Família

| Valor | Descrição                        |
| ----- | -------------------------------- |
| 0     | Nenhuma Renda                    |
| 1     | Até R$ 1.320,00                  |
| 2     | De R$ 1.320,01 até R$ 1.980,00   |
| 3     | De R$ 1.980,01 até R$ 2.640,00   |
| 4     | De R$ 2.640,01 até R$ 3.300,00   |
| 5     | De R$ 3.300,01 até R$ 3.960,00   |
| 6     | De R$ 3.960,01 até R$ 5.280,00   |
| 7     | De R$ 5.280,01 até R$ 6.600,00   |
| 8     | De R$ 6.600,01 até R$ 7.920,00   |
| 9     | De R$ 7.920,01 até R$ 9.240,00   |
| 10    | De R$ 9.240,01 até R$ 10.560,00  |
| 11    | De R$ 10.560,01 até R$ 11.880,00 |
| 12    | De R$ 11.880,01 até R$ 13.200,00 |
| 13    | De R$ 13.200,01 até R$ 15.840,00 |
| 14    | De R$ 15.840,01 até R$ 19.800,00 |
| 15    | De R$ 19.800,01 até R$ 26.400,00 |
| 16    | Acima de R$ 26.400,00            |

### 4. Q010: Presença de Carro na Residência

| Valor | Descrição           |
| ----- | ------------------- |
| 0     | Não                 |
| 1     | Sim, um             |
| 2     | Sim, dois           |
| 3     | Sim, três           |
| 4     | Sim, quatro ou mais |

### 5. Q011: Presença de Motocicleta na Residência

| Valor | Descrição           |
| ----- | ------------------- |
| A     | Não                 |
| B     | Sim, uma            |
| C     | Sim, duas           |
| D     | Sim, três           |
| E     | Sim, quatro ou mais |

### 6. PRESENCA_COMPLETA: Status de Presença

| Valor | Descrição                                   |
| ----- | ------------------------------------------- |
| 0     | Alunos que se abstiveram em um ou mais dias |
| 1     | Alunos presentes em todas as provas         |

### 7. GRUPO_ETARIO: Grupo Etário

| Valor | Descrição              |
| ----- | ---------------------- |
| 1     | Jovens (17-20)         |
| 2     | Jovens Adultos (21-25) |
| 3     | Adultos (26-55)        |
| 4     | Idosos (56+)           |

## Uso

Para explorar os passos de pré-processamento dos dados, abra o notebook `preProcessamento.ipynb`.

O arquivo `PreprocessedDataframe.csv` contém o dataset após a aplicação das etapas de pré-processamento.

O dataset original pode ser acessado através do link a seguir:
[Microdados ENEM - INEP](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem)

Em qualquer dúvida sinta-se à vontade para abrir uma issue.
