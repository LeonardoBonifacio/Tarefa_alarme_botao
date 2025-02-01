

# Tarefa6 U4: Geração de alarme para desligar leds atraves de botao

### Descrição do Projeto
Este projeto implementa a logica para que se o botão(pin 5) for apertado todos os leds são acesos e um "alarme" para cada led é ativado para eles serem desligados com 3s de diferença um do outro, e o botão so liga novamente os leds apos todos os 3 leds forem desligados(atravês da leitura se o botão foi apertado e com variáveis flags que são colocadas como false apos cada led ser desligado pelo seu proprio "alarme").


### Instruções de uso

Para rodar este código é necessário:

ter o arquivo .c e ter arquivo do cmakelist em uma pasta para que você os possa transformar em um projeto utilizando a extensão da raspberry pi pico

Você pode rodar ele :

Tanto na sua BitDogLab

Ou através da extensão wokwi pelo vs code, tendo os arquivos diagram.json  e o wokwi.toml preenchidos.

