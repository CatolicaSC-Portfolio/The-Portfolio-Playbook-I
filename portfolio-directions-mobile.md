## Linha de Projeto – Aplicações Mobile

### Obrigatório atender
- Aplicativo disponível em ambiente produtivo (ex.: APK instalável, publicado no Google Play ou hospedado em plataforma de testes como Firebase App Distribution, TestFlight etc.).
- Funcionalidades reais, alinhadas ao escopo apresentado no RFC.
- Arquitetura mobile compatível (ex.: MVC, MVVM, Clean Architecture).
- Código-fonte disponível em repositório com histórico de desenvolvimento.
- Interface funcional e testável no dispositivo, com link acessível por QR code no pôster.
- Documentação básica contendo:
  - Requisitos funcionais.
  - Casos de uso ou user stories.
  - Estrutura de navegação da aplicação.
  - Diagrama de arquitetura.

### Desejável atender
- Publicação em loja oficial (Google Play / App Store).
- Integração com serviços externos (ex.: APIs REST, Firebase, mapas, notificações push).
- Uso de práticas de versionamento e CI/CD (ex.: GitHub Actions, Codemagic, Bitrise).
- Aplicação de testes automatizados (unitários ou instrumentados).
- Responsividade para diferentes tamanhos de tela e dispositivos.
- Implementação de boas práticas de UX (Material Design, coerência visual, acessibilidade).
- Dados persistidos localmente ou remotamente (ex.: SQLite, Firebase, Supabase, RealmDB).

### Diferencial
- Sistema de autenticação robusto (ex.: login social, biometria).
- Publicação com analytics ou sistema de métricas de uso integrado.
- Interface multilíngue.
- Uso de arquitetura modular ou baseada em micro frontends para apps complexos.
- Testes com usuários reais ou prototipagem validada com feedback.
- Relatório de usabilidade ou acessibilidade.

### Deve ser evitado
- Aplicativos com apenas telas estáticas (mockups).
- Falta de testes básicos que causem crashes.
- Interface mal adaptada a diferentes dispositivos.
- Funcionalidades genéricas sem contexto real (ex.: lista de tarefas sem propósito específico).

### Não pode ter
- Plágio de aplicativos existentes sem alterações significativas.
- Reutilização de templates prontos sem personalização ou compreensão do funcionamento.
- Código sem modularização (tudo em um único arquivo).
- Aplicações não testáveis, que não abrem ou não apresentam nenhuma funcionalidade ativa.
- Violação de diretrizes da plataforma (ex.: uso indevido de permissões, coleta de dados sem consentimento).

### 📏 Régua de Avaliação
- **Aprovado**: Aplicativo funcional, de acordo com os requisitos de software e objetivos da aplicação, com documentação coerente. Resolve um problema real com escopo bem definido.
- **Destaque**: Além dos requisitos básicos, está publicado em loja oficial e possui múltiplos usuários ou uso comprovado por empresa, com evidência de uso baseada em APIs externas como Firebase.
- **Reprovado**: Não apresenta, quebra ou não cumpre os critérios obrigatórios.
