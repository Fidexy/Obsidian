Fact 1: Eigenvectors corresponding to different eignvalues must be linearly independent

Fact 2: If A is symmetric i.e. $A=A^T$, then eigenvectors corresponding to different eifenvalues must be orthogonal

Fact 3: Symmetric matrices must be diagonalizable

$$
\begin{align}
&AP=PD\\
&\{\vec{w_1},\vec{w_2},\vec{w_3}\}\\
&\text{is orthonormal if }\\
\text{(1) } &\vec{w_1^T}\vec{w_j}=0 \text{ when }i \pm j\\
\text{(2) } &||\vec{w_i}||^2=1 \text{ for all } i\\
&Q = (vec{w_1},\vec{w_2},\vec{w_3})\\
&A = QPQ^T,\\
&Q^TQ=I
\end{align}
$$

12. For eignevalue $\lambda$:
$$\begin{bmatrix}
2-\lambda&-1&1\\
-1&2-\lambda&1\\
2&1&2-\lambda
\end{bmatrix}
\\
\text{if } \lambda=3, \text{ then}\\
\begin{bmatrix}
-1&-1&1&|&0\\
-1&-1&1&|&0\\
1&1&-1&|&0\\
\end{bmatrix}\rightarrow
\begin{bmatrix}
1&1&-1&|&0\\
0&0&0&|&0\\
0&0&0&|&0\\
\end{bmatrix}\\
\therefore \vec{v_1}=\begin{bmatrix}-1\\1\\0\end{bmatrix}, \vec{v_2}=\begin{bmatrix}1\\0\\1\end{bmatrix}
\vec{w_1}=\frac{\vec{v_1}}{||\vec{v_1}||}=\begin{bmatrix}\frac{1}{\sqrt2}\\\frac{1}{\sqrt2}\\0\end{bmatrix}, 
\\
\text{if } \lambda=0, \text{ then}\\
\begin{bmatrix}
2&-1&1&|&0\\
-1&2&1&|&0\\
2&1&2&|&0\\
\end{bmatrix} \rightarrow \dots \rightarrow
\begin{bmatrix}
1&0&1&|&0\\
0&1&1&|&0\\
0&0&0&|&0\\
\end{bmatrix}\\
\therefore \vec{v_3}=\begin{bmatrix}-1\\-1\\1\end{bmatrix}\\
\vec{w_3}=\frac{\vec{v_3}}{||\vec{v_3}||}=\begin{bmatrix}\frac{1}{\sqrt3}\\\frac{1}{\sqrt3}\\0\end{bmatrix}\\
$$