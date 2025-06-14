```mermaid
graph TD
    A[Início] --> B{Iniciação do Projeto};
    B --> C{Definição do Escopo e Objetivos?};
    C -- Sim --> D[Planejamento do Projeto];
    C -- Não --> B;
    D --> E{Criação do Cronograma e Orçamento?};
    E -- Sim --> F[Execução do Projeto];
    E -- Não --> D;
    F --> G{Monitoramento e Controle do Projeto};
    G --> H{Problemas ou Desvios?};
    H -- Sim --> I[Ações Corretivas];
    I --> G;
    H -- Não --> J{Fase Concluída?};
    J -- Sim --> K[Encerramento do Projeto];
    J -- Não --> F;
    K --> L[Fim];
