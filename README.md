# GeoBusiness-Analytics-BR



GeoBusiness-Analytics-BR/
│
├── data/                   # (Opcional no Git) Dados locais para teste
│   ├── 01_bronze/          # Dados brutos da Receita Federal
│   ├── 02_silver/          # Dados limpos e tipados
│   └── 03_gold/            # Tabelas agregadas por região/franquia
│
├── notebooks/              # Jupyter Notebooks para exploração e testes rápidos
│   └── 01_exploracao_cnpj.ipynb
│
├── src/                    # Código fonte de produção em Python/PySpark
│   ├── config/             # Configurações do Spark e variáveis de ambiente
│   ├── extract/            # Scripts de ingestão (Raw -> Bronze)
│   ├── transform/          # Scripts de limpeza (Bronze -> Silver)
│   └── aggregate/          # Regras de negócio e agregação (Silver -> Gold)
│
├── docs/                   # Documentação técnica e dicionário de dados
├── requirements.txt        # Dependências do projeto (pyspark, pandas, etc.)
└── README.md               # Apresentação do seu projeto