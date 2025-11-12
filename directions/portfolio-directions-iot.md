# Linha de Projeto – Projetos IoT (Internet das Coisas)

## O que é obrigatório atender
Requisitos mínimos e obrigatórios para habilitação ao Poster + Demo Day.

- Além dos descritivos exigidos no RFC, é obrigatório apresentar especificações do escopo do projeto contendo:
  - Requisitos da aplicação IoT, que podem ser representados por **Diagrama Hierárquico de Requisitos (SySML)** e **Diagrama de Arquitetura** (C4 Model ou modelo em camadas contendo: camada de sensores/atuadores, camada de rede, camada de processamento de dados e camada de aplicação).  
  - Tais diagramas devem ser descritos e fundamentados.
- Implementação dos requisitos em consonância com a arquitetura aplicada ao domínio do problema abordado.
- Código-fonte no repositório do projeto, assim como os artefatos de especificação.
- Não restringir a implementação embarcada: é necessário incluir a **internet** como meio de comunicação.
- Mesmo que simplificada, é fundamental a **interação via web/mobile** (camada de aplicação) como parte da aplicação IoT, seja:
  - Interação direta (ex.: manipular configuração de dispositivo);
  - Interação indireta (ex.: consumo de dados oriundos da aplicação IoT).  

---

## O que é desejável atender
Melhora a qualidade do projeto. Fortemente recomendado, mas não elimina se ausente.

- Especificação esquemática de hardware, portas (lógica/digital), conectividade, componentes e restrições (**Diagramas de Blocos e Blocos Internos, SySML**).
- Escolha de protocolos de comunicação aderentes ao escopo do projeto.  
  - Por exemplo, ao invés de utilizar o protocolo HTTP como padrão, identificar outro que melhor satisfaça os requisitos da aplicação.

---

## O que é um diferencial
Características que elevam o nível do projeto e podem gerar destaque e convites.

- Camada de Aplicação contendo a utilização da aplicação IoT via aplicação Web ou Mobile.
- Utilização de dados oriundos da aplicação IoT em uma camada adicional contendo análise de dados e dashboards ou algum modelo de aprendizagem de máquina (predição/classificação).
- Camada de segurança com a implementação de ao menos uma prática de cibersegurança (conforme demanda do escopo do projeto).
- Integração com sistema externo à aplicação IoT.

---

## O que deve ser evitado
Más práticas que reduzem a percepção de qualidade, mesmo em projetos funcionais.

- Plataformas IoT com camadas prontas para utilização.
- Representar/simular comportamentos via utilização de LEDs, quando da falta de componentes.

---

## O que não pode ter
Erros graves que causam desclassificação ou reprovação direta.

- Apenas a simulação dos requisitos em detrimento da implementação.
- Aplicações IoT com escopo simplista, por exemplo: acender uma lâmpada, ligar um ar-condicionado, entre outros dessa natureza.
- Utilizar escopo de projetos prontos.
- Apenas a implementação embarcada.

---

## Régua de Avaliação
Define os níveis de qualidade do projeto, critérios de aprovação e acesso aos eventos de destaque.

- **Aprovado para apresentação**: Banner, projeto com escopo contendo os requisitos mínimos e obrigatórios  
  = Itens *“obrigatório atender”* (têm que ter) + *“desejável atender”*.
- **Aprovado com Diferencial**: Banner, convite para Banca Técnica/Seminário e Artigo, projeto que contempla os itens *“obrigatório atender”* + *“desejável atender”* e ao menos **+1** dos itens *“é um diferencial”*, **e** não pode ter *“deve ser evitado”*.
- Caso contrário, o projeto **não será aprovado**.
