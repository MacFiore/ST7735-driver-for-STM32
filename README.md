# ST7735-driver-for-STM32
ST 7735 driver for STM32 devices. Test with NUCLEO-L476RG

Em um projeto que estou desenvolvendo com o processador STM32, surgiu a necessidade de utilizar um display de baixo custo e de fácil acesso. 
Após pesquisa, encontrei um modelo que utiliza o driver ST7735, amplamente conhecido no mercado. 
Antes de desenvolver um driver próprio, decidi buscar por soluções já prontas e confiáveis que me permitissem uma implementação rápida. 
No entanto, nenhum dos arquivos encontrados oferecia a segurança necessária para seu uso. 
Durante a busca, identifiquei um driver simples voltado para a plataforma Arduino, que, após uma análise detalhada, demonstrou ser bastante robusto. 
Assim, adaptei o código para ser utilizado com o STM32, e a implementação funcionou perfeitamente em uma placa de testes NUCLEO-L476RG. 
As conexões entre o display e a placa foram devidamente documentadas nos comentários do código.


In a project I am developing with the STM32 processor, it became necessary to use a low-cost and easily accessible display. 
After some research, I found a model that uses the ST7735 driver, which is widely known in the market. 
Before writing my own driver, I decided to search for ready-made and reliable solutions that would allow for quick implementation.
However, none of the files I found provided the necessary confidence for use. 
During the search, I identified a simple driver intended for the Arduino platform, which, after a detailed analysis, proved to be quite robust. 
I then adapted the code to work with the STM32, and the implementation worked perfectly on a NUCLEO-L476RG test board. 
The connections between the display and the board were properly documented in the code comments.
