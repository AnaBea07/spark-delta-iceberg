# Projeto: Apache Spark com Delta Lake e Apache Iceberg

Projeto desenvolvido com o objetivo de demonstrar o uso do Apache Spark local (via PySpark), realizando leitura, gravação e manipulação de dados em arquivos nos formatos **Delta Lake** e **Apache Iceberg**, de forma totalmente local.

A estrutura do projeto inclui um ambiente configurado com `uv`, notebooks com exemplos de código PySpark e uma documentação interativa criada com MkDocs.

---

## Avisos

- Este projeto utiliza arquivos locais e bibliotecas específicas. Certifique-se de seguir os passos de instalação para garantir compatibilidade.
- A execução requer Python 3.11 ou superior.
- A manipulação dos dados é feita em notebooks Jupyter, e o kernel correto precisa ser selecionado.

---

## Pré-requisitos

- Python 3.11+
- uv
- JupyterLab para execução dos notebooks

---

## Instalação

1. Clone o repositório:


2. Inicialize o ambiente com o **uv**:

```bash
uv init
uv venv
source .venv/bin/activate  # No Windows use: .\.venv\Scripts\activate
uv add pyspark==3.5.3 delta-spark==3.2.0 jupyterlab ipykernel
```


3. Selecione o kernel do ambiente virtual `.venv` no Jupyter antes de executar os notebooks.

---

## How-to (Como utilizar)

- Os exemplos de Spark Delta estão no notebook:

  - `spark-delta-lake.ipynb` – demonstra como instanciar o SparkSession, criar uma tabela Delta Lake, inserir, atualizar e deletar dados.
  - `spark-apache-iceberg.ipynb` – demonstra como instanciar o SparkSession, criar uma tabela Apache Iceberg, inserir, atualizar e deletar dados.

---

## Documentação

A documentação completa do projeto foi desenvolvida com **MkDocs** e está disponível [aqui](https://anabea07.github.io/spark-delta-iceberg/)

---

## Referências

[Como Usar Python com Apache Spark? Guia Prático de PySpark! - DataWay BR](https://www.youtube.com/watch?v=WwrX1YVmOyA&t=1270s&ab_channel=DataWayBR) <br>
[Como Sair do Zero no Delta Lake e PySpark - DataWay BR](https://www.youtube.com/watch?v=eOrWEsZIfKU&ab_channel=DataWayBR) <br>
[Repositório spark-delta](https://github.com/jlsilva01/spark-delta) <br>
[Repositório spark-iceberg](https://github.com/jlsilva01/spark-iceberg)
