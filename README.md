<p align="center">
  <img src="Trabalho/TelaInicial.jpg" alt="Capa principal do jogo" width="400">
</p>
<h1>Legend of Zelda: A link to the future</h1>

## Índice

- [Descrição do projeto](#descrição-do-projeto)
- [História](#história)
- [Funcionalidades](#funcionalidades)
- [Demonstração da aplicação](#demonstração-da-aplicação)
- [Como rodar a aplicação](#como-rodar-a-aplicação)
- [Desenvolvedores](#desenvolvedores)

## Descrição do projeto
<p align="justify"> Projeto para o trabalho final da matéria "Introdução aos sistemas computacionais" da Universidade de Brasília. Foi desenvolvido um jogo inteiramente em Assembly RISC-V, explorando conceitos fundamentais de programação de baixo nível, lógica computacional, manipulação direta de memória e desenvolvimento de jogos. A história foi inspirada em "The Legend of Zelda", jogo lançado em 1986 pela Nintendo, e traz uma releitura futurista aos combates épicos da saga. </p>

## História
<p align="justify">Baseada no conceito de que Link e Zelda sempre renascem para combater o mal de Ganon, esta releitura busca transportar essa história para um cenário futurista. Nela, Zelda está em uma missão final para hackear e destruir o sistema que alimenta o mal na cidade. No entanto, para que isso seja possível, ela precisa que Link entre no castelo e destrua as defesas internas. O jogo conta com cutscenes no início para contextualizar a narrativa e aumentar a imersão do jogador com esse universo.</p>

## Funcionalidades
- **Movimentação:** Controle por WASD, com verificação de limites de tela e colisão  
- **Combate:** Sistema de ataque e defesa  
- **Vida:** Sistema de corações com feedback visual ao receber dano  
- **Inimigos:** Drone com dano de contato e torre que dispara projéteis  
- **Loja:** Verificação de quantidade de moedas e compra de itens  
- **Inventário:** Coleta de moedas e animação especial ao obter itens  
- **HUD:** Informações de moedas, vida, inventário e fase  
- **Puzzle:** Quebra-cabeça lógico sobre conversão de bases numéricas  
- **Música:** Músicas completas em loop na tela inicial e nas fases, além de efeitos sonoros  

<sub>→ Na pasta de tutoriais há sugestões de como fazer a música e a conversão de imagens</sub>

## Demonstração da aplicação
###Inserir vídeo

## Como rodar a aplicação
<p align="justify">Como o FPGRars já está dentro da pasta do jogo nesse repositório, não é necessária sua instalação.
Talvez seja necessária a instalação de Java para rodar o FPGRars</p>

Para rodar o jogo, baixe os arquivos desse repositório, acesse seu prompt de comando a partir da pasta 'Trabalho' (mesma pasta em que o FPGRars está) e rode o comando 
```bash
fpgrars.exe dataset\trabalho.asm -w 640 -h 480 -s 1
```

<sub> 
- <code>-w 640</code> e <code>-h 480</code> definem a resolução maior que o padrão 240x320. Nosso grupo optou por aumentar a resolução do jogo para permitir maior detalhamento nas artes
- <code>-s 1</code> reduz a proporção do jogo para caber em telas menores, como a do meu notebook 
</sub>

## Desenvolvedores
- [João Lucas de Andrade](https://github.com/Sespiny)
- Isabela Honda 
- [Michele Aiko](https://github.com/michele-aiko)
- Mariana Souza

