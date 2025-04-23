# Técnicas para especificação de requisitos

## 1. Pesquisa

### Prototipagem

A técnica de prototipagem tem como finalidade representar as o _layout_ e as características de funcionamento da interface do sistema por meio de desenhos, sejam eles “rabiscos” no papel ou interfaces bem próximas do real, feitas com ferramentas que permitem esboçar a interface de uma maneira semelhante ao sistema final. Por isso, é uma técnica aplicável em projetos que tenham foco na interface ou na interação do usuário com o sistema. Nesse sentido, é possível classificar protótipos em três tipos:
- Baixa fidelidade (wireframes): não são semelhantes ao sistema final e são feitos apenas para esboçar as características iniciais da interface;
- Média fidelidade (mockups): é mais elaborado do que uma amostra de baixa fidelidade, mas ainda não possui tantos detalhes que remetem à interface final do produto;
- Alta fidelidade: oferece uma interface semelhante à final, além de alto grau de interatividade e de realismo.
  
O uso de protótipos possibilita mostrar a interface e o processo de interação com funcionalidades e botões, de uma maneira fácil de se compreender. Por meio dessa informação concreta, o uso de protótipos evita interpretações erradas dos usuários quanto ao sistema e facilita o feedback. No entanto, é preciso tomar cuidado, especialmente com protótipos de alta fidelidade, para evitar expectativas irreais dos usuários. Também é necessário avaliar o tempo gasto na elaboração do protótipo e o custo desse protótipo, uma vez que protótipos mais elaborados demandam maior conhecimento técnico e uso de ferramentas específicas.

### Casos de uso

A UML (Unified Modeling Language) possui diversos diagramas, cada um com uma finalidade e com regras específicas, que podem ser utilizados na especificação de sistemas. O Diagrama de Casos de Uso, na UML, é um diagrama comportamental e é utilizado juntamente com a especificação do caso de uso, que trata da descrição textual dos cenários. Essa técnica é muito utilizada em projetos que utilizam desenvolvimento ágil, visando analisar as funcionalidades de um sistema e como um ator interage com esse sistema para atingir determinado objetivo.
Um caso de uso é uma sequência de interações entre o ator (alguém ou algo que interage com o sistema) e o sistema, que acontece de forma atômica, na perspectiva do ator. Nesse sentido, um caso de uso se preocupa em especificar _o que_ o sistema deve fazer e não _como_ isso deve ser feito.
Um diagrama de caso de uso é composto por três elementos principais:
- Ator (o bonequinho);
- Casos de uso (as elipses);
- Relacionamentos (as setas que ligam os casos de uso entre si e com os atores).
  
A utilização de casos de uso na especificação de requisitos pode ser vantajosa por sua fácil compreensão e por ajudar na criação de cenários de teste. Contudo, é necessário utilizar essa técnica combinada com outras técnicas de especificação, uma vez que ela pode não ser suficiente para documentar todos os requisitos.

## 2. Especificação dos requisitos

### Requisito A: “O sistema deve permitir que o médico crie uma sala virtual para a consulta.”
	
**Técnica de especificação: história de usuário.**

Como médico,
quero criar uma sala virtual de consulta,
para que eu possa atender os pacientes de forma remota utilizando realidade virtual.

Critérios de aceitação:
O médico deve estar autenticado no sistema;
A sala virtual só pode ser criada para datas e horários futuros;
O sistema deve gerar um link de acesso único para a sala VR;
O link gerado para a sala virtual deve expirar após a realização da consulta ou após 1 hora do horário agendado para a consulta, em caso de inatividade;
O sistema deve notificar o paciente e o médico com 24 horas de antecedência da consulta, via e-mail.


### Requisito B: “O sistema deve permitir que o paciente avalie o médico que o atendeu.”

**Técnica de especificação: simulação de cenário.**

Cenário: Avaliação do médico pelo paciente após consulta

Após o término de uma consulta virtual em realidade virtual, o paciente recebe uma notificação com a opção de avaliar o atendimento.
Ele acessa o sistema, visualiza a consulta realizada e escolhe entre 1 e 5 estrelas, sendo opcional, também, deixar um comentário.
A avaliação é registrada e fica disponível publicamente no perfil do médico avaliado. A identidade do paciente que realizou a avaliação, porém, não é disponibilizada.
