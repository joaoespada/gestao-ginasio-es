# Registo de Riscos do Projeto

Registo de riscos identificados para o desenvolvimento do software de Gestão de Ginásio, com inclusão obrigatória de riscos associados ao uso de Ferramentas de IA:

| ID | Risco | Tipo | Prob. | Imp. | Nível | Resposta | Dono |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **R1** | **IA — Alucinação de Bibliotecas:** A IA sugerir dependências ou bibliotecas obsoletas/inexistentes no código gerado. | Tecnológico / IA | Média | Moderado | Médio | **Mitigar:** Validar manualmente e testar todas as dependências antes da integração no repositório. | João Espada |
| **R2** | **IA — Falha em Concorrência:** A IA gerar a funcionalidade de reserva de aulas sem mecanismos de sincronização (*race conditions*), permitindo reservas acima da lotação máxima. | Técnico / IA | Média | Elevado | Alto | **Mitigar:** Escrever casos de teste automatizados de concorrência antes de solicitar o código à IA (*Test-Driven*). | André Oliveira |
| **R3** | **Requisitos Ambíguos:** Definição vaga das regras de negócio associadas ao cancelamento de reservas e penalizações de acesso. | Requisitos | Média | Moderado | Médio | **Mitigar:** Formalizar critérios de aceitação rigorosos e verificáveis em formato *Given-When-Then*. | Diogo Mata |
| **R4** | **Conflitos no Git:** Falhas na sincronização de *commits* entre os 3 elementos do grupo, provocando perda de rastreabilidade ou código sobreposto. | Organizacional | Baixa | Elevado | Médio | **Evitar:** Impor uma estratégia clara de *branches* e *Pull Requests* obrigatórios revistos por outro elemento. | João Espada |
| **R5** | **IA — Fuga de Dados Pessoais:** Introdução acidental de dados pessoais reais de clientes do ginásio em *prompts* submetidos a assistentes de IA. | Segurança / IA | Média | Catastrófico | Alto | **Evitar:** Garantir o uso exclusivo de dados fictícios em todas as interações e ficheiros do projeto. | André Oliveira |
| **R6** | **Ausência de Membro da Equipa:** Impossibilidade temporária de um dos elementos trabalhar durante um dos Sprints. | Gestão | Baixa | Elevado | Médio | **Aceitar:** Manter o código modular e documentado para permitir a redistribuição rápida de casos de uso. | Diogo Mata |
