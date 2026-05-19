# MATRIZES — O GUIA ABSURDAMENTE COMPLETO PARA GABARITAR A PROVA

> Conteúdo: lei de formação, operações com matrizes, propriedades e equação matricial.

---

# 1. O QUE É UMA MATRIZ?

Uma **matriz** é uma tabela organizada em **linhas** e **colunas**.

Exemplo:

$$
A=
\begin{bmatrix}
1 & 2 & 3\\
4 & 5 & 6
\end{bmatrix}
$$

- possui **2 linhas**
- possui **3 colunas**

Então sua ordem é:

$$
2 \times 3
$$

---

# 2. REPRESENTAÇÃO GERAL

Uma matriz qualquer pode ser escrita assim:

$$
A_{m\times n}=(a_{ij})
$$

Onde:

- \(m\) = número de linhas
- \(n\) = número de colunas
- \(a_{ij}\) = elemento da linha \(i\) e coluna \(j\)

Exemplo:

$$
A=
\begin{bmatrix}
7 & 8\\
1 & 9
\end{bmatrix}
$$

- \(a_{11}=7\)
- \(a_{12}=8\)
- \(a_{21}=1\)
- \(a_{22}=9\)

---

# 3. LEI DE FORMAÇÃO

A lei de formação é a fórmula usada para descobrir os elementos da matriz.

Exemplo:

$$
a_{ij}=2i+j
$$

Isso significa:

- substitui \(i\) pela linha
- substitui \(j\) pela coluna

Se a matriz for \(2\times2\):

---

## Calculando

### Elemento \(a_{11}\)

$$
a_{11}=2(1)+1=3
$$

### Elemento \(a_{12}\)

$$
a_{12}=2(1)+2=4
$$

### Elemento \(a_{21}\)

$$
a_{21}=2(2)+1=5
$$

### Elemento \(a_{22}\)

$$
a_{22}=2(2)+2=6
$$

Logo:

$$
A=
\begin{bmatrix}
3 & 4\\
5 & 6
\end{bmatrix}
$$

---

# 4. PRINCIPAIS TIPOS DE MATRIZ

---

## MATRIZ LINHA

Só possui uma linha.

$$
\begin{bmatrix}
1 & 2 & 3
\end{bmatrix}
$$

Ordem:

$$
1\times3
$$

---

## MATRIZ COLUNA

Só possui uma coluna.

$$
\begin{bmatrix}
4\\
7\\
9
\end{bmatrix}
$$

---

## MATRIZ QUADRADA

Mesmo número de linhas e colunas.

$$
2\times2,\ 3\times3,\ 4\times4...
$$

Exemplo:

$$
\begin{bmatrix}
1 & 2\\
3 & 4
\end{bmatrix}
$$

---

## MATRIZ NULA

Todos os elementos são zero.

$$
\begin{bmatrix}
0 & 0\\
0 & 0
\end{bmatrix}
$$

---

## MATRIZ IDENTIDADE

Diagonal principal com 1 e resto 0.

$$
I_2=
\begin{bmatrix}
1 & 0\\
0 & 1
\end{bmatrix}
$$

$$
I_3=
\begin{bmatrix}
1 & 0 & 0\\
0 & 1 & 0\\
0 & 0 & 1
\end{bmatrix}
$$

Ela funciona como o número 1 nas multiplicações.

$$
AI=A
$$

---

# 5. IGUALDADE DE MATRIZES

Duas matrizes são iguais quando:

- possuem mesma ordem
- elementos correspondentes iguais

Exemplo:

$$
\begin{bmatrix}
x & 2\\
3 & y
\end{bmatrix}
=
\begin{bmatrix}
1 & 2\\
3 & 5
\end{bmatrix}
$$

Comparando posição por posição:

$$
x=1
$$

$$
y=5
$$

---

# 6. ADIÇÃO DE MATRIZES

Só pode somar matrizes de MESMA ORDEM.

Somamos elemento por elemento.

$$
A=
\begin{bmatrix}
1 & 2\\
3 & 4
\end{bmatrix}
$$

$$
B=
\begin{bmatrix}
5 & 6\\
7 & 8
\end{bmatrix}
$$

$$
A+B=
\begin{bmatrix}
1+5 & 2+6\\
3+7 & 4+8
\end{bmatrix}
$$

Resultado:

$$
\begin{bmatrix}
6 & 8\\
10 & 12
\end{bmatrix}
$$

---

# 7. SUBTRAÇÃO DE MATRIZES

Mesma ideia da soma.

$$
A-B
$$

Subtrai elemento por elemento.

---

# 8. MULTIPLICAÇÃO POR ESCALAR

Escalar = número real.

Multiplica TODOS os elementos.

$$
2\cdot
\begin{bmatrix}
1 & 3\\
4 & 5
\end{bmatrix}
=
\begin{bmatrix}
2 & 6\\
8 & 10
\end{bmatrix}
$$

---

# 9. MULTIPLICAÇÃO DE MATRIZES

A parte que mais derruba gente.

## REGRA MAIS IMPORTANTE DA PROVA

Para multiplicar:

$$
A_{m\times n}\cdot B_{n\times p}
$$

o número de colunas da primeira TEM que ser igual ao número de linhas da segunda.

---

## Exemplo

$$
A_{2\times3}\cdot B_{3\times2}
$$

PODE multiplicar.

Resultado será:

$$
2\times2
$$

---

# COMO MULTIPLICAR

Multiplica linha por coluna.

Exemplo:

$$
A=
\begin{bmatrix}
1 & 2\\
3 & 4
\end{bmatrix}
$$

$$
B=
\begin{bmatrix}
5 & 6\\
7 & 8
\end{bmatrix}
$$

---

## Primeiro elemento

Linha 1 × coluna 1:

$$
1\cdot5+2\cdot7
$$

$$
5+14=19
$$

---

## Segundo elemento

Linha 1 × coluna 2:

$$
1\cdot6+2\cdot8
$$

$$
6+16=22
$$

---

## Terceiro elemento

Linha 2 × coluna 1:

$$
3\cdot5+4\cdot7
$$

$$
15+28=43
$$

---

## Quarto elemento

Linha 2 × coluna 2:

$$
3\cdot6+4\cdot8
$$

$$
18+32=50
$$

Resultado:

$$
AB=
\begin{bmatrix}
19 & 22\\
43 & 50
\end{bmatrix}
$$

---

# 10. PROPRIEDADES DAS MATRIZES

ESSA PARTE DESPENCA EM PROVA.

---

# PROPRIEDADES DA ADIÇÃO

## COMUTATIVA

$$
A+B=B+A
$$

---

## ASSOCIATIVA

$$
(A+B)+C=A+(B+C)
$$

---

## ELEMENTO NEUTRO

$$
A+0=A
$$

---

## ELEMENTO OPOSTO

$$
A+(-A)=0
$$

---

# PROPRIEDADES DA MULTIPLICAÇÃO

## ASSOCIATIVA

$$
(AB)C=A(BC)
$$

---

## DISTRIBUTIVA

$$
A(B+C)=AB+AC
$$

$$
(A+B)C=AC+BC
$$

---

## ELEMENTO NEUTRO

$$
AI=IA=A
$$

---

## NÃO É COMUTATIVA

$$
AB\neq BA
$$

---

# 11. MATRIZ TRANSPOSTA

Troca linhas por colunas.

$$
A=
\begin{bmatrix}
1 & 2 & 3\\
4 & 5 & 6
\end{bmatrix}
$$

Então:

$$
A^T=
\begin{bmatrix}
1 & 4\\
2 & 5\\
3 & 6
\end{bmatrix}
$$

---

# PROPRIEDADES DA TRANSPOSTA

$$
(A^T)^T=A
$$

$$
(A+B)^T=A^T+B^T
$$

$$
(AB)^T=B^TA^T
$$

---

# 12. EQUAÇÃO MATRICIAL

É literalmente uma equação com matrizes.

Exemplo:

$$
X+
\begin{bmatrix}
1 & 2\\
3 & 4
\end{bmatrix}
=
\begin{bmatrix}
5 & 6\\
7 & 8
\end{bmatrix}
$$

Para achar \(X\):

$$
X=
\begin{bmatrix}
5 & 6\\
7 & 8
\end{bmatrix}
-
\begin{bmatrix}
1 & 2\\
3 & 4
\end{bmatrix}
$$

Resultado:

$$
X=
\begin{bmatrix}
4 & 4\\
4 & 4
\end{bmatrix}
$$

---

# 13. PEGADINHAS MAIS COMUNS

## 1. SOMAR MATRIZES DE ORDENS DIFERENTES

ERRADO.

$$
2\times2 + 3\times3
$$

não existe.

---

## 2. ACHAR QUE \(AB=BA\)

Quase nunca.

---

## 3. ERRAR A ORDEM DA MATRIZ RESULTANTE

Se:

$$
(2\times3)\cdot(3\times5)
$$

resultado:

$$
2\times5
$$

---

## 4. MULTIPLICAR ELEMENTO POR ELEMENTO

ERRADO.

Multiplicação de matrizes NÃO funciona assim.

É linha por coluna.

---

# 14. RESUMO ULTRA RÁPIDO DE VÉSPERA

$$
A+B
$$

somar elemento por elemento.

---

$$
AB
$$

linha × coluna.

---

$$
AB\neq BA
$$

quase sempre.

---

$$
AI=A
$$

identidade não muda nada.

---

$$
(A+B)^T=A^T+B^T
$$

transposta distribui na soma.

---

$$
(AB)^T=B^TA^T
$$

INVERTE A ORDEM.

---

$$
X+A=B
$$

$$
X=B-A
$$
