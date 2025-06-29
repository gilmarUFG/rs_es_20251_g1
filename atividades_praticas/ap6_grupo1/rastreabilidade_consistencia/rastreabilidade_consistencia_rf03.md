# 🔗 Rastreabilidade e Consistência de Requisito

**Identificação do Requisito:** RF03 - Envio de exames e documentos médicos

---

## 1. Transcrição do Requisito

O sistema deve permitir que o paciente envie exames e documentos médicos antes da consulta para análise do médico.

---

## 2. Rastreabilidade

| Elemento de Origem            | Elemento Relacionado          | Descrição da Relação                                                                               |
|-------------------------------|-------------------------------|----------------------------------------------------------------------------------------------------|
| História de Usuário RF03      | RF03 - Envio de exames        | O requisito está baseado na HU do paciente que quer enviar exames antes da consulta.                |
| Critérios de Aceitação RF03   | Casos de Teste para RF03      | Os critérios de aceitação originam os testes de upload, formatos, tamanho e visualização de arquivos.|
| DocumentoMedico (Modelo)      | Implementação Backend         | Classe/modelo representa e armazena os documentos enviados, associados ao agendamento.              |
| Agendamento de Consulta       | Permissão de Envio            | O envio só é permitido até 24h antes da consulta, conforme regra de negócio.                        |
| Tela de Upload do Paciente    | Interface do Usuário          | Implementa o formulário para envio, confirmação visual e feedback de erro.                          |
| Tela do Médico (Consulta)     | Visualização dos Documentos   | Médicos acessam e visualizam documentos enviados ao abrir detalhes da consulta.                     |

---

## 3. Consistência

- **Consistência com Outros Requisitos:**  
O RF03 complementa o fluxo de agendamento, permitindo anexos de exames e documentos e respeita regras de permissão e privacidade.

- **Coerência entre Descrição e Implementação:**  
A implementação contempla todos os critérios, incluindo formatos, tamanho, regras de associação e restrições de envio.

- **Não há sobreposição ou conflito** com outros requisitos ou regras de negócio identificados.

---

## 4. Observações

- O requisito está alinhado às normas de segurança, confidencialidade e usabilidade em sistemas de saúde.
- Garante que somente o paciente da consulta pode enviar documentos e limita o envio conforme a data do agendamento.

---

**Revisor:** Aline Nunes dos Santos Ribeiro  
**Data da revisão:** 28/05/2025
