# ✅ Checklist de Verificação de Requisitos

**Identificação do Requisito:** RF10 - Avaliação de médicos pelos pacientes
--------------------------------------------------------------------------------------------------------------
| Critério de Verificação                                              | Status (✅ / ❌ / ?) | Observações |
|----------------------------------------------------------------------|-----------------------|-------------|
| A descrição está clara e compreensível?                              | ✅                       | A descrição é clara e cobre a criação, a edição, a visualização e a exclusão das avaliações.             |
| O requisito atende a uma necessidade real do usuário?                | ✅                       | Sim, a partir da avaliação um paciente pode expressar sua opinião e os outros pacientes podem obter noção da qualidade de um atendimento médico.              |
| Há valor de negócio claramente definido?                             | ✅                       | O feedback dos pacientes fornece transparência e incentiva a melhora do atendimento médico.             |
| Os critérios de aceitação estão descritos e são objetivos?           | ✅                       | Sim, os critérios são objetivos e detalham bem condições e restrições.             |
| O requisito é testável (permite escrita de casos de teste)?          | ✅                       | Os cenários de teste escritos permitem a criação de casos de teste completos, tanto para casos de sucesso quanto de falha.             |
| Estão descritos os fluxos principais e alternativos?                 | ✅                       | Sim, os fluxos incluem os cenários principais para o CRUD de avaliações, assim como os cenários alternativos em casos de erro nessas ações.            |
| Há tratamento de exceções e erros?                                   | ✅                       | Sim, com mensagens em casos de erros, tais como exceder limite de caracteres, e tentar editar ou excluir uma avaliação após o prazo permitido.             |
| O requisito está alinhado com regras de negócio conhecidas?          | ✅                       | Sim, especialmente no que diz respeito ao controle de quem pode avaliar (após atendimento), anonimato dos pacientes e restrição de prazos para editar/excluir avaliações.              |
| Existe rastreabilidade com histórias ou regras relacionadas?         | ✅                       |  O requisito está diretamente relacionado às HUs 10.1 a 10.5, que detalham o CRUD de avaliações.            |
| O requisito está consistente com outras funcionalidades existentes?  | ✅                       |  Sim, especialmente com as funcionalidades de cadastro de médicos, pacientes e controle de atendimentos realizados.            |
| Há viabilidade técnica para entrega no sprint?                       | ✅                       |  A implementação é tecnicamente viável, utilizando práticas comuns (sistema de reviews, controle de prazos, CRUD simples e média aritmética).            |
--------------------------------------------------------------------------------------------------------------

**Revisor:** Aline Lima Martins Coelho  
**Data da revisão:** 27/05/2025
