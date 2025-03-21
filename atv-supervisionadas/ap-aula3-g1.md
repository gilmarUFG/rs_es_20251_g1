[21:29, 20/03/2025] Stephany Milhomem: # Requisito: O sistema deve permitir que os clientes façam pedidos diretamente pelo aplicativo ou pelo site.

## 1. Descrição Detalhada do Requisito - Aline Nunes

### Objetivo:
Permitir que os clientes realizem pedidos de maneira direta e integrada tanto pelo aplicativo quanto pelo site, oferecendo uma experiência de compra rápida, intuitiva e personalizada. Essa funcionalidade tem como meta facilitar o acesso ao catálogo de produtos, simplificar a finalização dos pedidos e permitir o acompanhamento em tempo real do status da entrega, elevando a satisfação do cliente e fortalecendo o relacionamento com a marca.

### Escopo:
Abrange todas as etapas do processo de pedido, desde o cadastro/login do cliente até o acompanhamento pós-compra, incluindo:
- Cadastro …
[21:33, 20/03/2025] Stephany Milhomem: # Requisito: O sistema deve permitir que os clientes façam pedidos diretamente pelo aplicativo ou pelo site.

## Descrição Detalhada do Requisito - Aline Nunes

### Objetivo
Permitir que os clientes realizem pedidos de maneira direta e integrada tanto pelo aplicativo quanto pelo site, oferecendo uma experiência de compra rápida, intuitiva e personalizada. Essa funcionalidade tem como meta facilitar o acesso ao catálogo de produtos, simplificar a finalização dos pedidos e permitir o acompanhamento em tempo real do status da entrega, elevando a satisfação do cliente e fortalecendo o relacionamento com a marca.

### Escopo
Abrange todas as etapas do processo de pedido, desde o cadastro/login do cliente até o acompanhamento pós-compra, incluindo:
- Cadastro e aut…
[21:34, 20/03/2025] Stephany Milhomem: # Requisito: O sistema deve permitir que os clientes façam pedidos diretamente pelo aplicativo ou pelo site.

## Descrição Detalhada do Requisito - Aline Nunes

### Objetivo
Permitir que os clientes realizem pedidos de maneira direta e integrada tanto pelo aplicativo quanto pelo site, oferecendo uma experiência de compra rápida, intuitiva e personalizada. Essa funcionalidade tem como meta facilitar o acesso ao catálogo de produtos, simplificar a finalização dos pedidos e permitir o acompanhamento em tempo real do status da entrega, elevando a satisfação do cliente e fortalecendo o relacionamento com a marca.

### Escopo
Abrange todas as etapas do processo de pedido, desde o cadastro/login do cliente até o acompanhamento pós-compra, incluindo:
- Cadastro e autenticação de clientes.
- Navegação e seleção de produtos/serviços.
- Adição dos itens ao carrinho de compras.
- Escolha e processamento do método de pagamento.
- Confirmação do pedido e envio de notificações.
- Acompanhamento do status do pedido em tempo real.

## Histórias de Usuários

### Cadastro e Login
*User Story:*
> Como usuário, eu quero me cadastrar e fazer login no sistema para que eu possa acessar minha conta, visualizar meu histórico de pedidos e garantir uma experiência personalizada e segura.

### Navegação e Seleção de Produtos
*User Story:*
> Como usuário, eu quero navegar pelo catálogo de produtos e visualizar os detalhes de cada item para que eu possa selecionar os produtos que desejo comprar com confiança.

### Finalização do Pedido
*User Story:*
> Como usuário, eu quero revisar e finalizar meu pedido, escolhendo o método de pagamento preferido, para que minha compra seja processada de forma rápida e segura.

### Acompanhamento do Status do Pedido
*User Story:*
> Como usuário, eu quero acompanhar o status do meu pedido em tempo real para que eu possa me manter informado sobre o andamento e a entrega da minha compra.

## Regras de Negócio

### Autenticação Segura
- Todas as operações de cadastro, login e finalização de pedido devem ser realizadas através de conexões seguras (HTTPS), garantindo a proteção dos dados dos clientes.

### Validação dos Dados
- As informações inseridas pelo cliente (no cadastro, na seleção de produtos e na finalização do pedido) devem ser validadas para evitar erros ou inconsistências.

### Atualização em Tempo Real
- O status do pedido deve ser atualizado em tempo real no sistema para que o cliente possa acompanhar a evolução do seu pedido sem atrasos.

### Integração com Sistemas de Pagamento
- O sistema deve integrar-se com provedores de pagamento confiáveis, garantindo a segurança e a efetividade na autorização e processamento dos pagamentos.

### Notificações Automatizadas
- Após etapas críticas (cadastro, confirmação do pedido, alteração do status do pedido), o sistema deve enviar notificações (por e-mail ou push) para manter o cliente informado.

## Requisitos Não Funcionais

### Usabilidade
- Interface intuitiva e responsiva, compatível com dispositivos móveis e desktops, para facilitar a navegação e a finalização do pedido.

### Desempenho
- O sistema deve ser capaz de processar e atualizar os pedidos em tempo real, garantindo uma experiência sem lentidão, mesmo em períodos de alta demanda.

### Segurança
- Implementar práticas de segurança, como criptografia de dados sensíveis, proteção contra ataques cibernéticos e conformidade com normas de segurança (ex.: LGPD).

### Escalabilidade
- Estrutura capaz de suportar um aumento significativo no número de usuários e transações sem degradação do desempenho.

### Disponibilidade
- O sistema deve ter alta disponibilidade, garantindo acesso contínuo, com tempo mínimo de inatividade, e planos de contingência para falhas.

## Considerações Técnicas e Integrações

### Plataformas Suportadas
- O aplicativo deve estar disponível para as principais plataformas móveis (iOS e Android) e o site deve ser compatível com os navegadores modernos.

### Integração com Sistemas de Backend
- O sistema de pedidos deve integrar-se com o backend para gerenciamento de estoque, logística e atualizações dos status de entrega.

### API de Pagamento
- Integração com uma ou mais APIs de pagamento que atendam aos requisitos de segurança e performance.

### Banco de Dados
- Utilizar um banco de dados confiável e escalável para armazenar as informações dos clientes, produtos e pedidos.

## Identificação das Fontes dos Requisitos - Ayumi

### Entrevistas
- As fontes iniciais podem ser entrevistas com os stakeholders, incluindo brainstorming com as equipes de marketing e de gerência.

### Análise de Mercado
- As pesquisas de mercado também serão importantes para analisar como outros aplicativos semelhantes funcionam, identificando tendências de mercado e possíveis melhorias para diferenciar o produto.

### Feedbacks de Usuários
- Os feedbacks de possíveis usuários ajudam a criar ou atualizar novos requisitos, tudo baseando-se nas necessidades/preferências do usuário final.

## Fluxos de Execução - Aline Lima e Stephany
1. O cliente acessa o sistema via aplicativo ou site.
2. O cliente navega pelo catálogo e escolhe seus produtos.
3. O cliente adiciona os produtos desejados no carrinho de compras.
4. O cliente visualiza os produtos no carrinho e pode alterá-los.
5. O cliente seleciona a sua forma de pagamento.
6. O cliente realiza o pagamento do seu pedido.
7. O pedido é registrado no sistema e encaminhado para a equipe responsável.
8. O cliente acompanha em tempo real o status do seu pedido.

## Perfis de Usuários com Permissão de Execução - Gabriel

### Cliente
- Pode visualizar o histórico de pedidos anteriores.
- Pode editar ou cancelar um pedido antes da confirmação do preparo.
- Pode avaliar pedidos e deixar feedback sobre a experiência.
- Pode acessar e resgatar pontos do programa de fidelidade.
- Pode adicionar observações ao pedido (exemplo: "sem cebola", "molho separado").

### Atendente
- Pode visualizar pedidos realizados pelos clientes.
- Pode alterar o status do pedido conforme ele avança no processo.
- Pode cancelar um pedido caso necessário.
- Pode reembolsar pedidos.
- Pode priorizar pedidos em caso de urgência.
- Pode adicionar manualmente pedidos feitos presencialmente no restaurante.

### Administrador/Gerente
- Pode cadastrar, editar e remover itens do cardápio, incluindo descrições e imagens.
- Pode configurar horários de funcionamento e disponibilidade de itens do cardápio.
- Pode visualizar estatísticas detalhadas, como vendas diárias, horários de pico e avaliações dos clientes.
- Pode definir promoções e descontos automáticos no sistema.
- Pode configurar regras de taxas de entrega (exemplo: taxa variável por distância).gi