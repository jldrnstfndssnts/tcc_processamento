# TCC

## Pré-requisitos

Os programas necessários para rodar o código deste repositório são:

- Git
- uv (Será reposnsável pela instalação do Python e das bibliotecas do Python necessárias)

## Estrutura do repositório

```
.
├── data                        # Pasta com dados 
│   └── raw                     # Dados brutos
│       └── dados_vao_aqui.csv 
├── pyproject.toml              # Arquivo de matadados utilizado pelo Python
├── .python-version             # Arquivo criado pelo uv para dizer listar a versão do Python utilizada 
├── .gitignore                  # arquivo usado pelo git para excluir arquivos do repositório 
├── src                         # Código fonte (arquivos .py e arquivos .ipynb)
│   └── example.ipynb
│   └── example.py
└── uv.lock                     # Aarquivo utilizado pelo uv para dar "lock" nas dependências. Isto é fixá-las em uma versão específica que garantirá que nosso programá rodará sem falhas.
```

## FAQ

Q: De onde o `uv` (bem como o `pip`) baixa as bibliotecas que usarei com o Python?

A: Do repositório <https://pypi.org/>

Q: Como rodar o códgio?

A: Em um terminal, com o virutal environment do Python ativo, rode o servidor do jupyter notebook

```sh
$ jupyter notebook
```

Você também pode abrir o carderno do Jupyter pelo próprio VSCode.