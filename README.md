# educonnect
Criar um sistema gamificado de incentivo à participação e frequência dos alunos, onde eles podem ganhar estalecas (pontos) baseadas em sua presença, participação em atividades e eventos da escola. As estalecas podem ser trocadas por prêmios mensais.


📌 Funcionalidades Principais:


🎓 Para os Alunos:


✅ Perfis individuais (exibidos em telas no pátio/escola ou acessíveis na web).

✅ Acúmulo de estalecas baseadas na frequência, participação em eventos e desempenho.

✅ Visualização de ranking de alunos mais engajados.

✅ Possibilidade de trocar estalecas por recompensas.


👩‍🏫 Para os Professores e Administradores:


✅ Atribuir estalecas para alunos por presença e atividades.

✅ Gerenciar os prêmios disponíveis e o catálogo de trocas.

✅ Relatórios sobre engajamento e participação.


🏗 Arquitetura do Sistema:


1️⃣ Backend (Flask + MySQL)

API RESTful com Flask para gerenciar alunos, estalecas e premiações.
Banco de dados MySQL para armazenar usuários, pontos e prêmios.
Autenticação de usuários (professores e administradores).
Roteamento para exibição de perfis e rankings.

2️⃣ Frontend (HTML, CSS, JavaScript)

Interface simples para exibição dos perfis e ranking de alunos.
Painel para professores distribuírem pontos.
Tela de troca de estalecas por prêmios.
Dashboard administrativo.

3️⃣ Exibição nas Telas da Escola

Página pública mostrando o ranking dos alunos mais engajados.
Exibição dos perfis individuais com as estalecas acumuladas.

🚀 Próximos Passos

Criar o painel administrativo para atribuir pontos e gerenciar prêmios.
Criar a página de trocas de estalecas.
Melhorar o design com CSS e interatividade com JavaScript.
Implementar autenticação de professores e alunos.
Publicar o sistema na web (usando Heroku ou Railway).
