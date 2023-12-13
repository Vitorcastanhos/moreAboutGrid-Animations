introdução á variáveis de cores na pseudoclasse :root

using tag figure and figcaption, never used before.

overflow-y: scroll; Faz com que o main permaneça
rolando a pagina enquanto o footer fica fixo no final. Muito bom!

aspect-ratio: 16/9, change the proportion of the image on the screen, like pinterest. cool.

header {
  --startY: -100%;
  animation: move 0.3s;
}

footer {
  --startY: 100%;
  animation: move 0.3s;
}

@keyframes move {
  from {
    transform: translateY(var(--startY));
  }
}

formas de animar a navbar e footer...