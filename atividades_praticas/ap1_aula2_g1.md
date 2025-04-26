# Requisitos de Software

Problema: Problemas de gerenciamento de pedidos e reservas em um restaurante


## Requisitos Funcionais:
 	
O sistema deve permitir que os clientes façam pedidos diretamente pelo aplicativo ou pelo site.

O sistema deve permitir o acompanhamento do status do pedido em tempo real.

O cliente deve conseguir realizar a reserva no restaurante.

O usuário deve poder visualizar os itens disponíveis no cardápio, juntamente com uma descrição do produto.

O sistema deve permitir que os clientes realizem pagamentos via cartão de crédito, débito, dinheiro ou PIX.

## Requisitos Não Funcionais:

Segurança: O software deve oferecer segurança seguindo a LGPD com relação a dados sensíveis de pagamento pelo sistema, impedindo fraudes e vazamento de dados.

O sistema deve processar e exibir a confirmação de um pedido em até 2 segundos após a sua submissão.

O sistema deve realizar backups automáticos dos dados críticos (como pedidos, reservas e transações financeiras) a cada 12 horas e manter esses backups por um período mínimo de 30 dias. Dessa forma, em caso de falhas ou desastres, será possível restaurar rapidamente a integridade e disponibilidade das informações.

O sistema deve ser escalável para suportar um aumento na demanda em horários de pico.

O software deve ter uma interface responsiva, funcionando tanto para web quanto para mobile.




## Regras de Negócio:

Só serão aceitos pedidos de delivery em um raio de 10km de distância do restaurante;

O pagamento de um pedido online só será confirmado após a aprovação da transação pelo sistema financeiro.

O sistema deverá implementar um programa de fidelidade onde, a cada 5 pedidos concluídos, o cliente acumula pontos. 

Esses pontos poderão ser trocados por descontos ou brindes em futuros pedidos, incentivando a repetição de compras e aumentando a satisfação do cliente.

As reservas devem ser confirmadas até 15 minutos antes do horário agendado; caso contrário, serão canceladas automaticamente.

Pedidos para entrega terão uma taxa calculada com base na distância do restaurante, sendo isentos para distâncias inferiores a 2 km.
