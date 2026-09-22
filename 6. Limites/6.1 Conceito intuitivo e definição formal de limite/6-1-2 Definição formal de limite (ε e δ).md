# 6.1.2 Definição formal de limite (ε e δ)


# 📕Introdução
	No capitulo anterior [[6.1.1 Conceito intuitivo de limite]], a gente chegou à ideia de que:
		> Quando 𝑥 se aproxima de a, 𝑓(𝑥) pode se aproximar cada vez mais de um determinado valor L.
	Até aí beleza. 😎
	Mas existe um pequeno problema: “cada vez mais próximo” é uma frase intuitiva, não uma definição matemática rigorosa.
	E é justamente aqui que entram os famosos:
		𝜀 (épsilon)
	e
		𝛿 (delta)
	Cala. Eles não mordem. 😂
	A missão deste capítulo é entender o que eles significam e por que essa definição realmente garante que estamos falando de um limite.

# **📍 Relembrando a ideia do capítulo anterior**
	Considere novamente a função:
		𝑓(𝑥) = 2x + 1
	e vamos analisar:
		lim<sub>𝑥→3</sub>𝑓(2x + 1)
	No capítulo anterior, fizemos algo parecido com:
		𝑥 = 3,1 → 𝑓(𝑥) = 7,2
		𝑥 = 3,01 → 𝑓(𝑥) = 7,02
		𝑥 = 3,001 → 𝑓(𝑥) = 7,002
	Até ficando claro que:
		𝑥 = 3 → 𝑓(𝑥) = 7
	Então concluímos intuitivamente que:
		lim<sub>𝑥→3</sub>𝑓(2x + 1) = 7
	Até aqui, tranquilo.
	Mas agora vem a pergunta que o professor de Cálculo resolve fazer só para testar a nossa paz:
		> 🤔”Tá! Mass o que significa exatamente ‘ficar próximo’?”
	Qual próximo?
		- 0,1?
		- 0,001?
		- 0,00001?
	E quem decide isso?
	**Nós!**
	É aí que entra o 𝜀.

# **🎯 O que é o** 𝜀?
	O 𝜀 representa quanto permitirmos que 𝑓(𝑥) se afaste do limite L (valor para o qual 𝑓(𝑥) está se aproximando). Ou seja, ele representa nossa margem de erro. Por exemplos:
		L = 7
	e escolhemos:
		𝜀 = 0,1
	Estamos dizendo:
		> “Quero que 𝑓(𝑥) fique menos que 0,1 de distância de 7.”
	Matematicamente:
		|𝑓(𝑥) - 7| < 0,1
	Isso significa que 𝑓(𝑥) precisa estar entre
		6,9
	e
		7,1
	😈 Agora podemos ser mais exigentes. Digamos que queremos:
		𝜀 = 0,001
	Agora exigimos:
		|𝑓(𝑥) - 7| < 0,001
	Ou seja, 6,999 < 𝑓(𝑥) < 7,001
	A margem ficou muito menor.
	💡Portanto:
 		> 𝜀 diz quão perto queremos que 𝑓(𝑥) fique perto de L.

# 🧲 Beleza... mas como fazemos 𝑓(𝑥) ficar tão perto?
	Agora temos um problema. Nós escolhemos a distância que queremos para 𝑓(𝑥), mas precisamos descobrir:
		> O quão perto de  <span style="font-family: STIXTwoMath-Regular;">
     > 𝑥
 </span> > precisa estar de a (valor para o qual  <span style="font-family: STIXTwoMath-Regular;">
     > 𝑥
 </span> > está se aproximando) para garantir  <span style="font-family: STIXTwoMath-Regular;">
     > 𝑓
 </span>> ( <span style="font-family: STIXTwoMath-Regular;">
     > 𝑥
 </span>> ) fique dentro da margem de erro que escolhemos? 🤔
	É aí que o nosso segundo personagem entra:
		𝛿
	O 𝛿 determina o quão próximo x precisa estar de a para garantir a precisão desejada para 𝑓(𝑥). Logo:
		𝛿 → controla o 𝑥 para garantir a precisão de 𝑓(𝑥).
	Então, matematicamente podemos dizer que:
		|𝑥 - a| < 𝛿
	Então temos uma espécie de acordo:
		🎯 𝜀
			Controla a distância entre:
				𝑓(𝑥) e L.
		🎯 𝛿
			Controla a distância entre:
				𝑥 e a.
	Podemos resumir:
		|𝑥 - a| < 𝛿 → |𝑓(𝑥) - L| < 𝜀
	Traduzindo do matematiquês:
		> Se eu fizer 𝑥 ficar suficientemente próximo de a (valor que o mesmo está se aproximando), consigo garantir que 𝑓(𝑥) fique tão próxima de L (valor que o limite está ganhando) quanto eu quiser.
	💡E perceba: Isso é exatamente a ideia intuitiva que vimos no capitulo anterior!
	Só que agora estamos colocando números e símbolos na brincadeira.

# **📐 A definição formal do limite**
	Agora podemos finalmente apresentar a definição que costuma assustar os alunos quando aparece pela primeira vez:
		∀𝜀 > 0, ∃𝛿 > 0 tal que 0 < |𝑥 - a| < 𝛿 → |𝑓(𝑥) - L| < 𝜀
	Respira. 🥲
	Não precisamos decorar isso como se fosse a senha do Wi-Fi
	Vamos desmontar a frase.

# 🔍 Traduzindo o “matematiquês”
	A definição começa com:
		∀𝜀 > 0
	O simbolo:
		∀
	Significa “para todo”. Então:
		∀𝜀 > 0
	Significa:
		> Para qualquer imagem de erro positiva que alguém escolher…
	Pode ser:
		𝜀 = 0,1
	ou
		𝜀 = 0,0001
	ou
		𝜀 = 10<sup>-100</sup>.
	Não importa. Pode escolher qualquer uma. 😎
	
	Depois aparece:
		∃𝛿 > 0
	O simbolo:
		𝛿
	Significa “existe”. Então:
		∃𝛿 > 0
	Significa:
		> Existe algum 𝛿 > 0 capaz de garantir essa precisão.
	E aqui está o coração da definição:
		∀𝜀 > 0, ∃𝛿 > 0
	Ou seja:
		> Você escolhe a precisão que quiser. Eu encontro um 𝛿 adequado.

# 🚪 Mas por que aparece 0 < |𝑥 - a| < 𝛿?
	Temos:
		0 < |𝑥 - a| < 𝛿
	Esse trecho diz duas coisas.
		1. |𝑥 - a| < 𝛿
	Significa que 𝑥 está próximo de a.
		1.  0 < |𝑥 - a|
	Significa que:
		𝑥 ≠ a.
	E isso é importante!
	Lembra do que vimos no capítulo anterior?
> 👀 Limite não está necessariamente interessado no valor da função exatamente em a.
	Ele quer saber o que acontece quando chegamos perto de a. Por isso usamos:
		0 < |𝑥 - a|.

# **🧠 O limite não está preocupado com o “ponto exato”**
	Como vimos anteriormente, o ponto exato nunca foi exatamente aquilo que o limite estava procurando. Imagine o uso prático do que aprendemos para resolver limites:
		𝑓(𝑥)	= ( 𝑥<sup>2 </sup>- 1 ) / ( 𝑥<sup> </sup>- 1 )
	Se tentarmos calcular 𝑓(1):
		𝑓(1) = ( 𝑥<sup>2 </sup>- 1 ) / ( 𝑥<sup> </sup>- 1 ) = 0/0
	🚨 E divisão por zero não existe.
	E mesmo que se a gente fatorasse usando ￼ deixando:
		𝑓(𝑥)	= ( 𝑥<sup> </sup>- 1 ) * ( 𝑥<sup> </sup>+ 1 ) / ( 𝑥<sup> </sup>- 1 )
	Agora se usarmos o ￼, nem precisamos testar os valores próximos de 𝑥, com isso ficamos com:
		𝑓(𝑥)	= 𝑥<sup> </sup>+ 1
	Enfim podemos substituir o valor na equação, e mesmo que no começo a gente não conseguia colocar o 1, agora sabemos que, se o 𝑥 se aproximar de 1, temos:
		𝑥<sup> </sup>+ 1 → 2
	Portanto:
		lim <span style="font-size: 13.0;">
     <sub>𝑥→1</sub>
 </span>( 𝑥 <span style="font-size: 13.0;">
     <sup>2 </sup>
 </span>- 1 ) / ( 𝑥 <span style="font-size: 13.0;">
     <sup> </sup>
 </span>- 1 ) = 2
	Mesmo que:
		𝑓(1) ∄ ou 𝑓(1) não existe.
	👀 E aqui está a grande sacada:
		O limite não está perguntando:
			> “Quanto vale a função exatamente em 𝑥 = 1?”
		Ele está perguntando:
			> 🎯”O que acontece com os valores de 𝑓(𝑥) quando 𝑥 chega cada vez mais perto de 1?”
		E nesse caso, a resposta é:
			2, definitamente
		Isso explica uma parte importante da definição formal que acabamos de estudar. Na definição 𝜀 - 𝛿, aparece:
			0 < | <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span> - a| <  <span style="font-family: STIXTwoMath-Regular;">
     𝛿
 </span>
		🎯 Sendo “a”, o ponto que  <span style="font-family: STIXTwoMath-Regular;">
     𝑥 
 </span>está tentando alcançar.
		Esse 0 < não está ali só para enfeitar a fórmula 😂. Ele significa que estamos olhando para valores de x que estão próximos de a, mas são diferentes de a. Nesse exemplo:
			a = 1.
		Então podemos considerar valores como:
			0.9, 0.99, 0.001, 1.01, …
		Estamos cada vez mais perto de 1, mas não precisamos chegar exatamente em 1.
		🎯 E é justamente por isso que conseguimos falar sobre:
			lim <span style="font-size: 13.0;">
     <sub>𝑥→1</sub>
 </span>𝑓(𝑥)
		Mesmo que 𝑓(1) nem mesmo exista.
		💡 Moral da história:
 			> O limite diz que, não importa o quão pequeno seja o 𝜀 que escolhermos para controlar a distância de 𝑓(𝑥) até L, sempre podemos encontrar um 𝛿 que determina o quão perto 𝑥 precisa estar de a para garantir essa aproximação.

# 🎮 E se alguém mudar o 𝜀?
	Aqui está um a parte muito importante. Imagine que alguém diga:
		> “Quero 𝑓(𝑥) a no máximo 0,1 de distância de 7.”
	Então:
		𝜀 = 0,1
	Como:
		𝛿 = 𝜀/2
	Temos:
		𝛿 = 0,05
	Então basta garantir:
		|𝑥 - 3| < 0,05
	Agora alguém chega e fala:
		> “Muito fácil. Quero uma precisão ainda maior, vamos tentar 0,001.”
	Então:
		𝜀 = 0,001
	Como:
		𝛿 = 𝜀/2
	Temos:
		𝛿 = 0,0005
	Novamente, basta garantir:
		|𝑥 - 3| < 0,0005
	Queremos ainda mais precisão, não queremos? Sem problemas:
		 <span style="font-family: STIXTwoMath-Regular;">
     𝜀
 </span> = 0,0000001
	Como:
		𝛿 = 𝜀/2
	Temos:
		𝛿 = 0,00000005
	Novamente, basta garantir:
		|𝑥 - 3| < 0,00000005
	🔥 Perceba o que aconteceu:
		𝜀↓ ⇒ 𝛿↓
	Quanto mais exigente somos com a aproximação de 𝑓(𝑥) para L, mais perto precisamos colocar 𝑥 de a.

# 📊 10. A interpretação geométrica
	Agora vamos visualizar essa história, tentaremos fazer uma visualização desses elementos em um gráfico da seguinte função:
		lim<sub>𝑥→a</sub>𝑓(𝑥) - L
	O 𝛿 cria uma sombra lateral tanto à esquerda quanto direita de a dentro do eixo X:
		a - 𝛿 < 𝑥 < a + 𝛿
		> 🎯 “É aqui que 𝑥 precisa ficar para estar suficientemente próximo de a.
	O 𝜀 cria uma sombra lateral tanto à esquerda quanto direita de L dentro do eixo Y:
		L - 𝜀 < 𝑓(𝑥) < L + 𝜀
	Essa faixa representa:
		> 🎯 “É aqui que quero que os valores de 𝑓(𝑥) fiquem.
	💡 Ou sejam em português de gente normal:
		> 🔥 “Eu descubro o quanto preciso aproximar 𝑥 de a, usando 𝛿. Assim, consigo garantir que 𝑓(𝑥) fique tão perto de L quanto eu quiser, dentro da margem definida pelo 𝜀.

# 📝 13. Resumão para não esquecer
	
| Símbolo                                               | O que significa?                                      | Pense em...                                           |
|-------------------------------------------------------|-------------------------------------------------------|-------------------------------------------------------|
| 𝜀                                                     | Margem de erro para 𝑓(𝑥) em relação a L               | 🎯 “Quão perto quero que 𝑓(𝑥) fique de L?”             |
| 𝛿                                                     | Margem de proximidade de 𝑥 em relação a a             | 🚶 “Quão perto 𝑥precisa ficar de a?”                   |
| 0 < |𝑥 - a| < 𝛿                                       | 𝑥 está próximo de a, mas 𝑥 ≠ a                        | 👀 “Estou olhando ao redor de a, não exatamente em a.” |
| |𝑓(𝑥) - L| < 𝜀                                        | 𝑓(𝑥) está próximo de L                                | 🎯 “A função entrou na margem que eu determinei.”      |
| ∀                                                     | Para todo                                             | 🌎 “Não importa qual você escolha.”                    |
| ∃                                                     | Existe                                                | 🔎 “Consigo encontrar um 𝛿 que funcione.”              |

	Como frase lógica:
		0 < |𝑥 - a| < 𝛿 ⇒ |𝑓(𝑥) - L| < 𝜀
	🧠 **Traduzindo:** “Eu aproximo 𝑥 de a usando o 𝛿, e isso garante que 𝑓(𝑥) fique próxima de L dentro da margem 𝜀.”