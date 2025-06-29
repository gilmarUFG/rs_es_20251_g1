# Rastreabilidade e Análise de Consistência – RF05

## Matriz de Rastreabilidade

| Requisito / User Story | Relacionado a | Descrição / Observações |
|------------------------|---------------|--------------------------|
| HU 5.1 – Troca de mensagens de texto entre médico e paciente | RF01 - Cadastro de Usuários  | Apenas usuários cadastrados e autenticados podem enviar e receber mensagens. |
| HU 5.1 – Troca de mensagens de texto entre médico e paciente | Política de Privacidade e LGPD | Mensagens devem ser armazenadas de forma segura e criptografada, conforme LGPD. |
| HU 5.2 - Registro de anotações médicas sobre um paciente | RF01 - Cadastro de Usuários        | Apenas médicos cadastrados podem registrar anotações no sistema. |
| HU 5.2 - Registro de anotações médicas sobre um paciente | RF03 - Envio de Exames e Documentos Médicos       | As anotações de um médico sobre um paciente se baseiam nos exames e documentos enviados pelo paciente. |
| HU 5.2 - Registro de anotações médicas sobre um paciente | RF06 - Visualização de Exames Médicos em 3D       | A visualização de exames pelo sistema é fundamental para que o médico consiga registrar laudos e anotações sobre o paciente. |
| HU 5.2 - Registro de anotações médicas sobre um paciente | RF08 - Acesso ao Repositório de Documentos Médicos       | Com o repositório de documentos médicos, o paciente tem acesso a quaisquer laudos, exames e orientações que o médico tenha escrito para ele. |
| HU 5.2 - Registro de anotações médicas sobre um paciente | Política de Privacidade e LGPD       |  Dados sensíveis; devem ser protegidos por criptografia e controle de acesso rigoroso |

---

## Análise de Consistência

- [x] O médico e o paciente estão cadastrados no sistema?
- [ ] As mensagens são criptografadas em trânsito e em repouso?
- [ ] O sistema trata desconexões ou falhas na entrega em tempo real?
- [ ] As mensagens possuem controle de histórico e rastreabilidade?
- [x] O médico está autenticado e autorizado a acessar o prontuário do paciente?
- [x] As anotações possuem controle de data, hora e usuário que realizou?
- [x] A edição das anotações atualiza corretamente a data da última modificação?
- [ ] Existe política de versionamento das anotações (por exemplo, manter histórico de edições)?
- [ ] As anotações são criptografadas em repouso no banco de dados?

### Recomendações:

- Adicionar tratamento de falhas. Por exemplo, usuário desconectado ou serviço de mensagens fora do ar.
- Integrar mensagens com sistema de notificações.
- Implementar criptografia para proteger as conversas.
- Avaliar a necessidade de versionamento das anotações médicas.
- Implementar criptografia no armazenamento das anotações, além da autenticação e autorização.
- Incluir logs de acesso para rastrear quem visualiza ou altera uma anotação.
