# Desafio Data Engineering

Este desafio faz parte do processo de contratação para o time de Engenharia de Dados que trabalhará na Plataforma de Dados do Grupo Todos.

Nossa squad é responsável pelas iniciativas de ingestão, processamento e transformação de Dados em ecossistema Big Data, de acordo com as necessidades das Unidades de Negócio.


# Uso

Dentro da pasta do repositório executar o seguinte comando:

``` sh
docker-compose up
```

> OBS: processo irá executar o build do container com o `jupyter + pandas + spark`

## acesso ao jupyter

Após a conclusào do build o jupyter irá iniciar: utilize a url de localhost para logar no jupyter lab.

O jupyter lab necessita de um token que é gerado no ato do start do container, ele aparece junto com a URL.

## notebooks
Dentro do jupyter haverá dois container, são eles:
 - **MaisTodosPandas**: código do desafio feito usando o pandas.
 - **MaisTodosSpark**:  código do desafio feito usando o Spark.
 