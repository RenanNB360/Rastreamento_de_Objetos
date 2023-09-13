<h2>Rastreamento de Objetos<h2/>
  
<h3>Descrição do projeto:</h3>

Este projeto tem por intuito testar algumas funções especificas para rastreamento de objetos da biblioteca do OpenCV em python.

<h3>Preparando o ambiente</h3>

As bibliotecas do OpenCV, do OpenCV-Contrib e do Numpy precisam ser instaladas

~~~python
pip install opencv-python
pip install opencv-contrib-python
~~~

<h3>Como executar o código</h3>

Após colocar o mesmo para rodar selecione o objeto a ser rastreado, após presciona a tecla de espaço e acompanhe o rastreamento

<h3>Resultado do Rastreador MIL</h3>

![MIL](https://github.com/RenanNB360/Rastreamento_de_Objetos/assets/87036785/628f174e-c4bd-4d5a-b708-901f340dc98c)

Para o determinado video analisado, tivemos uma performance ruim pois a pessoa teve um deslocamento brusco no video e 
como este rastreador não possui uma precisão alta o mesmo não conseguiu efetuar este processo.
