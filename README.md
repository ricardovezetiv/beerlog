# beerlog
Python Week 2022 na Linux Tips

## Obtendo repositório

1. Faça login no github
2. Crie um **fork** (cópia) deste repositório clicando em [fork](https://github.com/ricardovezetiv/beerlog/fork)
3. O seu repositório estará em `https://github.com/username/beerlog`
4. Copie a URL do seu repositório

> **Observação**: substitua `username` pelo seu nome de usuário do github.

## Preparando o ambiente

- Você pode rodar localmente em seu computador desde que tenha o Python 3.8+
  - Para rodar localmente faça o clone com `git clone https://github.com/username/beerlog`
  - Acesse a pasta `beerlog`
- Ou em qualquer plataforma que permita executar Python 3.8

## Requisitos

Este template utiliza o gerenciador de pacotes **poetry**

### Ambiente Windows
Se estiver rodando no Windows no seu ambiente local, execite o comando abaixo
no `Windows PowerShell` para instalar o Poetry no Linux

```bash
$ (Invoke-WebRequest -Uri https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py -UseBasicParsing).Content | python -
```

### Ambiente Linux
Se estiver rodando no Linux no seu ambiente local, execute o comando abaixo
para instalar o Poetry no Linux

```bash
$ curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
```

## Instalando o ambiente

O comando a seguir instala as dependências do projeto.

```bash
$ poetry install
```

O comando a seguir ativa o ambiente virtual do poetry

```bash
$ poetry shell
```

> **Importante:** o ambiente precisa estar ativado para o programa executar.

Executando o programa

```bash
beerlog
# ou
python -m beerlog
```

Se apareceu `Hello from beerlog` então está tudo certo.
