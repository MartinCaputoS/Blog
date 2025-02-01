# Construcción de los números reales $\mathbb{R}$

Decimos que una sucesión de números racionales $a_n:\mathbb{N}\to\mathbb{Q}$ es Cauchy, si y solo si,

$$\forall \varepsilon \in \mathbb{Q}^{+},\exists N\in \mathbb{N},\forall n,m \geq N, \vert a_n-a_m \vert < \varepsilon.$$

Dos sucesiones Cauchy $(a_n)$ y $(b_n)$ son equivalentes, si y solo si,

$$\forall \varepsilon >0,\exists N\geq 0, \forall n\geq N, \vert a_n-b_n \vert<\varepsilon.$$

En tal caso escribimos $(a_n)\sim_C (b_n)$ (es posible demostrar que es una relación de equivalencia). Un número real es una clase de equivalencia bajo $\sim_C$, es decir, $\llbracket(a_n)\rrbracket:=\{(x_n): (x_n)\sim_C(a_n)\}$. El conjunto de los números reales es

$$\mathbb{R}:=\{\llbracket(a_n)\rrbracket: (a_n) \text{ es Cuachy}\}.$$


Podemos definir $+_{\mathbb{R}},\cdot_{\mathbb{R}}$ y $<_{\mathbb{R}}$. Sean $\llbracket(a_n)\rrbracket,\llbracket(b_n) \rrbracket \in \mathbb{R}$,  

$$\llbracket(a_n) \rrbracket<_{\mathbb{R}}\llbracket(b_n) \rrbracket \iff \exists\varepsilon\in\mathbb{Q}^+,\exists N\in \mathbb{N}, \forall n\geq N, a_n\leq b_n-\varepsilon.$$ 

$$\llbracket(a_n) \rrbracket+_{\mathbb{R}} \llbracket(b_n) \rrbracket:=\llbracket(a_n+b_n) \rrbracket.$$

$$\llbracket(a_n) \rrbracket\cdot_{\mathbb{R}} \llbracket(b_n) \rrbracket:=\llbracket(a_n\cdot b_n) \rrbracket.$$

Es posible demostrar que estas operaciones y relaciones están bien definidas, es decir, que no dependen de la sucesión representativas $(a_n)$, $(b_n)$ que se escojan de sus clases de equivalencia. Esto se reduce a demostrar que si $(a_n),(a_n') \in \llbracket(a_n) \rrbracket$ y $(b_n),(b_n') \in \llbracket(a_n) \rrbracket$, entonces, 

$$\llbracket(a_n) \rrbracket<_{\mathbb{R}}\llbracket(b_n) \rrbracket \iff \llbracket(a_n') \rrbracket<_{\mathbb{R}}\llbracket(b_n') \rrbracket,$$

$$(a_n+b_n) \sim(a_n^{\prime}+b_n^{\prime}),$$ 

$$(a_n \cdot b_n) \sim( a_n^{\prime} \cdot b_n^{\prime}) .$$

Por último, podemos encajar $\mathbb{Q}$ en $\mathbb{R}$. Dado un racional $q$, el número real correspondiente es $\llbracket(q_n)\rrbracket$, donde $(q_n)$ es la sucesión constante $q_n=q$ para todo $n\in\mathbb{N}$ (que claramente es de Cauchy). Establecido lo anterior, podemos asegurar que $\mathbb{R}$ es al menos igual en estructura que $\mathbb{Q}$, es decir, es un cuerpo ordenado, posee la propiedad Arquimediana, es denso, etc. Pero ¿Tendrá alguna ventaja por sobre $\mathbb{Q}$? ¿Habrá alguna propiedad que se cumpla en $\mathbb{R}$ pero no en $\mathbb{Q}$? Si; la propiedad del SUPREMO:

Si $E\subseteq \mathbb{R}$ es un conjunto no vacío y acotado superiormente en $\mathbb{R}$, entonces posee una menor cota superior llamada "supremo".

Antes de demostrar que esto se cumple para cualquier subconjunto de $\mathbb{R}$, demostramos que: $\exists A\subseteq \mathbb{Q}$, no vacío y acotado superiormente en $\mathbb{Q}$, donde no existe una menor cota superior. Por lo que $\mathbb{R}$ es "mejor". 


