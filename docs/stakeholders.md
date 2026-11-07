# Análise de Stakeholders

## 1. Identificação e Classificação dos Stakeholders
Identificação dos intervenientes chave no desenvolvimento e operação do sistema de gestão de ginásio:

| Stakeholder | Posição | Influência | Interesse | Função |
| :--- | :--- | :--- | :--- | :--- |
| **Gestor do Ginásio (Sr. Carlos)** | Interno | Alta | Direto | Negócio / Gestão |
| **Membro / Cliente (Ana Sousa)** | Interno | Média | Direto | Operacional / Utilizador |
| **Rececionista (Pedro Santos)** | Interno | Média | Direto | Operacional |
| **Personal Trainer (Sara Martins)** | Interno | Média | Direto | Técnica / Instrução |
| **Docente da UC (Prof. André Xavier)** | Externo | Alta | Indireto | Avaliação / Conformidade |
| **Equipa de Engenharia (Grupo 3)** | Interno | Alta | Direto | Técnica / Desenvolvimento |

---

## 2. Matriz Poder-Interesse
Alocação dos stakeholders segundo a sua capacidade de influenciar o projeto e o seu nível de interesse:

* **Poder Alto / Interesse Alto (Gerir de Perto):** Gestor do Ginásio e Equipa de Engenharia.
* **Poder Baixo / Interesse Alto (Manter Informado):** Membros/Clientes, Rececionistas e Personal Trainers.
* **Poder Alto / Interesse Baixo (Manter Satisfeito):** Docente da UC (garantir conformidade com os requisitos de ES e prazos de entrega).
* **Poder Baixo / Interesse Baixo (Monitorizar):** Provedores de infraestrutura/alojamento *cloud*.

---

## 3. Estratégia de Comunicação
Plano de envolvimento e partilha de informação com os stakeholders:

| Stakeholder | Canal de Comunicação | Frequência | Linguagem |
| :--- | :--- | :--- | :--- |
| **Gestor do Ginásio** | Reuniões de alinhamento / Demonstração | Quinzenal | Negócio / Operacional |
| **Membros e Staff** | Testes de usabilidade / Inquéritos | Por Sprint | Operacional / Simples |
| **Docente da UC** | Repositório GitHub / Checkpoint oral / Por e-mail | Por Entrega / Semanal | Técnica / Académica |
| **Equipa de Engenharia** | GitHub Issues / Commits / Standups | Diária | Técnica |

---

## 4. Conflito Previsível entre Stakeholders
* **Conflito Identificado:** **Membros vs. Gestor do Ginásio**
* **Descrição:** Os **Membros** pretendem efetuar reservas de aulas de grupo com várias semanas de antecedência para assegurar lugar na sua rotina. Contudo, o **Gestor do Ginásio** prefere limitar a janela de reserva a 48 horas antes da aula para minimizar a taxa de *no-shows* (ausências sem cancelamento) e evitar que lugares fiquem bloqueados em detrimento de outros membros.
* **Resolução Proposta:** Estabelecer a limitação de reserva a 48 horas, implementando uma lista de espera automática que notifique o membro seguinte em caso de desistência.
