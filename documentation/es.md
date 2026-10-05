<!-- ELUCENIA technical documentation · ipss · es · no clinical/professional/rights approval -->

# IPSS (puntuación internacional de síntomas prostáticos)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/ipss)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Vaciado incompleto: sensación de no vaciar totalmente la vejiga

`esvaz`

- `0` — Nunca
- `1` — Menos de 1 vez de cada 5
- `2` — Menos de la mitad de las veces
- `3` — Aproximadamente la mitad de las veces
- `4` — Más de la mitad de las veces
- `5` — Casi siempre

### Frecuencia: necesidad de volver a orinar menos de 2 horas después

`freq`

- `0` — Nunca
- `1` — Menos de 1 vez de cada 5
- `2` — Menos de la mitad de las veces
- `3` — Aproximadamente la mitad de las veces
- `4` — Más de la mitad de las veces
- `5` — Casi siempre

### Intermitencia: el chorro de orina se detuvo y reinició varias veces

`inter`

- `0` — Nunca
- `1` — Menos de 1 vez de cada 5
- `2` — Menos de la mitad de las veces
- `3` — Aproximadamente la mitad de las veces
- `4` — Más de la mitad de las veces
- `5` — Casi siempre

### Urgencia: dificultad para aguantar la orina

`urg`

- `0` — Nunca
- `1` — Menos de 1 vez de cada 5
- `2` — Menos de la mitad de las veces
- `3` — Aproximadamente la mitad de las veces
- `4` — Más de la mitad de las veces
- `5` — Casi siempre

### Chorro de orina débil

`jato`

- `0` — Nunca
- `1` — Menos de 1 vez de cada 5
- `2` — Menos de la mitad de las veces
- `3` — Aproximadamente la mitad de las veces
- `4` — Más de la mitad de las veces
- `5` — Casi siempre

### Esfuerzo: necesidad de hacer fuerza para empezar a orinar

`esforco`

- `0` — Nunca
- `1` — Menos de 1 vez de cada 5
- `2` — Menos de la mitad de las veces
- `3` — Aproximadamente la mitad de las veces
- `4` — Más de la mitad de las veces
- `5` — Casi siempre

### Nicturia: cuántas veces se levantó por la noche para orinar

`noct`

- `0` — Ninguna
- `1` — 1 vez
- `2` — 2 veces
- `3` — 3 veces
- `4` — 4 veces
- `5` — 5 o más veces

## Edición del método

AUASI/Barry 1992, IPSS 7 ítems 0–5, total 0–35; calidad de vida, 8º ítem separado

## Fórmula documentada

Siete preguntas sobre el último mes, cada una de 0 a 5 puntos. Total 0 a 35.

La 8ª pregunta (calidad de vida, de 0 "encantado" a 6 "pésimo") se registra por separado y no entra en la suma.

## Límites y población

El IPSS/AUA cuantifica síntomas urinarios y su evolución, pero el total no establece que la causa sea hiperplasia prostática benigna. La validación original incluyó a personas con HPB y controles. La redacción, la ventana temporal, la calidad de vida y las limitaciones de la versión lingüística deben conservarse y verificarse por separado.

## Referencias

- [Barry MJ et al. The American Urological Association symptom index for benign prostatic hyperplasia. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)36966-5)

- [Lerner LB et al. Management of lower urinary tract symptoms attributed to benign prostatic hyperplasia: AUA guideline part I, initial work-up and medical management. J Urol, 2021.](https://doi.org/10.1097/JU.0000000000002183)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
