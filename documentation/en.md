<!-- ELUCENIA technical documentation · ipss · en · no clinical/professional/rights approval -->

# IPSS (International Prostate Symptom Score)

[conditions, sources and permissions](https://elucenia.org/en/tools/ipss)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Incomplete emptying: feeling that the bladder has not emptied completely

`esvaz`

- `0` — Never
- `1` — Less than 1 time in 5
- `2` — Less than half the time
- `3` — About half the time
- `4` — More than half the time
- `5` — Almost always

### Frequency: needing to urinate again less than 2 hours later

`freq`

- `0` — Never
- `1` — Less than 1 time in 5
- `2` — Less than half the time
- `3` — About half the time
- `4` — More than half the time
- `5` — Almost always

### Intermittency: the urine stream stopped and started several times

`inter`

- `0` — Never
- `1` — Less than 1 time in 5
- `2` — Less than half the time
- `3` — About half the time
- `4` — More than half the time
- `5` — Almost always

### Urgency: difficulty postponing urination

`urg`

- `0` — Never
- `1` — Less than 1 time in 5
- `2` — Less than half the time
- `3` — About half the time
- `4` — More than half the time
- `5` — Almost always

### Weak urine stream

`jato`

- `0` — Never
- `1` — Less than 1 time in 5
- `2` — Less than half the time
- `3` — About half the time
- `4` — More than half the time
- `5` — Almost always

### Straining: needing to push to begin urinating

`esforco`

- `0` — Never
- `1` — Less than 1 time in 5
- `2` — Less than half the time
- `3` — About half the time
- `4` — More than half the time
- `5` — Almost always

### Nocturia: how many times you got up at night to urinate

`noct`

- `0` — None
- `1` — 1 time
- `2` — 2 times
- `3` — 3 times
- `4` — 4 times
- `5` — 5 or more times

## Method edition

AUASI/Barry 1992, IPSS 7 items 0–5, total 0–35; quality of life 8th item separate

## Documented formula

Seven questions about the last month, each scored 0 to 5. Total 0 to 35.

The 8th question (quality of life, from 0 "delighted" to 6 "terrible") is recorded separately and not included in the sum.

## Limits and population

IPSS/AUA quantifies urinary symptoms and their evolution, but the total does not establish benign prostatic hyperplasia as the cause. The original validation included people with BPH and controls. Wording, time window, quality of life and limitations of the language version must be preserved and checked separately.

## References

- [Barry MJ et al. The American Urological Association symptom index for benign prostatic hyperplasia. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)36966-5)

- [Lerner LB et al. Management of lower urinary tract symptoms attributed to benign prostatic hyperplasia: AUA guideline part I, initial work-up and medical management. J Urol, 2021.](https://doi.org/10.1097/JU.0000000000002183)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
