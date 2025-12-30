# Chat-Bot Reserva de Salas V1 🏢🗓️
Este sistema é um chatbot inteligente desenvolvido em CodeIgniter 4 (PHP), focado na automação do processo de agendamento e reserva de salas corporativas.
Este sistema é um chatbot inteligente desenvolvido em CodeIgniter 4 (PHP), focado na automação do processo de agendamento e reserva de salas corporativas.

# 📋 Sobre o Projeto
O Chat-Bot V1 foi criado para simplificar a gestão de espaços físicos, permitindo que usuários consultem disponibilidade e realizem reservas através de uma interface de chat intuitiva, integrada ao ecossistema da empresa.

# 🛠️ Tecnologias e Frameworks
* Backend: CodeIgniter 4 (PHP) - seguindo o padrão MVC.
* Frontend: HTML5, CSS3 (Custom UI) e JavaScript.
* Banco de Dados: MySQL / MariaDB.
* Comunicação: AJAX / JSON para integração com o controller do CI4.

# ✅ Funcionalidades Implementadas (V1)
* Fluxo de Reserva: Diálogo estruturado para escolha de data, horário e sala.
* Integração com Banco de Dados: Registro e consulta de agendamentos em tempo real.
* Validação de Disponibilidade: Sistema que impede reservas duplicadas no mesmo horário.
* Interface Amigável: Layout focado em conversação para facilitar o uso por funcionários.
* Autenticação CI4: Filtros de autenticação para garantir que apenas colaboradores acessem o bot.

# 📂 Estrutura de Pastas (CI4)
* ``app/Controllers``: Lógica de controle do chat e processamento de mensagens.
* ``app/Models``: Gerenciamento das tabelas de ``salas``, ``reservas`` e ``usuarios``.
* ``app/Views``: Interface visual do chat-bot.
* ``public/assets``: Arquivos CSS e JS customizados.

# 🚀 Como instalar
1. Clone o repositório.
2. Configure o arquivo `.env` com as credenciais do seu banco de dados local.
3. Execute as migrations:
```bash
php spark migrate
```
4. Inicie o servidor local:
```Bash
php spark serve
```
