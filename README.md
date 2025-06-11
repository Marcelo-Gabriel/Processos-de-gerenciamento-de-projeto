# Meu Fluxograma de Gerenciamento de Projetos

Este é um exemplo de fluxograma de gerenciamento de projetos usando Mermaid.

```mermaid
graph TD
    A[Início do Projeto] --> B{Iniciação};

    B --> B1[Identificar Stakeholders];
    B --> B2[Definir Objetivo e Escopo Preliminar];
    B --> B3[Criar Termo de Abertura do Projeto (TAP)];
    B --> B4[Aprovação do TAP];
    B3 -- "Rejeitado" --> B2;
    B4 -- "Não Aprovado" --> B3;

    B --> C{Planejamento};
    C --> C1[Detalhamento do Escopo];
    C --> C2[Estrutura Analítica do Projeto (EAP)];
    C --> C3[Cronograma do Projeto];
    C --> C4[Orçamento do Projeto];
    C --> C5[Plano de Gerenciamento de Riscos];
    C --> C6[Plano de Aquisições];
    C --> C7[Plano de Comunicação];
    C --> C8[Plano de Qualidade];
    C --> C9[Plano de Gerenciamento de Recursos];
    C --> C10[Plano de Gerenciamento de Partes Interessadas];
    C1 --> C2; C2 --> C3; C3 --> C4; C4 --> C5; C5 --> C6; C6 --> C7; C7 --> C8; C8 --> C9; C9 --> C10;
    C10 --> C11[Plano de Gerenciamento do Projeto (Integrado)];
    C11 --> D{Execução};

    D --> D1[Mobilizar Equipe e Recursos];
    D --> D2[Realizar Atividades do Projeto];
    D --> D3[Gerenciar Comunicações];
    D --> D4[Gerenciar Engajamento das Partes Interessadas];
    D --> D5[Realizar Aquisições];
    D --> D6[Desenvolver Entregas];

    D --> E{Monitoramento e Controle};
    E --> E1[Monitorar e Controlar o Trabalho do Projeto];
    E --> E2[Controlar o Escopo];
    E --> E3[Controlar o Cronograma];
    E --> E4[Controlar os Custos];
    E --> E5[Realizar Controle de Qualidade];
    E --> E6[Gerenciar Riscos];
    E --> E7[Gerenciar Aquisições];
    E --> E8[Gerenciar Comunicações];
    E --> E9[Gerenciar Partes Interessadas];
    E1 -- "Identificar Desvios" --> E2; E2 --> E3; E3 --> E4; E4 --> E5; E5 --> E6; E6 --> E7; E7 --> E8; E8 --> E9;
    E9 --> E10[Análise e Ações Corretivas/Preventivas];
    E10 --> D2;

    E --> F{Encerramento};
    F --> F1[Obter Aceitação Formal das Entregas];
    F --> F2[Encerrar Contratos];
    F --> F3[Liberar Recursos];
    F --> F4[Análise Pós-Projeto (Lições Aprendidas)];
    F --> F5[Arquivo de Documentos do Projeto];
    F5 --> G[Fim do Projeto];
