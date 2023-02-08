# installment-loan-service
Este Projeto é um programa no qual o usuário simula o seu empréstimo e suas respectivas parcelas.
Para gerar implementar a Lista de Installments da class Contract utilizei a class ContractService 
na qual se associa com a interface OnlinePaymentService e calcula as Installments e adiciona a class Conctract
para que haja uma inversão de controle, onde pelo construtor da class ContractService pode ser mudado o tipo de pagamento
assim deixando o código mais limpo e facil de ser modificado e implementado.
