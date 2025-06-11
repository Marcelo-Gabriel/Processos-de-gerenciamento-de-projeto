```mermaid
graph TD
    A[Iniciação] --> B[Planejamento];
    B --> C[Execução];
    C --> D[Monitoramento e Controle];
    D -- (Iterativo) --> C;
    C --> E[Encerramento];
    D --> E;
