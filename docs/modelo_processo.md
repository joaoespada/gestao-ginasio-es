# Escolha do Modelo de Processo

## 1. Modelo Escolhido: Desenvolvimento Iterativo e Incremental

O modelo de processo selecionado para o projeto de Gestão de Ginásio é o **Modelo Iterativo e Incremental** (estruturado com a metodologia ágil Scrum em 2 Sprints curtos).

### Justificação do Contexto do Projeto:

1. **Dimensão e Natureza da Equipa:** A equipa é constituída por 3 alunos a desenvolver um projeto assistido por IA. A IA permite acelerar a produção de código, mas exige ciclos curtos de verificação e refatoração para validar se as funcionalidades cumprem os requisitos de engenharia.
2. *Construção por Incrementos e Organização em Sprints:* O sistema será entregue em partes funcionais ao longo dos dois Sprints definidos para a fase de construção (Sprint 1 de 4 a 13/14 de janeiro; Sprint 2 até 25 de janeiro). Esta divisão permite implementar e validar primeiro o núcleo de gestão administrativa do ginásio (membros e planos com limites), deixando para o segundo incremento as regras de negócio de maior risco e concorrência (inscrições em aulas, controlo de lotação e listas de espera), bem como a adaptação ao pedido de mudança da aula 11. As revisões frequentes entre os 3 elementos da equipa ao longo de cada Sprint garantem que o código gerado pela IA é testado e ajustado antes de cada entrega.
3. **Validação Contínua por Testes:** Cada iteração produz uma versão testada e executável do sistema, permitindo validar os casos de teste antes de avançar para a iteração seguinte.

---

## 2. Comparação com Alternativa: Modelo em Cascata Revisto (com Realimentação)

Como modelo alternativo, analisou-se o **Modelo em Cascata Revisto** (*waterfall with feedback loops*).

### Razões de Rejeição do Modelo em Cascata Revisto:

* **Estrutura Baseada em Fases Sequenciais:** Embora o Modelo em Cascata Revisto introduza flexibilidade documental ao permitir regressar a uma fase anterior (por exemplo, voltar ao design após a deteção de erros nos testes), continua a organizar o trabalho em grandes fases sequenciais (Requisitos $\rightarrow$ Design $\rightarrow$ Implementação $\rightarrow$ Testes).
* **Risco de Ciclo de Retrabalho sem Fim:** O desenvolvimento assistido por IA gera código rapidamente, mas pode introduzir alucinações de bibliotecas ou defeitos de lógica. No Cascata Revisto, a ausência de iterações curtas com *Sprints* e *Backlogs* definidos faz com que as correções constantes entre testes e design possam levar o projeto a um ciclo de retrocessos indeterminado ("ciclo sem fim").
* **Diferimento da Entrega Funcional e Ajuste ao Pedido de Mudança:** No Modelo em Cascata Revisto, uma versão executável e integrada de ponta a ponta só fica disponível nas fases finais de testes de sistema. Pelo contrário, o modelo Iterativo e Incremental garante um incremento estável e funcional logo no final do Sprint 1, preparando o sistema para responder com segurança ao Pedido de Mudança estipulado para a Aula 11.
