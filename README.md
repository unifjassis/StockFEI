# StockFEI
Plataforma simulada de negociação de ações.

Esta plataforma será chamada de StockFEI e é responsável pela iteração com os clientes e armazenamento das contas e está dividida em dois sistemas: o DealBroker e o Market.
As informações disponibilizadas como requisitos iniciais são:
• O DealBroker é um centralizador e responsável por disponibilizar as ações que serão negociadas naquele pregão, bem como os respectivos preços de abertura.
• O Market é responsável pela abertura da conta dos clientes, bem como pela manutenção da sua carteira individual de cada um deles.
  o Além da sua carteira de ações, cada cliente deve possuir uma contacorrente, onde é feito o depósito inicial dos valores a serem negociados. Depósitos feitos nesta conta-corrente poderão ser negociados apenas a partir do pregão seguinte.
• Ordens de Compra (OC) e de venda (OV) são colocadas pelos clientes e enviadas pelo Market ao DealBroker para que sejam disponibilizadas a todos os associados.
  o OC e OV podem ser limitados em valor total, quantidade de ações e duração
  o Também podem ter execução completa ou parcial
• O Market deve fornecer um relatório individual com a posição de cada cliente, bem como um relatório consolidado com todos os ativos em posse dos seus clientes no
encerramento do pregão.
• O DealBroker deve fornecer um relatório consolidado sobre todos os negócios relacionado naquele pregão, bem como um relatório para auditoria, com informações sobre os últimos 10 pregões (pelo menos!).
• O DealBroker é responsável pela abertura e fechamento dos pregões. Ordens enviados enquanto o pregão estiver fechado devem ser desconsideradas.
• O DealBroker deve assegurar que uma mesma pessoa não tenha contas abertas em plataforma de negociação diferentes.

Os requisitos apresentados devem ser detalhados conforme as boas práticas de levantamento de requisitos. Novos requisitos podem e devem ser inseridos nesta lista.
