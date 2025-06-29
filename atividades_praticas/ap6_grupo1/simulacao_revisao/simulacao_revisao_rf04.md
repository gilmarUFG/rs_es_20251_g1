# ✅ Checklist de Verificação de Requisitos - Histórias de Usuário (RF04)

## 1. H04.1 - Iniciar Sessão 3D (Médico)
**História:** "Como médico, quero iniciar uma sessão de consulta 3D para realizar atendimentos imersivos"

| Critério de Verificação | Status | Observações |
|-------------------------|--------|-------------|
| A descrição está clara e compreensível? | ✅ | Objetivo imersivo bem definido |
| O requisito atende a uma necessidade real do usuário? | ✅ | Substitui necessidade de presença física |
| Há valor de negócio claramente definido? | ✅ | Reduz custos de infraestrutura física |
| Os critérios de aceitação estão descritos e são objetivos? | ✅ | Necessita definir tempo máximo de sessão |
| O requisito é testável? | ✅ | Testes de inicialização possíveis |
| Estão descritos os fluxos principais e alternativos? | ✅ | Incluir falhas de conexão |
| Há tratamento de exceções e erros? | ✅ | Tratar indisponibilidade do servidor 3D |
| O requisito está alinhado com regras de negócio conhecidas? | ✅ | Segue normas telemedicina |
| Existe rastreabilidade com histórias ou regras relacionadas? | ✅ | Integra com H04.2 (Paciente) |
| O requisito está consistente com outras funcionalidades existentes? | ✅ | Complementa módulo de agendamento |
| Há viabilidade técnica para entrega no sprint? | ✅ | Plataforma 3D já contratada |

---

## 2. H04.2 - Entrar na Sala Virtual (Paciente)
**História:** "Como paciente, quero entrar na sala virtual 3D para não me deslocar até a clínica"

| Critério de Verificação | Status | Observações |
|-------------------------|--------|-------------|
| A descrição está clara e compreensível? | ✅ | Benefício de deslocamento claro |
| O requisito atende a uma necessidade real do usuário? | ✅ | Pacientes em locais remotos |
| Há valor de negócio claramente definido? | ✅ | Amplia alcance geográfico |
| Os critérios de aceitação estão descritos e são objetivos? | ✅ | Validar autenticação prévia |
| O requisito é testável? | ✅ | Testes de acesso simultâneo |
| Estão descritos os fluxos principais e alternativos? | ✅ | Incluir atrasos na entrada |
| Há tratamento de exceções e erros? | ✅ | Tratar sessão já encerrada |
| O requisito está alinhado com regras de negócio conhecidas? | ✅ | Compatível com LGPD |
| Existe rastreabilidade com histórias ou regras relacionadas? | ✅ | Relaciona-se com H04.1 |
| O requisito está consistente com outras funcionalidades existentes? | ✅ | Usa mesmo sistema de login |
| Há viabilidade técnica para entrega no sprint? | ✅ | SDK de acesso já testado |

---

## 3. H04.3 - Comunicação por Voz (Médico)
**História:** "Como médico, quero falar com o paciente por voz em tempo real para explicar diagnósticos"

| Critério de Verificação | Status | Observações |
|-------------------------|--------|-------------|
| A descrição está clara e compreensível? | ✅ | Finalidade clínica explícita |
| O requisito atende a uma necessidade real do usuário? | ✅ | Comunicação essencial para diagnóstico |
| Há valor de negócio claramente definido? | ✅ | Melhora qualidade do atendimento |
| Os critérios de aceitação estão descritos e são objetivos? | ✅ | Definir qualidade mínima de áudio |
| O requisito é testável? | ✅ | Testes de latência possíveis |
| Estão descritos os fluxos principais e alternativos? | ✅ | Incluir fallback para texto |
| Há tratamento de exceções e erros? | ✅ | Tratar microfone não detectado |
| O requisito está alinhado com regras de negócio conhecidas? | ✅ | Exigência do CFM |
| Existe rastreabilidade com histórias ou regras relacionadas? | ✅ | Vincula-se a H04.4 (Paciente) |
| O requisito está consistente com outras funcionalidades existentes? | ✅ | Usa mesma rede de comunicação |
| Há viabilidade técnica para entrega no sprint? | ✅ | API de voz integrada |

---

## 4. H04.4 - Comunicação por Voz (Paciente)
**História:** "Como paciente, quero falar com o médico por voz em tempo real para explicar sintomas"

| Critério de Verificação | Status | Observações |
|-------------------------|--------|-------------|
| A descrição está clara e compreensível? | ✅ | Necessidade do paciente clara |
| O requisito atende a uma necessidade real do usuário? | ✅ | Descrição verbal é mais precisa |
| Há valor de negócio claramente definido? | ✅ | Reduz retrabalho por má interpretação |
| Os critérios de aceitação estão descritos e são objetivos? | ✅ | Definir limite de ruído aceitável |
| O requisito é testável? | ✅ | Testes de clareza possíveis |
| Estão descritos os fluxos principais e alternativos? | ✅ | Incluir paciente sem microfone |
| Há tratamento de exceções e erros? | ✅ | Tratar permissões negadas |
| O requisito está alinhado com regras de negócio conhecidas? | ✅ | Segue acessibilidade |
| Existe rastreabilidade com histórias ou regras relacionadas? | ✅ | Complementa H04.3 |
| O requisito está consistente com outras funcionalidades existentes? | ✅ | Mesmo protocolo de áudio |
| Há viabilidade técnica para entrega no sprint? | ✅ | Codec já licenciado |

---

## 5. H04.5 - Movimentação de Avatar (Médico)
**História:** "Como médico, quero mover meu avatar no consultório virtual para examinar melhor o paciente"

| Critério de Verificação | Status | Observações |
|-------------------------|--------|-------------|
| A descrição está clara e compreensível? | ✅ | Finalidade clínica explícita |
| O requisito atende a uma necessidade real do usuário? | ✅ | Simula aproximação física |
| Há valor de negócio claramente definido? | ✅ | Aumenta realismo da consulta |
| Os critérios de aceitação estão descritos e são objetivos? | ✅ | Definir limites de movimento |
| O requisito é testável? | ✅ | Testes de colisão possíveis |
| Estão descritos os fluxos principais e alternativos? | ✅ | Incluir obstruções de visão |
| Há tratamento de exceções e erros? | ✅ | Tratar travamento de avatar |
| O requisito está alinhado com regras de negócio conhecidas? | ✅ | Mantém ética médica |
| Existe rastreabilidade com histórias ou regras relacionadas? | ✅ | Dependente de H04.1 |
| O requisito está consistente com outras funcionalidades existentes? | ✅ | Usa mesmo motor 3D |
| Há viabilidade técnica para entrega no sprint? | ✅ | Controles de movimento prontos |