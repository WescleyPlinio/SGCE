# SGCE
Sistema de Gerenciamento para Clubes Esportivos

## Análise e projeto do sistema
Documentação oficial do sistema, aqui serão mostradas informações como requisitos funcionais/não-funcionais, diagramas de casos de uso/classes e protótipos de tela.

### Requisitos Funcionais

| ID   | Requisito Funcional        | Descrição |
|------|----------------------------|-----------|
| RF01 | Blog de notícias           | O sistema deve permitir a publicação, edição e exclusão de notícias. |
| RF02 | CRUD de atletas            | O sistema deve possibilitar criar, visualizar, editar e excluir registros de atletas. |
| RF03 | Página individual de atleta | O sistema deve exibir uma página dedicada para cada atleta, com seus dados e histórico. |
| RF04 | CRUD de times              | O sistema deve permitir gerenciar times, divididos por ano e categoria. |
| RF05 | Associação atletas x times | O sistema deve permitir vincular atletas a um time específico. |
| RF06 | História do clube          | O sistema deve disponibilizar uma seção com informações históricas do clube. |
| RF07 | Pagamentos mensais         | O sistema deve permitir registrar, acompanhar e controlar pagamentos mensais dos atletas. |
| RF08 | Autenticação de usuários   | O sistema deve ter login para administradores gerenciarem conteúdos e dados. |
| RF09 | Categorias de notícias     | O sistema deve permitir classificar notícias em categorias (ex.: jogos, eventos, comunicados). |
| RF10 | Busca simples              | O sistema deve permitir buscar atletas e notícias por nome ou palavra-chave. |
| RF11 | Painel administrativo      | O sistema deve exibir um painel de resumo com informações gerais (nº de atletas ativos, pagamentos pendentes, últimas notícias). |

### Requisitos Não Funcionais

| ID   | Requisito Não Funcional     | Descrição |
|------|-----------------------------|-----------|
| RNF01 | Usabilidade               | O sistema deve possuir uma interface simples e intuitiva, acessível a usuários não técnicos. |
| RNF02 | Performance               | O sistema deve responder às ações do usuário em até 2 segundos para operações comuns. |
| RNF03 | Segurança                 | O sistema deve armazenar senhas criptografadas e proteger dados de atletas. |
| RNF04 | Disponibilidade           | O sistema deve estar disponível em 95% do tempo, exceto durante manutenções programadas. |
| RNF05 | Escalabilidade            | O sistema deve permitir futuras expansões (novos módulos, mais usuários). |
| RNF06 | Compatibilidade           | O sistema deve ser acessível via navegadores modernos (Chrome, Firefox, Edge). |
| RNF07 | Portabilidade             | O sistema deve ser responsivo, acessível em computadores, tablets e celulares. |
| RNF08 | Manutenibilidade          | O código deve ser organizado, com separação clara entre frontend, backend e banco de dados. |
| RNF09 | Personalização            | O sistema deve permitir total personalização de identidade visual (cores, logos, estrutura e layout). |