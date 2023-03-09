Esse é o estudo de caso da aula de Banco de Dados SQL.

Este estudo de caso contempla a modelagem de um banco de dados de um delivery.

#ETAPA 01 DA MODELAGEM:

##MODELAGEM CONCEITUAL

###Primeiro Passo:
Entender as regras de negócios, as quais são:

O restaurante “Comer é Bom Demais” forneceu, inicialmente, as seguintes regras de negócio: 
1. O restaurante possui diversas filiais espalhadas pelo território nacional, podendo ter mais de uma filial na mesma cidade. Essas informações devem estar devidamente cadastradas. 
2. O restaurante possui vários funcionários. 
3. Os pedidos são entregues por entregadores autônomos. 
4. O aplicativo deverá possuir produtos. 
5. Os pedidos referentes a cada restaurante deverão ser devidamente armazenados. 
6. Para fazer um pedido no sistema de delivery, o cliente deverá estar previamente cadastrado.

A partir das regras de negócio identifiquei as seguintes ENTIDADES:
Restaurante - Cliente - Pedido - Produto - Funcionario - Entregador - Cidade - Estado.