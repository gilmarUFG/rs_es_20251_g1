# 🧪 Simulação de Revisão de Requisito

**História de Usuário 5.1 – Troca de mensagens de texto entre médico e paciente**  

> **Como** médico,  
> **Quero** poder enviar mensagens para um paciente específico,  
> **Para** estabelecer comunicação de forma rápida através um chat de texto.  

---

## ✅ Verificação com Checklist
---------------------------------------------------------------------------------------------------------------------------------
| Critério de Verificação                                              | Status | Observações                                    |
|----------------------------------------------------------------------|--------|------------------------------------------------|
| A descrição está clara e compreensível?                              | ✅     | Descrição clara e bem detalhada.                               |
| O requisito atende a uma necessidade real do usuário?                | ✅     | Sim, promove comunicação rápida e eficiente entre médico e paciente.    |
| Há valor de negócio claramente definido?                             | ✅     | Sim, melhora a qualidade do atendimento e acompanhamento dos pacientes |
| Os critérios de aceitação estão descritos e são objetivos?           | ✅     | Os critérios estão bem definidos e objetivos.                         |
| O requisito é testável?                                              | ✅     | Sim, com cenários bem definidos.                   |
| Estão descritos os fluxos principais e alternativos?                 | ❌     | Poderia abordar mais fluxos alternativos, como envio-malsucedido de mensagens.     |
| Há tratamento de exceções e erros?                                   | ❌     | Não foi especificado.                                 |
| O requisito está alinhado com regras de negócio conhecidas?          | ✅     | Sim, está alinhado.                   |
| Existe rastreabilidade com histórias ou regras relacionadas?         | ✅     | A HU está diretamente relacionada com o RF05 e com outros requisitos, como o de cadastro e autenticação de usuários.   |
| O requisito está consistente com outras funcionalidades existentes?  | ✅     | Sim, há consistência.             |
| Há viabilidade técnica para entrega no sprint?                       | ✅     | Sim, desde que haja infraestrutura de websocket, fila ou serviço de mensagens para tempo real         |
----------------------------------------------------------------------------------------------------------------------------------
---

**Conclusão:** É possível implementar a história de usuário, porém tratamentos de exceções e cenários de teste são questões que precisam ser melhoradas.
