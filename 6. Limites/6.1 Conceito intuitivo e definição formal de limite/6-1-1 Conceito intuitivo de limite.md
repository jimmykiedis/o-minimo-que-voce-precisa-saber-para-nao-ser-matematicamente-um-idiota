# 6.1.1 Conceito intuitivo de limite


	
# 🎯 O que é limite?
	O limite é a ferramenta matemática que responde à pergunta:
		👉”para onde uma função está indo quando a variável se aproxima de um valor especifico?”
	* Nem sempre importa o valor exato da função naquele ponto.
	* Às vezes, a função nem existe nesse ponto (buraco, divisão por zero, etc).
	* O que interessa é o comportamento ao redor..
	📌 Exemplo simples:
		lim<sub>𝑥→7</sub>x<sup>2</sup> = 49
	Mesmo que você não calcule diretamente 7<sup>2</sup>, basta ver que conforme x schega perto de 7, a função chega perto 49.

# ↔️ Aproximação pela esquerda e pela direita
	Para garantir que o limite existe, precisamos olhar de dois lados:
		* Valores menores que 7 (6,9; 6,99; 6,999…)
		* Valores maiores que 7 (7,1; 7,01; 7,001…)
	✔️Se ambos os lados chegam aos mesmo número → limite existe.
	 <span style="font-family: .AppleColorEmojiUI;">
     ❌
 </span>Se cada lado vai para lugares diferentes → limite não existe (bilateralmente).
	📌 Exemplo:
		lim<sub>𝑥→7</sub>𝑓([x / (x - 7)]) = 49
		* Pela esquerda explode para **-∞.**
		* Pela direita explode para +**∞.**
		→Significa que o limite bilateral não existe.

# 🌉 Metáforas para entender limites
	Para compreender os possíveis comportamentos de um limite, vamos utilizar quatro metáforas. Imagine uma ponte atravessando um grande rio. Conforme caminhamos em direção a um ponto específico dessa ponte, podemos encontrar diferentes situações. Cada uma delas representa um resultado possível para o comportamento de uma função.
		1. 🌉 **Ponte nova (contínua):**
			A ponte está completamente intacta. Você consegue caminhar normalmente pela esquerda e pela direita, chegando exatamente ao mesmo ponto, sem precisar parar ou desviar. O que isso significa?
				* ✅ A função está definida nesse ponto;
				* ✅ Logo o limite existe;
				* ✅ O valor da função é igual ao valor do limite. 
	Por exemplo: 
 <span style="font-family: STIXTwoMath-Regular;">
     				𝑓
 </span>( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) =  <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span><sup>2
</sup>			em  <span style="font-family: STIXTwoMath-Regular;">
     𝑥 = 7:
 </span>
				 <span style="font-family: STIXTwoMath-Regular;">
     𝑓
 </span>(7) = 7<sup>2</sup>
	e:
		lim<sub>𝑥→7</sub>𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = 49
	> **Metáfora**> : A ponte está perfeita. Você atravessa sem perceber nenhuma diferença no caminho.

		1. 🕳️ **Buraco (descontinuidade removível):**
			O caminho está perfeito até um determinado ponto da ponte. Porém, exatamente onde você pisaria para prosseguir ali, existe um pequeno buraco. Você consegue caminhar normalmente até a beira dele, tanto pela esquerda quanto pela direita, e consegue até imaginar exatamente onde pisaria se aquele buraco não existisse. Mas, como falta justamente aquele pedaço da ponte, você não consegue colocar o pé naquele ponto.
				* ✅ Os limites laterais chegam ao mesmo valor;
				* ✅ Logo o limite existe;
 <span style="font-family: .AppleColorEmojiUI;">
     				* ❌ A função não está definida naquele ponto (ou seja, foi definida com um valor incorreto)

 </span>			Exemplo:
				 <span style="font-family: STIXTwoMath-Regular;">
     𝑓
 </span>( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = ( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span><sup>2</sup>-1) / ( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>-1)
			Em  <span style="font-family: STIXTwoMath-Regular;">
     𝑥 = 1:

 </span>				* A função pode ser calculada, pois resultada em 0/0;
				* Mas:
					lim<sub>𝑥→1</sub> <span style="font-family: STIXTwoMath-Regular;">
     𝑓
 </span>( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = ( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span><sup>2</sup>-1) / ( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>-1) = 2
	> **Metáfora**> : O caminho existe antes e depois do buraco. Bastaria colocar uma tábua para a estrada ficar perfeita.

		1. 📉 **Abismos ou precipício (Assíntota vertical)**			Você está caminhando normalmente pela ponte. De repente, ela termina em um enorme precipício. Não existe mais chão para continuar. Quanto mais você se aproxima da borda, mais percebe que a queda parece não ter fim. Você tenta enxergar o fundo, mas ele simplesmente não aparece.
 <span style="font-family: .AppleColorEmojiUI;">
     				* ❌ A função não se aproxima de um número;

 </span>				* 📈 Ela cresce ou diminui indefinidamente;
				* Escrevemos isso usando +∞ ou -∞.
			Exemplo:
				 <span style="font-family: STIXTwoMath-Regular;">
     𝑓
 </span>( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = (1/ <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>)
			Quando  <span style="font-family: STIXTwoMath-Regular;">
     𝑥 → 
 </span>0 <span style="font-family: STIXTwoMath-Regular;">
     :
				
 </span>Pela esquerda:
					lim<sub>𝑥→1</sub> <span style="font-family: STIXTwoMath-Regular;">
     𝑓
 </span>( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = -∞
				Pela direita:
					lim<sub>𝑥→1</sub> <span style="font-family: STIXTwoMath-Regular;">
     𝑓
 </span>( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = +∞
	> **Metáfora**> : Não há como “consertar” o caminho colocando uma tábua. A estrada simplesmente caba em um precipício.

		1. 🔄 **Looping infinito (Oscilação)**
			A ponte não segue em frente. Ela entra em um looping interminável. Você continua andando, mas nunca consegue dizer para qual ponto está indo, pois o caminho muda de direção o tempo todo. O que isso significa?
 <span style="font-family: .AppleColorEmojiUI;">
     				* ❌ A função nunca se aproxima de um único valor;

 </span> <span style="font-family: .AppleColorEmojiUI;">
     				* 📉Ela oscila continuamente;

 </span> <span style="font-family: .AppleColorEmojiUI;">
     				* O limite não existe.

 </span>			Exemplo:
				 <span style="font-family: STIXTwoMath-Regular;">
     𝑓
 </span>( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = sin(1/ <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>)
			Quando  <span style="font-family: STIXTwoMath-Regular;">
     𝑥 → 
 </span>0, os valores continuam oscilando entre -1 e 1.
	> **Metáfora**> : Não importa quanto você espere, o caminho nunca aponta para um único destino.

# 🎯 Exemplo lógico
	Vamos tentar sintetizar algo que te leve exatamente ao ponto da pergunta do nosso exemplo lógico: 
		> “O que é Limites, exatamente?”
	Imagine que faltam poucos segundos para a virada do ano. Todos estão reunidos, contando em voz alta:
		10… 9… 8… 7…
	A expectativa e tão grande que o tempo passa mais devagar. Você observa as pessoas sorrindo, os fogos preparados e a ansiedade aumenta a cada segundo. A contagem continua:
		6… 5… 4… 3… 2… 1…
	Cada número está cada vez mais próximo de 0, que representa o instante da virada. Nesse momento, podemos pensar em um limite:
		> À mediada que o tempo restante se aproxima de 0, o instante do Ano Novo se aproxima.
	A idéia do Limite não é perguntar “o que acontece exatamente no 0?” Mas sim observar o comportamento enquanto nos aproximamos dele. Assim como na contagem regressiva, os limites estudam para onde um processo está caminhando antes de chegar ao ponto de interesse, 
	Nesses últimos 10 segundos antes do “feliz Ano Novo” você diz pra si mesmo, “já é Ano Novo?”:
| Tempo restante (s)                                      | O quão perto está do Ano Novo                           |
|---------------------------------------------------------|---------------------------------------------------------|
| 10                                                      | Ainda não, mas falta pouco                              |
| 9                                                       | 1 segundo se passou, mas ainda faltam aproximadamente 9 |
| 5                                                       | Estamos chegando lá                                     |
| 2                                                       | Já posso ouvir o Champagne se abrindo na minha mente    |
| 1                                                       | *Prende a respiração                                    |
| 0,1                                                     | Tudo tá em camera lenta                                 |
| 0,01                                                    | Todos já estão tomando ar para gritar                   |
| 0,001                                                   | Você já não sabe mais dizer se já é ou não ano novo     |

	Perceba que todos esses valores estão se aproximando de 0. Na matemática, escrevemos essa ideia como:
		𝑡 → 0
	Que se lê:
		> O tempo 𝑡 tende a zero

	Significa apenas que estamos observando valores cada vez mais próximos de zero. É exatamente isso que acontece em um limite: Não perguntamos qual é o valor em um ponto, mas o que acontece conforme nos aproximamos dele. E neste caso, a resposta a pergunta do exemplo lógico seria:
		> “O momento mais importantes e aguardado do ano são aqueles 10 derradeiros segundos até o seu fim. Ou seja, tanto faz a virada do ano, se o momento de mais ansiedade são os seus últimos 10 segundos.”

# **🧮 Exemplos pratico**
	Usando o exemplo lógico como base, podemos considerar uma função semelhante à essa:
		𝑓(𝑡) = 10 - 𝑡
	Ela representa a quantidade de segundos que já passaram desde o início da contagem regressiva. Observe alguns valores:
| 𝑡     | 𝑓(𝑡)  |
|-------|-------|
| 9     | 1     |
| 9,9   | 0,1   |
| 9,99  | 0,01  |
| 9,999 | 0,001 |

	Percebe que, à medida que:
		𝑡 → 10
	Os valores da função ficam cada vez mais próximos de:
		0
	Então escrevemos:
		lim <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑡</sub>
 </span><sub>→10</sub>(10 -  <span style="font-family: STIXTwoMath-Regular;">
     𝑡) = 0
	
 </span>Lemos essa expressão da seguinte forma:
		> “O limite de 10 - 𝑡, quando o 𝑡 tende a 10, é igual a 0.”

# **💡O que acabais de fazer?**
	Sem perceber, respondemos exatamente à pergunta que fizemos lá em “O que é limite”:
		> “Para onde a função está indo quando a variável se aproxima de um determinado valor?”

	Nese exemplo:
		* A variável 𝑡 está se tendendo a se aproximar de 10;
		* A função 10 -  <span style="font-family: STIXTwoMath-Regular;">
     𝑡 
 </span>está se aproximando de 0.
	Esse é o primeiro contato com um calculo de limite: Observar o comportamento da função conforme a variável se aproxima de um valor.

# 🌎 Aplicação da vida real
	Limites não são só abstrações, eles aparecem em várias situações práticas:
		1. 🚗Velocidade instantânea:
			* Quando você olha o velocímetro, está vendo a variação de posição quando o tempo tende a um intervalo cada vez menor.
			* Isso é ruim limite → base da derivada
		2. 💉Concentração de remédio no sangue:
			* A taxa de absorção é estudada vendo como a função se comporta em instantes muito próximos.
		3. 📈Economia e tendências:
			* Limite quando → **+∞:** Prever para onde vai o custo ou o lucro de uma empresa no longo prazo.
		4. 🛰️ Engenharia
			* Estruturas precisam saber o que acontece quando o esforço tende a valores críticos (limite de resistência).
		5. 🕹️Computação gráfica:
			* Renderizar curvas suaves exige cálculo de limites (por trás das derivadas e integrais);

# 📝 Resumo
	* **Limite:** descreve o comportamento de uma função à medida que a **variável se aproxima de um determinado valor**.
	* **Limites laterais:** verificam esse comportamento por **ambos os lados da aproximação**, isto é, pela esquerda (a<sup>-</sup>) e pela direita (a<sup>+</sup>)
	* **Regra fundamental:** um limite só existe quando a aproximação pela esquerda e pela direita conduz ao **mesmo resultado**.
| Metáfora                                                          | O que acontece com a função?                                      | O limite existe?                                                  |
|-------------------------------------------------------------------|-------------------------------------------------------------------|-------------------------------------------------------------------|
| 🌉 Ponte nova                                                      | Tudo está contínuo e sem interrupções                             | ✅ Sim!                                                            |
| 🕳️ Buraco                                                          | Falta apenas um ponto, mas o caminho continua antes e depois dele | ✅ Sim!                                                            |
| 📉 Abismo ou precipício                                            | A função cresce ou diminui sem limite.                            | ❌ Não! (não há valor finito para o qual ela tende)                |
| 🔁 Looping                                                         | A função oscila e nunca se aproxima de um único valor.            | ❌ Não!                                                            |

