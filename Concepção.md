
# Concepção

O nosso objetivo desse projeto, é fazer um sistema de automação residencial que de maneira inteligente e integrada, que consiga trazer mais benefícios tanto de comodidade, segurança e economia de energia para o cliente.

### Objetivos do projeto:

* Uma breve previsão meteorológica. (Utilizaremos o "Sensor DHT" p/ a medição da temperatura e umidade, o "Módulo Sensor de Nível Água Chuva" p/ pedir quantos mm de chuva caíram e aparecerá no Display ou na Matriz de Led)
* Sistemas de segurança contra alagamentos e vazamento de gases. (Para alagamentos, quando passar de um certa medida {utilizando o "Módulo Sensor de Nível de Água Chuva"} de mm de água, o buzzer ira produzir um som e em seguida aparecerá o alerta escrito no display. Para o vazamento de gases utilizaremos o "Sensor MQ-2", o qual vai acionar um alerta com o buzzer, acionara o "Módulo Relé" para acionar um cooler {gerar a circulção do ar})
* Abrir/Fechar janelas da casa, tanto para dias com muita chuva, quanto para o vazamento de gases. (Vão ser utilizados Servos para controlar as janelas, a identifiação dos dias chuvosos vai ser feita pelo item nº1, e vazamento de gases item nº3)
* Controle de iluminação remotamente ou automaticamente. (Realizada por leds, onde serão ativadas/desativadas de acordo com o "Sensor de movimento PIR".
* Guia para o estacionamento do veículo. (Estaremos utilizando o "Sensor Ultrassônico HC-SR04", a "Matriz de Led" e o "Buzzer". O ultrassonico irá medir a distancia do carro em relação a parede, quando o carro vai se aproximando, a matriz de led vai acendendo de baixo para cima e o buzzer vai aumentando a frequência do som)
* Todos os acionamentos importantes, serão avisados com um "alarme".
* Display LCD mostrando as informações relevantes do sistema.


### Componentes Eletrônicos:

* Placa MEGA 2560 R3 + Fonte + Cabo USB p/ Arduino
 
![MEGA 2560](https://www.filipeflop.com/wp-content/uploads/2017/07/1AC04-1.jpg)

https://www.filipeflop.com/produto/placa-mega-2560-r3-cabo-usb-para-arduino/

* Sensor de Umidade e Temperatura DHT11
 
![DHT11](https://www.filipeflop.com/wp-content/uploads/2017/07/Dht11.jpg)

https://www.filipeflop.com/blog/monitorando-temperatura-e-umidade-com-o-sensor-dht11/

* Sensor de presença e movimento PIR
 
![PIR](https://www.filipeflop.com/wp-content/uploads/2017/07/1220801-2.jpg)

https://www.filipeflop.com/produto/sensor-de-movimento-presenca-pir/

* Sensor de gás MQ-2 inflamável e fumaça
 
![MQ2](https://www.filipeflop.com/wp-content/uploads/2017/07/sku_193001_2.png)

https://www.filipeflop.com/produto/sensor-de-gas-mq-2-inflamavel-e-fumaca/

* Micro Servo SG92R 9g TowerPro
 
![SERVO](https://cdn.awsli.com.br/600x450/535/535286/produto/121183340/f853b364ba.jpg)

https://www.filipeflop.com/produto/micro-servo-sg92r-9g-towerpro/

* Módulo Sensor de Umidade/Nível Água Chuva

![NIVELAGUA](https://www.eletronicacastro.com.br/21212-large_default/modulo-sensor-de-umidade-nivel-agua-chuva-ardui.jpg)

https://www.filipeflop.com/produto/sensor-de-agua/

* Módulo  Relé 5V e um Canal
 
![rele](https://www.filipeflop.com/wp-content/uploads/2017/07/SKU099653h.jpg)

https://www.filipeflop.com/produto/modulo-rele-5v-1-canal/

* Sensor ultrasônico HC-SR04
 
![ultrassonico](https://cdn.awsli.com.br/600x700/78/78150/produto/2888532/62bc744cec.jpg)

https://www.filipeflop.com/blog/sensor-ultrassonico-hc-sr04-ao-arduino/

* Módulo Matriz de LED 8x8 com MAX7219
 
![matrizled](https://www.usinainfo.com.br/1017274-thickbox_default/modulo-matriz-de-led-8x8-vermelho-max7219-jumpers.jpg)

https://www.filipeflop.com/produto/modulo-4-matrizes-de-led-8x8-com-max7219/

* Buzzer passivo
 
![buzzer](https://www.filipeflop.com/wp-content/uploads/2017/07/2-142.jpg)

https://www.filipeflop.com/produto/modulo-buzzer-5v-ativo/

* Display LCD 16x2 I2C Backlight Azul

![display](https://cdn.awsli.com.br/600x700/468/468162/produto/19414150/display-lcd-16x2-i2c-backlight-azul-7ff37942.jpg)

https://www.filipeflop.com/produto/display-lcd-16x2-backlight-verde/

