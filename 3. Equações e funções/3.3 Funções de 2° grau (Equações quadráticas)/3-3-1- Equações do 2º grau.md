# 3.3.1. Equações do 2º grau


```
	**A matemática é como um videogame: no início você apanha, mas quando entende as regras, começa a se divertir.**

```


## 🧠Introdução
	Se a equação do 1° grau era uma linha reta, a equação do 2° grau é uma curva com atitude – ela não quer só equilibrar uma balança, quer fazer um show no gráfico 🎢.
	Aqui o nosso querido 𝑥 aparece elevado ao quadrados, e isso muda tudo.
	A estrutura clássica é:
		𝑎𝑥<sup>2</sup> +  <span style="font-family: STIXTwoMath-Regular;">
     𝑏
 </span> +  <span style="font-family: STIXTwoMath-Regular;">
     𝑐
 </span> = 0
	Onde:
		* 𝑎, 𝑏, 𝑐 são números reais (e 𝑎 ≠ 0, por que se fosse 0, voltaria a ser de 1° grau);
		* 𝑥 é a incógnita (a estrela do show).

## 🎯O objetivo continua o mesmo
	Descobrir o valor de x que faz essa equação funcionar, ou sejam que faz os dois lados ficarem em equilíbrio. 

## 💡 **Tipos de equações do 2º grau que você pode encontrar:**
	1. **Equações literais (com parâmetros)** – o x aparece elevado ao quadrado, como em 𝑎𝑥<sup>2</sup> +  <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑏
 </span>𝑥 +  <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑐
 </span> = 0, e ainda existem letras representando valores desconhecidos, tipo custos extras da pizzaria ou ingredientes variáveis.
	9. **Equações com radicais** – o x² aparece dentro de uma raiz, por exemplo √( <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑥
 </span><sup>2</sup> + 2 <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑥
 </span>) = 5, e para resolver você eleva ambos os lados ao quadrado, ficando  <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑥
 </span><sup>2</sup> + 2 <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑥
 </span> = 25.
	21. **Equações com frações** – o x² aparece no numerador ou denominador, como (( <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑥
 </span><sup>2</sup> + 3 <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑥
 </span>) / 2) = 5, e para encontrar o x você multiplica ambos os lados por 2, obtendo  <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑥
 </span><sup>2</sup> + 3 <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑥
 </span> = 10 e então resolve como uma quadrática normal.

## **💡Exemplo lógico**
	Supondo sua visão empreendedora 😎, você decidiu abrir uma **pizzaria delivery dentro da faculdade**, pra competir com o RU (Restaurante Universitário). Depois de alguns dias de funcionamento, você percebeu algo importante:
		“Preciso saber quanto preciso vender para não sair no prejuízo e quando começo a estourar a banca.”
	Você fez as contas rápidas e chegou às seguintes conclusões realistas:
| Situação                                                                                    | Quantidade de pizzas vendidas (x)                                                           | Lucro (R$)                                                                                  |
|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| Mesmo sem vender nada, já gasta com ingredientes estragando, energia do salão e taxa do app | 0                                                                                           | -8                                                                                          |
| Quando vende 2 pizzas, já começa a equilibrar as contas                                     | 2                                                                                           | 0                                                                                           |
| Quando vende 4 pizzas, o lucro é o máximo (tudo dá certo)                                   | 3                                                                                           | 1                                                                                           |
| Mas se vender 6 pizzas, o lucro cai de novo (muitos custos extras)                          | 6                                                                                           | -8                                                                                          |

		Esses valores de lucro mostram um comportamento que sobe e depois desce – o formato perfeito de uma parábola, ou seja, uma equação do 2° grau. Com um calculo simples você pode descobrir quando você alcançou o topo e quando você beijou a lona.
	Sabendo que o formato geral é:
		L(𝑥) = 𝑎𝑥<sup>2</sup> +  <span style="font-family: STIXTwoMath-Regular;">
     𝑏
 </span>𝑥 +  <span style="font-family: STIXTwoMath-Regular;">
     𝑐
 </span> = 0

	Onde:
		* L(𝑥) é o lucro (em reais);
		* x é o numero de pizzas vendidas;
		* 𝑎, 𝑏, 𝑐 são números que descrevem a curva (cada um com um papel bem claro).
	
	🎯**Como escolheremos os valores de a, b e c:**
		* 𝑎 = -1 → indica que a parábola é “virada para baixo”, porque o lucro aumenta ate um ponto e depois cai (exatamente como no seu negócio). O sinal negativo representa o limite do crescimento.
 <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     		* 𝑏
 </span> = 6 → Seria o valor arbitrário de cada pizza sem deduzir os custos da sua manufatura, armazenamento ou distribuição, em outras palavras, nossa pizza custaria 6 reais (eu acho que isso tá mais pra brusqueta).
		* 𝑐 = -8 é o lucro inicial, quando você ainda não vendeu nada (prejuízo de R$ 8,00).
		Assim, nossa equação do lucro fica:
			L(𝑥) = -𝑥<sup>2</sup> + 6𝑥 - 8 = 0
		Aqui podemos ver que se x é o numero de pizzas vendidas, e se você vender 0 pizzas, você terá um prejuízo de R$ 8,00, pois zeraria as 2 incógnitas.
	
	🧩 **Testando os valores**
| x (pizzas vendidas) | Cálculo             | L(x)                |
|---------------------|---------------------|---------------------|
| 0                   | −02+6(0)−8          | -8                  |
| 2                   | −22+6(2)−8=−4+12−8  | 0                   |
| 3                   | −32+6(3)−8=−9+18−8  | 1                   |
| 4                   | −42+6(4)−8=−16+24−8 | 0                   |
| 5                   | −32+6(3)−8=−9+18−8  | -3                  |

		Perceba como:
			* O lucro aumenta até um ponto máximo (entre 3 e 4 pizzas);
			* e depois começa a cair.

 <span style="font-family: .AppleColorEmojiUI;">
     	📈
 </span> **Interpretação**
		* Se vender menos de 2 pizzas, ainda está no prejuízo.
		* Entre 2 e 4 pizzas está no lucro.
		* Passando disso, o custo começa a vencer o ganho.
		Ou seja, o equilíbrio (lucro zero) acontece quando:
			L(𝑥) = 0 ⇒ -𝑥<sup>2</sup> + 6𝑥 - 8 = 0
		E resolvendo essa equação, encontramos os pontos de equilíbrio:
			𝑥’ = 2 e 𝑥’’ = 4
	
## 🧮Exemplo prático
	Suponha que, na sua pizzaria, o lucro L(𝑥) dependa do número de pizzas vendadas 𝑥 assim:
		L(𝑥) = -𝑥<sup>2</sup> + 6𝑥 - 8
	Queremos saber quando o lucro será zerado (ponto de equilíbrio).
		1. Identificar 𝑎, 𝑏, 𝑐:
			L(𝑥) = -𝑥<sup>2</sup> + 6𝑥 - 8
				𝑎: -1
				𝑏: 6
				𝑐: -8
		1. Calcular o Delta (Δ):
			Δ =  <span style="font-family: STIXTwoMath-Regular;">
     𝑏
 </span><sup>2</sup> - 4 × 𝑎 ×  <span style="font-family: STIXTwoMath-Regular;">
     𝑐
 </span> 
			Substituindo fica:
				Δ = 6<sup>2</sup> - 4 × (-1) × (-8) 
				Δ = 36 - 32
				Δ = 4
			💡 **Dica rápida:**
				Sempre comece pelo Delta (Δ)!
				Ele mostra quantas vezes o gráfico da parábola cruza o eixo x:
					* Se Δ > 0, ou seja, se o delta dor positivo, há 2 soluções (em outras palavras a parábola cruzará em 2 pontos diferentes).
					* Se Δ = 0, ou seja, se o delta for zero você, no fim haverá apenas 1 solução (em outras palavras a parábola cruzará em apenas 1 ponto)
					* Se Δ < 0, ou seja, se delta for negativo você não terá uma solução dentro dos conjuntos dos reais, o que geralmente é as precondições em exercícios até Calculo I (em outras palavras, sua parábola não tocará o eixo x em nenhum ponto.)
		1. Aplicamos a fórmula de Bhaskara:
			𝑥 = ( -𝑏 ± √Δ ) / ( 2 × 𝑎 )
			Substituindo fica:
				𝑥 = ( -6 ± √4 ) / ( 2 × (-1) )
				𝑥 = ( -6 ± 2 ) / -2 
		1. Separando as soluções (2 soluções já que o delta é um numero positivo):
			𝑥’ = ( -6 -2 ) / - 2
			𝑥’ = -8 / -2
			𝑥’ = 4
				Logo temos o valor para 𝑥’, agora vamos descobrir o 𝑥’’
			𝑥’’ = ( - 6 + 2 ) / -2
			𝑥’' = -4 / -2
			𝑥’' = 2
				Agora temos os resultados de 𝑥’ e 𝑥’’, são os pontos onde nossa parábola cruz o eixo x.

## ✅Resumo
	O lucro será **zero** quando você vender **2 ou 4 pizzas**.
		Isso significa que:
			* 🍕 **Menos de 2 pizzas** → prejuízo (você ainda não cobriu seus custos fixos)
			* 🍕 **Entre 2 e 4 pizzas** → lucro positivo (a pizzaria está no azul!)
			* 🍕 **Mais de 4 pizzas** → o custo começa a crescer mais rápido que o ganho, reduzindo o lucro novamente
	💡 Agora que você entende **onde o lucro zera e onde ele cresce**, é possível identificar **onde seus cálculos — ou seus preços — precisam ser ajustados** para aumentar o resultado no final do dia (podemos ver claramente que o valor da sua pizza é extremamente baixo, o que as vezes não paga seus custos).

