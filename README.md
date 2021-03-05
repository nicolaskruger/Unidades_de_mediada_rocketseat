# distancias

## Tipos numéricos

- `<integer>`       Número inteiro como -10 ou 223
- `<number>`        Número decimal como -2.4, 64 ou 0.234
- `<dimension>`     É um `<number>` com uma unidade junto: 90deg, 2s, 8px
- `<percentagem>`   Representa a fração de outro número: 50%

## Unidades comuns

- `<length>`        Representa um valor de distância: px, em, vw
- `<angle>`         Representa um ângulo: deg, rad, turn
- `<time>`          Representa um tempo: s, ms
- `<resolution>`    Represena resoluções para dispositivos: dpi

## Distancia absolutas `<length>`

São fixas e não alteram seu valor

| Unidade | Nome | Equivalência |
| :--- | :--- | :--- |
| cm | Centímetros | 1cm = 96px/2.54 |
| in | Inches | 1in = 2.54cm = 96px |
| px | Pixels | 1px = 1/96th of 1in |

- o main comum e mais utilizado é o **px**
- não recomendado usar cm

## distancia relativa

São relativas a algum outro valor, pode ser o elemento pai, ou root, ou o tamanho da tela.

- Benefício: Maior adaptação aos diferentes tipos de tela

| Unidade | Relativo a |
| :--- | :--- |
| em | Tamanho da font do pai |
| rem | Tamanho da font do elemento raiz (root/html) |
| vw | 1% da viewport width |
| vh | 1% da viewport height |

## Porcentagem %

- em muitos casos é tratado da mesma maneira que as distâncias `<length>`
- Sempre será relativo a algum valor

## Posições

`<position>`

Representa um conjunto de coordenadas 2D:

- top, right, bottom, left e center
- Usado para alguns tipos de propriedades
- Não confundir com propriedade `position`

## funções

Em programação, funções são reconhecidas por causar um reaproveitamento de código.

- rgb()
- hsl()
- url()
- calc()

## strings e identificadores

- string: Texto envolto em aspas
- identificadores: red, black, gold
