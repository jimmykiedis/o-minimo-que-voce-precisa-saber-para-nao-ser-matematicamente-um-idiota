# 6.2.1. Limites laterais


# 🧠Introdução
	Até agora, aprendemos que um limite reponde á pergunta:
		> “Para onde uma função está indo quando nos aproximamos de um determinado valor?”

	Mas existe uma nova pergunta:
		> “E se pudermos chegar nesse valor por caminhos diferentes?”

	Imagine que você está se numa sala fechada, e pretende ligar o ar condicionado para chegar em uma temperatura específica no ambiente. Você pode chegar:
		* Aquecendo;
		* Refrigerando.
	Ou seja, ligando o aquecedor ou o ar condicionado!

	A pergunta é:
		> “Será que, independente do caminho escolhido, chegaremos ao mesmo ponto?”

	Essa é a ideia dos limites laterais.

# 🎯 Exemplo lógico
	Vamos definir uma temperatura padrão como 25°C, que seria o que chamamos de “temperatura ambiente”, a temperatura ideal, sem suor e sem congelar. Agora imagine uma sala com ar-condicionado ligado e definido para essa temperatura padrão. Durante o dia a temperatura está mudando até chegar próxima de 25°C. Podemos observar dois momentos:
## 		A temperatura subindo:
			20°C → 23°C → 24,5°C → 24,9°C
		Ela está se aproximando da temperatura ambiente média:
			25°C
## 		A temperatura está descendo:
			30°C → 27°C → 25,5°C → 25,1°C
		Ela está se aproximando da temperatura ambiente média:
			25°C
	nos dois casos, chegamos ao mesmo valor, a temperatura ambiente. Então podemos dizer:
		> “Não importa se viemos de uma temperatura menor ou maior, o comportamento da temperatura tende ao mesmo ponto.”

	
# **🧮 Exemplos prático**
	Vamos começão pelo exemplo mais fácil: O contínuo, quando há limites e a função existe, ou seja, ela está definida:
		Imagina que lá fora está passando uma onda de extremo calor, e você opta pela maneira mais inteligente de equilibrar a temperatura para uma temperatura mais agradável usando seu novo ar condicionado tipo *inverter*, então você define que a temperatura esperada é a temperatura ambiente, 25°C. A temperatura passa por:
| Temperatura                                                              | Aproximação                                                              |
|--------------------------------------------------------------------------|--------------------------------------------------------------------------|
| 39°                                                                      | Acho que estou febril!                                                   |
| 35°                                                                      | Tenho certeza que peguei algum tipo de insolação!                        |
| 31°                                                                      | Essa temperatura na praia seria ótima                                    |
| 27°                                                                      | Está quente, mas não mais como estava antes                              |
| 25,5°                                                                    | Já estamos quase lá                                                      |
| 25,1°                                                                    | Não dá nem pra sentir a diferença entre a temperatura atual a e esperada |
| 25,01°                                                                   | Se olhar direitinho, o termômetro de mercúrio já diz que é 25°C          |

	Percebemos que:
		𝑇 → 25
	pela direita, porque estamos vindo de valores maiores que 25. Representamos isso como:
		lim<sub>𝑇→25</sub>+f( <span style="font-family: STIXTwoMath-Regular;">
     𝑇
 </span>) = 25
	O simbolo:
		25<sup>+</sup>
	Significa:
		“Estamos chegando em 25 usando valores menores que 25.

	Assim como nos dias quentes, talvez você possa querer usar esse ar condicionado *inverter* para equilibrar a temperatura e deixar você mais confortável:
| Temperatura                                                             | Aproximação                                                             |
|-------------------------------------------------------------------------|-------------------------------------------------------------------------|
| 14°                                                                     | Está praticamente a mesma temperatura lá de fora                        |
| 18°                                                                     | Tá começando a melhorar, já até tirei minhas luvas                      |
| 21°                                                                     | Você está razoavelmente confortável                                     |
| 24°                                                                     | Estamos bem próximos do esperado                                        |
| 24,5°                                                                   | Já estamos quase lá                                                     |
| 24,9°                                                                   | Não dá nem pra sentir a diferença entre a temperatura atua a e esperada |
| 24,99°                                                                  | Se olhar direitinho, o termômetro de mercúrio já diz que é 25°C         |

	Agora estamos chegando em:
		25°C
	Usando valores menores que 25. Então
		lim<sub>𝑇→25</sub>-f( <span style="font-family: STIXTwoMath-Regular;">
     𝑇
 </span>) = 25
	O simbolo:
		25<sup>-</sup>
	Significa:
		> “Estamos chegando em 25 usando valores menores que 25.

## Em suma
	Agora temos:
		Pela esquerda:
			lim<sub>𝑇→25</sub>-f( <span style="font-family: STIXTwoMath-Regular;">
     𝑇
 </span>) = 25
		Pela direita:
			lim<sub>𝑇→25</sub>+f( <span style="font-family: STIXTwoMath-Regular;">
     𝑇
 </span>) = 25
	Os dois caminhos chegaram ao mesmo lugar. Então podemos afirmar que:
		lim<sub>𝑇→25</sub>f( <span style="font-family: STIXTwoMath-Regular;">
     𝑇
 </span>) = 25
# 
# ❗️E se houver limites, mas a função não existir?
	Considerando a função:
		𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = (𝑥<sup>2</sup>-1/𝑥-1).
	Queremos descobrir o que acontece quando:
		𝑥→1.
	Se tentarmos substituir 𝑥 = 1 diretamente, teremos:
		𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = (1<sup>2</sup>-1/1-1) = 0/0
	Essa divisão não existe. Ou seja, exatamente no ponto 𝑥 = 1, a função possui um buraco. Mas será que o caminho realmente termina aí? Vamos observar valores próximos de 1:
| 𝑥     | 𝑓(𝑥)  |
|-------|-------|
| 0,9   | 1,9   |
| 0,99  | 1,99  |
| 0,999 | 1,999 |
| 1,001 | 2,001 |
| 1,01  | 2,01  |
| 1,1   | 2,1   |

	Perceba que, tanto pela esquerda quanto pela direita, os valores se aproxima de:
		2.
	Portanto:
		lim<sub>𝑥→1</sub>𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = (𝑥<sup>2</sup>-1/𝑥-1) =2.

	💡**O que aconteceu?**
		A função não esta definida exatamente em 𝑥=1, pois resulta em uma dia por zero. No entanto, o caminho existe antes e depois desse ponto. Por isso, conseguimos descobrir para onde a função está indo.
		Na metáfora da ponte:
			* Você consegue caminhar normalmente pela esquerda;
			* Você consegue caminhar normalmente ela direita;
			* Mas exatamente onde pisaria existe um pequeno buraco.
		Mesmo saem conseguir pisar naquele ponto, você sabe perfeitamente onde pisaria, e é por isso que dizemos que o **limite existe**, mesmo que a função não seja definida naquele ponto.

# ‼️ E se não houver limites?
	Nem sempre a aproximação pela esquerda e pela direita levam ao mesmo resultado. Em algumas funções, cada lados e aproxima de um valor diferente. Quando isso acontece, **não existe um único valor que para o qual a função está tendendo**.
	Regra fundamental:
		* ✅ Se o limite pela esquerda e o limite pela direita chegam ao mesmo valor, então o limite existe:
			lim<sub>𝑥→𝑎</sub>-𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = lim<sub>𝑥→𝑎</sub>+𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) ⇒ lim<sub>𝑥→𝑎</sub>𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) existe!
		* ❌ Se os limites laterais são diferentes, então o limite da função não existe:
			lim<sub>𝑥→𝑎</sub>-𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) ≠ lim<sub>𝑥→𝑎</sub>+𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) ⇒ lim<sub>𝑥→𝑎</sub>𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) não existe!
	Quando o limite não existe, geralmente escrevemos:
		lim<sub>𝑥→𝑎</sub>𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) ∄
	O simbolo ∄ (um E invertivo cortado) significa:
		> “Não existe”
	Também é comum encontrar com sua forma abreviada:
		lim<sub>𝑥→𝑎</sub>𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) não existe
	Ou simplesmente: 
		L.N.E.
	(Limite não existe), embora essa abreviação seja mais usada em anotações do que em livros.

# **🔑 O que acabamos de fazer?**
	Os limites laterais apenas perguntam:
		> “O que acontece quando chegamos perto de um ponto vindo de cada lado do mesmo?”

Existem duas possibilidades:
	1. **Os dois lados chegaram no mesmo valor:**
			Esquerda = Direita
		Ou seja, o **Limite existe**.
	1. Se cada lado chega em um valor diferente:
			Esquerda ≠ Direita
		Ou seja, o **limite não existe**.

# 💡 Dica para nunca errar
	Sempre siga esta ordem:
		1. Calcule o limite pela esquerda ( <span style="font-family: STIXTwoMath-Regular;">
     𝑎
 </span><sup>-</sup>).
		5. Calcule o limite pela direita ( <span style="font-family: STIXTwoMath-Regular;">
     𝑎
 </span><sup>+</sup>).
		9. Compare os resultados.
			* Se forem iguais, ou estiverem claramente caminhando para o mesmo valor, o **limite existe e esse será o valor do limite**.
			* Se forem diferentes, Pare por aí: **O limite não existe,** pois não há um único valor para o qual a função esteja tendendo.

# 📝 Resumo
	Limites laterais são um conceito teórico fundamental do cálculo. Eles aprofundam a ideia de limite que vimos anteriormente com a contagem regressiva, que só era observada por valores menores. Se antes aprendemos que um limite estuda para onde uma função está indo, quando nos aproximamos de um determinado valor, agora damos um passo além: Verificamos como essa aproximação acontece por cada lado do ponto.
	Em um limite lateral, observamos dois caminhos possíveis:
		* **Pela esquerda** ( <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑎
 </span><sup>-</sup>): Aproximamo-nos do valor usando números **menores** que o ponto de interesse.
		* **Pela direita** ( <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑎
 </span><sup>+</sup>): Aproximamo-nos do valor usando números **maiores** que o ponto de interesse.
	Essa análise é importante por que uma função pode apresentar comportamentos diferentes dependendo do lado pelo qual nos aproximamos.
	E nunca se esqueça da regra fundamental:
		* ✅ Se o limite pela esquerda e o limite pela direita chegam ao mesmo valor, então o limite existe;
		* ❌ Se cada lado chega a uma valor diferente, então o limite não existe.
	Em outra palavras, o limite de uma função só existe quando há concordância entre os dois lados da aproximação.
		lim<sub>𝑥→𝑎</sub>-𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) = lim<sub>𝑥→𝑎</sub>+𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) ⇒ lim<sub>𝑥→𝑎</sub>𝑓( <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>) existe!