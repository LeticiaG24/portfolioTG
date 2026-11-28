# Quarto Semestre (2026-2)

O projeto do quarto semestre teve como empresa parceira a PRO4TECH, que atua na área de consultoria em transformação digital e Inteligência Artificial.

O problema apresentado consistia em centralizar e organizar o conhecimento produzido durante projetos de software (decisões, problemas encontrados, soluções adotadas e experiências anteriores), que costuma ficar disperso e deixar de ser aproveitado por Product Owners em novos projetos e backlogs.

Como solução, minha equipe desenvolveu uma aplicação com base de conhecimento e chats com Inteligência Artificial que apoiam o PO na análise e na elaboração de projetos e backlogs, identificando informações relevantes, relações com projetos anteriores, inconsistências e oportunidades de melhoria, sem substituir a decisão do PO.

[GIT](https://github.com/TeamMinerva/PRO4TECH-API)

## Tecnologias Utilizadas

As seguintes tecnologias foram utilizadas nesse projeto:

* Python e FastAPI - Back-end e API da aplicação;
* React e TypeScript - Front-end;
* Tailwind CSS - Estilização das telas;
* PostgreSQL - Banco de dados;
* LightRAG - Recuperação de conhecimento para a IA;
* Ollama - Execução dos modelos de IA;
* Docker - Containerização dos serviços.

## Contribuições Pessoais

Nesse projeto atuei como Product Owner. Mantive contato com o cliente para entender suas necessidades, apresentar o andamento e ajustar as entregas. Participei da definição das funcionalidades considerando os objetivos do projeto e a experiência do usuário (UX), criei e organizei o backlog em épicos, user stories e tarefas, auxiliando na priorização e distribuição das atividades, e elaborei e mantive a documentação (requisitos, funcionalidades e decisões). No desenvolvimento, criei rotas de consulta e cadastro de dados no banco e colaborei na integração dos chats com IA à aplicação, conectando o back-end aos serviços de IA.

## Hard Skills

Exercitei as seguintes hard skills durante esse projeto:

* FastAPI - uso com autonomia
* React / TypeScript - uso com autonomia
* PostgreSQL - uso com ajuda
* Integração com serviços de IA - faço com ajuda

## Soft Skills

**Criatividade e pensamento centrado no usuário:** Durante o desenvolvimento do sistema, busquei compreender as dificuldades enfrentadas pelo cliente para propor funcionalidades que realmente agregassem valor à sua rotina. Um dos problemas relatados era a dificuldade em criar backlogs padronizados. A partir disso, propus uma interface dividida entre o backlog e um chat com inteligência artificial, permitindo que o usuário solicitasse análises e feedbacks sobre o conteúdo enquanto construía o planejamento, além de receber sugestões de desenvolvedores para os PBIs. A proposta foi bem recebida e elogiada pelo cliente, por facilitar o processo e otimizar o trabalho.

**Visão estratégica e resolução de problemas:** Ao compreender que o cliente não pretendia substituir o Azure DevOps, identifiquei um possível problema na utilização simultânea de duas ferramentas: a necessidade de manter informações atualizadas em ambos os sistemas, o que poderia gerar retrabalho e dificultar a manutenção dos backlogs. Antecipando essa dificuldade, propus a implementação de uma funcionalidade de exportação dos backlogs para o Azure DevOps. A ideia foi incorporada ao projeto por meio da integração com a API da plataforma, permitindo que o sistema complementasse a ferramenta já utilizada pelo cliente, em vez de substituí-la.
