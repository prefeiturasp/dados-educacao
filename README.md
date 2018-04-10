Seguindo a sua Política de Transparência Ativa e Dados Abertos, a Secretaria Municipal de São Paulo (SME-SP) tem aberto uma série de bases de dados sobre suas políticas educacionais. Devido ao volume de registros, algumas dessas bases não podem ser abertas em programas como o Excel, e necessitam de ferramentas mais avançadas para sua leitura e análise. 

Neste repositório, disponibilizamos tutoriais com operações básicas para explorar as bases e realizar algumas análises que são demandadas com mais frequência à Secretaria. Desta forma, além de compartilhar conhecimento sobre essas análises, também ficam transparentes os filtros e operações realizadas.

Utilizamos aqui a biblioteca Pandas, poderosa ferramenta de análise de dados do Python.

**Requisitos:** 

* Noções de Python /ou/ vontade de aprender!
* Instalação do Python e bibliotecas como numpy e pandas. Para facilitar, você pode instalar o Anaconda, que, além do Python, já vem com [mais de 150 pacotes](https://docs.anaconda.com/anaconda/packages/pkg-docs) relacionados a Ciência de Dados. [Saiba mais](https://conda.io/docs/user-guide/install/download.html).

**Dados:**

* As bases estão disponíveis na página mantida pela SME no [Portal de Dados Abertos](http://dados.prefeitura.sp.gov.br/organization/educacao1) da Prefeitura de São Paulo, no conjunto ["Microdados da Rede Municipal de Ensino - Matrículas"](http://dados.prefeitura.sp.gov.br/dataset/microdados-da-rede-municipal-de-ensino-matriculas). 
* Baixe os arquivos dos anos com que deseja trabalhar. Estão em um arquivo compactado do tipo .rar. 
* Descompacte e deixe o arquivo .csv na mesma pasta deste Jupyter Notebook com que estamos trabalhando. 
* Note que, além dos dados, há um arquivo chamado "LEIA-ME" e um "Dicionário de Variáveis". Trata-se da documentação que explica a metodologia utilizada e o significado dos dados. Você precisará deles para interpretar a base corretamente!
* Os resultados das análises ficam disponíveis aqui em .CSV.
