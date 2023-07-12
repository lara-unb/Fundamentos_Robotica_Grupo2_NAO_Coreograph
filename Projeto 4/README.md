# Projeto 4

## Introdução
Para essa implementação foi requisitado que o NAO identificasse, algum obstáculo à sua frente, estando essa obstáculo à sua frente, a sua direita ou à sua esquerda, depois de localizado a direção que se encontra o seu obstáculo. o NAO usando a sua função fala indicaria a presença de obstáculos à sua frente.

## Ideia
Para a realização dessa interação foi necessário a utilização correta dos sensores dispostos na parte frontal do NAO.

<p align="center">
  <img width="423" height="621" src= img41.png title="Eye Led">
  <h6 align="center">Eye Led</h6>
</p>

Cada sensor localiza o objeto a frente, se o objeto estiver frontalmente ao Robô, o sensor frontal indicará a presença de algo, se os demais sensores forem ativados o sensor da esquerda ou o sensor da direita estará ativado.


## Implementação

Nessa implementação o diagrama de blocos de programação usados foram os Utilizados na imagem abaixo.

<p align="center">
  <img width="750" height="457" src= img42.png title="Eye Led">
  <h6 align="center">Eye Led</h6>
</p>

Identificado os parâmetros do sonar(alcance de detecção) foi realizado o conexão do bloco sonar com o bloco say(fala),para depois da detecção do obstáculo pelo sonar o NAO indicaria presença do mesmo, falando pelo comando say se o obstáculo está a sua frente, ou a direita, ou à esquerda


## Conclusão
A interação Reconhecimento de Obstáculos se mostrou satisfatória, tendo o NAO realizado a mesma com êxito, pois os comandos solicitados foram devidamente assertivos narealização da ação.

## Vídeo
[Clique aqui para assistir o vídeo](https://www.youtube.com/watch?v=ipwHjoswMEE)
