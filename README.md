# Previsão de Vendas de uma Sorveteria

Via IA, foram gerados dados contendo a quantidade de sorvetes vendidos ao dia nos meses de janeiro e fevereiro conforme a temperatura do dia.

![Tabela de vendas](https://github.com/luisinhisbox/VendasSorveteria/blob/55cb8d4e345280128e1b4253d2b77b90b163dc92/assets/tabeladados.png)


Foi criado um workspace no Azure Machine Learning e, de dentro do studio, os jobs foram feitos via AutoML e  pipeline (designer). Foi escolhido o método de regressão para as tarefas por se tratar de uma previsão de dados numéricos.

## PIPELINE

### DESIGN
![Design](https://github.com/luisinhisbox/VendasSorveteria/blob/55cb8d4e345280128e1b4253d2b77b90b163dc92/assets/pipelinedesign.png)

### SCORE DATASET
![Score Dataset](https://github.com/luisinhisbox/VendasSorveteria/blob/55cb8d4e345280128e1b4253d2b77b90b163dc92/assets/scored_dataset.png)

## AUTOML
### MÉTRICAS CHILD JOB
![Métricas do melhor child job](https://github.com/luisinhisbox/VendasSorveteria/blob/b1c1cd34ccf53dab4ddb712bee36c6aa012a76f8/assets/m%C3%A9tricaschildjob.png)

