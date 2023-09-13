<h2>Rastreamento de Objetos<h2/>
  
<h3>Descrição do Projeto:</h3>

Este projeto tem por intuito testar algumas funções especificas para rastreamento de objetos da biblioteca do OpenCV em python.

<h3>Preparando o ambiente</h3>

As bibliotecas do OpenCV e do OpenCV-Contrib precisam ser instaladas.

~~~python
pip install opencv-python
pip install opencv-contrib-python
~~~

<h3>Como executar o código</h3>

![selecao](https://github.com/RenanNB360/Rastreamento_de_Objetos/assets/87036785/b191bd8a-3537-48f7-b166-7ec9ae4be057)

Após colocar o mesmo para rodar selecione o objeto a ser rastreado e após pressionar a tecla de espaço e acompanhe o rastreamento.

<h3>Resultado do Rastreador MIL</h3>

![MIL](https://github.com/RenanNB360/Rastreamento_de_Objetos/assets/87036785/628f174e-c4bd-4d5a-b708-901f340dc98c)

Para o determinado video analisado, tivemos um desempenho ruim, pois a pessoa teve um deslocamento brusco no video e 
como este rastreador não possui uma precisão alta, o mesmo não conseguiu efetuar este processo.

<h3>Resultado do Rastreador KCF</h3>

![KCF](https://github.com/RenanNB360/Rastreamento_de_Objetos/assets/87036785/0b954e0a-f021-493a-a16c-349d469efe24)

Para esta implementação da função KCF, onde temos uma correlação através do kernel, tivemos um bom desempenho apesar do mesmo não ser
robusto também. Este resultado também estava mais acelerado, mostrando que a precisão pode não ser tão alta.

<h3>Resultado do Rastreador CSRT</h3>

![CSRT](https://github.com/RenanNB360/Rastreamento_de_Objetos/assets/87036785/59d9bd26-bc9f-4d75-beed-124c3871f947)

Já para o CSRT, tivemos o melhor resultado dentre todos, pois sua precisão é melhor, tornando o video um pouco mais lento.
Sendo uma implementação mais robusta, pois trabalha com o filtro de Correlação Discriminativa. 
