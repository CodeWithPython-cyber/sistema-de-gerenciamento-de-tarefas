# Sistema de gerenciamento de tarefas

Esse projeto será dividido em várias partes, cada uma responsável por uma funcionalidade específica, e usará as bibliotecas sqlite3 para armazenamento de dados e pandas para manipulação e exportação de dados. A estrutura modular e o uso de um banco de dados local simulam um sistema de backend real.

Estrutura do Projeto
O projeto terá a seguinte estrutura de diretórios e arquivos:

```bash
task_manager/
├── main.py               # Arquivo principal para execução
├── database/
│   └── db_handler.py     # Funções para lidar com o banco de dados
├── models/
│   └── task_model.py     # Modelo de dados para a tarefa
├── controllers/
│   ├── task_controller.py # Controlador de lógica de tarefas
│   └── report_controller.py # Controlador de relatórios
└── data/
    └── tasks.db          # Banco de dados SQLite
```
#### Funcionalidades do Projeto

**Adicionar Tarefas**: O usuário pode adicionar uma nova tarefa com título, descrição e data de conclusão.
**Listar Tarefas**: Exibir todas as tarefas cadastradas.
**Marcar como Concluída**: Permitir ao usuário marcar uma tarefa como concluída.
**Relatório**: Gerar um relatório em CSV de todas as tarefas.
