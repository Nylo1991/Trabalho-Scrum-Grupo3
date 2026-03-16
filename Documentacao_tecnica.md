# Documentação Tecnica Scrum

SENAI AFONSO GRECO 

CURSO TÉCNICO EM DESENVOLVIMENTO DE SISTEMAS






NOME: Danilo Silva Santos,
Otávio Henrique Barbosa Soares

PROFESSOR: Frederico Martins Aguiar


ANÁLISE TÉCNICA: METODOLOGIA SCRUM E SUA APLICABILIDADE NO DESENVOLVIMENTO DE SOFTWARE






NOVA LIMA - MG 2026
Danilo Silva Santos,
Otávio Henrique Barbosa Soares







ANÁLISE TÉCNICA: METODOLOGIA SCRUM E SUA APLICABILIDADE NO DESENVOLVIMENTO DE SOFTWARE




Trabalho técnico e acadêmico apresentado ao Curso Técnico em Desenvolvimento de Sistemas do SENAI, como requisito parcial para avaliação. 
Professor: Frederico Martins Aguiar



NOVA LIMA - MG 2026


1. INTRODUÇÃO À METODOLOGIA
No cenário contemporâneo da engenharia de software, a adaptabilidade e o tempo de resposta às demandas do mercado (Time-to-Market) são métricas críticas de sucesso. Tradicionalmente, o desenvolvimento de sistemas era regido por modelos preditivos e sequenciais, como o modelo em Cascata (Waterfall). Tais modelos baseiam-se na premissa de que todos os requisitos do sistema podem ser mapeados exaustivamente na fase inicial do projeto. Contudo, a alta volatilidade dos negócios demonstrou que essa abordagem engessada frequentemente resulta em softwares obsoletos no momento da entrega e em baixo Retorno sobre o Investimento (ROI).
Como resposta a essas limitações, consolidaram-se as metodologias ágeis, impulsionadas pelo Manifesto Ágil de 2001. Dentro desse ecossistema, o Scrum emergiu como o framework (estrutura de trabalho) mais adotado mundialmente. Criado por Ken Schwaber e Jeff Sutherland, o Scrum não é um processo prescritivo ou uma técnica rígida, mas sim um framework leve, iterativo e incremental. Seu propósito central é auxiliar equipes e organizações a gerar valor de forma adaptativa para problemas complexos. O Scrum rompe com o modelo de comando e controle, instituindo uma cultura de autogerenciamento, onde a equipe técnica tem autonomia para decidir a melhor forma de transformar requisitos em um software funcional.

2. CARACTERÍSTICAS E TIPOS DE PROJETOS
   
2.1 Fundamentos e Características Principais
   A principal característica que difere o Scrum dos métodos tradicionais é a sua base no Empirismo e no pensamento enxuto. O empirismo afirma que o conhecimento vem da experiência. Em vez de criar planos teóricos de longo prazo, a equipe inspeciona o software real constantemente. Esse controle empírico é sustentado por três pilares:
   Transparência: O processo emergente e o trabalho devem ser visíveis, com um vocabulário comum compartilhado por todos os envolvidos.
   
   Inspeção: Os artefatos e o progresso do projeto devem ser inspecionados com frequência para detectar desvios indesejados na qualidade do código ou no escopo.
   
   Adaptação: Se um problema é detectado, o processo ou o produto deve ser ajustado o mais rápido possível para minimizar desvios.

A arquitetura do framework funciona através da sinergia entre Papéis, Eventos e Artefatos:

Papéis (Accountabilities): * Product Owner (PO): Representante do cliente e do negócio. É o único responsável por gerenciar o Product Backlog e garantir que a equipe técnica está desenvolvendo as funcionalidades de maior valor financeiro e estratégico.

Scrum Master: Atua como um líder-servidor. Não é um gerente de projetos tradicional, mas um facilitador que remove impedimentos técnicos ou organizacionais e garante que a equipe siga os valores do Scrum.

Developers: Equipe técnica (programadores, designers, testadores) multifuncional e autogerenciável, responsável por estimar o esforço e criar o incremento de software.

Eventos (Timeboxes): Todo o trabalho ocorre dentro de Sprints, ciclos de duração fixa (1 a 4 semanas). Os eventos protegem a equipe de interrupções e incluem o Planejamento (Sprint Planning), o alinhamento diário (Daily Scrum), a revisão do software com o cliente (Sprint Review) e a análise de processos da própria equipe (Sprint Retrospective).

Artefatos: O Product Backlog (lista viva de requisitos), o Sprint Backlog (plano tático da Sprint atual) e o Incremento (a soma de todos os itens concluídos). Para garantir a qualidade técnica, cada Incremento deve atender rigorosamente à Definição de Pronto (Definition of Done - DoD), um padrão de qualidade (como passar em testes automatizados) acordado pela equipe.

2.2 Tipos de Projetos Adequados

A literatura de gestão de projetos (como o framework Cynefin) classifica problemas em diferentes domínios. O Scrum é projetado especificamente para o domínio complexo. Projetos adequados incluem:

Desenvolvimento de produtos inovadores (como novos aplicativos móveis e plataformas SaaS).

Criação de Startups e desenvolvimento de Produtos Mínimos Viáveis (MVPs).

Projetos onde os requisitos de software sofrem mutações contínuas devido à concorrência ou mudanças na legislação.

Migração ou refatoração de sistemas legados de grande porte, permitindo entregas modulares.

Em contrapartida, o Scrum é desaconselhado para projetos de domínio simples ou complicado/previsível (como manutenções corriqueiras de infraestrutura ou replicação de um software padrão sem customizações), onde a sobrecarga administrativa de cerimônias ágeis não justificaria o ganho de flexibilidade.



3. FERRAMENTAS UTILIZADAS
   
A execução do Scrum exige alta transparência, o que é viabilizado por ferramentas de Gestão de Ciclo de Vida de Aplicações (Application Lifecycle Management - ALM). Estas ferramentas digitalizam os quadros Kanban e centralizam a comunicação, sendo indispensáveis para o desenvolvimento de sistemas moderno:

Jira Software (Atlassian): A ferramenta mais robusta e utilizada pelo mercado corporativo. Permite a gestão épica de requisitos, rastreamento de bugs e fornece relatórios essenciais para a inspeção ágil, como o Burndown Chart (que mede o esforço restante) e o gráfico de Velocity (que mede a capacidade de entrega da equipe).

Azure DevOps (Microsoft): Extensamente utilizado em arquiteturas complexas. Seu diferencial é o módulo Azure Boards, que integra nativamente o planejamento das Sprints com repositórios Git e esteiras de CI/CD (Integração e Entrega Contínuas), automatizando testes e implantações sempre que a equipe finaliza uma tarefa.

Trello e Asana: Ferramentas mais leves, focadas puramente na gestão visual via quadros Kanban. São altamente eficazes para equipes juniores, projetos acadêmicos ou startups em estágio inicial que buscam agilidade sem a complexidade de configuração do Jira.

Confluence / Notion: Ferramentas de wiki corporativa. São essenciais para documentar regras de negócio complexas, arquitetura de banco de dados e APIs, complementando o princípio ágil de que a documentação deve ser útil e colaborativa.
