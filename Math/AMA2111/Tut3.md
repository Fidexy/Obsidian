## Finite-dimensional vector space
$$
\begin{align}
\{\vec{v_1}, \vec{v_2} ... \vec{v_n}\} \neq \phi\\
\text{span} \{\vec{v_1}, \vec{v_2} ... \vec{v_n}\}=\{t_1\vec{v_1}+t_2\vec{v_2}+ ... +t_n\vec{v_n}|t_1, t_2,...,t_n \in \mathbb{R}\}
\end{align}
$$
## Linear independance
$$
\begin{align}
\{\vec{v_1}, \vec{v_2} ... \vec{v_n}\} \text{ is linearly independent if}\\
t_1\vec{v_1}+t_2\vec{v_2}+ ... +t_n\vec{v_n}=\vec{0}
\end{align}$$
# Questions

$$
\begin{align}
\text{1a}\\
&\text{span}\{(1,0,0),(0,1,0),(0,0,1)\}\\
&=\{x(1,0,0)+y(0,1,0)+z(0,0,1)|x,y,z\in \mathbb{R}\}\\
&=\{(x,y,z)|x,y,z\in \mathbb{R} \}\mathbb{R}^3\\
\\
\text{1b}\\
&\text{span}\{(1,1,0),(1,0,0),(0,1,0),(0,0,1)\}\\
&=\{a(1,1,0)+b(1,0,0)+c(0,1,0)+d(0,0,1)|a,b,c,d \in \mathbb{R}\}\\
&=\{(a+b. a+c, d)| a,b,c,d \in \mathbb{R}\}=\mathbb{R}^3\\
&\text{They both span } \mathbb{R}^3\\
\\
2\\
&\vec{v_1},\vec{v_2},\vec{v_3} \text{are linearly independant}\\
&\Leftrightarrow 
\begin{pmatrix}
0&1&0&|&0\\
1&2&6&|&0\\
-2&2&2&|&0\\
4&5&\beta&|&0
\end{pmatrix}\text{has only trivial solutions}\\
&\begin{pmatrix}
0&1&0&|&0\\
1&2&6&|&0\\
-2&2&\alpha&|&0\\
4&c&\beta&|&0
\end{pmatrix}\rightarrow\begin{pmatrix}
1&0&6&|&0\\
0&1&0&|&0\\
0&0&\alpha+12&|&0\\
0&0&\beta-24&|&0\\
\end{pmatrix}\\
&\therefore\vec{v_1}, \vec{v_2},\vec{v_3}\text{are linearly independant}\Leftrightarrow\alpha+12\neq0\text{or} /beta-24 \neq 0
\Leftrightarrow \alpha \neq -12 \text{or} \beta \neq 24 
\end{align}
$$
### 22/23 Sem1
$$
\begin{bmatrix}
1&3&2&-1&|&1\\
2&5&2&-3&|&0\\
1&0&-a&-5&|&-b\\
3&7&2&a&|&-2
\end{bmatrix}\rightarrow \dots\rightarrow
\begin{bmatrix}
1&3&2&-1&1\\
0&1&2&1&|&2\\
0&0&4-a&-1&|&5-b\\
0&0&0&a-5&|&3\\
\end{bmatrix}$$
b(i)
$$
[\vec{v_1},\vec{v_2},\vec{v_4},\vec{v_5}]\rightarrow
\begin{bmatrix}
1&3&-1&1\\
0&1&1&2\\
0&0&-1&5-b\\
0&0&a+5&3\\
\end{bmatrix} \rightarrow \begin{bmatrix}
\alpha&3&-1&1\\
0&\beta&1&2\\
0&0&\alpha&\beta-5\\
0&0&0&3-(a+5)(b-5) 
\end{bmatrix} \begin{pmatrix}1\\0\\0\\0 \end{pmatrix}\\
\text{span}\{\vec{v_1},\vec{v_2},\vec{v_4},\vec{v_5}\}=\mathbb{R_4}\Rightarrow 3 \neq (a+5)(b+5)
$$