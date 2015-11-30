#ESP8266
O objetivo desse projeto é disponibilizar um material de consulta com exemplos prontos e comentados para quem deseja se aventurar no ESP8266 utilizando o firmware NodeMCU.

###O que precisa para começar

Para começar a usar você, além do ESP8266, você precisa de um conversor usb/uart e  uma fonte de alimentação de 3.3V.
As ligações necessárias podem ser vistas na imagem abaixo.

Para usar o esp no modo de atualização de firmware, devem ser feitas as ligações em vermelho, preto e pontilhado.
Para gravação de arquivos, fazer as ligações em vermelho e preto.
Para ligar o módulo basta fazer as ligações em preto(fonte de alimentação 3,3v e o GND).


![ligacoes](https://raw.githubusercontent.com/GEEE-UEFS/ESP8266/master/images/Liga%C3%A7%C3%B5es%20ESP.png)\n

#Instalando o nodeMCU
O nodeMCU permite a programação via scripts em Lua.
Download do nodeMCU-flasher para: 
	-Windowns de 32 bits https://github.com/nodemcu/nodemcu-flasher/tree/master/Win32/Release
	-Windowns de 64 bits https://github.com/nodemcu/nodemcu-flasher/tree/master/Win64/Release

Clique no botão Flash(F).
![Instalando1](https://raw.githubusercontent.com/GEEE-UEFS/ESP8266/master/images/1.png)
Espere até o processo ser concluido.
![Instalando2](https://raw.githubusercontent.com/GEEE-UEFS/ESP8266/master/images/2.png)
Quando aparecer o símbolo de confirmado na parte inferior da janela ao lado da frase "NODEMCU TEAM" significa que o firmware foi atualizado.
![Instalando3](https://raw.githubusercontent.com/GEEE-UEFS/ESP8266/master/images/3.png)
Na aba "Config" estará desse jeito.
![Instalando4](https://raw.githubusercontent.com/GEEE-UEFS/ESP8266/master/images/4.png)

###Bibliotecas Disponiveis
#####GPIO

#####WIFI
