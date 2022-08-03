# waka
Jogo Pacman que utiliza a biblioteca gráfica SFML executando sob um sistema operacional a nível de usuário.

### Dependências:

- libpng: ```sudo apt-get install libpng-dev```

- sfml: ```sudo apt-get install libsfml-dev```

### Construção:
Para compilar o código: ```make```

Para executar o código: ```./main```

Para executar valgrind: ```make valgrind```

Para limpar arquivos binários: ```make clean```

### Jogo:
Para movimentar o Pacman, deve ser utlizado as teclas **UP_ARROW_KEY**, **DOWN_ARROW_KEY**, **LEFT_ARROW_KEY**, **RIGHT_ARROW_KEY**. Para pausar o jogo, utiliza-se a tecla **P**. Para reiniciar o jogo, utiliza-se a tecla **R**. Para fechar o jogo, utiliza-se a tecla **Q**.

![Jogo](https://raw.githubusercontent.com/rafaelbcastilhos/waka/main/diagrams/Jogo.png)

### Diagramas:
Os diagramas foram elaborados utilizando o software [Visual Paradigm](https://www.visual-paradigm.com/), maiores detalhes e outros diagramas estão contidos no arquivo [pacman_diagram.vpp](https://github.com/rafaelbcastilhos/waka/blob/main/diagrams/pacman_diagram.vpp).

#### Classes:
![Classes](https://raw.githubusercontent.com/rafaelbcastilhos/waka/main/diagrams/Diagrama%20de%20Classes.jpg)

#### Casos de uso:
![Casos de uso](https://raw.githubusercontent.com/rafaelbcastilhos/waka/main/diagrams/Casos%20de%20Uso.jpg)
