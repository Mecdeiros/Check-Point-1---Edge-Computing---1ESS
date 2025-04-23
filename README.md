# Check-Point-1---Edge-Computing---1ESS
Grupo: 
Guilherme de Medeiros RM:561699
Victor Pucci Ferreira RM:561736
Mikael de Albuquerque Santana RM:
Murilo Henrique Vieira da Cruz RM:
Otávio Magno da Silva RM:

Explicação do projeto:
O que é isso aqui?
Esse projeto é tipo um alarme que monitora a luz no ambiente onde os vinhos são guardados. A ideia é proteger o vinho da luz demais (que estraga ele), usando um sensor de luz (LDR), LEDs e um buzzer (buzina). Tudo isso feito com Arduino.

Como funciona?
O sensor LDR mede a quantidade de luz no ambiente.

O Arduino pega esse valor e verifica se está:

Boa - Acende LED verde.

Meia-boca (alerta) - Acende LED amarelo e toca uma buzina por 3 segundos.

Ruim (muita luz) - Acende LED vermelho (mas a buzina não toca).

O sistema checa a luz de tempo em tempo e atualiza tudo sozinho.

O que foi usado?
1 Arduino Uno
1 sensor LDR
4 resistores (para os LEDs e a LDR)
3 LEDs (vermelho, amarelo, verde)
1 buzzer
1 protoboard + cabos jumper

Link do Tinkercard:
https://www.tinkercad.com/things/566L7d2xBXK/editel?sharecode=PijT7flvNV9pO3pCSQptTz4c5qvasQWv-7FYI6z4Dyk
