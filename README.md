#PI II - Termômetro Inteligente com ESP32

##Descrição do Projeto Este projeto foi desenvolvido como Projeto Integrador II (PI II) da FATEC Santo André e consiste em um sistema de monitoramento de temperatura e umidade. O objetivo é demonstrar o uso do ESP32 para aquisição de dados e comunicação sem fio (Bluetooth Low Energy - BLE).

##Tecnologias e Componentes O projeto utiliza uma combinação de hardware e software para adquirir e transmitir dados:

Microcontrolador: ESP32 Super Mini C3 (para processamento e conectividade).
Sensor: DHT22 (para medição de temperatura e umidade).
Comunicação: Bluetooth Low Energy (BLE).
Linguagem: C++ (utilizada na IDE do Arduino).
##Funcionamento O código realiza a leitura dos dados do sensor DHT22 a cada 3 segundos. Se a leitura for válida, os dados de temperatura e umidade são formatados em uma string (ex: "Temp: 25.5°C | Umid: 60%") e transmitidos via BLE.

A aplicação cliente (não inclusa neste repositório) pode se conectar ao dispositivo "ESP32C3_DHT22" e ler os valores da característica UUID.
##Estrutura do Repositório

TermometroInteligente.ino: Contém o código C++ principal para o ESP32, incluindo inicialização do BLE, callbacks de conexão e lógica de leitura/notificação do sensor DHT22.
[Nome do Aluno: Kauê monteiro da silva] [Curso: Sistemas Embarcados - FATEC Santo André]
