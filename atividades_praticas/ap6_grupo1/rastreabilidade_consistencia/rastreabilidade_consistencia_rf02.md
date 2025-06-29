# Rastreabilidade e Análise de Consistência – RF02

## Matriz de Rastreabilidade

| Requisito / User Story | Relacionado a | Descrição / Observações |
|------------------------|---------------|--------------------------|
| RF02 - Agendamento e Participação em Consultas VR | RF01 - Cadastro de Usuários | Necessita de **cadastro de médico e paciente** para agendar e participar da consulta. |
| RF02 - Agendamento e Participação em Consultas VR | RF04 - Interação em Ambiente 3D | A participação da consulta envolve a **interação em ambiente virtual 3D**. |
| RF02 - Agendamento e Participação em Consultas VR | RF05 - Chat e Anotações | As funcionalidades de **chat e anotações** serão utilizadas durante as consultas em VR. |
| RF02 - Agendamento e Participação em Consultas VR | RF06 - Visualização de Exames 3D | O médico precisa **visualizar exames 3D** durante a consulta em VR. |
| RF02 - Agendamento e Participação em Consultas VR | RF09 - Gravação de Teleconsultas | As consultas em VR devem ser **gravadas para fins de auditoria**. |

---

## Análise de Consistência

- [x] O ambiente de realidade virtual é compatível com os dispositivos dos usuários (médicos e pacientes)?
- [ ] Existe um sistema de notificação para lembretes de agendamento?
- [ ] A interação em tempo real é garantida em ambientes de realidade virtual?
- [ ] Como é feito o controle de acesso e privacidade nas consultas em realidade virtual?
- [ ] Existem requisitos de largura de banda e hardware para o funcionamento da realidade virtual?

### Recomendações:

- **Especificar** os requisitos mínimos de **hardware e software** para a execução das consultas em realidade virtual.
- **Detalhar o fluxo de notificação** de agendamentos para pacientes e médicos.
- **Definir políticas de privacidade e segurança** para as gravações das teleconsultas em realidade virtual.
- **Realizar testes de desempenho** para garantir a fluidez da interação em tempo real no ambiente VR.
