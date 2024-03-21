# The Ultimate Platformer

  > Em um mundo repleto de desafios e mistérios, surge o The Ultimate Platformer, um jogo envolvente e cheio de adrenalina. Prepare-se para embarcar em uma jornada emocionante, onde cada passo pode ser um novo desafio ou um encontro com o perigo. Com Plataformas de diferentes Alturas, Obstáculos Mortais e Inimigos Traiçoeiros, cada fase é um teste de habilidade e agilidade.
Você assume o controle de um corajoso personagem, com o objetivo de alcançar a bandeira que marca o próximo nível. Mas cuidado! Cada erro pode custar uma vida, e com apenas três corações, o perigo está sempre à espreita. Explore cenários intricados, supere obstáculos desafiadores enquanto busca a vitória.
Embarque nesta aventura cheia de suspense, onde cada decisão pode ser crucial. Será você capaz de superar todos os desafios e se tornar o mestre do The Ultimate Platformer?

| |
|:-------------------------:|
|![video2](https://github.com/joseivann/jogo/assets/84510651/f25b0bfd-8eb3-467d-a4eb-6ca39b0a111d)|

## 👥 Membros da equipe:
   * Lucas Guimarães Fernandes </lgf> ([CS-LucasGuimaraes](https://github.com/CS-LucasGuimaraes))
   * Marcos Didier Oliveira Neto </mdon> ([marcosdidier](https://github.com/marcosdidier)) 
   * Fernanda Marques Neves </fmn> ([fiefaneves](https://github.com/fiefaneves))
   * Rafael Domingos Nobrega </rdn> ([]())
   * José Ivan Xisto Vilela Junior </jixvj> ([joseivann](https://github.com/joseivann))

## 🎯 Índice

| [👥 Informações-chave](#-Membros-da-equipe)
| [🎮 Instruções de execução](#-Como-Baixar-e-Jogar)
| [📖 Bibliotecas usadas](#-Bibliotecas-usadas)
| [📋 Divisão de tarefas](#-Divisão-de-tarefas)
| [👨🏻‍💻 Organização do código](#-Organização-do-código)
| [📝 Conceitos](#-Conceitos)
| [🧠 Desafios/Experiência](#-Desafios/Experiência)
| [📸 Galeria de Imagens](#-Galeria-de-Imagens) |

## 🎮 Como Baixar e Jogar

> Para rodar o jogo basta ter python e pygame instalados, baixar o zip ou clonar esse repositório e rodar o arquivo main_menu.py no diretório do arquivo.

> Desenvolvido com plataformas de diferentes Alturas, Obstáculos e Inimigos o seu objetivo principal é mover o personagem do jogador da base até a bandeira que indicará o próximo nível

> Sua vida e a quantidade de itens coletados apareceram no canto superior da tela.

**Link para o codigo fonte**: https://github.com/CS-LucasGuimaraes/Platformer.git

**Controles**:
  |            Teclas              |          Descrição           |
  | ------------------------------ | -------------------------- |
  | **W-A-S-D** | Movimento |
  | **Tecla de Espaço** | Pula |
  | **&#8592; , &#8593; , &#8594; , &#8595;** | Movimento |

## 📖 Bibliotecas usadas

 **PyGame**:
> Essa biblioteca consiste em um conjunto de módulos criados com o propósito de facilitar a criação de jogos, possibilitando o desenvolvimento de jogos e aplicativos multimídia utilizando a linguagem Python.
   
 **JSON**:
> O JSON (JavaScript Object Notation) é uma ferramenta essencial na criação de jogos simples em 2D com Python, permitindo o armazenamento e troca eficiente de dados.

## 📋 Divisão de tarefas

|            Equipe              |          Tarefas           |
| ------------------------------ | -------------------------- |
| **Lucas Guimarães** | Draw Levels, Menu, Game Over, Collectible system, Local Multiplayer, new Assets (Pixel Plataformer), JoyStick Integration, inGame User Interface, Gates System, Enemies |
| **Marcos Didier** | Draw Levels, Menu, Game Over, Collectible system, new Assets (Pixel Plataformer), Enemies |
| **Fernanda Marques** | Draw Levels, Menu, Game Over, Collectible system, Pause game, Relatório, Gates System  |
| **Rafael Domingos** | Draw Levels, Local Multiplayer, new Assets (Pixel Plataformer), Relatório |
| **José Ivan** | Draw Levels, Local Multiplayer, Relatório, new Assets (Pixel Plataformer) |

## 👨🏻‍💻 Organização do código

   **A organização do código é composta por diversas partes, sendo as principais:**

  - **data**
   > Contém os arquivos de fontes, sons, imagens, níveis e saves que serão utilizados nos códigos e vistos ao jogar.

| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
|![img1](https://github.com/joseivann/Relatorio/assets/84510651/7006f882-5288-47e0-b3ec-7590d0e39a19) | ![img2](https://github.com/joseivann/Relatorio/assets/84510651/01157b39-2e87-4a6a-b8d4-99b376ba353f) | ![img3](https://github.com/joseivann/Relatorio/assets/84510651/70c22d47-9aa1-45f5-a611-e0053045b94c) |

 - **editor.py**
  > Contém o modo editor, em que é possível adicionar, excluir e editar tiles nas diferentes fases. Essa função foi de grande relevância ao nosso trabalho pois possibilita trazer mais dinâmica e facilidade para a criação de novos níveis que explorem a criatividade e o tamanho do desafio que se deseja propor.

| | | 
|:-------------------------:|:-------------------------:|
|![img4](https://github.com/joseivann/Relatorio/assets/84510651/d85b3525-450b-46d6-ad2e-3e1897aaeaa0) | ![Gravação de Tela 2024-03-21 às 00 37 00](https://github.com/joseivann/Relatorio/assets/84510651/0a4f09ea-bf64-4e82-a62e-da3c0c40e662) |

 - **main_menu.py**
   
   > É responsável por conter a renderização do menu completo, incluindo logo e 3 botões que direcionam para o **Start, Load e Exit**.

| | | 
|:-------------------------:|:-------------------------:|
|![img5](https://github.com/joseivann/Relatorio/assets/84510651/25ce1609-118d-4cd0-8321-8c3b15eb0725) | ![img6](https://github.com/joseivann/Relatorio/assets/84510651/934eae6b-3480-4d72-a4fc-64c19bccb969) |

 - **game.py**

   > Abriga as linhas responsáveis pela renderização de nível, coletáveis e inimigos. Também contendo as funções de controle de câmera e dos processamentos de eventos.

| | | 
|:-------------------------:|:-------------------------:|
|![img7](https://github.com/joseivann/Relatorio/assets/84510651/e0e2a37e-18fd-43d5-b1e2-8d0db6609f52) | ![img8](https://github.com/joseivann/Relatorio/assets/84510651/af8e8727-ab23-4510-9bb0-2008050e8a54) |

 - **scripts**

   > Responsável por fornecer a base para o funcionamento do jogo auxiliando a execução das outras frentes de código. Abriga a estrutura dos tiles no tilemap.py e do menu em utils.py.


## 📝 Conceitos


 **Estruturas Condicionais**:
 
 -
 -
 -
 -
 -
 
  **Laços**:
> Dentro do jogo, é possível empregar essas estruturas no código através dos comandos For e While. Eles possibilitam a repetição de instruções até que uma condição seja alcançada. Dentro do jogo...
-
-
-
-

 **Loops**:

-
-
-
-
-
 

## 🧠 Desafios/Experiência

 **Maiores desafios**:

> Os grandes desafios enfrentados pela nossa equipe foi o uso de ferramentas como Pygame, Github, Programação Orientada a Objetos, dado que a maioria dos membros tinha pouca ou nenhuma experiência anterior com essas ferramentas. Além disso, a utilização dessas ferramentas era indispensável, o que nos levou a aprender o básico rapidamente para iniciar o desenvolvimento do projeto. E acabou nos proporcionando uma aprendizagem diversificada, desde a criação de elementos simples, como um quadrado móvel na tela, até a elaboração de um jogo mais complexo, que era o objetivo do nosso projeto.

 **Maiores erros cometidos**:

 > Acreditamos que um dos nossos erros significativos foi a coordenação do trabalho em equipe, quem vai fazer o que, como cada pessoa vai fazer a sua parte, a integração das partes desenvolvidas e a resolução de alguns bugs durante o processo.

 **Lições aprendidas**:

> Durante o projeto, aprendemos duas lições fundamentais. Primeiramente, compreendemos a importância do planejamento e da organização da equipe. Além disso, outro aspecto significativo que aprendemos foi a importância em reconhecer que sempre há algo a aprender e que a ajuda de outras pessoas pode ser fundamental para o progresso do projeto.


## 📸 Galeria de Imagens

| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
|![Screenshot (1)](https://github.com/joseivann/Relatorio/assets/84510651/1b8eca5e-f82a-41e6-b71c-56330fd32925) | ![Screenshot (2)](https://github.com/joseivann/Relatorio/assets/84510651/ccd4f4b5-707f-4f7d-92e8-641a29ff6800) | ![Screenshot (5)](https://github.com/joseivann/Relatorio/assets/84510651/fecf1953-76d8-44d7-a9ae-e3488644073d) |

| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
|![Screenshot (7)](https://github.com/joseivann/Relatorio/assets/84510651/d591fe5e-c80d-49c5-a335-885605a4935b) | ![Screenshot (4)](https://github.com/joseivann/Relatorio/assets/84510651/b945ef18-7fe9-433e-a8f4-349aa302cc65) | ![Screenshot (6)](https://github.com/joseivann/Relatorio/assets/84510651/de852e59-8147-4b27-abb0-bde9ed32c31e) |





