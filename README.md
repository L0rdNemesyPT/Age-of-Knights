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

## Raças
Humanos, Orcs, Elfos, Goblins e Anões — cada uma com bónus próprios.

## Unidades e vantagens
| Unidade | Era | Forte contra | Fraca contra |
|---|---|---|---|
| Lanceiro | I | Cavalaria | Arqueiro, Espadachim |
| Espadachim | I | Lanceiro, edifícios | Besteiro, Cavalaria |
| Arqueiro | I | Lanceiro, Mago | Cavalaria, Espadachim |
| Besteiro | II | Espadachim | Mago, Cavalaria |
| Espadachim a Cavalo | II | Arqueiro, Besteiro, Mago | Lanceiro |
| Mago | III | Besteiro, grupos (dano em área) | Cavalaria, Arqueiro |

## Ferreiro
Melhora as tropas (ataque corpo-a-corpo, arcos e bestas, armaduras, magia e têmpera das armas) e os aldeões (ferramentas, mochilas e martelos). Cada melhoria tem 3 níveis; os níveis 2 e 3 precisam da Era II e Era III.

## Armas
Em combate as armas podem partir-se. A unidade desarmada luta à murro e vai buscar a arma de um corpo caído ou rouba-a ao inimigo. A arma decide o estilo de luta (ex.: cavaleiro com arco = arqueiro a cavalo). Os corpos desaparecem ao fim de 30 segundos.

## Ficheiros
- `index.html` — o jogo completo
- `sprites/` — sprites das unidades, edifícios, recursos e terreno
