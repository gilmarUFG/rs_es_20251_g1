# RF03 - Envio de Exames e Documentos Médicos

## 1. Técnicas de Especificação

### Histórias de Usuário

Histórias de Usuário são descrições curtas e simples de funcionalidades desejadas, escritas sob a perspectiva do usuário. Seguem o formato:
**"Como \[ator], eu quero \[ação] para que \[benefício]."**

* **Cenários de Aplicação:**

  * Projetos de telemedicina onde o médico precisa revisar exames antes da consulta.
  * Sistemas de agendamento online de consultas médicas.
  * Ambientes ágeis que priorizam feedback prévio entre paciente e médico.

* **Vantagens:**

  * Permite ao médico preparar o atendimento com antecedência.
  * Melhora a qualidade da consulta ao reduzir surpresas.
  * Aumenta a satisfação do paciente pela comunicação prévia.

* **Desvantagens:**

  * Exige infraestrutura de upload e armazenamento de arquivos.
  * Riscos de segurança e privacidade de dados médicos.
  * Possibilidade de falhas de rede afetando o envio de documentos.

---

## 2. Especificação de Requisitos do Cenário

### Requisito RF03

**RF03 - O sistema deve permitir que o paciente envie exames e documentos médicos antes da consulta para análise do médico.**

#### Técnica: História de Usuário

> **Como** paciente,
> **Eu quero** enviar exames e documentos médicos antes da consulta
> **Para que** o médico possa analisá-los previamente.

#### Critérios de Aceitação

1. Deve existir um formulário de upload de arquivos para exames e documentos médicos.
2. Formatos aceitos: PDF, JPG e PNG.
3. Tamanho máximo de cada arquivo: 10 MB.
4. Os arquivos enviados devem ser associados ao agendamento da consulta correspondente.
5. Após o envio, o paciente recebe confirmação visual na interface.
6. O médico, ao acessar os detalhes da consulta, deve visualizar a lista de arquivos enviados.

#### Cenários de Uso

* **Cenário 1: Upload bem-sucedido**
  *Dado* que o paciente acessa a página de upload antes da data da consulta
  *Quando* ele envia um arquivo PDF de 2 MB
  *Então* o sistema exibe mensagem de sucesso e lista o arquivo enviado.

* **Cenário 2: Formato inválido**
  *Dado* que o paciente tenta enviar um arquivo DOCX
  *Quando* ele confirma o envio
  *Então* o sistema rejeita e exibe “Formato não suportado”.

* **Cenário 3: Arquivo muito grande**
  *Dado* que o paciente seleciona um arquivo de 15 MB
  *Quando* ele confirma o envio
  *Então* o sistema rejeita e exibe “Tamanho máximo de 10 MB excedido”.

* **Cenário 4: Visualizar documentos no back-end**
  *Dado* que o médico acessa os detalhes de uma consulta com documentos enviados
  *Quando* ele abre a seção “Documentos do paciente”
  *Então* o sistema lista todos os arquivos com nome e data de upload.

#### Regras de Negócio

1. Apenas o paciente dono da consulta pode enviar documentos.
2. Envio permitido até 24 horas antes da data e hora agendadas.
3. Arquivos devem ser armazenados de forma criptografada.

---
