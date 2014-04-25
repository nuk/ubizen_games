uClue é uma variação do jogo [Detetive](http://pt.wikipedia.org/wiki/Detetive_(jogo))

História
============

```
História também é conhecida como Narrativa. 
Ela define a sequencia de eventos do jogo. 
Também define a motivação daqueles que jogam ou razão por trás do jogo.
```


Num momento de descontração sua você recebe uma mensagem em seu celular. Dona Maria, velha conhecida, pede a sua ajuda de maneira urgente.
Sem mais informações, você apenas sabe que é uma questão de vida ou morte.
Dona Maria te solicita que vá a sua casa o mais rápido possível.
Ao chegar lá você se depara com outros conhecidos que receberam o mesmo e parecem tão perdidos como você.
Entrando na casa vocês encontram Dona Maria que os convida a entrar. 
Sem esperar, as luzes se apagam, barulhos diversos percorrem o ambiente.
Você se assusta.
Ao se acender as luzes, vocês notam que Dona Maria sumiu.
As portas da casa se encontram fechadas.
Cabe a você descobrir o que aconteceu.
Não confie em ninguém.
E boa sorte.



Estética
============
```
A Estética (ou Interface) define como o jogo estimula os sentidos do Jogador trazendo imersão a realidade criada.
```

O jogo se utiliza de da troca de mensagens textuais para informar o que está acontecendo no jogo. O uso de textos é limitante a imersão, mas possibilita que dados individuais e públicos sejam trocados de forma adequada.
Sons são utilizados para informar os locais onde os eventos ocorrem na casa. A utilização de um estímulo auditivo causa uma maior imersão, simulando a ocorrência dos eventos dentro da casa. 
Por fim, um retorno tátil (vibração) é usado para eventos de maior impacto (como a queda de um objeto pesado, ou o fechar de uma porta).



Mecânica
============
```
A Mecânica define as regras do jogo. 
Como os elementos interagem entre si.
Como se progride no jogo.
Como se ganha ou perde.
```

A cada 1 minuto, um evento ocorre em algum dos cômodos da casa. Dispositivos fixos (como PCs e Laptops) representam estes locais. Os jogadores devem correr até aquele cômodo pois na tela correspondente terá uma pegunta para ser respondida. Essa pergunta tem por objetivo comprovar que o jogador chegou aquele local a tempo. 

O primeiro jogador a chegar recebe duas dicas, enquanto os demais recebem apenas uma. Se o jogador chegar após 30 segundos ele não receceberá nenhuma dica sobre o que ocorreu naquele ambiente. 

As dicas informam sobre pedaços da história que aconteceram naquele ambiente no momento que as luzes se apagaram. Pode ser quem estava naquele local, ou um objeto que alí se encontra.

A qualquer momento o jogador pode digitar a sequencia da solução do mistério composta por Local, Pessoa e Objeto que acredita que ocasionaram o crime. Se o jogador acertar, ele ganha o jogo. Caso contrário, os demais jogadores ganham uma pista extra.




Tecnologia
============
```
A tecnologia define como o jogo é operacionalizado.
Como o mundo virtual criado é mapeado no mundo real.
```
O Jogo consiste em uma aplicação executando em um dispositivo fixo no ambiente (como um PC). Ele se comunica com os recursos presentes nos demais dispositivos para a execução da experiência do jogo.


- *Ambiente* : O Jogo pode ser realizado em qualquer ambiente contendo os dispositivos necessários. É aconselhado que se jogue em ambientes fechados devido a presença de PCs e Laptops. A existência de outros cômodos torna a experiẽncia mais rica e dinâmica. Para os testes iniciais, usaremos o laboratório Laico onde temos a presença dos dispositivos necessários para a execução do jogo.
- *Dispositivos* : O Jogo se baseia em dois tipos de dispositivos:
 - *PCs e Laptops* : Que representam os locais do jogo. Eles devem possuir recursos de **console** e de **som**.
 - *Celulares* : Representam os jogadores. Eles devem possuir os recursos de **console** e de **retorno tátil** usado para interagir com os jogadores.
- *Recursos e Serviços* :
 - *Console*: Permite a interação textual dos jogadores.
  - Serviço de *Imprimir Mensagem* : Exibe uma mensagem textual na tela desejada de forma síncrona.
  - Serviço de *Emitir Mensagem* : Emite uma mensagem textual de forma assíncrona. A mensagem deve ser digitada no dispositivo alvo.
 - *Som*:
  - Serviço de *Tocar Som* : Reproduz um arquivo de audio de forma síncrona no dispositivo desejado.
 - *Retorno Tátil*:
  - Serviço de *Vibrar* : Emite uma vibração na intensidade desejada de forma síncrona.
