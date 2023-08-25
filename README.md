# Hefesto
Objetivo:
Este projeto tem como objetivo mitigar os riscos associados aos vazamentos de gás em ambientes residenciais, como apartamentos e casas. O foco principal é evitar explosões, incêndios e asfixia ao detectar precocemente a presença de gases perigosos, como monóxido de carbono (CO) e hidrogênio (H2), e alertar os residentes de maneira eficaz.

Componentes do Sistema:

Sensor MQ-9:
O sensor MQ-9 é fundamental para detectar gases potencialmente perigosos, como CO e H2. Ele monitora constantemente o ambiente e envia leituras ao microcontrolador.

Microcontrolador ESP32:
O ESP32 processa as leituras do sensor MQ-9 e é responsável por determinar a gravidade da situação. Ele controla o alarme e as notificações, além de poder tomar ações para prevenir riscos.

Buzzer:
O buzzer é utilizado para emitir um alarme sonoro forte e audível, alertando os ocupantes sobre a detecção de gás perigoso.

Notificações por Aplicativo:
O sistema pode ser integrado a um aplicativo móvel através da conectividade Wi-Fi do ESP32. Isso permite que os residentes sejam notificados mesmo quando não estão presentes no local.

Interrupção de Energia e Sistemas de Ventilação:
Em situações críticas, o sistema pode ser configurado para interromper a alimentação de eletrodomésticos ou interruptores, reduzindo o risco de faíscas. Além disso, pode acionar sistemas de ventilação para dissipar os gases acumulados
