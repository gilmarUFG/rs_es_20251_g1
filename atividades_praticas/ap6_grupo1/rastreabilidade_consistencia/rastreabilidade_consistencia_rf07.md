# 🔗 Rastreabilidade e Consistência de Requisito

**Identificação do Requisito:** RF07 - Geração de autenticador para receitas virtuais

---

## 1. Transcrição do Requisito

O sistema deve gerar automaticamente um autenticador único (alfanumérico de 8 caracteres) ao emitir uma receita virtual, permitindo que farmácias e pacientes validem a autenticidade do documento. O autenticador estará vinculado à receita, será apresentado ao paciente e poderá ser validado por sistemas externos via endpoint público. O autenticador tem validade de 30 dias e só pode ser gerado por prescritores autenticados.

---

## 2. Rastreabilidade

| Elemento de Origem         | Elemento Relacionado                 | Descrição da Relação                                                  |
|----------------------------|--------------------------------------|-----------------------------------------------------------------------|
| História de Usuário RF07   | RF07 - Geração de autenticador       | O requisito decorre da HU do médico, que deseja garantir autenticidade na receita digital. |
| Critérios de Aceitação RF07| Casos de Teste para RF07             | Os critérios de aceitação são convertidos em casos de teste para geração, associação, expiração, validação e erros do autenticador. |
| DocumentoMedico (Modelo)   | Implementação Backend                | Os atributos autenticador e dataValidadeAutenticador refletem o requisito e estão presentes na modelagem do banco. |
| Endpoint de Validação      | Interface Farmácia / Sistema Externo | Farmácias e sistemas externos acessam o endpoint para validar autenticadores. |

---

## 3. Consistência

- **Consistência com Outros Requisitos:**  
O RF07 é consistente com as funcionalidades de emissão de documentos médicos digitais e com o controle de acesso do sistema.  
Integra-se às políticas de autenticação de prescritores e à visualização de receitas pelos pacientes.

- **Coerência entre Descrição e Implementação:**  
Os critérios de aceitação são atendidos na implementação, que gera, associa, exibe e valida o autenticador conforme especificado.

- **Não há sobreposição ou conflito** com outros requisitos funcionais ou regras de negócio identificados no sistema.

---

## 4. Observações

- O requisito contribui para a segurança e validade jurídica das receitas digitais.
- Está alinhado com normas de segurança, privacidade e rastreabilidade de documentos médicos.

---

**Revisor:** Aline Nunes dos Santos Ribeiro  
**Data da revisão:** 27/05/2025
