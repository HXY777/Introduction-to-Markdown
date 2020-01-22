# Hello, this is a brief introduction of MD
## 1. Insert code block   
```python
import numpy as np
a = np.array([1,2,3])
print('Hello, world!')
```

## 2. Insert inline code:
For example, if you want to make plots, you can use `from matplotlib import pyplot as plt` to import `matplotlib`... 

## 3. Anotherway to implement different levels...
?
* * *
?
______________________
?
-----
?
=========================

## 4. Mathematical expression:
First we need to install *==Markdown Preview Enhanced==* to enable Latex equation editting. This extension contains many other useful features.
>Need to enable **enableExtendedTableSyntax** in ***extension settings*** to enable table cells merge.
### Inline Equation
For example: $ \sum_{\forall i}{x_i^{2}} $    
We say function $f$ is continuous at point $x_0$ if $\forall{\epsilon}>0, \exist{\delta}\gt{0}$ such that  $| f(x) - f(x_0) | \lt \epsilon$ for all $x$ lies in the neighbourhood $(x_0-\delta, x_0+\delta)$.

Some popular mathematical symbols:
symbol|code|comment
:--:|:--:|:--:
$\forall$ | \forall | for all
$\exist$ | \exist | there exist one or more
$\in$ | \in | belong to 
$\notin$ | \notin | not belong to
$\subset$ | \subset | proper subset
$\subseteq$ | \subseteq | is a subset of 
$\not\subset$ | \not\subset | is not a proper subset of 
$\not\subseteq$ | \not\subseteq | is not a subset of 
$\R$ | \R | real numner 
$\propto$ | \propto | Proportional to 
$\gg$ | \gg | is much greater than
$\ll$ | \ll  | is much less than
$\leq$ | \leq | is less or equal to 
$\geq$ | \geq | is greater or equal to
$\neq$ | \neq | is not equal
$\neg$ | \neg | logical negation 
$\Rightarrow$ | \Rightarrow |  
$\Leftrightarrow$ | \Leftrightarrow | if and only if
$\cap$ | \cap | intersection
$\cup$ | \cup | union
$\vee$ | \vee | similar to intersection (and)
$\wedge$ | \wedge | similar to union (or)
$\because$ | \because | because
$\therefore$ | \therefore | therefore
$\blacksquare$ | \blacksquare | Q.E.D.
$\Box$ | \Box | ^



### Math expression block
$$ \int_{-\infty}^{\infty}e^{-x^2}=\sqrt{2\pi}$$

### Expression alignment
$$
\begin{aligned}
Statement1 &\Rightarrow s2 \quad (1)\\
  &\Rightarrow s3 \\
  &\Leftrightarrow s4 
\end{aligned} 
$$




