
# Apresentação
## Sobre o repositório
Esse repositório contém o Projeto Final do Módulo 01 do Bootcamp Data Science da Alura:Python e Pandas para análise de dados reais.

## Sobre o Módulo 01
O objetivo desse módulo foi analisar dados de saúde utilizando a biblioteca pandas do python. Os dados analisados foram coletados do site [DATASUS](http://www2.datasus.gov.br/DATASUS/index.php?area=0202&id=11633&VObj=http://tabnet.datasus.gov.br/cgi/deftohtm.exe?sih/cnv/qi). Eles continham informações, por unidade federativa, sobre os gastos com saúde pública, no período de 2007 a 2021. Esse módulo foi estruturado em 5 aulas:

- Aula 01: Aquisição e leitura de dados
- Alua 02: Primeiras visualizações de dados
- Aula 03: Manipulação de dados
- Aula 04: Análise gráfica e criação de hipóteses
- Aula 05: Manipulação e interpretação de gráficos

Em cada aula foram propostos desafios (alguns realmente bem desafiadores). Os resultados dos estudos desse módulo podem ser encontrados [nesse repositório](https://github.com/renanmath/Alura_Bootcamp_Data_Science/tree/main/Modulo01). 

## Sobre o Projeto do Módulo 01

O objetivo do projeto final é pôr em prática o que foi aprendido no módulo 01, analizando uma base de dados diferente. Foi recomendado o uso de uma base de dados exxtraída também do DATASUS, mas podendo conter análises cruzadas com dados de outras fontes. Os dados a serem escolhidos para trabalhados e analizados ficariam a critério do aluno. 

# O projeto: dengue, aqui não!
![aqui não](https://github.com/renanmath/Bootcamp_Projeto_Modulo01/blob/main/a1da7c570f8c41ed8ed66fd1f9d2f4c3.jpeg)

O tema escolhido para o projeto foi dengue, mais precisamente um estudo descritivo da doença no Ceará, meu estado natal, no período de 2008 à 2020. Escolhi esse tema por dois motivos:
- Apesar de não ser tão letal como, por exemplo, a covid, a dengue é uma doença que pode evoluir para casos muito graves chegando mesmo ao óbito. O fato de não estarmos vendo um quadro tão desolador quanto poderia ser provavelmente deve-se aos esforços no combate à doença e ao vetor trasmissor. Ainda assim é necessário uma conscientização maior por parte da população, para evitar que a epidemia de dengue tome proporções catastróficas. 
- O DATASUS tinha um bom banco de dados sobre dengue, ao contrário de outros temas que pesquisei, antes de decidir por esse. 

![Combate a dengue](https://github.com/renanmath/Bootcamp_Projeto_Modulo01/blob/main/combate_dengue.jpg)

![evitar a dengue](https://github.com/renanmath/Bootcamp_Projeto_Modulo01/blob/main/dengue-cuidados.jpg)

A fim de implementar esse projeto, importei do site do DATASUS cinco banco de dados:
- Valor total gasto com despesas hospitalares relacionadas à dengue, no estado do Ceará, organizados por município e ano/mês de atendimento, no período de Jan/2008 à Mar/2021.
- Número de internações relacionadas à dengue, no estado do Ceará, organizados por município e ano/mês de atendimento, no período de Jan/2008 à Mar/2021.
- Número de óbitos por dengue, no estado do Ceará, organizados por município e ano/mês de atendimento, no período de Jan/2008 à Mar/2021.
- Taxa de mortalidade da dengue, no estado do Ceará, organizados por município e ano/mês de atendimento, no período de Jan/2008 à Mar/2021.
- Estimativa populacional, no estado do Ceará, organizados por município, de 2008 a 2020.

O [notebook do projeto](https://github.com/renanmath/Bootcamp_Projeto_Modulo01/blob/main/Projeto_Bootcamp(Modulo01).ipynb) está estruturado da seguinte maneira:
- Introdução
  - Coleta dos dados: onde falo um pouco mais sobre a extração dos dados do site do DATASUS
  - Sobre a dengue: onde comento brevemente algumas informações importantes sobre a doença
- Importação e tratamento inicial: carrego os dataframes e faço o tratamento dos dados.
- Análise dos dados (valores absolutos): faço análise descritiva e gráfica dos dados brutos, levando hipóteses e tiro conclusões.
- Análise per capita: importo dados populacionais do Ceará e cruzo esses dados com os dataframes previamente estudados para incluir uma análise per capita das informações
