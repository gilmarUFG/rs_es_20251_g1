# Rastreabilidade e Análise de Consistência – RF04 (Consultas 3D)

## Matriz de Rastreabilidade

| Histórias de Usuário | Requisitos Relacionados | Dependências Funcionais | Observações Críticas |
|-----------------------|-------------------------|-------------------------|----------------------|
| H04.1 - Iniciar sessão 3D (Médico) | RF04 | RF01, RF02 | Requer validação de agendamento ativo |
| H04.2 - Entrar na sala virtual (Paciente) | RF04 | RF03 (Documentos), RF06 (Exames 3D) | Paciente deve ter exames pré-carregados |
| H04.3 e H04.4 - Comunicação por voz (Médico/Paciente) |RF04 | RF03 | Exige QoS mínimo de 500kbps |
| H04.5 - Movimentação de avatar (Médico) | RF04 | RF03 | Registra aproximação para métricas |

---

## Análise de Consistência Detalhada

### 1. Iniciação de Sessão (H04.1)
**Verificações:**
- [x] Validação cruzada com agenda médica
- [x] Limite máximo de sessões simultâneas por profissional
- [x] Pré-carregamento de documentos do paciente

### 2. Acesso do Paciente (H04.2)
**Verificações:**
- [x] Autenticação em dois fatores
- [x] Compatibilidade com navegadores mobile
- [x] Notificação em tempo real para o médico

**Dados Obrigatórios:**
- Termo de consentimento digital
- Configurações de acessibilidade

### 3. Comunicação por Voz (H04.3/H04.4)
**Métricas Chave:**
- Latência máxima: 280ms
- Taxa de perda de pacotes: <1%
- [x] Suporte a codecs médicos (para auscultação)

**Restrições:**
- Bloqueio em redes não criptografadas
- Gravação opcional com consentimento

### 4. Movimentação de Avatar (H04.5)
**Parâmetros Técnicos:**
- Área navegável: 10x10m virtual
- [x] Detecção de colisão com objetos 3D
- [x] Salvamento de posições estratégicas

**Regras de Negócio:**
- Distância mínima paciente-médico: 1.2m virtual
- Zonas restritas (equipamentos médicos)