# Rastreabilidade e Análise de Consistência – RF09

## Matriz de Rastreabilidade

| Requisito / User Story | Relacionado a | Descrição / Observações |
|------------------------|---------------|--------------------------|
| RF09 - Gravação de Teleconsultas | RF02 - Agendamento e Participação em Consultas VR | As consultas realizadas em realidade virtual devem ser gravadas. |
| RF09 - Gravação de Teleconsultas | RF08 - Repositório do Paciente | As gravações podem ser parte do repositório de laudos e documentos do paciente, se aplicável, ou linkadas a ele. |
| RF09 - Gravação de Teleconsultas | Políticas de Segurança e Privacidade (a definir) | Necessita de diretrizes claras sobre armazenamento, acesso e descarte das gravações. |
| RF09 - Gravação de Teleconsultas | Legislação de Saúde (ex: LGPD) | A gravação de teleconsultas deve estar em conformidade com as leis de proteção de dados e privacidade. |

---

## Análise de Consistência

- [x] Existe consentimento explícito do paciente e do médico para a gravação da teleconsulta?
- [ ] Como é feito o armazenamento seguro das gravações para garantir a privacidade e integridade dos dados?
- [ ] Quem terá acesso às gravações e em quais circunstâncias (auditorias, casos de negligência)?
- [ ] Por quanto tempo as gravações serão armazenadas e qual o processo de descarte?
- [ ] O sistema tem a capacidade técnica de gravar e armazenar vídeos de alta qualidade gerados pelas consultas em VR?

### Recomendações:

- **Desenvolver e implementar uma política clara de consentimento** para a gravação das consultas, informando médicos e pacientes sobre o propósito e uso das gravações.
- **Definir a arquitetura de armazenamento** que garanta a segurança, criptografia e redundância das gravações.
- **Estabelecer um protocolo de acesso** às gravações, detalhando quem pode acessá-las, sob quais condições e para quais finalidades.
- **Criar uma política de retenção e descarte** das gravações em conformidade com as regulamentações aplicáveis.
- **Avaliar a capacidade de armazenamento e processamento** do sistema para lidar com o volume de dados das gravações de vídeo.
