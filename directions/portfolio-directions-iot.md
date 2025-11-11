## Linha de Projeto – Projetos IoT (Internet das Coisas)

### Obrigatório atender
- Apresentar especificações do escopo do projeto contendo:
  - Requisitos da aplicação IoT representados por **Diagrama Hierárquico de Requisitos (SySML)**.
  - **Diagrama de Arquitetura** (C4 Model ou modelo em camadas com: camada de sensores/atuadores, camada de rede, camada de processamento de dados e camada de aplicação).  
- Implementar requisitos em conformidade com a arquitetura definida.  
- Código-fonte disponível em repositório junto com os artefatos de especificação.  
- Incluir a internet como meio de comunicação, mesmo em implementações embarcadas.  
- Garantir interação via web ou mobile como parte da aplicação IoT:
  - Interação direta (configuração/manipulação do dispositivo).
  - Interação indireta (consumo de dados gerados).  

### Desejável atender
- Especificação esquemática de hardware, portas (lógica/digital), conectividade, componentes e restrições (Diagramas de Blocos e Blocos Internos – SySML).  
- Escolha de protocolos de comunicação adequados ao escopo (ex.: MQTT, CoAP, LoRaWAN), evitando uso genérico de HTTP quando houver opções mais eficientes.  

### Diferencial
- Camada de Aplicação utilizando a solução IoT via aplicação web ou mobile.  
- Utilização de dados IoT em camada adicional para análise de dados e dashboards.  
- Integração de modelos de aprendizado de máquina (predição/classificação).  
- Implementação de camada de segurança com ao menos uma prática de cibersegurança (conforme demanda do escopo).  
- Integração com sistemas externos.  

### Deve ser evitado
- Uso de plataformas IoT com camadas prontas que limitem personalização.  
- Simulação de comportamentos apenas com LEDs na falta de componentes, sem demonstrar aplicação real.  

### Não pode ter
- Apenas simulação, sem implementação real dos requisitos.  
- Escopo simplista (ex.: acender lâmpada, ligar ar-condicionado sem contexto avançado).  
- Uso de projetos prontos sem modificações significativas.  
- Apenas implementação embarcada sem conectividade à internet.  

### Régua de Avaliação
- **Aprovado para apresentação**: Atende a todos os itens “Obrigatório atender” + parte dos “Desejável atender”.  
- **Aprovado com Diferencial**: Atende obrigatórios + desejáveis e ao menos um item de “Diferencial”, sem conter itens de “Deve ser evitado”.  
- **Reprovado**: Não atende obrigatórios ou apresenta itens proibidos.
