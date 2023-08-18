# MLOPS-Template-23-2
 
## Cookiecutter Repository Template

Este repositório serve como um template para criação de novos projetos utilizando o Cookiecutter. O Cookiecutter é uma ferramenta que permite criar projetos a partir de templates predefinidos, agilizando o processo de inicialização e padronização de novos projetos. Este projeto foi desenvolvido para a diciplina de MLOps.

## Funcionalidades

- Estrutura de diretórios e arquivos predefinida para um novo projeto.
- Configurações iniciais, como arquivos de configuração, dependências e estrutura básica de código.

## Requisitos

Antes de utilizar este template, certifique-se de ter o Cookiecutter instalado

## Como Usar

1. Instale o Cookiecutter, caso ainda não esteja instalado.
   ```bash
   pip install cookiecutter
   ```

2. Crie um novo projeto utilizando o template.
   ```bash
   cookiecutter gh:seu-usuario/cookiecutter-template
   ```

3. Siga as instruções para preencher as informações específicas do seu projeto.

4. O Cookiecutter irá gerar a estrutura do novo projeto com base no template.

## Estrutura de Arquivos

```
cookiecutter-template/
│   README.md
│   cookiecutter.json
│   
└───{{cookiecutter.project_name}}/
│   │   data
|   |   models
|   |   notebooks
|   └───src
│   │   |   __init__.py
│   │   |   process.py
│   │   |   train.py

```

- `README.md`: Documentação do template.
- `cookiecutter.json`: Arquivo de configuração para definir as variáveis do projeto.
- `{{cookiecutter.project_name}}/`: Diretório principal do projeto gerado.
- `__init__.py`: Arquivo de código principal.
- `process.py`: Arquivo de código para preprocessamento.
- `train.py`: Arquivo de código para treinar o modelo.
- `src`: Repositório para os scripts.
- `data`: Repositório para a base de dados.
- `models`: Repositório para os modelos de machine learning.
- `noteboks`: Repositório para os jupyter notebooks.
