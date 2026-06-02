# Patologias Cardíacas em Crianças e Adolescentes

Este projeto tem como objetivo criar e executar um pipeline extração de conhecimento e predição de patologias cardíacas em crianças e adolescentes. Os dados utilizados foram disponibilizados pelo Real Hospital Português (RHP) em Recife-PE, anonimizados com a aprovação do Comitê de Ética do RHP.

## Requisitos do Projeto

Abaixo temos uma lista de softwares necessários:

- **[Python](https://www.python.org/downloads/) (3.12+):** Linguagem de programação.
- **[uv](https://docs.astral.sh/uv/getting-started/installation/) (0.11.18+):** Gerenciador de pacotes e ambientes virtuais.
- **[Git](https://git-scm.com/install/linux) (2.54+):** Sistema de versionamento do projeto.

## Setup do Projeto

Primeiro, é necessário clonar o repositório:

```bash
git clone https://github.com/gauloish/condicao-cardiaca.git
```

Após isso, você deve entrar na raíz do projeto:

```bash
cd condicao-cardiaca
```

Por fim, você deve criar o ambiente virtual e instalar as dependências com o uv:

```bash
uv sync
```