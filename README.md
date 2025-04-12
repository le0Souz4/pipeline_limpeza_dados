# 🧼 Pipeline Automatizado de Limpeza de Dados

Este projeto tem como objetivo o desenvolvimento de um pipeline automatizado e modular para limpeza de dados brutos, utilizando Python e suas principais bibliotecas para manipulação e tratamento de dados.

---

## 📌 Objetivo

Automatizar o processo de limpeza de dados brutos, tratando:

- Valores ausentes (missing values)
- Formatação inconsistente de colunas
- Detecção e tratamento de outliers
- Tipagem e padronização de dados

Com registro de logs e estrutura modular para fácil manutenção e reutilização em diferentes projetos.

---

## 🛠️ Tecnologias Utilizadas

- [Python 3.9+](https://www.python.org/)
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [PyYAML](https://pyyaml.org/)
- [logging (builtin)](https://docs.python.org/3/library/logging.html)
- (Opcional) [typer](https://typer.tiangolo.com/) — para interface via terminal
- (Opcional) [pytest](https://docs.pytest.org/) — para testes automatizados

---

## 🧱 Estrutura do Projeto

pipeline_limpeza_dados/
├── data/
│   ├── raw/           # Dados brutos
│   └── processed/     # Dados limpos
├── logs/              # Arquivos de log
├── config/
│   └── rules.yaml     # Regras de limpeza configuráveis
├── src/
│   ├── loader.py      # Módulo de leitura de arquivos
│   ├── cleaner.py     # Módulo de tratamento dos dados
│   ├── utils.py       # Funções auxiliares
│   └── pipeline.py    # Lógica principal do fluxo
├── main.py            # Script principal para execução do pipeline
└── README.md          # Documentação do projeto
