# Técnicas para especificação de requisitos

## 1. Técnicas de Especificação

### Histórias de Usuário

Histórias de Usuário são descrições curtas e simples de funcionalidades desejadas, escritas sob a perspectiva do usuário. Seguem o formato:
**"Como [ator], eu quero [ação] para que [benefício]."**

- **Cenários de Aplicação:**
  - Métodologias ágeis (Scrum, Kanban).
  - Projetos com requisitos dinâmicos e iterativos.
  - Equipes que priorizam a comunicação direta com stakeholders.

- **Vantagens:**
  - Simplicidade: Fáceis de entender e escrever.
  - Foco no usuário: Centralizadas nas necessidades do cliente.
  - Flexibilidade: Podem ser refinadas e priorizadas ao longo do projeto.

- **Desvantagens:**
  - Falta de detalhes: Podem ser muito vagas sem critérios de aceitação claros.
  - Dependência de comunicação: Requerem interação constante com stakeholders.
  - Escalabilidade limitada: Complexas para sistemas com muitos requisitos inter-relacionados.

### Casos de uso

Casos de Uso descrevem as interações entre atores (usuários ou sistemas) e o software para atingir um objetivo específico. Incluem fluxos principal e alternativos.

- **Cenários de Aplicação:**
  - Projetos com requisitos bem definidos e estáveis.
  - Sistemas complexos com muitas interações.
  - Documentação formal (ex.: processos em UML).

- **Vantagens:**
  - Detalhamento: Descrevem cenários completos, incluindo exceções.
  - Clareza: Úteis para validação com stakeholders.
  - Reutilização: Facilitam o mapeamento de requisitos similares.

- **Desvantagens:**
  - Complexidade: Demandam mais tempo para elaboração.
  - Rigidez: Difíceis de ajustar em projetos ágeis.
  - Risco de excesso de documentação: Podem se tornar burocráticos.
    
## 2. Especificação de Requisitos do Cenário

### Requisito A (RF15)  
**"O sistema deve cadastrar um usuário; esse podendo ser médico ou paciente."**

#### Técnica: História de Usuário

> **Como** um administrador,  
> **Eu quero** cadastrar um novo usuário (médico ou paciente),  
> **Para que** ele possa acessar o sistema conforme seu perfil de uso.

**Critérios de Aceitação:**
- Deve haver um formulário de cadastro com campos obrigatórios como nome, CPF, e-mail e tipo de usuário (médico ou paciente).
- O sistema deve validar os dados antes de permitir o cadastro.
- Após o cadastro, o usuário deve receber uma confirmação.
- O usuário deve ser classificado como "médico" ou "paciente", com permissões distintas.

---

### Requisito B (RF40)  
**"O sistema deve notificar os usuários no momento de uma consulta."**

#### Técnica: Caso de Uso

**Nome:** Notificar usuários no momento da consulta  
**Ator principal:** Sistema  
**Atores secundários:** Usuário (médico e paciente)  
**Descrição:** Este caso de uso descreve como o sistema envia uma notificação para os usuários (médico e paciente) no horário agendado para a consulta.

**Fluxo principal:**
1. O horário da consulta se aproxima.
2. O sistema verifica o agendamento atual.
3. O sistema envia uma notificação ao paciente e ao médico informando o início da consulta.

**Fluxos alternativos:**
- **A1:** Caso o usuário esteja offline, a notificação será enviada por e-mail.
- **A2:** Caso o agendamento tenha sido cancelado anteriormente, a notificação não será enviada.

**Pré-condições:**
- Consulta previamente agendada e registrada no sistema.
- Dados de contato dos usuários (e-mail, notificações push) cadastrados.

**Pós-condições:**
- Os usuários são notificados no momento exato da consulta.
