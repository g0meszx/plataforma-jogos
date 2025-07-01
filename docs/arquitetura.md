# Diagrama da Arquitetura

O sistema segue a arquitetura MVC com as seguintes camadas:

- **Frontend (Vue.js):** Interface do usuário com componentes reutilizáveis.
- **Backend (Laravel):** Responsável pelas regras de negócio e controle de dados.
- **Banco de Dados (MySQL):** Armazena todas as informações persistentes.
- **Integrações Externas:** API de pagamento, serviços de e-mail e autenticação social.

Fluxo básico:
Usuário → Frontend → Backend → Banco de Dados / APIs externas
