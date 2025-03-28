# Requisito: O sistema deve permitir que os clientes façam pedidos diretamente pelo aplicativo ou pelo site.

## Descrição Detalhada do Requisito - Aline Nunes

### Objetivo:

Permitir que os clientes realizem pedidos de maneira direta e integrada, seja pelo aplicativo ou pelo site, oferecendo uma experiência de compra rápida, intuitiva e personalizada. Essa funcionalidade visa facilitar o acesso ao catálogo de produtos, simplificar a finalização dos pedidos e permitir o acompanhamento em tempo real do status da entrega, elevando a satisfação do cliente e fortalecendo o relacionamento com a marca.

### Escopo:

O projeto abrange todas as etapas do processo de pedido, desde o cadastro/login do cliente até o acompanhamento pós-compra, incluindo:

- Cadastro e autenticação de clientes.
- Navegação e seleção de produtos/serviços.
- Adição dos itens ao carrinho de compras.
- Escolha e processamento do método de pagamento.
- Confirmação do pedido e envio de notificações.
- Acompanhamento do status do pedido em tempo real.

## Métodos utilizados na identificação das Fontes dos Requisitos - Ayumi

### Interações com os Stakeholders
As fontes iniciais podem ser entrevistas com os stakeholders, incluindo brainstorming com as equipes de marketing e de gerência.

### Stakeholders Envolvidos:
- **Clientes**: Usuários finais que farão os pedidos via aplicativo ou site.
- **Equipe de Negócios**: Responsáveis por definir estratégias de relacionamento com o cliente e metas comerciais.
- **Equipe de Desenvolvimento**: Profissionais encarregados de construir o sistema, garantindo a viabilidade técnica.
- **Equipe de Suporte e Operacional**: Encarregados do acompanhamento do atendimento e da logística dos pedidos.

### Benchmarking
Foram realizadas pesquisas de mercado também serão importantes para analisar como outros aplicativos semelhantes funcionam, identificando tendências de mercado e possíveis melhorias para diferenciar o produto.

### Feedbacks de Usuários
Os feedbacks de possíveis usuários ajudam a criar ou atualizar novos requisitos, tudo baseando-se nas necessidades/preferências do usuário final.

## Técnicas utilizadas na Elicitação de Requisitos

### Workshops JAD
Reuniu-se com os gerentes, equipes do financeiro e de serviço do restaurante em workshops para elicitar requisitos, juntamente com os analistas de sistemas e um facilitador.

### Descrições de casos de uso
Podemos definir casos de uso como um “documento narrativo que descreve a sequência de eventos de um ator que usa um sistema para completar um processo". Sendo assim, a utilização desse tipo de modelagem ajuda a validar o que o sistema deve fazer, evitando ambiguidades e problemas de comunicação, além de guiar o desenvolvimento e ajudar na criação de cenários de teste.

### Prototipagem
Criação de modelos preliminares das telas, com o intuito de validar o layout e interações do usuário com o software.

## Documentação e Validação de requisitos usados:

- **Registro Detalhado dos Requisitos**: Cada requisito deve ser documentado com sua origem, prioridade e critérios de aceitação.
- **Revisão com Stakeholders**: Realização de reuniões de validação para confirmar se os requisitos capturados atendem às necessidades e se estão alinhados com os objetivos do negócio.
- **Priorização e Mapeamento**: Utilização de técnicas como MoSCoW ou Matriz de Priorização para definir quais requisitos são críticos e quais podem ser aprimorados em fases posteriores.

## Fluxos de Execução - Aline Lima e Stephany

1. O cliente acessa o sistema via aplicativo ou site.
2. O cliente navega pelo catálogo e escolhe seus produtos.
3. O cliente adiciona os produtos desejados no carrinho de compras.
4. O cliente visualiza os produtos no carrinho e pode alterá-los.
5. O cliente seleciona a sua forma de pagamento.
6. O cliente realiza o pagamento do seu pedido.
7. O pedido é registrado no sistema e encaminhado para a equipe responsável.
8. O cliente acompanha em tempo real o status do seu pedido.

## Perfis de Usuário e Permissões - Gabriel

Para definir os perfis e suas respectivas permissões, foram utilizadas as seguintes técnicas de elicitação de requisitos:

- **Observação Direta**: Analisamos o fluxo operacional real dos restaurantes para identificar atividades críticas.
- **Análise de Tarefas**: Identificamos e documentamos as ações que cada perfil deve executar no sistema.
- **Casos de Uso e Cenários**: Estruturamos as permissões com base em situações reais enfrentadas pelos usuários, garantindo uma experiência funcional e eficiente.

### 1. Cliente
- Pode visualizar o histórico de pedidos anteriores.
- Pode editar ou cancelar um pedido antes da confirmação do preparo.
- Pode avaliar pedidos e deixar feedback sobre a experiência.
- Pode acessar e resgatar pontos do programa de fidelidade.
- Pode adicionar observações ao pedido (exemplo: "sem cebola", "molho separado").
- Pode ver e editar informações do cliente, como nome, endereço e método de pagamento.

### 2. Atendente
- Pode visualizar pedidos realizados pelos clientes.
- Pode alterar o status do pedido conforme ele avança no processo.
- Pode cancelar um pedido caso necessário.
- Pode reembolsar pedidos.
- Pode priorizar pedidos em caso de urgência.
- Pode adicionar manualmente pedidos feitos presencialmente no restaurante.

### 3. Administrador/Gerente
- Pode cadastrar, editar e remover itens do cardápio, incluindo descrições e imagens.
- Pode configurar horários de funcionamento e disponibilidade de itens do cardápio.
- Pode visualizar estatísticas detalhadas, como vendas diárias, horários de pico e avaliações dos clientes.
- Pode definir promoções e descontos automáticos no sistema.
- Pode configurar regras de taxas de entrega (exemplo: taxa variável por distância).
- Pode acessar relatórios financeiros e autorizar acessos a informações de pagamento.
