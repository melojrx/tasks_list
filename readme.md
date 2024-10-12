# Task List Application

Uma aplicação simples de lista de tarefas construída com **Flask** e **SQLite**, utilizando **Bootstrap** para o front-end responsivo e **SQLAlchemy** para a persistência dos dados.

## Funcionalidades
- Adicionar tarefas
- Marcar tarefas como concluídas
- Excluir tarefas com confirmação por modal
- Interface responsiva utilizando Bootstrap

## Estrutura do Projeto

```bash
task_list_app/
│
├── app.py                 # Arquivo principal que contém as rotas e lógica da aplicação
├── db.py                  # Configuração do banco de dados usando SQLAlchemy
├── models.py              # Definição do modelo de tarefas (Task)
├── templates/             # Pasta contendo os templates HTML
│   ├── base.html          # Template base com layout da página
│   ├── index.html         # Página inicial com a lista de tarefas
│   └── add_task.html      # Página para adicionar uma nova tarefa
├── static/                # Pasta para arquivos estáticos (CSS, JS)
│   └── styles.css         # Arquivo de estilos (se necessário)
└── tasks.db               # Arquivo de banco de dados SQLite (gerado automaticamente)

Pré-requisitos
Antes de começar, você precisará ter o seguinte instalado:

Python 3.x
Pip (gerenciador de pacotes do Python)
Virtualenv (opcional, mas recomendado)

Instalação
Siga os passos abaixo para rodar a aplicação localmente.

Clone este repositório:

bash
git clone https://github.com/seu-usuario/task_list_app.git
cd task_list_app
Crie e ative um ambiente virtual:

bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
.\venv\Scripts\activate    # Windows
Instale as dependências do projeto:

bash
pip install -r requirements.txt
Execute a aplicação:

bash
python app.py
Acesse a aplicação no navegador:
http://127.0.0.1:5000/

Banco de Dados
A aplicação utiliza SQLite como banco de dados. O arquivo de banco de dados (tasks.db) será gerado automaticamente ao rodar a aplicação pela primeira vez.

Tecnologias Utilizadas
Flask - Framework web leve para Python
SQLite - Banco de dados relacional leve
SQLAlchemy - ORM para Python
Bootstrap 5 - Biblioteca CSS para um design responsivo

Melhorias Futuras
Adicionar paginação à lista de tarefas.
Implementar autenticação de usuários.
Filtrar tarefas por status (completas/incompletas).

Contribuições
Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request com melhorias ou correções.

