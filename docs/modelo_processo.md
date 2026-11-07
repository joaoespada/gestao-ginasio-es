# Escolha do Modelo de Processo

## 1. Modelo Escolhido: Desenvolvimento Iterativo e Incremental

O modelo de processo selecionado para o projeto de Gestão de Ginásio é o **Modelo Iterativo e Incremental** (estruturado com a metodologia ágil Scrum em 2 Sprints curtos).

### Justificação do Contexto do Projeto:

1. **Dimensão e Natureza da Equipa:** A equipa é constituída por 3 alunos a desenvolver um projeto assistido por IA. A IA permite acelerar a produção de código, mas exige ciclos curtos de verificação e refatoração para validar se as funcionalidades cumprem os requisitos de engenharia.
2. **Construção por Incrementos:** O sistema será entregue em partes funcionais. No **Sprint 1**, será desenvolvido o núcleo funcional (registo de membros, associação de planos e controlo simples de check-in). No **Sprint 2**, o sistema será expandido com os incrementos mais complexos (agendamento de aulas de grupo, controlo de lotação em tempo real e listas de espera).
3. **Validação Contínua por Testes:** Cada iteração produz uma versão testada e executável do sistema, permitindo validar os casos de teste antes de avançar para a iteração seguinte.

---

## 2. Comparação com Alternativa: Modelo em Cascata Revisto (com Realimentação)

Como modelo alternativo, analisou-se o **Modelo em Cascata Revisto** (*waterfall with feedback loops*).

### Razões de Rejeição do Modelo em Cascata Revisto:

* **Estrutura Baseada em Fases Sequenciais:** Embora o Modelo em Cascata Revisto introduza flexibilidade documental ao permitir regressar a uma fase anterior (por exemplo, voltar ao design após a deteção de erros nos testes), continua a organizar o trabalho em grandes fases sequenciais (Requisitos $\rightarrow$ Design $\rightarrow$ Implementação $\rightarrow$ Testes).
* **Risco de Ciclo de Retrabalho sem Fim:** O desenvolvimento assistido por IA gera código rapidamente, mas pode introduzir alucinações de bibliotecas ou defeitos de lógica. No Cascata Revisto, a ausência de iterações curtas com *Sprints* e *Backlogs* definidos faz com que as correções constantes entre testes e design possam levar o projeto a um ciclo de retrocessos indeterminado ("ciclo sem fim").
* **Diferimento da Entrega Funcional e Ajuste ao Pedido de Mudança:** No Modelo em Cascata Revisto, uma versão executável e integrada de ponta a ponta só fica disponível nas fases finais de testes de sistema. Pelo contrário, o modelo Iterativo e Incremental garante um incremento estável e funcional logo no final do Sprint 1, preparando o sistema para responder com segurança ao Pedido de Mudança estipulado para a Aula 11.
