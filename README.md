Este codigo implementa a logica para que se o botão for apertado todos os leds são acesos e um "alarme" para cada led é ativado para eles serem desligados com 3s de diferença um do outro, e o botão so liga novamente os leds apos todos os 3 forem desligados(atravês da leitura se o botão foi apertado e com variáveis flags que são colocadas como false apos cada led ser desligado pelo seu proprio "alarme").

Para rodar este código é necessário ter o arquivo .c e o arquivo do cmakelist em uma pasta para que logo apos você utilize a extensão da raspberry pico para importar este projeto e poder compilá - lo e rodar tanto na sua BitDogLab(colocando dentro do cmakelist "pico_enable_stdio_usb(UC4_TAREFA6 1)" esta configuração) ou através da extensão wokwi pelo vs code, tendo os arquivos diagram.json  e o wokwi.toml preenchidos.