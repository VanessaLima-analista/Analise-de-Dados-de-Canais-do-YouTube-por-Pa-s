### Projeto 6: Análise de Dados de Canais do YouTube por País

#### **Visão Geral**

Este projeto realiza uma análise descritiva de dados de canais do YouTube, com foco no desempenho por país. O objetivo é extrair insights sobre a quantidade de inscritos e uploads, e entender a relação entre essas métricas para diferentes nações.

#### **Fonte dos Dados**

A base de dados original, intitulada "YOUTUBE CHANNELS DATASET", é pública e foi obtida no **Kaggle**. As análises foram realizadas a partir de uma tabela dinâmica criada no **Google Sheets**, que serviu como ponto de partida para este projeto.

#### **Metodologia**

A análise foi conduzida através dos seguintes passos:

1.  **Limpeza e Agregação no Google Sheets:** O arquivo original foi importado para o Google Sheets, onde foi realizada a limpeza de dados e a criação de tabelas dinâmicas para agregar as métricas por país.
2.  **Análise de Desempenho:** Foram identificados os top 10 países com base no número total de inscritos e no total de uploads.
3.  **Análise de Correlação:** A correlação entre a quantidade de inscritos e o número de uploads foi calculada para entender a relação entre as duas métricas.
4.  **Visualização (Python):** Utilizei Python para gerar gráficos de barras, que visualizam os rankings dos países e ajudam a comunicar os insights de forma mais clara.

#### **Resultados e Insights**

* **Top 10 Países por Inscritos:**
    Os países com maior número de inscritos são liderados por Estados Unidos e Índia, que representam uma grande parte da audiência global.

| Country | Subscribers |
|:---|:---|
| US | 2241.8 |
| IN | 2175.6 |
| N.A. | 473.6 |
| KR | 324.3 |
| BR | 256.7 |
| MX | 210.2 |
| AE | 164.0 |
| JP | 156.3 |
| AR | 123.0 |
| PK | 122.8 |

* **Top 10 Países por Uploads:**
    A quantidade de uploads também é dominada por Estados Unidos e Índia, o que sugere que os maiores mercados também são os mais prolíficos em criação de conteúdo.

| Country | Uploads |
|:---|:---|
| US | 8460.17 |
| IN | 3955.99 |
| BR | 929.07 |
| NO | 676.0 |
| KR | 611.51 |
| SV | 548.83 |
| GB | 538.0 |
| CO | 362.0 |
| MX | 342.11 |
| PK | 307.69 |

* **Correlação entre Inscritos e Uploads:**
    A correlação entre o número de inscritos e a quantidade de uploads foi de **0.98**. Isso indica uma correlação extremamente forte e positiva: quanto mais uploads um país tem, maior é o número de inscritos.

---

### **Arquivos**

* **YOUTUBE CHANNELS DATASET.csv**: A base de dados original obtida no Kaggle.
* **N2 - Youtube Channel - Tabela dinâmica - Tabela dinâmica 2.csv**: O arquivo com os dados agregados que você gerou no Google Sheets.
* **top_countries_by_subscribers.png**: O gráfico de barras dos top 10 países por inscritos.
* **top_countries_by_uploads.png**: O gráfico de barras dos top 10 países por uploads.
* **top_countries_subscribers.csv**: A tabela de dados para o gráfico de inscritos.
* **top_countries_uploads.csv**: A tabela de dados para o gráfico de uploads.
