# Product Backlog Inicial

Histórias de Utilizador (*User Stories*) priorizadas para o Sistema de Gestão de Ginásio, focadas no desenvolvimento do núcleo da aplicação (3 a 5 casos de uso principais):

### US01 — Registo e Adesão de Membro [Prioridade: Alta / P1]
* **Como** Rececionista,
* **Quero** registar a ficha de um novo membro e associar-lhe um plano de adesão (ex: Livre Trânsito, Off-Peak),
* **Para que** o cliente fique devidamente cadastrado e com permissões de acesso configuradas.
* **Critério de Aceitação Inicial:** O sistema deve impedir a criação de membros com dados obrigatórios em falta e atribuir um estado "Ativo" após a criação com sucesso.

### US02 — Check-in e Validação de Acesso [Prioridade: Alta / P1]
* **Como** Rececionista,
* **Quero** registar a entrada (check-in) de um membro através do seu ID,
* **Para que** o sistema confirme se a subscrição está ativa e dentro do horário permitido pelo seu plano.
* **Critério de Aceitação Inicial:** Se a subscrição estiver suspensa ou o horário for inválido, o check-in deve ser recusado com uma mensagem explicativa visível na interface.

### US03 — Agendamento de Aula de Grupo com Controlo de Lotação [Prioridade: Alta / P1]
* **Como** Membro,
* **Quero** reservar o meu lugar numa aula de grupo disponível no mapa semanal,
* **Para que** garanta a minha vaga dentro do limite de capacidade máxima fixado para a sala.
* **Critério de Aceitação Inicial:** A reserva só deve ser confirmada se houver vagas disponíveis; quando a lotação atinge o limite máximo, o botão de reserva deve passar a "Entrar na Lista de Espera".

### US04 — Gestão Automática de Lista de Espera [Prioridade: Média / P2]
* **Como** Membro,
* **Quero** inscrever-me na lista de espera de uma aula esgotada,
* **Para que** seja automaticamente promovido a inscrito caso ocorra um cancelamento de outro membro.
* **Critério de Aceitação Inicial:** Havendo um cancelamento, o primeiro elemento da lista de espera deve passar automaticamente ao estado "Inscrito", libertando a sua posição na lista.

### US05 — Controlo de Lotação do Ginásio em Tempo Real [Prioridade: Média / P2]
* **Como** Gestor do Ginásio,
* **Quero** consultar o número total de membros presentes no espaço em tempo real,
* **Para que** possa monitorizar os picos de afluência e garantir o cumprimento das normas de lotação.
* **Critério de Aceitação Inicial:** O indicador de lotação deve atualizar automaticamente a cada check-in ou check-out efetuado no sistema.
