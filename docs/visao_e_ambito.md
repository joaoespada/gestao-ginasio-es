# Visão do Sistema e Âmbito — Gestão de Ginásio

## 1. Problema de Negócio
A gestão operacional de um ginásio envolve o controlo de acessos dos membros, a validação de planos de adesão e a gestão da lotação de aulas de grupo. A ausência de um sistema integrado origina:
* Picos de afluência imprevisíveis sem controlo de lotação em tempo real.
* Sobrelotação de aulas de grupo por falta de controlo de capacidade máxima e ausência de listas de espera automáticas.
* Dificuldade no controlo de acessos por incumprimento dos horários ou mensalidades associadas aos planos subscritos.

O **Sistema de Gestão de Ginásio** visa automatizar estes processos, garantindo transparência no acesso, controlo estrito de lotação e facilidade no agendamento de aulas.

---

## 2. Perfis de Utilizador
* **Membro / Cliente:** Utilizador final que consulta a disponibilidade de aulas, efetua reservas, entra em listas de espera e consulta o seu histórico de acessos.
* **Rececionista / Staff:** Responsável por registar novos membros, atribuir planos de adesão, processar o check-in presencial e gerir pagamentos locais.
* **Personal Trainer (PT) / Instrutor:** Define o mapa de aulas de grupo, estabelece a lotação máxima das salas e acompanha a lista de inscritos.
* **Gestor do Ginásio:** Administrador do sistema responsável por configurar tipologias de planos, definir regras de negócio e monitorizar a afluência ao espaço em tempo real.

---

## 3. Âmbito do Produto (Fora do Âmbito)
Para garantir a exequibilidade do projeto no âmbito da UC de Engenharia de Software, ficam formalmente excluídas as seguintes funcionalidades:
1. **Integração física com torniquetes/catracas:** O controlo de acesso físico será simulado via software através da validação do ID do membro.
2. **Processamento real de pagamentos bancários:** Não haverá integração com *gateways* financeiros reais (ex: MB WAY, SEPA ou Stripe), sendo as transações simuladas por estados de pagamento.
3. **Gestão de inventário e bar:** Venda de produtos alimentares, suplementação ou equipamento desportivo.
4. **Aplicação móvel nativa:** O sistema será desenvolvido exclusivamente como aplicação web responsiva.
