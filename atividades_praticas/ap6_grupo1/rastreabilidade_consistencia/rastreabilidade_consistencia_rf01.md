# 🔗 Rastreabilidade e Análise de Consistência – RF01

## Matriz de Rastreabilidade

| Requisito / User Story     | Relacionado a                     | Descrição / Observações |
|---------------------------|----------------------------------|------------------------|
| RF01 - Cadastro de Usuários | RF02 - Agendamento de Consultas | O cadastro é pré-requisito para o agendamento e participação em consultas remotas. |
| RF01 - Cadastro de Usuários | RF03 - Envio de Exames          | Apenas usuários autenticados (pacientes) podem enviar exames para o médico. |
| RF01 - Cadastro de Usuários | RF04 - Ambiente Virtual 3D      | O acesso ao ambiente virtual depende de o usuário estar cadastrado e autenticado. |
| RF01 - Cadastro de Usuários | RF05 - Chat e Anotações         | A comunicação entre médico e paciente depende do vínculo estabelecido após o cadastro. |
| RF01 - Cadastro de Usuários | RF06 - Visualização de Exames 3D| O médico, após o cadastro, poderá visualizar os exames enviados pelos pacientes. |
| RF01 - Cadastro de Usuários | RF07 - Autenticador de Receitas | Somente médicos cadastrados podem gerar autenticadores para receitas virtuais. |
| RF01 - Cadastro de Usuários | RF08 - Repositório do Paciente | O paciente cadastrado terá acesso ao repositório pessoal de documentos médicos. |
| RF01 - Cadastro de Usuários | RF09 - Gravação de Teleconsultas| A gravação das consultas só ocorre após a identificação e autenticação dos participantes cadastrados. |
| RF01 - Cadastro de Usuários | RF10 - Avaliação do Médico     | Apenas pacientes cadastrados podem avaliar médicos após a realização das consultas. |

---

## Análise de Consistência

- [x] O fluxo de cadastro é indispensável e está corretamente posicionado como etapa inicial para todas as demais funcionalidades.
- [x] As validações de campos obrigatórios (nome, e-mail, CPF para pacientes, CRM para médicos) estão adequadamente especificadas.
- [x] O cadastro está alinhado com a política de privacidade e proteção de dados (LGPD), especialmente no tratamento de informações sensíveis.
- [x] As mensagens de erro e exceção (ex.: CPF ou CRM já cadastrados) estão definidas.
- [x] O relacionamento com outros requisitos foi mapeado, garantindo que todos dependem da existência do cadastro prévio.
- [x] Compatibilidade garantida entre o fluxo de cadastro e os mecanismos de autenticação para acesso seguro às funcionalidades.


## Recomendações

- Reforçar na especificação que a autenticação é necessária para qualquer operação subsequente ao cadastro.
- Validar a integração entre o módulo de cadastro e o sistema de autenticação.
- Assegurar que o sistema registre logs de cadastro para eventual auditoria, conforme requisitos relacionados à segurança e LGPD.
- Implementar validação de duplicidade no backend para garantir integridade dos registros de usuários.
