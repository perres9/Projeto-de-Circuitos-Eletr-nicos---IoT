Controle de Temperatura Automatizado com Arduino
Este projeto consiste em um sistema de monitoramento térmico desenvolvido no Tinkercad. Ele foi projetado para simular o controle de um ambiente onde o resfriamento e os alertas de segurança são automatizados com base na leitura de um sensor de temperatura.

O sistema opera em três níveis de estado:

Normal: Monitoramento constante via Monitor Serial.

Resfriamento Ativo: O ventilador (Motor CC) é acionado quando a temperatura atinge o primeiro limiar.

Alerta Crítico: Um LED e uma buzina (alarme sonoro) são ativados caso a temperatura atinja níveis de risco.
-------Componentes Utilizados--------------
Microcontrolador: Arduino Uno R3.

Sensor de Temperatura: TMP36 (Analógico).

Atuador de Resfriamento: Motor CC (Simulando um ventilador).

Alerta Visual: LED Vermelho.

Alerta Sonoro: Piezo Buzzer.
-------Especificações Técnicas--------------
Linguagem: C++ (Arduino Framework). 
Comunicação: Serial via USB (9600 baud) para telemetria de dados.Lógica de Controle:Pino 9 (Ventilador): Ativado quando a leitura analógica for >= 164.
Pinos 1 e 3 (Alerta): Ativados quando a leitura analógica for >= 207.
