# arquitetura_de_dados
diagrama 

O diagrama segue estruturado dentro do Azure, onde a orquestração dos pipelines, serão executados no Azure data Factory. A ingestão conterá dados heterogêneos, dando execução ao ETL, seguindo para o Azure Data lake que será um repositório centralizador em que se armazena todos os tipos de dados gerados, seguindo integração com o Databricks para processamentos e distribuição de dados, sendo armazenado pelo Azure SQL, podendo gerar relatórios e visualizações no Power BI.

A escolha pelo diagrama, leva em consideração a desenvoltura organizacional de forma centralizada, não sendo necessário um esquema definido e estruturado, havendo apenas o armazenamento dos dados em estado bruto. Por ser uma abordagem de arquitetura que permite armazenar uma grande quantidade de dados em um local central, permitindo que esses dados estejam disponíveis para serem categorizados, processados, analisados e consumidos por diversos grupos dentro de sua organização, possibilitando maior agilidade, interatividade, insights e colaboração para o negócio.

