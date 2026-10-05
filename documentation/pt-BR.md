<!-- ELUCENIA technical documentation · ipss · pt-BR · no clinical/professional/rights approval -->

# IPSS (Escore Internacional de Sintomas Prostáticos)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/ipss)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Esvaziamento incompleto: sensação de não esvaziar totalmente a bexiga

`esvaz`

- `0` — Nenhuma vez
- `1` — Menos de 1 vez em cada 5
- `2` — Menos da metade das vezes
- `3` — Cerca de metade das vezes
- `4` — Mais da metade das vezes
- `5` — Quase sempre

### Frequência: precisou urinar de novo menos de 2 horas depois

`freq`

- `0` — Nenhuma vez
- `1` — Menos de 1 vez em cada 5
- `2` — Menos da metade das vezes
- `3` — Cerca de metade das vezes
- `4` — Mais da metade das vezes
- `5` — Quase sempre

### Intermitência: o jato parou e recomeçou várias vezes

`inter`

- `0` — Nenhuma vez
- `1` — Menos de 1 vez em cada 5
- `2` — Menos da metade das vezes
- `3` — Cerca de metade das vezes
- `4` — Mais da metade das vezes
- `5` — Quase sempre

### Urgência: dificuldade para segurar a urina

`urg`

- `0` — Nenhuma vez
- `1` — Menos de 1 vez em cada 5
- `2` — Menos da metade das vezes
- `3` — Cerca de metade das vezes
- `4` — Mais da metade das vezes
- `5` — Quase sempre

### Jato fraco

`jato`

- `0` — Nenhuma vez
- `1` — Menos de 1 vez em cada 5
- `2` — Menos da metade das vezes
- `3` — Cerca de metade das vezes
- `4` — Mais da metade das vezes
- `5` — Quase sempre

### Esforço: precisou fazer força para começar a urinar

`esforco`

- `0` — Nenhuma vez
- `1` — Menos de 1 vez em cada 5
- `2` — Menos da metade das vezes
- `3` — Cerca de metade das vezes
- `4` — Mais da metade das vezes
- `5` — Quase sempre

### Noctúria: quantas vezes levantou à noite para urinar

`noct`

- `0` — Nenhuma
- `1` — 1 vez
- `2` — 2 vezes
- `3` — 3 vezes
- `4` — 4 vezes
- `5` — 5 ou mais vezes

## Edição do método

AUASI/Barry 1992, IPSS 7 itens 0–5, total 0–35; qualidadedevida 8ºitemseparado

## Fórmula documentada

Sete perguntas sobre o último mês, cada uma de 0 a 5 pontos. Total de 0 a 35.

A 8ª pergunta (qualidade de vida, de 0 "encantado" a 6 "péssimo") é registrada à parte e não entra na soma.

## Limites e população

O IPSS/AUA quantifica sintomas urinários e sua evolução, mas o total não estabelece que a causa seja hiperplasia prostática benigna. A validação original envolveu pessoas com HPB e controles. Redação, janela temporal, qualidade de vida e limites da versão linguística devem ser preservados e verificados separadamente.

## Referências

- [Barry MJ et al. The American Urological Association symptom index for benign prostatic hyperplasia. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)36966-5)

- [Lerner LB et al. Management of lower urinary tract symptoms attributed to benign prostatic hyperplasia: AUA guideline part I, initial work-up and medical management. J Urol, 2021.](https://doi.org/10.1097/JU.0000000000002183)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
