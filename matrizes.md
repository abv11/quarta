# MATRIZES — O GUIA ABSURDAMENTE COMPLETO PARA GABARITAR A PROVA

> Conteúdo: lei de formação, operações com matrizes, propriedades e equação matricial.

---

# 1. O QUE É UMA MATRIZ?

Uma matriz é uma tabela organizada em linhas e colunas.

Exemplo:

|   |   |   |
|---|---|---|
| 1 | 2 | 3 |
| 4 | 5 | 6 |

- possui 2 linhas
- possui 3 colunas

Ordem:

2 × 3

---

# 2. REPRESENTAÇÃO GERAL

Uma matriz qualquer pode ser escrita assim:

A(m×n) = (aij)

Onde:

- m = número de linhas
- n = número de colunas
- aij = elemento da linha i e coluna j

Exemplo:

|   |   |
|---|---|
| 7 | 8 |
| 1 | 9 |

- a11 = 7
- a12 = 8
- a21 = 1
- a22 = 9

---

# 3. LEI DE FORMAÇÃO

A lei de formação é a fórmula usada para descobrir os elementos da matriz.

Exemplo:

aij = 2i + j

Isso significa:

- substitui i pela linha
- substitui j pela coluna

Se a matriz for 2×2:

---

## Calculando

### Elemento a11

a11 = 2(1)+1 = 3

### Elemento a12

a12 = 2(1)+2 = 4

### Elemento a21

a21 = 2(2)+1 = 5

### Elemento a22

a22 = 2(2)+2 = 6

Logo:

|   |   |
|---|---|
| 3 | 4 |
| 5 | 6 |

---

# 4. PRINCIPAIS TIPOS DE MATRIZ

---

## MATRIZ LINHA

Só possui uma linha.

| 1 | 2 | 3 |

Ordem:

1 × 3

---

## MATRIZ COLUNA

Só possui uma coluna.

|   |
|---|
| 4 |
| 7 |
| 9 |

---

## MATRIZ QUADRADA

Mesmo número de linhas e colunas.

2×2, 3×3, 4×4...

Exemplo:

|   |   |
|---|---|
| 1 | 2 |
| 3 | 4 |

---

## MATRIZ NULA

Todos os elementos são zero.

|   |   |
|---|---|
| 0 | 0 |
| 0 | 0 |

---

## MATRIZ IDENTIDADE

Diagonal principal com 1 e resto 0.

|   |   |
|---|---|
| 1 | 0 |
| 0 | 1 |

Ela funciona como o número 1 nas multiplicações.

AI = A

---

# 5. IGUALDADE DE MATRIZES

Duas matrizes são iguais quando:

- possuem mesma ordem
- elementos correspondentes iguais

Exemplo:

| x | 2 |
|---|---|
| 3 | y |

=

| 1 | 2 |
|---|---|
| 3 | 5 |

Comparando posição por posição:

x = 1

y = 5

---

# 6. ADIÇÃO DE MATRIZES

Só pode somar matrizes de MESMA ORDEM.

Somamos elemento por elemento.

A:

|   |   |
|---|---|
| 1 | 2 |
| 3 | 4 |

B:

|   |   |
|---|---|
| 5 | 6 |
| 7 | 8 |

Resultado:

|    |    |
|----|----|
| 6  | 8  |
| 10 | 12 |

---

# 7. SUBTRAÇÃO DE MATRIZES

Mesma ideia da soma.

A − B

Subtrai elemento por elemento.

---

# 8. MULTIPLICAÇÃO POR ESCALAR

Escalar = número real.

Multiplica TODOS os elementos.

2 ·

|   |   |
|---|---|
| 1 | 3 |
| 4 | 5 |

=

|   |    |
|---|----|
| 2 | 6  |
| 8 | 10 |

---

# 9. MULTIPLICAÇÃO DE MATRIZES

A parte que mais derruba gente.

## REGRA MAIS IMPORTANTE DA PROVA

Para multiplicar:

(m×n)(n×p)

o número de colunas da primeira TEM que ser igual ao número de linhas da segunda.

---

## Exemplo

(2×3)(3×2)

PODE multiplicar.

Resultado:

2×2

---

# COMO MULTIPLICAR

Multiplica linha por coluna.

A:

|   |   |
|---|---|
| 1 | 2 |
| 3 | 4 |

B:

|   |   |
|---|---|
| 5 | 6 |
| 7 | 8 |

---

## Primeiro elemento

Linha 1 × coluna 1:

1·5 + 2·7

5 + 14 = 19

---

## Segundo elemento

Linha 1 × coluna 2:

1·6 + 2·8

6 + 16 = 22

---

## Terceiro elemento

Linha 2 × coluna 1:

3·5 + 4·7

15 + 28 = 43

---

## Quarto elemento

Linha 2 × coluna 2:

3·6 + 4·8

18 + 32 = 50

Resultado:

|    |    |
|----|----|
| 19 | 22 |
| 43 | 50 |

---

# 10. PROPRIEDADES DAS MATRIZES

ESSA PARTE DESPENCA EM PROVA.

---

# PROPRIEDADES DA ADIÇÃO

## COMUTATIVA

A + B = B + A

---

## ASSOCIATIVA

(A + B) + C = A + (B + C)

---

## ELEMENTO NEUTRO

A + 0 = A

---

## ELEMENTO OPOSTO

A + (−A) = 0

---

# PROPRIEDADES DA MULTIPLICAÇÃO

## ASSOCIATIVA

(AB)C = A(BC)

---

## DISTRIBUTIVA

A(B + C) = AB + AC

(A + B)C = AC + BC

---

## ELEMENTO NEUTRO

AI = IA = A

---

## NÃO É COMUTATIVA

AB ≠ BA

---

# 11. MATRIZ TRANSPOSTA

Troca linhas por colunas.

A:

| 1 | 2 | 3 |
|---|---|---|
| 4 | 5 | 6 |

AT:

|   |   |
|---|---|
| 1 | 4 |
| 2 | 5 |
| 3 | 6 |

---

# PROPRIEDADES DA TRANSPOSTA

(AT)T = A

(A + B)T = AT + BT

(AB)T = BTAT

---

# 12. EQUAÇÃO MATRICIAL

É literalmente uma equação com matrizes.

Exemplo:

X +

|   |   |
|---|---|
| 1 | 2 |
| 3 | 4 |

=

|   |   |
|---|---|
| 5 | 6 |
| 7 | 8 |

Para achar X:

X = B − A

Resultado:

|   |   |
|---|---|
| 4 | 4 |
| 4 | 4 |

---

# 13. PEGADINHAS MAIS COMUNS

## 1. SOMAR MATRIZES DE ORDENS DIFERENTES

ERRADO.

2×2 + 3×3

não existe.

---

## 2. ACHAR QUE AB = BA

Quase nunca.

---

## 3. ERRAR A ORDEM DA MATRIZ RESULTANTE

(2×3)(3×5)

resultado:

2×5

---

## 4. MULTIPLICAR ELEMENTO POR ELEMENTO

ERRADO.

Multiplicação de matrizes NÃO funciona assim.

É linha por coluna.

---

# 14. RESUMO ULTRA RÁPIDO DE VÉSPERA

A + B

→ somar elemento por elemento

---

AB

→ linha × coluna

---

AB ≠ BA

→ quase sempre

---

AI = A

→ identidade não muda nada

---

(AB)T = BTAT

→ INVERTE A ORDEM

---

X + A = B

X = B − A
