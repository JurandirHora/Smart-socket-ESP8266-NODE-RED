
Atualizei o arquivo do codigo, porque encontrei um erro, faltava uma # antes do define na linha #define CLIENT_ID "client1" e causava um erro na hora de compilar.Agora compila sem erro


I updated the code file, because I encountered an error, it was missing the # before set in line #define CLIENT_ID "client1" and caused an error when compiling. Now work fine

Using this code you can use an ESP8266, and a DHT11 temperature sensor, to publish and subscribe to a topic on an MQTT (Broker) server 
by sending the temperature and humidity data of the place on the DHT11 to the broker, and subscribing the topic To receive this
information, the information will be received in the node-red, and you can create two gauges to observe in an interface (UI) the data
value, temperature and humidity. I also put in the code, a potentiometer, which would publish its value too, and you can also visualize
the value of it in a gauge, I called this potentiometer, SeTPoint, and in the code, I made an equation that allows you to adjust the value
of it , So if the temperature exceeds the value determined by you with the potentiometer, it will trigger a GPIO output of the ESP8266, 
I used the GPIO D2, and I connected it to the base of a transistor, and the collector of this transistor will drive the coil of a
Relay module, this relay can trigger a load that could be a fan, or a heater, depends on what you want to trigger.

Link video youtube https://youtu.be/uKdEMALlciI 

Let me know if you have any doubts about using this code, I'll respond as soon as possible.


Usando este codigo você podera usar um ESP8266, e um sensor de teperatura DHT11, publicar e assinar um topico em um servidor MQTT (Broker) 
enviando os dados de temperatura e umidade do local on de ensontra o DHT11 para o broker, e assinando o topico para receber esta infomação,
a informação sera recebida no node-red, e você podera criar dois gauges para observar em uma interface (UI) o valor dos dados, temperatura
e umidade.

Eu também coloquei no codigo, um potenciometro, que publicara seu valor também, e você também podera visualizar o valor dele em um gauge,
eu chamei este potenciometro, de SeTPoint, e no codigo, fiz uma equação que permite que você ajuste o valor dele, de modo que, 
se a temperatura ultrapassar o valor determiando por você com o potenciometro, ele acionara uma saida GPIO do ESP8266, eu usei o GPIO D2,
e liguei na base de um transistor, e o coletor deste transistor acionara a bobina de um modulo rele, este relay pode acionar uma
carga que poderia ser um ventilador, ou um aquecedor, depende do que quer acionar .

Caso exista duvidas sobre o uso deste codigo, deixe-me saber, responderei o mais breve possivel. 
Link video youtube https://youtu.be/uKdEMALlciI 
