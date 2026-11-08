# Age of Knights

Jogo de estratégia em tempo real no browser, inspirado em Age of Empires, com mundo aberto, construção de cidade e acampamentos inimigos que aparecem e enviam raids à medida que evoluis.

## Como jogar
Abre o `index.html` num browser (ou usa o GitHub Pages deste repositório). Funciona em telemóvel e computador.

- Arrasta para mover o mapa, pinça (ou ＋/－) para zoom.
- Toca numa unidade para a selecionar (2 toques seleciona todas as iguais no ecrã).
- Aldeões recolhem madeira, comida, ouro e pedra e constroem edifícios.
- Treina tropas no Quartel e destrói 12 acampamentos inimigos para vencer.

## Dificuldade
Fácil, Moderada ou Difícil — escolhe no início e muda a qualquer momento no menu ☰.
- **Fácil:** raids pequenas e espaçadas.
- **Moderada:** raids em grupo que evitam as tuas defesas e escolhem alvos com vantagem.
- **Difícil:** raids maiores que contrariam o teu exército, caçam aldeões e recuam quando perdem.

## Mods
No ecrã inicial podes ligar mods (combináveis): ×3 recursos coletados, ×3 população dada pelas casas (máx. 200) e ×3 velocidade de construção.

## Controlos
**Telemóvel:** toca para selecionar e dar ordens · toque longo + arrastar = seleção em caixa · pinça = zoom.

**PC (estilo Age of Empires):** clique esquerdo seleciona (arrastar = caixa, Shift = juntar, duplo clique = todos iguais) · clique direito dá ordens · WASD/setas ou rato na borda move a câmara · roda = zoom.

| Tecla | Ação |
|---|---|
| B | Construir |
| H | Centro da Cidade |
| . / , | Aldeão / tropa parada seguinte |
| Ctrl+1–9 / 1–9 | Criar / escolher grupo |
| Espaço | Ir à seleção |
| Q E R T F G Z X C V | Botões do painel |
| Tab | Mudar categoria (Construir) |
| Delete | Apagar seleção |
| P / F3 | Pausa |
| Esc / F10 | Cancelar / Menu |

## Raças
Humanos, Orcs, Elfos, Goblins e Anões — cada uma com bónus próprios.

## Unidades e vantagens
| Unidade | Era | Forte contra | Fraca contra |
|---|---|---|---|
| Lanceiro | I | Cavalaria | Arqueiro, Espadachim |
| Espadachim | I | Lanceiro, edifícios | Besteiro, Cavalaria |
| Espadachim Longo | II | Espadachim, Lanceiro (golpe em área) | Arqueiro, Besteiro |
| Arqueiro | I | Lanceiro, Mago | Cavalaria, Espadachim |
| Besteiro | II | Espadachim | Mago, Cavalaria |
| Espadachim a Cavalo | II | Arqueiro, Besteiro, Mago | Lanceiro |
| Mago | III | Besteiro, grupos (dano em área) | Cavalaria, Arqueiro |

## Muralhas e portões
Muralhas de madeira (Era I) e de pedra (Era II), com o estilo de cada raça. Os portões deixam passar as tuas tropas mas não os inimigos — se não houver caminho, eles partem a muralha.

## Ferreiro
Melhora as tropas (ataque corpo-a-corpo, arcos e bestas, armaduras, magia e têmpera das armas) e os aldeões (ferramentas, mochilas e martelos). Cada melhoria tem 3 níveis; os níveis 2 e 3 precisam da Era II e Era III.

## Armas
Em combate as armas podem partir-se. A unidade desarmada luta à murro e vai buscar a arma de um corpo caído ou rouba-a ao inimigo. A arma decide o estilo de luta (ex.: cavaleiro com arco = arqueiro a cavalo). Os corpos desaparecem ao fim de 30 segundos.

## Interface
Barra de baixo com Construir, Aldeões, Exército, Base e Menu. Ícones e efeitos (sangue, fumo, pó, fogo, magia) em pixel art; o sangue pode ser desligado no Menu.

## Ficheiros
- `index.html` — o jogo completo
- `sprites/` — sprites das unidades, edifícios, muralhas, recursos e terreno
- `icons/` — ícones da interface
- `fx/` — efeitos visuais
