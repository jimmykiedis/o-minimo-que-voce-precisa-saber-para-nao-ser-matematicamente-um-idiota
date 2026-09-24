# 6.2.3. 🚀 Propriedades dos limites


# 🧠Introdução
	Antes de mergulhar em contas complicadas, precisamos das regras do jogo.
	As propriedades dos limites funcionam como as leis da álgebra dos limites: elas permitem manipular somas, produto, quocientes e até raízes sem ter que reinventar a roda outra vez.
	📌 Observação inicial:
		> Em todos as propriedades a seguir, consideramos x→a, c uma constante e supondo sempre que os limites existam.

# 🔢 Propriedades fundamentais
### 4️⃣Quarteto Sinistro:
	1. **Soma**
		lim<sub>x→a</sub>f(x) + g(x) = lim<sub>x→a</sub>f(x) + lim<sub>x→a</sub>g(x) 
		*Obs.: Se as funções se somam, podemos calcular os limites de cada uma separadamente e depois somar seus resultados.*
	1. **Subtração**		lim<sub>x→a</sub>f(x) - g(x) = lim<sub>x→a</sub>f(x) - lim<sub>x→a</sub>g(x) 
 		*Obs.: Se as funções se subtraem, podemos calcular os limites de cada uma separadamente e depois subtrair seus resultados.*
	1. **Produto**		lim<sub>x→a</sub>(f(x) * g(x)) = (lim<sub>x→a</sub>f(x)) * (lim<sub>x→a</sub>g(x)) 
		*Obs.: Se as funções se multiplicam, podemos calcular os limites de cada uma separadamente e depois multiplicar seus resultados.*
	1. **Quociente**		lim<sub>x→a</sub>(f(x) / g(x)) = (lim<sub>x→a</sub>f(x)) / (lim<sub>x→a</sub>g(x))
		*Obs.: Se as funções se dividem, podemos calcular os limites de cada uma separadamente e depois dividir seus resultados, isso se lim**<sub>x→a</sub>**g(x) for diferente de zero.*

🔑**Manuseio simples de constante**
	1. **Multiplicação por constante**
		lim<sub>x→a</sub>(c * f(x)) = c * lim<sub>x→a</sub>(f(x)) 
		*Obs.: Se uma constante multiplica a função, podemos calcular seus limites primeiro e depois multiplicar seu resultado pela constante.*

### ✅Potências e raízes
	1. **Potência inteira**
		lim<sub>x→a</sub>[(f(x))]<sup>n</sup> = [lim<sub>x→a</sub>(f(x))]<sup>n</sup> 
		*Obs.: Se a função tem um expoente, podemos calcular o limite primeiro e depois exponencializar o resultado.*
	1. **Raiz**		lim<sub>x→a</sub><sup>n</sup>√f(x) = <sup>n</sup>√lim<sub>x→a</sub>(f(x)), se 𝑛 for par, lim f(x) ≥ 0
		*Obs.: Se a função tem uma raiz, podemos calcular o limite primeiro e depois aplicar raiz ao resultado.*

### ⚙️ Casos básicos
	1. **a) Constante** 
		lim<sub>x→a</sub>c = c
		*Obs.: Se a função é uma constante, seu limite é sempre essa mesma constante, independente do valor para o qual o x tende.*
	1. **b) Identidade**
		lim<sub>x→a</sub>x = a 
		*Obs.: Se a função é simplesmente x, o limite é o próprio valor para o qual o x está tendendo.*
	1. **Potencia simples (monômio)**
		lim<sub>x→a</sub>x<sup>n</sup> = a<sup>n</sup>, 𝑛 pertence a ℤ<sup>+</sup><sub>*</sub> (positivos não nulos)
		*Obs.: Se a função é x elevado a uma potência, o limite é o valor para o qual o x está tendendo, elevado a mesma potência.*
	1. **Raiz da variável:**
		lim<sub>x→a</sub><sup>n</sup>√x = <sup>n</sup>√a, se 𝑛 for para, a ≥ 0 
		*Obs.: Se a função é x radicalizado, o limite é o próprio valor para o qual o x está tendendo, radicalizado.*


