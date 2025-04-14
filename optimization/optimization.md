# Linear programming
## Introdução
Programação linear (linear programming) busca otimizar uma **função objetivo linear** sujeito a algumas restrições que também são lineares. Técnicas de programação linear são empregadas em um grande número de problemas, como planejamento de produção, planejamento financeiro, gestão de recursos humanos, problemas de transporte, distribuição, distribuição de subsídios, planejamento florestal, programação de voos, etc. 

A base da programação linear está no estudo de **inequações lineares**. Que são desigualdades matemáticas que envolvem uma variável e símbolos de desigualdade, como <, >, ≤, ou ≥. São chamadas lineares porque o maior expoente da variável é 1. Exemplos de inequações lineares 2x – 5 > 4, 4x > 8, 3x + 1 < -14. Resolver uma inequação significa determinar qual intervalo de valores que a incógnita pode assumir para satisfazer a expressão. 

A programação linear é um processo matemático para determinar a alocação ideal de recursos escassos. Dois problemas de alocação de recursos clássicos são: o _product mix problem_ e o  _mixtures problem_. O problema do mix de produtos visa descobrir quais e quantos produtos devem ser incluídos no programa de produção para maximizar os lucros. O problema do mix busca determinar a quantidade mínima de recursos possível a ser utilizada para obter um determinado nível de produto ou serviço.

Qualquer problema de programação linear consiste em uma função objetivo e um conjunto de restrições que devem satisfazer as seguintes condições: 
- a função objetivo deve ser linear; 
- o objetivo deve representar a meta do tomador de decisão e deve ser a maximização ou a minimização de uma função linear; 
- as restrições também devem ser lineares.

Os modelos de programação linear apresentam uma série de limitações devido a algumas premissas criadas para simplificar a realidade e representá-la por meio de um modelo matemático. As premissas criadas são:
1. Problemas determinísticos são considerados. Em outras palavras, todos os dados são conhecidos com certeza.
2. Assume-se que a função objetivo é linear.
3. Restrições também são consideradas lineares.
4. Variáveis ​​de decisão não podem assumir valores negativos.
5. A aditividade dos recursos, o uso total de cada recurso, é obtida pela soma dos usos parciais desse recurso.
6. A divisibilidade das variáveis ​​de decisão; essas variáveis ​​podem assumir valores fracionários.
7. Assume-se a independência entre atividades e recursos para as diversas variáveis ​​de decisão.
8. Tanto a quantidade do recurso empregado quanto o valor da função objetivo são proporcionais aos valores das variáveis ​​de decisão. Esse requisito de proporcionalidade é atendido, pois a função é objetiva e as restrições são lineares.

Um moldeo de programação linear consiste em três componentes linkados por relações matemáticas:
1. **Variáveis de decisão**: Fatores que o tomador de decisão deve escolher e são variáveis controláveis. O objetivo da programação linear é encontrar os melhores valores dessas variáveis de decisão.
2. **Função objetivo**: Representa a relação as variáveis de decisão e variáveis incontroláveis. Pode ser maximizar ou minimizar uma quantidade, e é limitada pelas restrições.
3. **Restrições (constraints)**: São as limitações impostas pelas variáveis não controláveis (ambiente) pelo tomador de decisão.

A construção de um modelo de programação linear consiste nas seguintes etapas:
1. definir variáveis ​​de decisão; 
2. definir o objetivo ou meta em termos das variáveis ​​de decisão; 
3. definir todas as restrições do sistema, e;
4. restringir todas as variáveis ​​para que não sejam negativas. 

Um modelo de programação linear pode ser expresso formalmente como:

$$
\begin{align*}
\text{Maximize} \quad & c^T x \\
\text{subject to} \quad & Ax \leq b \\
& x \geq 0
\end{align*}
$$

Em que x representa o vetor de variáveis de decisão, c e b são vetores de coeficientes conhecidos e A é uma matriz de coeficientes conhecidos. A função objetivo $c \cdot x$ pode ser maximizada ou minimizada. As inequações $A \cdot x \leq b$ são as restrições. A restrição de não negatividade é representada por $x \ge 0$.

## Bonuses and Merits

# Integer programming
# Nonlinear programming
# Network modelling
# Inventory theory
# Queueing theory
# Tree decision
# Games theory
# Dynamic programming and
# Markov processes

# Disclaimer
Este arquivo possui anotações, resumos, fichamentos e insights **pessoais** sobre estudos. Ele não possui materiais derivados.

# References
- Poler, R., Mula, J., & Díaz-Madroñero, M. (2014). *Operations research problems: Statements and solutions*. Springer-Verlag.
