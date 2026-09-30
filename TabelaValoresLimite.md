# Tabela de Valores de Teste – Análise do Valor Limite

| Caso | Valor de entrada | Resultado esperado                      | Justificativa (Valor Limite)                              |
|------|------------------|-----------------------------------------|-----------------------------------------------------------|
| 1    | -1               | `"negativo"`                            | Limite da condição `valor < 0`                            |
| 2    | 0                | `"zero"`                                | Limite da condição `valor == 0`                           |
| 3    | 9                | `"digito_unico"`                        | Limite superior da condição `valor < 10`                  |
| 4    | 10               | `"dezenas_pares"`                       | Limite inferior da faixa de dezenas + par                 |
| 5    | 99               | `"dezenas_impares"`                     | Limite superior da faixa de dezenas + ímpar               |
| 6    | 100              | `"centenas_pares_multiplo_de_5"`        | Limite inferior da faixa de centenas + par + múltiplo de 5|
| 7    | 246              | `"centenas_pares"`                      | Valor interior da faixa de centenas + par (não múltiplo 5)|
| 8    | 155              | `"centenas_impares_multiplo_de_5"`      | Valor interior da faixa de centenas + ímpar + múltiplo 5  |
| 9    | 999              | `"centenas_impares"`                    | Limite superior da faixa de centenas + ímpar              |
| 10   | 1000             | `"grande"`                              | Limite da condição `valor < 1000` (falso)                 |