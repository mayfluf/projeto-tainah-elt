🚀 Projeto ETL Completo - Mercado Livre
Este projeto desenvolve um pipeline completo de ETL (Extração, Transformação e Carga) com dados obtidos via API do Mercado Livre, integrando diferentes ferramentas de armazenamento e análise em nuvem.

📌 Etapas do ETL
Extração: Consulta automática à API pública do Mercado Livre com base em um termo de busca (ex: webcam).

Transformação:

Normalização de dados

Remoção de nulos

Renomeação de colunas

Carga: Os dados tratados são enviados para:

📁 Google Cloud Storage (bucket mercadolivre_seunome)

🗃️ MongoDB Atlas (como coleção)

🛢️ Cloud SQL (MySQL)

📊 Google BigQuery (em dois datasets distintos: mercado_livre e mercado2)

Visualização: Conexão com Looker Studio para construção de dashboards.

🧰 Tecnologias Usadas
Python (Pandas, Requests, Pymongo, MySQL Connector)

Google Cloud Platform (Colab, GCS, BigQuery, Cloud SQL)

MongoDB Atlas

Looker Studio

📁 Arquivos
etl_mercado_livre.ipynb: notebook completo com o pipeline

mercado.csv: arquivo de dados tratado

💡 Como Usar
Configure variáveis como usuário, senha do MongoDB e IP do MySQL.

Execute o notebook no Google Colab.

Acompanhe os dados nos buckets, bancos e visualizações.
