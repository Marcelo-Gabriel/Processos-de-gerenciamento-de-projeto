```mermaid
graph TD
    A[Início do Projeto] --> B{Iniciação};

    B --> C[Definir Escopo do Projeto e Objetivos];
    C --> D[Identificar Stakeholders];
    D --> E[Desenvolver Termo de Abertura do Projeto (TAP)];
    E --> F[Obter Aprovação do TAP];

    F -- Aprovação Negada --> B;
    F -- Aprovação Concedida --> G{Planejamento};

    G --> H[Criar Plano de Gerenciamento do Projeto];
    H --> I[Definir Cronograma e Marcos];
    I --> J[Estimar Orçamento e Recursos];
    J --> K[Identificar e Analisar Riscos];
    K --> L[Planejar Comunicação e Qualidade];
    L --> M[Planejar Aquisições (se necessário)];
    M --> N[Obter Aprovação do Plano];

    N -- Aprovação Negada --> G;
    N -- Aprovação Concedida --> O{Execução};

    O --> P[Realizar o Trabalho do Projeto];
    P --> Q[Gerenciar Equipe do Projeto];
    Q --> R[Gerenciar Comunicações];
    R --> S[Gerenciar Stakeholders];
    S --> T[Gerenciar Aquisições (se necessário)];
    T --> U[Implementar Plano de Qualidade];

    U --> V{Monitoramento e Controle};

    V --> W[Monitorar e Controlar o Trabalho do Projeto];
    W --> X[Controlar Mudanças];
    X --> Y[Monitorar e Controlar Riscos];
    Y --> Z[Controlar Custos];
    Z --> AA[Controlar Cronograma];
    AA --> BB[Realizar Auditorias de Qualidade];
    BB --> CC[Gerenciar Aquisições (se necessário)];

    CC --> DD{Fechamento};

    DD --> EE[Encerrar Contratos/Aquisições];
    EE --> FF[Obter Aceitação Formal do Cliente];
    FF --> GG[Documentar Lições Aprendidas];
    GG --> HH[Arquivar Documentos do Projeto];
    HH --> II[Liberar Recursos da Equipe];
    II --> JJ[Fim do Projeto];
