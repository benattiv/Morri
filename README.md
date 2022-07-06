# ATTA
Projeto final da matéria **SEM0544 - Sistemas Embarcados (2022)**

## Alunos
[Leandro Yuji Kanno](https://github.com/L-Yuji) (NºUSP 10883811)
[Vinícius Motta Benatti](https://github.com/benattiv) (NºUSP 10820762)

## Introdução

## Proposta
O projeto possui o objetivo de implementar o movimento de caminhada de um robô hexapode. O hardware utilizado é composto por 12 servo motores de aeromodelismo, sendo 2 para cada perna, uma placa Toradex Viola, responsável por controlar todo o sistema, e duas MBEDS, que funcionarão como sistemas escravos controlando os servos.

## Desenvolvimento

A primeira etapa do desenvolvimento foi projetar a lógica do funcionamento do sistema, para depois programar o movimento do robô e a comunicação entre as placas. 

Como a Toradex não apresenta saídas de PWM suficientes para todos os motores, pensamos em utilizar 2 MBEDS como placas auxiliares (sistemas escravos) para controlar os motores, deixando uma delas com as pernas pares e a outra com as ímpares como mostrado na figura abaixo

![Formiga](https://user-images.githubusercontent.com/90531157/177629817-9f1fb4b1-df85-41d5-8581-431c12337dc5.jpg)

Após a definição do hardware, dividimos o projeto em duas partes, uma para desenvolver o código da movimentação e outra para desenvolver o código para a comunicação entres as três placas por meio do protocolo CAN.

### Movimentação

### Protocolo CAN

## Conclusão
