# 4.2. Distância entre dois pontos

# **4.2.** Distância entre dois pontos

# 📐Introdução:
	Imagine 2 pontos desenhados em um plano cartesiano:
		A(x<sub>a</sub>, y<sub>a</sub>) e B(x<sub>b</sub>, y<sub>b</sub>)
	A distância entre esses dois pontos é simplesmente um segmento de reta que liga A até B. Em outras palavras:
		👉Distância = quando precisamos percorrer em linha reta para sair de um ponto e chegar ao outro.
	Para trabalha com esse conceito, precisamos conhecer o plano cartesiano, formando por dois exios:
		* Eixo X → representa a posição horizontal.
		* Eixo Y → representa a posição vertical.
	Cada ponto é identificado por um par ordenado (x, y). Por exemplo:
		📍A(2, 3) significa:
			* Andar 2 unidades na horizontal;
			* Andar 3 unidades na vertical.
		📍B(7, 5) significa:
			* Andar 7 unidades na horizontal;
			* Andar 5 unidades na vertical.
	A nossa pergunta será:
	> Qual será a distância em linha reta entre A e B?

# 🧮Exemplos lógicos
	Antes de chegar à fórmula geral, vamos analisar situações simples. Isso ajuda a entender por que a fórmula existe:
## 
## Caso 1 - Pontos na horizontal ↔️
	Considere:
		A(2, 3)
		B(7, 3)
	Observe que os dois pontos possuem o mesmo valor de Y:
		y<sub>b</sub> = y<sub>a</sub> = 3
	Portanto, estão na mesma altura. Podemos imaginar que:
		A ⚪️——————⚪️ B
	Como estamos andando somente na horizontal, basta calcular a diferença entre valores de X:
		d =  x<sub>b </sub>- x<sub>a
</sub>	Substituindo:
		d = 7 - 2
		d ￼
	Portanto:
		📏A distância entre A e B é 3 unidades.
### 	Mas e se os pontos estiverem invertidos?
		Imagine:
			A(7, 3)
			B(2, 3)
		Teríamos:
			d = 2 - 7
			d ￼
		Por convenção lógica, distâncias não podem ser negativas. Por isso usamos o valor absoluto:
			d = |x<sub>b </sub>- x<sub>a</sub>|
		Assim:
			d = |2 - 7|
			d = |-5|
			d = 5
	✅Em suma, para pontos horizontais temos a seguinte fórmula:
		d = |x<sub>b </sub>- x<sub>a</sub>|

## Caso 2 - Pontos na vertical ↕️
	Agora considere os seguintes pares ordenados:
		A(2, 3)
		B(2, 5)
	Dessa vez, os dois pontos possuem o mesmo valor de X:
		x<sub>a</sub> = x<sub>b</sub> = 2
	Portanto, estão exatamente na mesma posição horizontal, a diferença acontece somente no eixo Y. Então:
		d = |y<sub>b</sub> - y<sub>a</sub>|
	Substituindo temos:
		d = |5 - 3|
		d = 2
	Visualmente:
		⚪️
		  |
		  |
		  |
		  |
		⚪️
	 ✅Em suma, a distância entre A e B é 2 unidades, valores obtidos a partir de:
		d = |y<sub>b </sub>- y<sub>a</sub>|

## Caso 3 - Quando os pontos estão inclinados ↙️↗️
	Agora chegamos ao caso mais interessante, considere os seguintes pares ordenados:
		A(1, 1)
		B(4, 5)
	Perceba:
		* Os valores de X são diferentes;
		* Os calores de Y também são diferentes.
	Portanto, os pontos não estão nem em uma linha horizontal nem em uma linha vertical. Temos algo parecido com:
	⚪️y<sub>b</sub> |
		  | \
		  |   \
		  |	\
		  |	  \
		  |	    \
		  |	      \
	⚪️y<sub>a</sub>|		\	
	——--+—————-
		⚪️x<sub>a	</sub>⚪️x<sub>b</sub>
	Mas como podemos calcula essa distância? Como? A resposta está no teorema mais famoso da matemática:
		🎉Teorema de Pitágoras🎉
	Perceba que obtemos um triangulo retângulo criando duas movimentações:
### 		Movimento Horizontal:
			De A até ficar diretamente abaixo de B.  A diferença os valores de X é:
				Δx = x<sub>b</sub> - x<sub>a
			</sub>No nosso exemplo:
				Δx = 4 - 1
				Δx = 3
			Então temos 3 unidades horizontais.

### 		Movimento vertical:
			Agora precisamos subir até chegarmos ao ponto B. A diferença entre os valores de Y é:
				Δy= y<sub>b</sub> - y<sub>a
			</sub>No nosso exemplo:
				Δy = 5 - 1
				Δy = 54
			Então temos 4 unidades verticalmente. E agora podemos formar o triangulo retângulo:
				⚪️B<sub> </sub> |\
					  |  \
					  |    \
					  |	 \
				      4 |	   \ d
					  |	     \
					  |	       \
					<sub>  </sub>|		 \	
				⚪️C  |—————⚪️A<sub> </sub>
						3
			Temos:
				* Cateto horizontal (adjacente) = 4
				* Cateto vertical (oposto) = 5
				* Hipotenusa = d
			Portanto:
				d<sup>2</sup> = 3<sup>2</sup> + 4<sup>2</sup>
			Calculando:
				d<sup>2</sup> = 9 + 16
				d<sup>2</sup> = 25
				√d<sup>2</sup> = √25
				d = 5
			✅Portanto:
				A distância entre A(1, 1) e B(4, 5) é 5 unidades.

## Caso 4 - Deduzindo a fórmula geral 🧠
 	Agora podemos generalizar tudo, considere dois pontos quaisquer:
		A(x<sub>a</sub>, y<sub>a</sub>)
		B(x<sub>b</sub>, y<sub>b</sub>)
	Quando criamos o triangulo retângulo, temos dois catetos:
### 		Cateto Horizontal:
			A diferença entre os Xis é:
				Δx = x<sub>b</sub> - x<sub>a
</sub>### 		Cateto Vertical:
			A diferença entre os Ys é:
				Δy= y<sub>b</sub> - y<sub>a
</sub>		Como queremos uma distância positiva, podemos utilizar o a Distância Euclidiana, que consiste no quadrados dessa diferença. Assim, mesmo que uma diferença seja negativa, o resultado será positivo (muito usado para fazer classificação de amostras por uso de IA):
			d = √[(x<sub>b</sub> - x<sub>a</sub>)<sup>2</sup>+(y<sub>b</sub> - y<sub>a</sub>)<sup>2</sup>]
		🎯Essa é a fórmula da distância entre dois pontos, e pra fixar vamos repetir:
			> Diferença dos Xis ao quadrado + diferença dos Ys ao quadrado, tudo dentro da raiz

# ✅Resumo
	O que realmente significa a distância entre dois pontos?
		A distância entre doiss pontos no plano cartesiano é o comprimento do segmento de reta que liga esses dois pontos, ou seja, a distância em linha reta entre eles.
			* Para pontos horizontais basta calcular a diferença entre os valores de X;
			* Para pontos verticais basta calcula a diferença entre os valores de Y.
		Quando os pontos estão inclinados, podemos projeta-los horizontal e verticalmente, formando um triângulo. Nesse triângulo:
			* A diferença entre os Xis forma um cateto;
			* A diferença entre os Ys forma o outro cateto;
			* A distância entre os pontos é a hipotenusa.
	Por isso usamos o Teorema de Pitágoras:
		d<sup>2</sup> = (Δx)<sup>2</sup> + (Δy)<sup>2
</sup>	E consequentemente usamos a Distância Euclidiana:
		d = √[(x<sub>b</sub> - x<sub>a</sub>)<sup>2</sup>+(y<sub>b</sub> - y<sub>a</sub>)<sup>2</sup>]
	🎯 Reforçando para lembrar na hora da prova:
		> A distância entre dois pontos é a hipotenusa de um triângulo retângulo formado pelas diferenças horizontais e verticais entre eles.
