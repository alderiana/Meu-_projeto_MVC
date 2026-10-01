# 🚀 Sistema de Gerenciamento de Usuários (Padrão MVC)

Este é um projeto escolar desenvolvido em **Python** que implementa o padrão de arquitetura **MVC (Model-View-Controller)** para realizar operações completas de CRUD (Cadastrar, Listar, Atualizar e Excluir) de usuários, com persistência de dados utilizando o banco de dados **PostgreSQL**.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python 3
* **Banco de Dados:** PostgreSQL (validado via pgAdmin)
* **Arquitetura:** MVC (Model-View-Controller)
* **Controle de Versão:** Git & GitHub

## 📂 Estrutura do Projeto
* `controller/`: Gerencia o fluxo da aplicação, validações e regras de negócio.
* `model/`: Realiza a comunicação direta com o banco de dados PostgreSQL e executa comandos SQL.
* `view/`: Responsável pelas interações com o usuário e exibição do menu no terminal.
* `main.py`: Arquivo principal que inicializa o loop do sistema.