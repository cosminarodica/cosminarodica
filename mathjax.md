<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script> 



# Inserarea ecuatiilor si formulelor in `MathJax`

**Sintaxa**

Formulele `MathJax` sunt inserate in aceeasi linie daca sunt plasate intr o pereche de simboluri `$`

exemplu: Aceasta este o ecuatie: $a=bc$

Formulele `LaTex` (prin `MathJax`) se introduc pe rand nou intre doua perechi de simboluri $$.

*exemplu:*

$$a=b^c$$

# Ridicarea la putere (`superscript)

 Se foloseste meta-caracter `LaTex`: `^`

exemplu:

$$a=10^7$$

# `subscript`

se foloseste mete-caracterul `LaTex` : `_`

*Exemplu:*

$$a_i=b^c$$

# Gruparea elementelor din formule

Elementele din formule se grupeaza prin meta-caracterele { si }

$$ 10^{10} $$

# Litere grecesti

*Exemple:*
`\alpha` - litera mica ($\alpha$)

`\Alpha` -litera mare ($$\Alpha$$)


# Parantezele 

- Parantezele rotunde se scriu direct( nu au un inteles special in `laTex`)
- Parantezele drepte se scriu direct ( nu au un inteles special in `laTex`)
- Acoladele, deoarece ele sunt metacaractere de grupare, vor fi renderizate corect daca sunt `escapate` de intelesul lor special, punand in fata lor `metacaracterul` `\`

  Exemple:

  $$a= (b+c)^{3x} - [3+6x]$$

# Fractiile

 *Exemplu:*

 `\frac {numarator} {numitor}`

 $$ a = \frac{6} {4} $$

 # Semnele de multiplicare si respectiv de diviziune

 *Exemple:*

 $$ a = c + 10\times x $$

 $$ a = c + 10\cdot x $$

 $$ a = b \div c $$

# Suma de la i=0 la n

**Exemplu:**

 $$ \sum_{i=0}^n i^2 = \frac{(a+b)\times (b+c)}{6} $$

 # Integrale

 **Exemple:**

$$ \int_o^1 x^4 dx $$






