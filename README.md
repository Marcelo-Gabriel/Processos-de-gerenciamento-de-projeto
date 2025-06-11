```mermaid
graph TD
    A[Início do Projeto] --> B{Iniciação do Projeto};
    B -- Sim --> C[Definir Escopo e Objetivos];
    B -- Não --> A;
    C --> D[Desenvolver Plano de Projeto];
    D --> E{Executar o Projeto};
    E -- Em Andamento --> F[Monitorar e Controlar];
    F -- Problemas/Mudanças --> G[Gerenciar Mudanças/Riscos];
    G --> E;
    E -- Concluído --> H[Encerrar o Projeto];
    H --> I[Revisão Pós-Projeto];
    I --> J[Fim do Projeto];

    subgraph Iniciação
        B;
        C;
    end

    subgraph Planejamento
        D;
    end

    subgraph Execução e Controle
        E;
        F;
        G;
    end

    subgraph Encerramento
        H;
        I;
        J;
    end
