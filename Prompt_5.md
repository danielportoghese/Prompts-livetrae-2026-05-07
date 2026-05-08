Aja como um Technical Product Architect e Staff Software Engineer especializado em arquitetura evolutiva, Domain-Driven Design, planejamento incremental de plataformas escaláveis e preparação de sistemas para agentes autônomos de IA. 
 
 Com base em toda a arquitetura, domínio, fluxos, regras, diagramas e documentação previamente definidos, sua tarefa agora é criar um plano para gerar a fonte oficial de evolução do projeto através do arquivo: 
 
 /docs/TODO.md 
 
 Este arquivo NÃO deve ser apenas uma lista de tarefas. 
 
 Ele deve funcionar como: 
 
 backlog arquitetural, 
 roadmap operacional, 
 plano evolutivo do produto, 
 referência para engenharia, 
 contexto consumível por agentes de IA, 
 mapa oficial de evolução incremental do sistema. 
 
 O documento deve ser altamente estruturado, versionável e orientado por domínio. 
 
 Estrutura obrigatória do TODO.md 
 
 O documento deve ser dividido em 3 grandes fases: 
 
 Fase 1 — MVP 
 
 Objetivo: 
 Validar rapidamente o produto com o menor conjunto funcional possível mantendo qualidade arquitetural. 
 
 Inclua: 
 
 autenticação, 
 cadastro de usuários, 
 restaurantes, 
 catálogo, 
 carrinho, 
 criação de pedidos, 
 pagamento básico, 
 rastreamento simplificado, 
 painel administrativo mínimo, 
 observabilidade básica, 
 deploy inicial, 
 testes críticos, 
 documentação mínima operacional. 
 Fase 2 — Sistema Completo 
 
 Objetivo: 
 Transformar o MVP em uma plataforma robusta, escalável e operacionalmente madura. 
 
 Inclua: 
 
 arquitetura orientada a eventos, 
 filas, 
 notificações avançadas, 
 rastreamento em tempo real, 
 geolocalização, 
 analytics, 
 antifraude, 
 auditoria, 
 RBAC avançado, 
 observabilidade distribuída, 
 automações operacionais, 
 performance, 
 escalabilidade, 
 hardening de segurança, 
 testes avançados, 
 resiliência, 
 automações internas. 
 Fase 3 — Roadmap Futuro 
 
 Objetivo: 
 Definir a visão estratégica de longo prazo da plataforma. 
 
 Inclua: 
 
 IA aplicada ao delivery, 
 previsão de demanda, 
 roteamento inteligente, 
 recomendação personalizada, 
 gamificação, 
 marketplace, 
 multi-tenant, 
 microsserviços, 
 event sourcing, 
 agentes autônomos, 
 AI Operators, 
 automações inteligentes, 
 arquitetura auto-observável, 
 validação arquitetural automatizada, 
 self-healing workflows, 
 internacionalização, 
 aplicativos mobile. 
 Organização obrigatória por domínio 
 
 Dentro de cada fase, organize as tarefas por domínio/contexto arquitetural. 
 
 Exemplos: 
 
 Core Ordering 
 Payments 
 Delivery Tracking 
 Notifications 
 Identity & Access 
 Admin Operations 
 Security 
 Observability 
 Platform Engineering 
 AI Readiness 
 Categorias obrigatórias 
 
 Cada domínio deve separar tarefas por categoria: 
 
 Features 
 Arquitetura 
 Infraestrutura 
 Segurança 
 Observabilidade 
 Developer Experience 
 AI Readiness 
 Technical Debt 
 Testing 
 Estrutura obrigatória de cada tarefa 
 
 Cada item do TODO.md DEVE conter: 
 
 Nome da tarefa 
 Objetivo 
 Descrição técnica 
 Impacto arquitetural 
 
 Explique: 
 
 módulos afetados, 
 contratos afetados, 
 diagramas impactados, 
 impacto em tipagem, 
 impacto em eventos, 
 impacto em fluxos. 
 Dependências 
 
 Liste: 
 
 pré-requisitos, 
 blockers, 
 dependências técnicas, 
 dependências operacionais. 
 Complexidade 
 
 Classifique: 
 
 baixa, 
 média, 
 alta. 
 Prioridade 
 
 Classifique: 
 
 crítica, 
 alta, 
 média, 
 baixa. 
 Riscos envolvidos 
 Critérios de conclusão (Definition of Done) 
 
 Inclua: 
 
 requisitos técnicos, 
 requisitos arquiteturais, 
 atualização de diagramas, 
 atualização de contratos, 
 atualização de documentação, 
 cobertura de testes, 
 validação de segurança. 
 AI Readiness (OBRIGATÓRIO) 
 
 O TODO.md deve conter tarefas explícitas para manter o sistema preparado para agentes de IA. 
 
 Inclua tarefas relacionadas a: 
 
 sincronização de diagramas Mermaid, 
 manutenção da fonte da verdade arquitetural, 
 consistência de contratos, 
 rastreabilidade de mudanças, 
 documentação viva, 
 versionamento arquitetural, 
 validação automática de arquitetura, 
 atualização de contexto para agentes, 
 integridade de domínio, 
 prevenção de divergência arquitetural. 
 IMPORTANTE 
 
 O documento deve parecer um roadmap real utilizado por uma equipe sênior de engenharia AI-Native. 
 
 Você DEVE: 
 
 estruturar tudo em Markdown, 
 utilizar checklists organizadas, 
 manter clareza extrema, 
 demonstrar evolução incremental do sistema, 
 pensar em longo prazo, 
 manter coerência com toda a arquitetura anterior, 
 escrever de forma operacional e técnica, 
 pensar como um arquiteto responsável pela evolução sustentável do produto. 
 
 Pense passo a passo antes de responder. 
 
 Use a skill:  `invoke_command:/writing-plans`
