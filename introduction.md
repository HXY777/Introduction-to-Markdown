# Hello, this is a brief introduction of MD
> Use **# Hello, this is a brief introduction of MD** to make title of this file.
## 1. Insert code block   
> You can use ## 1. Insert Code block to make this section title. The following code block is the result of  
>\`\`\`python 
>import numpy as np
>a = np.array([1,2,3])
>print('Hello, world!')
>\`\`\`

```python
import numpy as np
a = np.array([1,2,3])
print('Hello, world!')
```

## 2. Insert inline code:
For example, if you want to insert inline code, you can use \`from matplotlib import pyplot as plt\`. The outcome looks like this -`from matplotlib import pyplot as plt`

## 3. Anotherway to implement different levels...
> \#, \#\# and \#\#\# can be used to make different levels of headlines
> Another way to make different level is presented below: 
>?
>\-\-\-
>?
>\=\=\=

? 
-----
?
=========================
* * *
If you want a line to separate contents, try `* * *` or `______`.

______________________

## 4. Mathematical expression:
First we need to install *==Markdown Preview Enhanced==* to enable Latex equation editting. This extension contains many other useful features.
>Need to enable **enableExtendedTableSyntax** in ***extension settings*** to enable table cells merge.

> Highlight content by `== text you want to highlight ==`.
### Inline Equation
The dollar sign `$ write equation here $` is used to write inline equation.
For example, `$ \sum_{\forall i}{x_i^{2}} $` will generate $ \sum_{\forall i}{x_i^{2}} $.     
We say function $f$ is continuous at point $x_0$ if $\forall{\epsilon}>0, \exist{\delta}\gt{0}$ such that  $| f(x) - f(x_0) | \lt \epsilon$ for all $x$ lies in the neighbourhood $(x_0-\delta, x_0+\delta)$.

Use `:--|:--:|--:` to set table alignment. In this exmple, there are 3 columns in the table where first columns aligns to left, second column aligns to center and last column alians to right. You can merge cells to upper row by `^`. When one cell is empty, will merge to left column.

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
> The syntax to write equations or expressions with alignment: 
>\begin{aligned}
> Statement1 &\Rightarrow s2 \quad (1)\\\\
>  &\Rightarrow s3 \\\\
>  &\Leftrightarrow s4 
>\end{aligned}

$$
\begin{aligned}
Statement1 &\Rightarrow s2 \quad (1)\\
  &\Rightarrow s3 \\
  &\Leftrightarrow s4 
\end{aligned} 
$$




