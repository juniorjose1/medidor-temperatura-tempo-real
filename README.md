# PROJETO FINALIZADO

## Funcionamento e Tecnologias
<p>O Projeto foi desenvolvido com o propósito de exibir um medidor de temperatura em tempo real.</p>
<p>Foi utilizado Arduino para ler a temperatura através de um sensor, e criado um programa em JavaScript para se comunicar com a porta do Arduino e ler os valores que o Arduino estava captando, que no caso seriam as temperaturas.</p>
<p>E quando esses valores fossem lido pelo JavaScript teria que ser exibido de alguma forma para o usuário, e que no caso, foi desenvolvido um arquivo .html para exibir esses valores em forma de gráfico.</p>
<p>Foi criado um arquivo index.js que representa o servidor em que recebe os valores do Arduino e faz a comunicação com o arquivo index.html que fica dentro da pasta public, passando os valores, e exibindo em gráfico com o auxílio da biblioteca Chart.js</p>
<p>Conforme a imagem abaixo da tela principal do programa, temos a temperatura na linha vertical e os segundos na linha horizontal</p>
<img src="http://alejunqueira.com.br/img/medidor-temperatura.png" width="600">
