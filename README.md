# maquete-cisi
Repositório central da maquete do CISI desenvolvida para a prova de automação da gincana da Unipar

## Objetivo 1: Montar uma maquete que permita instalar e demonstrar as funcionalidades da solução apresentada pela equipe.
(foto da maquete aqui)

## Objetivo 2: Apresentar o orçamento para a instalação da solução proposta para funcionamento em situação real.
(link do google docs aqui)

## Objetivo 3: Apresentar o esquema elétrico/eletrônico da solução proposta.
(link para o arquivo aqui)

## Objetivo 4: Apresentar o código desenvolvido.
### App para controle da maquete
Aplicativo desenvolvido em React Native para os sistemas operacionais Android e iOS. [Link do repositório](https://github.com/GusAntoniassi/maquete-cisi-app)

### Servidor de mensagens
Servidor desenvolvido em NodeJS / Expressive com um serviço de WebSockets para a comunicação entre os dispositivos móveis e o dispositivo de controle da maquete. [Link do repositório](https://github.com/GusAntoniassi/maquete-cisi-node-server)

### Aplicação para gerenciamento do hardware (Raspberry Pi)
Aplicação desenvolvida em NodeJS para controle do Arduino e da tela LCD através do protocolo SPI. Recebe e trata as mensagens enviadas pelo servidor central. Também realiza a leitura do sensor de temperatura DHT11 para exibir a temperatura ambiente no display LCD. [Link do repositório](https://github.com/GusAntoniassi/maquete-cisi-node-raspi)

### Firmware para controle dos componentes (Arduino)
Firmware desenvolvido em C para Arduino com o objetivo de acionar os módulos relês para controle das luzes, acionar o motor de trava da porta e emitir os sons de controle do ar condicionado. [Link do repositório](https://github.com/GusAntoniassi/maquete-cisi-arduino)

## Objetivo 5: Demonstrar todas as funcionalidades propostas, tanto em relação ao acesso como quanto ao controle do mesmo (nome, horário, etc).
Será realizada a demonstração em sala de aula. (Ver pra anexar o vídeo aqui depois)

## Objetivo 6: Demonstrar o relatório com acesso via Web sobre os dados coletados.
O log de acesso está disponível [clicando aqui](http://18.231.50.4:5000/logs), e demonstra todas as alterações que foram realizadas na maquete no formato JSON, junto com a data e hora da alteração e o endereço IP do usuário que acionou um determinado controle.
