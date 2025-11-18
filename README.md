# Fonte de Dados (Dataset) de Correlação entre a fonte GODT e HDRO

## Descrição

A fonte de dados contida nesse repositório [df_transplants.csv](df_transplants.csv) é um arquivo do tipo CSV que utiliza como separador de campos o caractere ';' (ponto e vírgula).

Ela contém a correlação de dados da fonte do *Global Observatory on Donation and Transplantation* (GODT) e da fonte de dados do *Human Development Report Office* (HDRO).

Essa fonte foi criada no dia 14/11/2025.

## Pesquisadores

Adriana Leticia dos Reis - ORCID [https://orcid.org/0009-0007-6617-263X](https://orcid.org/0009-0007-6617-263X)

Romeo Bulla Junior - ORCID [https://orcid.org/0000-0001-6386-1500](https://orcid.org/0000-0001-6386-1500)

## Dicionário de Dados

A seguir seguem os campos presentes na fonte de dados supra mencionada:

| Coluna                  | Descrição                                                                                                                                                                                                                                                 |
|-------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| region                  | Regiões possíveis: "Africa" (África); "America" (América); "Eastern Mediterranean" (Mediterrâneo Oriental); "Europe" (Europa); "Southeast Asia" (Sudeste Asiático);e "Western Pacific" (Pacífico Ocidental)                                                                                                                                                                                                           |
| country                 | Nome do país (em inglês).                                                                                                                                                                                                                                 |
| year                    | Ano do registro: 2020, 2021, 2022, 2023 e 2024.                                                                                                                                                                                                           |
| population              | População em milhões de habitantes.                                                                                                                                                                                                                       |
| TOTAL tx         | Total de transplantes. TOTAL tx=TOTAL Kidney Tx + TOTAL Liver TX + Total Heart TX + TOTAL Lung Tx + Pancreas Tx + Small Bowel Tx.                                                                                                                                                                 |
| TOTAL Actual DD         | Total de doadores de órgãos que estão falecidos. TOTAL Actual DD=Actual DBD + Actual DCD.                                                                                                                                                                 |
| Actual DBD              | Qtde. de doadores cujo falecimento foi determinado por critério neurológico.                                                                                                                                                                              |
| Actual DCD              | Qtde. de doadores cujo falecimento foi determinado por critérios circulatórios.                                                                                                                                                                           |
| Total Utilized DD       | Total órgãos utilizados de doadores falecidos. Total Utilized DD=Utilized DBD+Utilized DCD.                                                                                                                                                               |
| Utilized DBD            | Qtde. órgãos utilizados após falecimento por critério neurológico.                                                                                                                                                                                        |
| Utilized DCD            | Qtde. órgãos utilizados após falecimento determinado por critérios circulatórios.                                                                                                                                                                         |
| DD Kidney Tx            | Qtde. de transplantes renais cujo doador é falecido.                                                                                                                                                                                                      |
| LD Kidney Tx            | Qtde. de transplantes renais cujo doador está vivo.                                                                                                                                                                                                       |
| TOTAL Kidney Tx         | Total de transplantes renais. TOTAL Kidney Tx=DD Kidney Tx+LD Kidney Tx.                                                                                                                                                                                  |
| DD Liver Tx             | Qtde. de transplantes de fígado cujo doador é falecido.                                                                                                                                                                                                   |
| DOMINO Liver Tx         | Qtde. de transplantes de fígado em cadeia: procedimento no qual um órgão é removido de um candidato a transplante e imediatamente transplantado para um segundo paciente, sendo que o primeiro paciente recebe um novo órgão de um doador falecido.       |
| LD Liver Tx             | Qtde. de transplantes de fígado cujo doador está vivo.                                                                                                                                                                                                    |
| TOTAL Liver TX          | Total de transplantes de fígado. TOTAL Liver TX=DD Liver Tx+DOMINO Liver Tx+LD Liver Tx.                                                                                                                                                                  |
| Total Heart TX          | Total de transplantes de coração.                                                                                                                                                                                                                         |
| DD Lung Tx              | Qtde. de transplantes de pulmão cujo doador é falecido.                                                                                                                                                                                                   |
| LD Lung Tx              | Qtde. de transplantes de pulmão cujo doador está vivo.                                                                                                                                                                                                    |
| TOTAL Lung Tx           | Total de Transplantes de pulmão. TOTAL Lung Tx=DD Lung Tx+LD Lung Tx.                                                                                                                                                                                     |
| Pancreas Tx             | Qtde. de transplantes de pâncreas.                                                                                                                                                                                                                        |
| Kidney Pancreas Tx      | Qtde. de transplantes de rins e pâncreas.                                                                                                                                                                                                                 |
| Small Bowel Tx          | Qtde. de transplantes de intestino delgado.                                                                                                                                                                                                               |
| develpoment             | Classificação de desenvolvimento de acordo com o HDRO: *Very high human development*, *High human development*, *Medium human development* ou *Low human development*.                                                   |
| idh                     | IDH de um país no ano indicado pela coluna year.                                                                                                                                                                                                     |
| pmp_TOTAL tx    | Total de transplantes (pmp).   |
| pmp_TOTAL Actual DD    | Total de doadores de órgãos que estão falecidos (pmp). pmp_TOTAL Actual DD=pmp_Actual DBD + pmp_Actual DCD.                                                                                                                                            |
| pmp_Actual DBD         | Qtde. de doadores cujo falecimento foi determinado por critério neurológico (pmp).                                                                                                                                                                        |
| pmp_Actual DCD         | Qtde. de doadores cujo falecimento foi determinado por critérios circulatórios (pmp).                                                                                                                                                                     |
| pmp_Total Utilized DD  | Total órgãos utilizados de doadores falecidos. pmp_Total Utilized DD=pmp_Utilized DBD+pmp_Utilized DCD.                                                                                                                                                |
| pmp_Utilized DBD       | Qtde. órgãos utilizados após falecimento por critério neurológico (pmp).                                                                                                                                                                                  |
| pmp_Utilized DCD       | Qtde. órgãos utilizados após falecimento determinado por critérios circulatórios (pmp).                                                                                                                                                                   |
| pmp_DD Kidney Tx       | Qtde. de transplantes renais cujo doador é falecido (pmp).                                                                                                                                                                                                |
| pmp_LD Kidney Tx       | Qtde. de transplantes renais cujo doador está vivo (pmp).                                                                                                                                                                                                 |
| pmp_TOTAL Kidney Tx    | Total de transplantes renais (pmp). pmp_TOTAL Kidney Tx=pmp_DD Kidney Tx+pmp_LD Kidney Tx.                                                                                                                                                             |
| pmp_DD Liver Tx        | Qtde. de transplantes de fígado cujo doador é falecido (pmp).                                                                                                                                                                                             |
| pmp_DOMINO Liver Tx    | Qtde. de transplantes de fígado em cadeia: procedimento no qual um órgão é removido de um candidato a transplante e imediatamente transplantado para um segundo paciente, sendo que o primeiro paciente recebe um novo órgão de um doador falecido (pmp). |
| pmp_LD Liver Tx        | Qtde. de transplantes de fígado cujo doador está vivo (pmp).                                                                                                                                                                                              |
| pmp_TOTAL Liver TX     | Total de transplantes de fígado (pmp). pmp_TOTAL Liver TX=pmp_DD Liver Tx+pmp_DOMINO Liver Tx+pmp_LD Liver Tx.                                                                                                                                        |
| pmp_Total Heart TX     | Total de transplantes de coração (pmp).                                                                                                                                                                                                                   |
| pmp_DD Lung Tx         | Qtde. de transplantes de pulmão cujo doador é falecido (pmp).                                                                                                                                                                                             |
| pmp_LD Lung Tx         | Qtde. de transplantes de pulmão cujo doador está vivo (pmp).                                                                                                                                                                                              |
| pmp_TOTAL Lung Tx      | Total de Transplantes de pulmão (pmp). pmp_TOTAL Lung Tx=pmp_DD Lung Tx+pmp_LD Lung Tx.                                                                                                                                                                |
| pmp_Pancreas Tx        | Qtde. de transplantes de pâncreas (pmp).                                                                                                                                                                                                                  |
| pmp_Kidney Pancreas Tx | Qtde. de transplantes de rins e pâncreas (pmp).                                                                                                                                                                                                           |
| pmp_Small Bowel Tx     | Qtde. de transplantes de intestino delgado (pmp).                                                                                                                                                                                                         |
| idx\_region             | Código da região (redundância com a coluna region), mas como inteiro onde: 1=Europe; 2=America; 3=Eastern Mediterranean; 4=Western Pacific; 5=South-East Asia; e 6=Africa                                                                                                                                                            |


## Referências

GODT
Disponível em: https://www.transplant-observatory.org/export-database/
Acessado em: 14/11/2025

HDRO
Disponível em: https://hdr.undp.org/sites/default/files/2025_HDR/HDR25_Statistical_Annex_HDI_Table.xlsx
Acessado em: 14/11/2025
