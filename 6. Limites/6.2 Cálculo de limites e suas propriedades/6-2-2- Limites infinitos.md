# 6.2.2. Limites infinitos


# 🧠Introdução
	Nos conceitos de limite, vimos que um limite pode assumir diferentes comportamentos. Utilizando a metáfora da ponte, aprendemos que:
		* 🌉 Uma ponte nova represa uma função contínua, em que o limite existe e coincide com o valor da função.
		* 🕳️ Buraco representa uma descontinuidade removível: A função falha em apenas um ponto, mas o limite continua existindo.
		* 📉 Precipício (ou abismo) representa uma situação completamente diferente: A função deixa de caminha para um número e passa a crescer ou diminuir sem limites, formando as famosas **Assíntota**.
	É justamente esse último que estudaremos agora. Já  estudamos situações em que a função se aproxima de um número específico. Por exemplo, vimos funções que tendiam para:
		* 49;
		* 2;
		* 10;
		* 25.
	Agora super uma nova pergunta:
		> “E se a função nunca parar de crescer?”
	Ou ainda:
		> “E se ela nunca parar de diminuir?”
	Nesse caso, não existe um número para o qual a função esteja caminhando. Ela Cresce (ou decresce) sem limites. É justamente essa situação que estudaremos agora.

# 🎯 Exemplo lógico
	Imagine que você está caminhando por uma ponte sobre um abismo, no início, o caminho é seguro e contínuo. Mas, de repente, a ponte termina em um enorme precipício. Você se aproxima cuidadosamente da borda, olha pra baixo, mas não enxerga o fundo. Quanto mais tenta olhar, mais sensação é de que a queda nunca termina. Ela continua indefinidamente. Neste momento, você percebe que não existe um ponto final para onde olhar, e a única conclusão possível é:
		> A profundidade aumenta sem fim.
	Ao nos aproximarmos de determinado ponto, a função não caminha para um número específico. Em vez disso, seus valores crescem ou diminuem indefinidamente. Por esse motivo, utilizamos os símbolos:
		+∞
	ou
		-∞
# **🧮 Exemplos prático**
	Agora vamos transformar essa ideia em matemática. Imagine que a variável 𝑥 represente a distância que ainda falta para chegar à borda do precipício. Quanto mais caminhamos, menor fica essa distância, e maior fica a profundidade observável dentro do abismo.
| Distancia até a borda (𝑥)     | Profundidade Observável (1/𝑥) |
|-------------------------------|-------------------------------|
| 1 m                           | 1                             |
| 0,5 m                         | 2                             |
| 0,1 m                         | 10                            |
| 0,001 m                       | 100                           |
| 0,0001 m                      | 1000                          |

	Perceba que, conforme a distância até a borda diminui, a profundidade observada aumenta cada vez mais. Em linguagem matemática:
		* 𝑥 está ficando cada vez menor;
		* (1/𝑥) está ficando cada vez maior.
	Escrevemos isso como:
		lim <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑥</sub>
 </span><sub>→0</sub>+ <span style="font-family: STIXTwoMath-Regular;">
     𝑓
 </span>( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = +∞
	Observe como a tabela conta exatamente a mesma história da metáfora. Quando ainda tamo a 1 metro da borda, enxergamos apenas uma pequena profundidade, ao chegar a 10 centímetros, a profundada já parece muito maior, a 1 centímetros, maior ainda, a 1 milímetros maior novamente. Quanto mais nos aproximamos da borda, mais a profundidade parece crescer, sem que consigamos enxergar um fundo. 
	Matematicamente, acontece exatamente a mesma coisa, à medida que 𝑥 se aproxima de zero, os valores da função aumenta indefinidamente, por isso podemos dizer que o limite tende a:
		+∞
	
	**🔄E se olharmos do outro lado?**
		Agora imagine que seu amigo está do outro lado da ponte, ele caminha no sentido contrário ao seu, ou seja, se aproximando na sua direção, a diferença é que agora convencionamos essa distância como negativa:
| Distancia até a borda (𝑥)     | Profundidade Observável (1/𝑥) |
|-------------------------------|-------------------------------|
| -1 m                          | -1                            |
| -0,5 m                        | -2                            |
| -0,1 m                        | -10                           |
| -0,001 m                      | -100                          |
| -0,0001 m                     | -1000                         |

		A profundidade continua aumentando sem fim. A única diferença é que, matematicamente os valores são negativos, logo escrevemos:
			lim <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑥</sub>
 </span><sub>→0</sub>- <span style="font-family: STIXTwoMath-Regular;">
     𝑓
 </span>( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = -∞
	Percebe a diferença? Agora não existe dois exemplos, existe uma única história:
		* A distância até a borda é o  <span style="font-family: STIXTwoMath-Regular;">
     𝑥;

 </span>		* A profundidade observada é  <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑓
 </span>( <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑥
 </span>) = (1/𝑥);
		* Caminhar até a borda é fazer  <span style="font-family: STIXTwoMath-Regular; font-size: 15.662651;text-align: left;">
     𝑥
 </span>→0;
		* O fundo que nunca aparece é o +∞ ou -∞.

# 📝 Resumo
	* Limite infinito ocorre quando a função não se aproxima de um número finito, mas cresce ou diminui indefinidamente.
	* O símbolo +∞ indica que os valores da função crescem sem limite.
	* O símbolo -∞ indica que os valores da função diminuem sem limite.
	* Um dos casos mais comuns acontece quando o denominador se aproxima de zero, fazendo com que o resultado da divisão aumente ou diminua indefinidamente.
	* Na metáfora da ponte, esse comportamento é representado por um precipício: Quanto mais nos aproximamos da borda, maior parece a profundidade, sem que exista um fundo visível.

	📌**Como reconhecer um limite infinito?**
		Ao calcular um limite, pergunte-se:
			* A função está caminhando para um número?
				* ✅ Sim → Trata-se de um limite finito.
				* ❌ Não → Observe o comportamento:
					* Se cresce sem parar → +∞
					* Se diminui sem parar → -∞
	
	🎯 **Regra para lembrar na prova**
		Sempre observe o comportamento da função durante a aproximação:
			* Se ela se estabiliza em um número, esse número é o limite.
			* Se ela crescer ou diminuir separar, estamos diante de um limite infinito.
			* Os símbolos +∞ ou -∞ não representam um número, mas sim o comportamento da função durante a aproximação.
