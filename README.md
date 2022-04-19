# Projeto_Engenharia_Dados_SC

Projeto de Engenharia de Dados da SoulCode para conclusão do curso, com o tema Segurança Pública


REQUISITOS OBRIGATÓRIOS
- Obrigatoriamente os datasets devem ter formatos diferentes (CSV / Json / Parquet / Sql / NoSql) e 1 deles obrigatoriamente tem que ser em CSV.
- Operações com Pandas (limpezas , transformações e normalizações) 
- Operações usando PySpark com a descrição de cada uma das operações.
- Operações utilizando o SparkSQL com a descrição de cada umas das operações.
- Os datasets utilizados podem ser em lingua estrangeira , mas devem ao final terem seus dados/colunas exibidos na lingua PT-BR
- Os datasets devem ser salvos e operados em armazenamento cloud obrigatoriamente dentro da plataforma GCP 
- os dados tratados devem ser armazenados também em GCP, mas obrigatoriamente em um datalake(Gstorage ) , DW(BigQuery) ou em ambos.
- Os datasets originais devem ser armazenados em MySql
- Os Dataframe(s) resultante(s) deve(m) estar em uma coleção do mongoDb atlas
- Deve ser feito análises dentro do Big Query utilizando a linguagem padrão SQL com a descrição das consultas feitas.
- Deve ser criado no datastudio um dashboard para exibição gráfica dos dados tratados trazendo insights importantes
- Deve ser demonstrado em um workflow simples (gráfico) as etapas de ETL com suas respectivas ferramentas.

REQUISITOS DESEJÁVEIS
- Implementar captura e ingestão de dados por meio de uma PIPELINE com modelo criado em apache beam usando o dataflow para o work
- Utilizar o dataflow com algum modelo pré-definido
- Criar plotagens usando pandas para alguns insights durante o processo de Transformação 
- Por meio de uma PIPELINE fazer o carregamento dos dados normalizados diretamente para um DW ou DataLake ou ambos
- Montar um relatório completo com os insights que justificam todo o processo de ETL utilizado
- Levantar custos com a utilização do google cloud no período do projeto e possíveis otimizações de custo
