#Direcionamentos para Portfólio. 

A tabela abaixo procura direcionar as decisões dos projetos. 

| Quadrante    | Nome                                                                 | Ação        | Descrição                                                                                              |
|--------------|----------------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------|
| Ferramenta   | Deploy via acesso ssh/ftp                                            | 🚫 Não Usar | Método tradicional de deploy, considerado inseguro e menos eficiente em comparação com práticas modernas de CI/CD. |
| Processo     | Processo em cascata                                                  | 🚫 Não Usar | Modelo tradicional de desenvolvimento de software considerado rígido e menos adaptável às mudanças.    |
| Processo     | eXtreme Go Horse                                                     | 🚫 Não Usar | Metodologia de desenvolvimento não convencional e não recomendada, focada na velocidade em detrimento da qualidade. |
| Stack        | Plataformas de No Code: Bubble.io, Webflow, Carrd, Thunkable, Bravo Studio, HubSpot CMS. (...) | 🚫 Não Usar | Permitem desenvolvimento rápido sem código, mas podem limitar a customização e escalabilidade.        |
| Stack        | Banco em disco: H2, SQLite                                           | 🚫 Não Usar | Soluções leves de armazenamento de dados, úteis para desenvolvimento e testes, mas limitadas para produção. |
| Tema         | Sistema de cardápio online/QRCode                                    | 🚫 Não Usar | Soluções simples para restaurantes, mas com muitas alternativas disponíveis no mercado.                |
| Tema         | Sistema de controle de estoque                                       | 🚫 Não Usar | Soluções simples, mas com muitas alternativas disponíveis no mercado.                |
| Tema         | Sistema de Tele-entrega                                              | 🚫 Não Usar | Serviços de entrega são populares, mas altamente competitivos e regulados.                             |
| Ferramenta   | Notepad++                                                            | ⚠️ Evitar   | Editor de texto leve, popular entre desenvolvedores, mas com limitações para projetos complexos.       |
| Ferramenta   | Documentação: Notion, Obsidian                                       | ⚠️ Evitar   | Ferramentas versáteis para notas e documentação, mas menos integradas ao fluxo de desenvolvimento.     |
| Ferramenta   | Ferramentas de monitoramento de performance e observabilidade - Ex: Zabbix, Prometheus, Grafana |  ✅ Preferir | Opções open-source para monitoramento, com necessidade de configuração e manutenção.                   |
| Processo     | Scrum                                                                | ⚠️ Evitar   | Metodologia ágil popular que, apesar de sua eficácia, pode não ser ideal para todos os projetos. Não indicada para projetos individuais. |
| Stack        | Plataforma otimizada para front-end, principalmente se não desenvolver backend (Vercel, Netlify, Firabase, Render) | ⚠️ Evitar | Soluções específicas para front-end podem limitar o controle sobre o backend e a customização.        |
| Stack        | Linguagem: PHP                                                       | ⚠️ Evitar   | Linguagem amplamente usada para desenvolvimento web, mas que enfrenta críticas quanto a modernidade e segurança. |
| Tema         | Apps Mobile                                                          | ⚠️ Evitar   | O desenvolvimento de apps mobile é crucial, mas pode ser desafiador sem as plataformas e ferramentas adequadas. |
| Tema         | Sistema de gestão de listas de livros, filmes, músicas, etc. (similares a goodread) | ⚠️ Evitar | Projetos como sistemas de gestão de listas são comuns, mas enfrentam alta concorrência e desafios de inovação. |
| Tema         | Sistema de gestão de ecommerce/lojas virtuais | ⚠️ Evitar | Projetos de lojas virtuais são comuns, mas enfrentam alta concorrência e desafios de inovação. |
| Ferramenta   | SonarQube, SonarCloud, CodeClimate                                   | ✅ Preferir  | Ferramentas de análise de código que ajudam a manter a qualidade e segurança do código.               |
| Ferramenta   | Modelagem C4                                                         | ✅ Preferir  | Método de modelagem visual para sistemas de software que promove uma compreensão clara da arquitetura.|
| Ferramenta   | Ferramentas de monitoramento de performance e observabilidade - Ex: Dynatrace, New Relic e Datadog | ✅ Preferir | Essenciais para monitorar, diagnosticar e otimizar aplicações.                                        |
| Ferramenta   | Issues/Tarefas: Trello, GitHub Project, Azure Devops                 | ✅ Preferir  | Ferramentas que facilitam o gerenciamento de projetos e colaboração.                        |
| Processo     | Kanban                                                               | ✅ Preferir  | Sistema visual para gerenciar trabalho conforme ele avança através de processos, promovendo flexibilidade e eficiência. |
| Stack        | Cloud (AWS, Heroku, Azure, Google Cloud, Magalu Cloud, ...)          | ✅ Preferir  | Serviços em nuvem oferecem escalabilidade, desempenho e flexibilidade.                               |
| Stack        | Docker                                                               | ✅ Preferir  | Ferramenta essencial para a criação, deploy e execução de aplicações em containers, promovendo portabilidade e consistência. |
| Stack        | Terraform                                                            | ✅ Preferir  | Ferramenta de infraestrutura como código que automatiza o provisionamento de infraestrutura em vários provedores de nuvem. |
| Stack        | Dados: PostgreSQL, MySQL, Oracle Database e Microsoft SQL Server.    | ✅ Preferir  | Bancos de dados relacionais robustos para aplicações de todos os tamanhos.                           |
| Stack        | Linguagem: Java, C#, Python, C++, Javascript, Typescript             | ✅ Preferir  | Linguagens fundamentais com amplo suporte, comunidades ativas e ecossistemas ricos.                  |
| Tema         | Solução que utilizem apis de LLMs públicas/comerciais                | ✅ Preferir  | Uso de APIs de linguagem de máquina oferece oportunidades para inovação em diversos campos.          |
| Tema         | Sistema de gestão de processos (ERP, Contábil, Comercial, ...)       | ✅ Preferir  | Ferramentas essenciais para a automação e eficiência de processos empresariais.                      |
| Processo         | Aplicar no código-fonte YAGNI, KISS e DRY                            | ✅ Preferir  | https://bit.ly/3WFa96N   |
| Processo         | APlicar SOLID e Clean Code                                           | ✅ Preferir  | SOLID - https://bit.ly/3tbawbD  e Clean Code - https://bit.ly/3E7AaDx |
| Ferramenta   | Documentação em Wiki junto com repositório (Wiki do Github, GitLabs, ...) | 🔑 Obrigatório  | Facilita o acesso e a colaboração na documentação de projetos.                                        |
| Ferramenta   | Deploy via CI/CD (Github Actions, Jenkins, ...)                      | 🔑 Obrigatório  | Automatiza o processo de deploy, melhorando a eficiência e a confiabilidade.                          |
| Processo     | TDD                                                                  | 🔑 Obrigatório  | Prática de escrever testes antes do código, garantindo qualidade e reduzindo bugs.   
| Stack        | Dados: Redis e Memcached                                             | 🔍 Explorar | Sistemas de armazenamento em memória para cache e sessões, essenciais para aplicações de alta performance. |
| Stack        | Dados: InfluxDB e TimescaleDB.                                       | 🔍 Explorar | Bancos de dados de séries temporais, úteis para análise de dados em tempo real.                      |
| Stack        | Dados: Elasticsearch                                                 | 🔍 Explorar | Motor de busca e análise, ideal para pesquisa de texto e análise de grandes volumes de dados. |
| Stack        | Linguagem: Rust, Go, Elixir, Dart                                    | 🔍 Explorar | Linguagens modernas oferecendo segurança, performance e concorrência para diversos tipos de projetos.|
| Tema         | Ferramentas de apoio a Engenharia de Software                        | 🔍 Explorar | Área em crescimento, com potencial para inovação em ferramentas e processos de desenvolvimento.      |
| Tema         | Desenvolvimento de Jogos                                             | 🔍 Explorar | Campo com grande potencial criativo e técnico, mas que requer habilidades especializadas e ferramentas dedicadas. |
| Tema         | Desenvolvimento de ferramentas para IA                               | 🔍 Explorar | Área promissora com demanda crescente por soluções inovadoras em inteligência artificial.            |
