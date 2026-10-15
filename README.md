# ritassiru.github.io

Página inicial dos jogos e leituras interativas em inglês do Prof. Ritaciro
Cavalcante (IFAL Campus Viçosa): **https://ritassiru.github.io/**

Os jogos ficam cada um no seu repositório, e o GitHub Pages os publica nos
endereços abaixo do mesmo site:

| Jogo | Endereço | Repositório |
|---|---|---|
| Story Shelf | `/story-shelf/` | [ritassiru/story-shelf](https://github.com/ritassiru/story-shelf) |
| The CEO Game | `/the-ceo-game/` | [ritassiru/the-ceo-game](https://github.com/ritassiru/the-ceo-game) |
| My Busy Week | `/my-busy-week/` | [ritassiru/my-busy-week](https://github.com/ritassiru/my-busy-week) |

## Para editar

Tudo fica em `index.html`, sem etapa de build:

- **Jogo novo publicado:** acrescente um item na lista `JOGOS` (no fim do
  arquivo) e copie o ícone do jogo (`icon-192.png`) para `img/`.
- **Jogo em produção:** acrescente um item em `EM_BREVE`. Quando ele for
  publicado, mova o item para `JOGOS`, com `link`, `professor` e `icone`.
- **Seção Sobre:** os trechos marcados com `class="todo"` (em amarelo na
  página) ainda precisam ser completados pelo professor.

As cores seguem as dos jogos (claro e escuro) e a página respeita a opção de
cores escolhida dentro deles. Nada de bibliotecas externas nem CDNs: as fontes
estão em `fonts/`.

## Licença

Textos e ícones em CC BY-SA 4.0, código em MIT, fontes em SIL OFL 1.1. Veja `LICENSE`.
