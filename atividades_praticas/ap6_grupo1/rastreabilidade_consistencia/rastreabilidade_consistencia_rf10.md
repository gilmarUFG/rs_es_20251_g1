# Rastreabilidade e Análise de Consistência – RF10

## Matriz de Rastreabilidade

| Requisito / User Story | Relacionado a | Descrição / Observações |
|------------------------|---------------|--------------------------|
| RF10 - Avaliação de médicos pelos paciente | RF01 - Cadastro de Usuários  | Apenas médicos cadastrados podem ser avaliados e apenas pacientes cadastrados podem avaliar. |
| RF10 - Avaliação de médicos pelos paciente | RF02 - Agendamento de Consultas | As avaliações estão relacionadas às consultas, uma vez que o atendimento médico durante as consultas é avaliado. |
| RF10 - Avaliação de médicos pelos paciente | RF05 - Funcionalidades de chat e anotações médicas      | Atendimento via chat e anotações médicas também podem ser levados em consideração no momento da avaliação. |
| RF10 - Avaliação de médicos pelos paciente | RF08 - Acesso ao Repositório de Documentos Médicos       | Assim, como mencionado anteriormente, tendo acesso às anotações médicas, o paciente pode levá-las em consideração no momento de avaliar o atendimento médico. |
| RF10 - Avaliação de médicos pelos paciente | RF09 - Gravação de Teleconsultas       | Em casos de avaliações negativas e denúncias de pacientes com relação a negligências médicas, ter consultas gravadas é de extrema importância. |
| RF10 - Avaliação de médicos pelos paciente | Políticas de Privacidade       | Proteção dos dados pessoais dos avaliadores (pacientes permanecem anônimos nas avaliações). |

---

## Análise de Consistência

- [x] O médico e o paciente estão cadastrados no sistema?
- [x] O paciente tem vínculo de atendimento com o médico para realizar a avaliação?
- [x] O sistema valida se os campos obrigatórios da avaliação foram preenchidos?
- [x] Há prevenção contra avaliações duplicadas para o mesmo atendimento?
- [x] Os dados das avaliações são armazenados de forma segura e estão aderentes à LGPD?
- [x] As informações são protegidas contra alterações não autorizadas?
- [ ] Há ferramentas de moderação (por exemplo, denúncia e exclusão de conteúdo ofensivo)?
- [ ] Existe funcionalidade de busca, filtros e ordenação nas avaliações?
- [x] Existem restrições quanto à edição e exclusão de avaliações?

### Recomendações:

- Implementar filtros avançados para as avaliações (médico, período, nota, denúncia).
- Adicionar funcionalidade de moderação (excluir avaliação ofensiva, denunciar como inadequada).
