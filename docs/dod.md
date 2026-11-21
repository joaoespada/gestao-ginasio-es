# Definition of Done (DoD)

Uma história de utilizador ou incremento só é considerado **concluído (Done)** quando cumpre cumulativamente todos os seguintes critérios:

1. **Critérios de Aceitação Cumpridos:** Todos os cenários definidos (Dado / Quando / Então) para a história foram validados sem erros.
2. **Testes Automatizados a Passar:** Os casos de teste unitários e de integração desenhados previamente pelo grupo estão implementados e passam a 100%.
3. **Revisão Humana do Código da IA:** Todo o código gerado com apoio de ferramentas de IA foi lido, compreendido e validado por um elemento do grupo, garantindo ausência de bibliotecas inexistentes, código morto ou falhas de segurança.
4. **Revisão por Pares (Pull Request):** A alteração entrou no ramo principal (`main`) através de um *Pull Request* revisto e aprovado por pelo menos outro elemento da equipa.
5. **Rastreabilidade e Documentação Atualizadas:** A matriz de rastreabilidade, os registos de interações relevantes com a IA e a documentação técnica em `docs/` refletem o estado atual do sistema.
6. **Conformidade com Regras de Dados:** Nenhum dado pessoal real ou segredo/chave de API foi incluído no código, nos testes ou nos *prompts* registados.