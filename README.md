```mermaid
graph TD
    A[Iniciação do Projeto] --> B{Definir Escopo e Objetivos?};
    B -- Sim --> C[Planejamento do Projeto];
    B -- Não --> D[Rejeitar Projeto/Revisar];
    D --> A;

    C --> E[Execução do Projeto];
    E --> F[Monitoramento e Controle do Projeto];
    F --> G{Desvios/Problemas Identificados?};
    G -- Sim --> H[Ações Corretivas/Preventivas];
    G -- Não --> I{Metas Atendidas?};
    H --> F;

    I -- Sim --> J[Encerramento do Projeto];
    I -- Não --> F;

    J --> K[Lições Aprendidas e Relatórios];
    K --> L[Arquivar Documentação];
