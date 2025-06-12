# 🕵️‍♀️ Análise de Padrões Criminais em Los Angeles
## Otimizando Recursos para a Segurança Urbana

### 📄 Visão Geral do Projeto
Este projeto de ciência de dados visa auxiliar o Departamento de Polícia de Los Angeles (LAPD) na identificação de padrões de comportamento criminal na cidade. Através da análise de dados de crimes, o objetivo é gerar insights que possam otimizar a alocação de recursos e estratégias para combater a criminalidade em diferentes áreas de Los Angeles.

O projeto foi desenvolvido como parte de *[Mencione o contexto, por exemplo: "um desafio de análise de dados", "um curso de ciência de dados", "um projeto acadêmico de portfólio"]*, demonstrando habilidades em manipulação de dados, análise exploratória e visualização.

---

### 📊 Dados
O dataset utilizado (`crimes.csv`) é uma versão modificada de dados publicamente disponíveis do Los Angeles Open Data. Ele contém informações detalhadas sobre ocorrências criminais, incluindo:

- `DR_NO`: Número de Registro da Divisão  
- `Date Rptd`: Data do relatório (MM/DD/YYYY)  
- `DATE OCC`: Data da ocorrência (MM/DD/YYYY)  
- `TIME OCC`: Hora da ocorrência (formato 24 horas)  
- `AREA NAME`: Nome da Área Geográfica/Divisão de Patrulha (ex: 77th Street)  
- `Crm Cd Desc`: Descrição do crime cometido  
- `Vict Age`: Idade da vítima em anos  
- `Vict Sex`: Sexo da vítima (F: Feminino, M: Masculino, X: Desconhecido)  
- `Vict Descent`: Descendência da vítima (códigos como A: Outros Asiáticos, B: Preto, W: Branco, H: Hispânico/Latino/Mexicano, etc.)  
- `Weapon Desc`: Descrição da arma utilizada (se aplicável)  
- `Status Desc`: Status do crime  
- `LOCATION`: Endereço da ocorrência  

---

### 📈 Análise e Insights

A análise exploratória dos dados revelou os seguintes insights:

- **Distribuição de Crimes por Hora do Dia**  
  Foi identificado um pico de ocorrências criminais em uma hora específica do dia.  
  **Hora de Pico de Crimes**: **[Inserir a variável `peak_crime_hour` aqui]** horas  
  > *(Sugestão: incluir o gráfico gerado com `sns.countplot(data=crimes, x="Hour OCC")`)*

- **Crimes Noturnos por Área**  
  Focando nas ocorrências entre 00:00h–05:59h e 20:00h–23:59h, foi possível determinar a área com o maior número de incidentes noturnos.  
  **Área com Maior Incidência de Crimes Noturnos**: **[Inserir a variável `peak_night_crime_location` aqui]**

- **Faixa Etária das Vítimas**  
  As vítimas foram categorizadas por faixas etárias para entender a distribuição dos crimes entre os grupos de idade.  
  **Distribuição de Vítimas por Faixa Etária**:  


### 🔍 Exemplo de `.head()` do Dataset

| DR_NO      | Date Rptd | DATE OCC  | TIME OCC | AREA NAME  | Crm Cd Desc       | Vict Age | Vict Sex | Vict Descent | Weapon Desc | Status Desc | LOCATION           |
|------------|-----------|-----------|----------|------------|-------------------|----------|----------|---------------|--------------|--------------|---------------------|
| 220314085  | 2022-07-22| 2020-05-12| 1110     | Southwest  | THEFT OF IDENTITY | 27       | F        | B             | NaN          | Invest Cont  | 2500 S SYCAMORE AV |
| 222013040  | 2022-08-06| 2020-06-04| 1620     | Olympic    | THEFT OF IDENTITY | 60       | M        | H             | NaN          | Invest Cont  | 3300 SAN MARINO ST |
| 220614831  | 2022-08-18| 2020-08-17| 1200     | Hollywood  | THEFT OF IDENTITY | 28       | M        | H             | NaN          | Invest Cont  | 1900 TRANSIENT     |
| 231207725  | 2023-02-27| 2020-01-27| 0635     | 77th Street| THEFT OF IDENTITY | 37       | M        | H             | NaN          | Invest Cont  | 6200 4TH AV        |
| 220213256  | 2022-07-14| 2020-07-14| 0900     | Rampart    | THEFT OF IDENTITY | 79       | M        | B             | NaN          | Invest Cont  | 1200 W 7TH ST      |

---

### 🛠️ Tecnologias Utilizadas

- **Linguagem de Programação:** Python  
- **Bibliotecas:**
- `pandas` (Manipulação e Análise de Dados)  
- `numpy` (Operações Numéricas)  
- `matplotlib.pyplot` (Visualização de Dados)  
- `seaborn` (Visualização de Dados Estatísticos)  

---

### 🚀 Como Executar o Projeto

Este repositório contém o código Python para a análise. Para replicar os resultados:

**Clone o Repositório:**

```bash
git clone https://github.com/seu-usuario/nome-do-seu-repositorio.git](https://github.com/Gustsilv/analise-exploratoria-crimes-de-los-angeles.git
cd analise-exploratoria-crimes-de-los-angeles
```
**Instale as Dependências:**
bash
```pip install pandas numpy matplotlib seaborn````

**Execute o Notebook ou Script:**

Abra o arquivo .ipynb (Jupyter Notebook) ou Execute o script Python .py no seu ambiente de preferência




