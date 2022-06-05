# Integração de arduino com IHM e FACTORY I/O
---

## Lista de equipamentos:

1.  1 Arduino UNO
2.  1 Ethernet Shield W5100
3.  6 Resistores 300 OHM
4.  6 Leds 5 volts
5.  2 Push Button
6.  1 Protoboard
7.  Cabos e Jumpers
8.  1 IHM Modelo WEINTEK MT807ip de 7"
9.  1 Switch de rede industrial
10.  Cabos de rede
11.  1 Fonte de alimentação bivolt com saída de 24 vcc
12.  Simulador de fabrica "FACTORY I/O"
13.  Notebook
14.  Cabo HDMI
---

![Projeto](./IMAGENS/projeto.jpg)

## Descrição do projeto

O projeto tem como objetivo integrar o Arduino com a IHM e o software FACTORY I/O, utilizando protocolo de comunicação Modbus Ethernet através das portas RJ45 dos nossos equipamentos. Com tudo configurado e funcionando, foi o possível demonstrar as grandes características didáticas embarcadas do FACTORY I/O, trazendo a possibilidade de simular equipamentos industriais tais como sensores, esteiras, atuadores, botões, sinaleiros, motores etc. O projeto foi um sucesso, funcionou como planejado, conseguimos demonstrar a virtualização de maneira muito realista sendo possível comandar e monitorar dados através da nossa IHM, que é um equipamento físico, nossos botões e leds que também eram componentes físicos, gerando redundância de 3 possibilidades de controle também sendo funcional pelo painel do operador agregado no software simulador de fábrica. Com tudo dito, foi possível ligar e desligar o processo virtual através da IHM, botão ligado no Arduino e botões virtuais. O mesmo para monitorar os dados do processo como os inputs e outputs, havendo possibilidade de monitorar pela IHM física, pelos leds físicos na protoboard e pelo FACTORY I/O virtual. A construção do projeto exigiu muito de todos os parceiros do grupo, trazendo como consequência grandes conhecimentos para nossa evolução. 

