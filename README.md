# Engenharia e visualização de dados - Pandemia Covid19

Este projeto faz parte da conclusão do treinamento de Big Data Engineer promovido pela Semantix. Os dados utilizados (disponível em: https://mobileapps.saude.gov.br/esus-vepi/files/unAFkcaNDeXajurGB7LChj8SgQYS2ptm/04bd3419b22b9cc5c6efac2c6528100d_HIST_PAINEL_COVIDBR_06jul2021.rar) serão inseridos no cluster de big data (disponibilizado em https://github.com/rodrigo-reboucas/docker-bigdata.git) que roda em conteineres via Docker. O Jupyter notebook foca principalmente na ferramenta Spark, utilizando Python como linguagem de programação (PySpark). Serão realizadas integrações com Elastic e Kafka também.

Esses dados são relacionados à pandemia Covid19 no Brasil de 2020 e 2021, o arquivo projeto_final_spark.pdf mostra as perguntas respondidas pelo jupyter notebook "Engenharia e visualização de dados Covid19.ipynb". Os itens foram carregado através do hdfs, salvos em diversos formatos demandados (.csv, parquet, tabelas) e analisados, criando indicadores e visualizaçao simples dos dados.

