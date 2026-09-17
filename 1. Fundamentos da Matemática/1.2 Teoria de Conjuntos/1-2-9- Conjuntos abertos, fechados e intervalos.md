# 1.2.9. Conjuntos abertos, fechados e intervalos

# 

```
	📢“Agora sim a matemática começa a mostrar que é frescurenta. Bem-vindo à topologia!”

```


## 🧭Pra que serve isso?
	Esse tópico é o ponto de encontro entre conjuntos e geometria da reta real. Aqui entra os famosos:
		* (0, 1)
		* [0, 1)
		* (-∞, 2]
		* etc.
	A ideia é representar intervalos de números e entender onde "entra" ou "não entra" o limite.

## 📏Tipos de intervalos
| Notação                              | Nome                                 | Inclui os extremos?                  |
|--------------------------------------|--------------------------------------|--------------------------------------|
| (a, b)                               | Intervalo aberto                     | ❌ não inclui a, nem b                |
| [a, b]                               | Intervalo fechado                    | ✅ inclui a e b                       |
| [a, b)                               | Fechado à esquerda, aberto à direita | ✅ a, ❌ b                             |
| (a, b]                               | Aberto à esquerda, fechado à direita | ❌ a, ✅ b                             |

	Exemplo teórico:
		(0, 1) → x > 0 e x < 1
		[0, 1] → x ≥ 0 e x ≤ 1

## ♾️Intervalos infinitos
	Sim, dá pra dizer que algo vai até o infinito:
| Intervalo   | Significado |
|-------------|-------------|
| (−∞, a)     | x < a       |
| (a, ∞)      | x > a       |
| [a, ∞)      | x ≥ a       |
| (−∞, b]     | x ≤ b       |

	⚠️Nunca colocamos colchetes ([) no ∞ ou -∞ por que infinito não é um número, é um conceito.

## 🌀Conjuntos abertos e fechados (na topologia)
	Agora entra a topologia básica, o lado filosófico e rigoroso da matemática:
		🔹Conjunto aberto:
			Um conjunto é aberto se nenhum dos seus extremos está incuído.
				Ex.: (0, 1) é aberto.
		🔸Conjunto fechado:
			Um conjunto é fechado se inclui todo os seus limites.
				Ex: [0, 1] é fechado.
		🧩Pode ser misto?
			Sim! [0, 1) e (0, 1] são semiabertos (ou meio-abertos). 

## 🧠Aplicações
| Área                                    | Exemplo                                 |
|-----------------------------------------|-----------------------------------------|
| Cálculo                                 | Domínio e imagem de funções             |
| Física                                  | Temperatura entre 20º e 30º → intervalo |
| Probabilidade                           | Valores entre 0 e 1                     |
| Informática                             | Intervalos para validação de inputs     |
| Machine Learning                        | Funções de ativação tipo sigmoid        |


## 🧾Resumo pra prova
| Conceito                             | Definição                            |
|--------------------------------------|--------------------------------------|
| Intervalo aberto                     | Não inclui os extremos: (a, b)       |
| Intervalo fechado                    | Inclui os extremos: [a, b]           |
| Intervalo semiaberto                 | Só um lado incluso: (a, b] ou [a, b) |
| Infinito nos intervalos              | Sempre com parênteses: (a, ∞)        |
| Topologicamente aberto               | Não inclui as bordas                 |
| Topologicamente fechado              | Inclui todas as bordas               |


## 🎯Resumo esperto
	Intervalos são jeitos bonitinhos de dizer onde os números vivem.
	Se tem colchetes [], é dentro.
	Se tem parênteses (), é fora.
	Se tem ∞, aceita que nunca vai fechar.
