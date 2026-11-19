# Trabalho A2 — Operações Vetoriais com p5.js

Atividade da disciplina de Matemática e Física para Jogos de SMD - UFC

Docente: Gilvan Maia

## Objetivo
O trabalho tem duas partes:

### Parte 1 — Operações entre vetores (10 pontos)
Implementar, em uma **classe de vetor própria**, as operações:
soma, subtração, inverso (−v), multiplicação por escalar, produto escalar (`dot`),
produto vetorial (`cross`), tamanho, projeção, deslizar e reflexão.

> Regra: nesta parte **não** é permitido usar bibliotecas de vetor prontas
> (como o `createVector()` do p5.js). A ideia é criar a própria classe e
> aprender com isso.

### Parte 2 — Visualizador da soma vetorial (2 pontos)
Um programa gráfico que mostra que a **soma de N vetores não depende da ordem**:
o caminho muda, mas o ponto final é sempre o mesmo.

## Linguagem e ferramenta
- **Linguagem:** JavaScript
- **Biblioteca:** [p5.js](https://p5js.org) (desenho em canvas)

## Como executar
1. Acesse o editor online: https://editor.p5js.org
2. Apague o conteúdo da aba **sketch.js** e cole o código do arquivo `.txt`.
3. Clique em **Play (▶)**.
   - A **Parte 1** imprime os resultados das operações no **console**
     (abra com o ícone `>_` no rodapé do editor, ou aperte F12).
   - A **Parte 2** é o visualizador que aparece no canvas.

## Controles do visualizador (Parte 2)
- **Clique do mouse** — adiciona um vetor (da ponta atual até o cursor)
- **R** — gera vetores aleatórios
- **E** — embaralha a ordem da soma
- **C** — limpa a tela
