# MATRIZES — O GUIA ABSURDAMENTE COMPLETO PARA GABARITAR A PROVA

> Conteúdo: lei de formação, operações com matrizes, propriedades e equação matricial.

Baseado em materiais didáticos de matemática do ensino médio e álgebra linear. ([Brasil Escola][1])

---

# 1. O QUE É UMA MATRIZ?

Uma **matriz** é uma tabela organizada em **linhas** e **colunas**.

Exemplo:

[
A=
\begin{pmatrix}
1 & 2 & 3\
4 & 5 & 6
\end{pmatrix}
]

* possui **2 linhas**
* possui **3 colunas**

Então sua ordem é:

[
2 \times 3
]

---

# 2. REPRESENTAÇÃO GERAL

Uma matriz qualquer pode ser escrita assim:

[
A_{m\times n}=(a_{ij})
]

Onde:

* (m) = número de linhas
* (n) = número de colunas
* (a_{ij}) = elemento da linha (i) e coluna (j)

Exemplo:

[
A=
\begin{pmatrix}
7 & 8\
1 & 9
\end{pmatrix}
]

* (a_{11}=7)
* (a_{12}=8)
* (a_{21}=1)
* (a_{22}=9)

---

# 3. LEI DE FORMAÇÃO

A lei de formação é a fórmula usada para descobrir os elementos da matriz.

Exemplo:

[
a_{ij}=2i+j
]

Isso significa:

* substitui (i) pela linha
* substitui (j) pela coluna

Se a matriz for (2\times2):

---

## Calculando

### Elemento (a_{11})

[
a_{11}=2(1)+1=3
]

### Elemento (a_{12})

[
a_{12}=2(1)+2=4
]

### Elemento (a_{21})

[
a_{21}=2(2)+1=5
]

### Elemento (a_{22})

[
a_{22}=2(2)+2=6
]

Logo:

[
A=
\begin{pmatrix}
3 & 4\
5 & 6
\end{pmatrix}
]

---

# 4. PRINCIPAIS TIPOS DE MATRIZ

---

## MATRIZ LINHA

Só possui uma linha.

[
\begin{pmatrix}
1 & 2 & 3
\end{pmatrix}
]

Ordem:

[
1\times3
]

---

## MATRIZ COLUNA

Só possui uma coluna.

[
\begin{pmatrix}
4\
7\
9
\end{pmatrix}
]

---

## MATRIZ QUADRADA

Mesmo número de linhas e colunas.

[
2\times2,\ 3\times3,\ 4\times4...
]

Exemplo:

[
\begin{pmatrix}
1 & 2\
3 & 4
\end{pmatrix}
]

---

## MATRIZ NULA

Todos os elementos são zero.

[
\begin{pmatrix}
0 & 0\
0 & 0
\end{pmatrix}
]

---

## MATRIZ IDENTIDADE

Diagonal principal com 1 e resto 0.

[
I_2=
\begin{pmatrix}
1 & 0\
0 & 1
\end{pmatrix}
]

[
I_3=
\begin{pmatrix}
1 & 0 & 0\
0 & 1 & 0\
0 & 0 & 1
\end{pmatrix}
]

Ela funciona como o número 1 nas multiplicações.

[
AI=A
]

---

# 5. IGUALDADE DE MATRIZES

Duas matrizes são iguais quando:

* possuem mesma ordem
* elementos correspondentes iguais ([uel.br][2])

Exemplo:

[
\begin{pmatrix}
x & 2\
3 & y
\end{pmatrix}
=============

\begin{pmatrix}
1 & 2\
3 & 5
\end{pmatrix}
]

Comparando posição por posição:

[
x=1
]

[
y=5
]

---

# 6. ADIÇÃO DE MATRIZES

Só pode somar matrizes de MESMA ORDEM.

Somamos elemento por elemento.

[
A=
\begin{pmatrix}
1 & 2\
3 & 4
\end{pmatrix}
]

[
B=
\begin{pmatrix}
5 & 6\
7 & 8
\end{pmatrix}
]

[
A+B=
\begin{pmatrix}
1+5 & 2+6\
3+7 & 4+8
\end{pmatrix}
]

Resultado:

[
\begin{pmatrix}
6 & 8\
10 & 12
\end{pmatrix}
]

---

# 7. SUBTRAÇÃO DE MATRIZES

Mesma ideia da soma.

[
A-B
]

Subtrai elemento por elemento.

---

# 8. MULTIPLICAÇÃO POR ESCALAR

Escalar = número real.

Multiplica TODOS os elementos.

[
2\cdot
\begin{pmatrix}
1 & 3\
4 & 5
\end{pmatrix}
=============

\begin{pmatrix}
2 & 6\
8 & 10
\end{pmatrix}
]

---

# 9. MULTIPLICAÇÃO DE MATRIZES

A parte que mais derruba gente.

## REGRA MAIS IMPORTANTE DA PROVA

Para multiplicar:

[
A_{m\times n}\cdot B_{n\times p}
]

o número de colunas da primeira TEM que ser igual ao número de linhas da segunda.

---

## Exemplo

[
A_{2\times3}\cdot B_{3\times2}
]

PODE multiplicar.

Resultado será:

[
2\times2
]

---

# COMO MULTIPLICAR

Multiplica linha por coluna.

Exemplo:

[
A=
\begin{pmatrix}
1 & 2\
3 & 4
\end{pmatrix}
]

[
B=
\begin{pmatrix}
5 & 6\
7 & 8
\end{pmatrix}
]

---

## Primeiro elemento

Linha 1 × coluna 1:

[
1\cdot5+2\cdot7
]

[
5+14=19
]

---

## Segundo elemento

Linha 1 × coluna 2:

[
1\cdot6+2\cdot8
]

[
6+16=22
]

---

## Terceiro elemento

Linha 2 × coluna 1:

[
3\cdot5+4\cdot7
]

[
15+28=43
]

---

## Quarto elemento

Linha 2 × coluna 2:

[
3\cdot6+4\cdot8
]

[
18+32=50
]

Resultado:

[
AB=
\begin{pmatrix}
19 & 22\
43 & 50
\end{pmatrix}
]

---

# 10. PROPRIEDADES DAS MATRIZES

ESSA PARTE DESPENCA EM PROVA.

---

# PROPRIEDADES DA ADIÇÃO

## COMUTATIVA

[
A+B=B+A
]

A ordem não altera.

---

## ASSOCIATIVA

[
(A+B)+C=A+(B+C)
]

---

## ELEMENTO NEUTRO

[
A+0=A
]

(0) = matriz nula.

---

## ELEMENTO OPOSTO

[
A+(-A)=0
]

([uel.br][2])

---

# PROPRIEDADES DA MULTIPLICAÇÃO

---

## ASSOCIATIVA

[
(AB)C=A(BC)
]

---

## DISTRIBUTIVA

[
A(B+C)=AB+AC
]

[
(A+B)C=AC+BC
]

---

## ELEMENTO NEUTRO

[
AI=IA=A
]

(I) = matriz identidade.

---

## NÃO É COMUTATIVA

ESSENCIAL.

Em geral:

[
AB\neq BA
]

Isso cai MUITO. ([uel.br][2])

---

# 11. MATRIZ TRANSPOSTA

Troca linhas por colunas.

Exemplo:

[
A=
\begin{pmatrix}
1 & 2 & 3\
4 & 5 & 6
\end{pmatrix}
]

Então:

[
A^T=
\begin{pmatrix}
1 & 4\
2 & 5\
3 & 6
\end{pmatrix}
]

---

# PROPRIEDADES DA TRANSPOSTA

[
(A^T)^T=A
]

[
(A+B)^T=A^T+B^T
]

[
(AB)^T=B^TA^T
]

([Projeto Agatha Edu][3])

---

# 12. EQUAÇÃO MATRICIAL

É literalmente uma equação com matrizes.

Exemplo:

[
X+
\begin{pmatrix}
1 & 2\
3 & 4
\end{pmatrix}
=============

\begin{pmatrix}
5 & 6\
7 & 8
\end{pmatrix}
]

Para achar (X):

[
X=
\begin{pmatrix}
5 & 6\
7 & 8
\end{pmatrix}
-------------

\begin{pmatrix}
1 & 2\
3 & 4
\end{pmatrix}
]

Resultado:

[
X=
\begin{pmatrix}
4 & 4\
4 & 4
\end{pmatrix}
]

---

# EQUAÇÃO COM MULTIPLICAÇÃO

Exemplo:

[
2X=
\begin{pmatrix}
6 & 8\
10 & 12
\end{pmatrix}
]

Divide tudo por 2:

[
X=
\begin{pmatrix}
3 & 4\
5 & 6
\end{pmatrix}
]

---

# 13. PEGADINHAS MAIS COMUNS

---

## 1. SOMAR MATRIZES DE ORDENS DIFERENTES

ERRADO.

[
2\times2 + 3\times3
]

não existe.

---

## 2. ACHAR QUE AB=BA

Quase nunca.

---

## 3. ERRAR A ORDEM DA MATRIZ RESULTANTE

Se:

[
(2\times3)\cdot(3\times5)
]

resultado:

[
2\times5
]

---

## 4. MULTIPLICAR ELEMENTO POR ELEMENTO

ERRADO.

Multiplicação de matrizes NÃO funciona assim.

É linha por coluna.

---

# 14. QUESTÕES QUE MAIS CAEM

---

## LEI DE FORMAÇÃO

“Determine a matriz de ordem (2\times3) dada por:

[
a_{ij}=i+j
]”

---

## MULTIPLICAÇÃO

“Calcule (AB).”

---

## PROPRIEDADES

“Julgue verdadeiro ou falso:

[
AB=BA
]”

Normalmente: FALSO.

---

## EQUAÇÃO MATRICIAL

“Resolva:

[
X+A=B
]”

---

# 15. MACETES PARA A PROVA

---

## SOMA E SUBTRAÇÃO

“mesma posição com mesma posição”

---

## MULTIPLICAÇÃO

“linha abraça coluna”

---

## ORDEM DO RESULTADO

“fica o lado de fora”

[
(2\times3)(3\times4)
\Rightarrow
2\times4
]

---

# 16. O QUE VOCÊ PRECISA DECORAR OBRIGATORIAMENTE

## DECORA ISSO HOJE:

* condição da multiplicação
* linha × coluna
* propriedades
* matriz identidade
* matriz transposta
* equação matricial
* lei de formação

Se dominar isso, você resolve praticamente qualquer prova de ensino médio sobre matrizes.

---

# 17. EXERCÍCIOS TREINO NÍVEL PROVA

---

## 1

Dada:

[
a_{ij}=i+2j
]

Monte a matriz (2\times2).

---

## 2

[
A=
\begin{pmatrix}
1 & 2\
3 & 4
\end{pmatrix}
]

[
B=
\begin{pmatrix}
5 & 6\
7 & 8
\end{pmatrix}
]

Calcule:

[
A+B
]

---

## 3

Calcule:

[
AB
]

com as matrizes acima.

---

## 4

Resolva:

[
X+
\begin{pmatrix}
1 & 1\
1 & 1
\end{pmatrix}
=============

\begin{pmatrix}
5 & 5\
5 & 5
\end{pmatrix}
]

---

# 18. RESPOSTAS

## 1

[
\begin{pmatrix}
3 & 5\
4 & 6
\end{pmatrix}
]

---

## 2

[
\begin{pmatrix}
6 & 8\
10 & 12
\end{pmatrix}
]

---

## 3

[
\begin{pmatrix}
19 & 22\
43 & 50
\end{pmatrix}
]

---

## 4

[
\begin{pmatrix}
4 & 4\
4 & 4
\end{pmatrix}
]

---

# 19. RESUMO ULTRA RÁPIDO DE VÉSPERA

[
A+B
]

somar elemento por elemento.

---

[
AB
]

linha × coluna.

---

[
AB\neq BA
]

quase sempre.

---

[
AI=A
]

identidade não muda nada.

---

[
(A+B)^T=A^T+B^T
]

transposta distribui na soma.

---

[
(AB)^T=B^TA^T
]

INVERTE A ORDEM.

---

[
X+A=B
]

[
X=B-A
]

---

Se você quiser, eu também posso fazer:

* um “formulário assassino” de 1 página só com o que cai
* 30 exercícios estilo IF/vestibular com gabarito
* mapa mental em Markdown
* lista das pegadinhas clássicas de professor
* revisão de 30 minutos pra véspera
* versão estética absurda pra README do GitHub

([Brasil Escola][1])

[1]: https://brasilescola.uol.com.br/matematica/matriz.htm?utm_source=chatgpt.com "Matriz: o que é, tipos, operações, exemplos - Brasil Escola"
[2]: https://www.uel.br/projetos/matessencial/basico/medio/matrizes.html?utm_source=chatgpt.com "Matemática Essencial :: Ensino Médio :: Matrizes"
[3]: https://projetoagathaedu.com.br/blog/matematica/algebra-linear/matriz.php?utm_source=chatgpt.com "Matrizes - Álgebra Linear: Enem, Vestibulares e Ensino Médio"
