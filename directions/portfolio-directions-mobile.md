## Linha de Projeto – Aplicações Mobile

## O que é obrigatório atender
- O aplicativo deve estar disponível em ambiente produtivo (por exemplo: APK instalável, publicado no Google Play ou hospedado em plataforma de testes como Firebase App Distribution, TestFlight etc.).
- O projeto deve conter funcionalidades reais, alinhadas ao escopo apresentado no RFC.
- O sistema deve demonstrar arquitetura mobile compatível (MVC, MVVM, Clean Architecture, etc.).
- Código-fonte disponível em repositório com histórico de desenvolvimento.
- Interface funcional e testável no dispositivo, com link acessível por QR code no pôster.
- Documentação básica contendo:
  - Requisitos funcionais.
  - Casos de uso ou user stories.
  - Estrutura de navegação da aplicação.
  - Diagrama de arquitetura.

---

## O que é desejável atender
- Publicação em loja oficial (Google Play / App Store).
- Integração com serviços externos (ex.: APIs REST, Firebase, mapas, notificações push).
- Uso de práticas de versionamento e CI/CD (como GitHub Actions, Codemagic, Bitrise).
- Aplicação de testes automatizados (unitários ou instrumentados).
- Responsividade para diferentes tamanhos de tela e dispositivos.
- Implementação de boas práticas de UX (material design, coerência visual, acessibilidade).
- Dados persistidos localmente ou remotamente (ex.: SQLite, Firebase, Supabase, RealmDB).

---

## O que é um diferencial
- Sistema de autenticação robusto (ex.: login social, biometria).
- Publicação com analytics ou sistema de métricas de uso integrado.
- Interface multilíngue.
- Uso de arquitetura modular ou baseada em micro frontends para apps complexos.
- Realização de testes com usuários reais ou prototipagem validada com feedback.
- Relatório de usabilidade ou acessibilidade.

---

## O que deve ser evitado
- Aplicativos com apenas telas estáticas (mockups).
- Falta de testes básicos que causem crashes.
- Interface mal adaptada a diferentes dispositivos.
- Funcionalidades genéricas sem contexto real (ex.: lista de tarefas sem propósito específico).

---

## O que não pode ter
- Plágio de aplicativos existentes sem alterações significativas.
- Reutilização de templates prontos sem personalização ou compreensão do funcionamento.
- Código sem modularização (tudo em um único arquivo).
- Aplicações não testáveis, que não abrem ou não apresentam nenhuma funcionalidade ativa.
- Violação de diretrizes da plataforma (ex.: uso indevido de permissões, coleta de dados sem consentimento).

---

## Régua de Avaliação
- **Aprovado**: o aplicativo funcional de acordo com os requisitos de software e objetivos da aplicação e, com documentação coerente. A aplicação resolve um problema real com escopo bem definido.  
- **Destaque**: além dos requisitos básicos, o projeto deve estar em uma loja e ter vários usuários ou estar em uso por uma empresa. E apresentar evidência de uso com base em APIs externas como Firebase.  
- **Reprovado**: não apresenta, quebra ou não cumpre os critérios obrigatórios.
