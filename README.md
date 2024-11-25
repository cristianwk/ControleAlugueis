# 🏠 Controle de Aluguéis

## 📝 Descrição do Projeto

O *Controle de Aluguéis* é um sistema simples para gerenciamento de imóveis em uma imobiliária. Com ele, é possível cadastrar imóveis, clientes, registrar locações, e gerar relatórios de imóveis locados. O sistema possui uma interface amigável desenvolvida com Bootstrap.


📂 Repositório inicial: [Configuração Padrão](https://github.com/cristianwk/ControleAlugueis)

Após configurar e executar o projeto inicial, avançaremos para a modelagem e estruturação do sistema *Controle de Aluguéis*.

## 🌟 Fluxo do Sistema

![Fluxo do Sistema](https://versamartonline.shop/images/core.png)

## ⚙️ Funcionalidades

- **Cadastro de Imóveis**:

  - Detalhes: Código, Tipo (Apartamento, Kitnet, Casa), Endereço e Valor.
  - Exibição e filtro por tipo de imóvel na homepage.
- **Cadastro de Clientes**:

  - Informações: Nome, E-mail e Telefone.
- **Registro de Locações**:

  - Relacionamento entre Cliente e Imóvel.
  - Período: Data de início e término.
- **Relatório de Imóveis Locados**:

  - Listagem detalhada dos imóveis alugados.

## 🛠️ Tecnologias Utilizadas

- **Backend**: Python, Django
- **Banco de Dados**: SQLite3
- **Frontend**: HTML, CSS, JavaScript, Bootstrap

## 📋 Pré-requisitos

Antes de iniciar o projeto, certifique-se de que os seguintes itens estão instalados:

- Python (python==3.*)
- Pip (gerenciador de pacotes do Python)

## ⚙️ Rodando o sistema

Para iniciar o projeto:

cristianms@PC-Casa MINGW64 /d/xampp/htdocs/python/ControleAlugueis (main)
$ python -m venv .venv

cristianms@PC-Casa MINGW64 /d/xampp/htdocs/python/ControleAlugueis (main)
$ source .venv/Scripts/activate
(.venv) 
cristianms@PC-Casa MINGW64 /d/xampp/htdocs/python/ControleAlugueis (main)
$ pip install -r requirements.txt

cristianms@PC-Casa MINGW64 /d/xampp/htdocs/python/ControleAlugueis (main)
$ python manage.py runserver

acessar em: http://127.0.0.1:8000/
---
