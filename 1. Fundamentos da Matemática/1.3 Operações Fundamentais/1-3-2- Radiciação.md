# 1.3.2. Radiciação


```
	📍Radiciação é a operação inversa da potenciação. Em vez de multiplicar várias vezes, agora queremos descobrir qual número foi multiplicado por ele mesmo para dar certo resultado.

```


## 🧠 O que é?
	É a operação inversa da potenciação. Ou seja, se:
		a<sup>n</sup> = b é o mesmo que <sup>n</sup>√b = a

## 📌Notação e elementos
<sup>	n</sup>√a = b <-> b<sup>n</sup> = a
| Termo            | Nome técnico     | Exemplo          |
|------------------|------------------|------------------|
| √                | Radical          | —                |
| a                | Radicando        | √a               |
| n                | Índice da raiz   | 3√a              |
| b                | Raiz (resultado) | b = ³√a          |


## 🧮Tipos comuns
| Tipo          | Exemplo       | Justificativa |
|---------------|---------------|---------------|
| Raiz quadrada | √25 = 5       | 5² = 25       |
| Raiz cúbica   | ³√27 = 3      | 3³ = 27       |
| Raiz quarta   | ⁴√16 = 2      | 2⁴ = 16       |


## 💡Raiz n-ésima
	> O que é?
		A raiz n-ésima de > **b** > é o número > **a** > tal que > **aⁿ = b**
			> <sup>n</sup>> √b = a <-> a> <sup>n</sup> > = b

## ⚠️Casos Especiais
|                                   | Caso                              | Exemplo                           | Resultado                         |
|-----------------------------------|-----------------------------------|-----------------------------------|-----------------------------------|
| 1                                 | Raízes múltiplas                  | √9 = ±3                           | 3² = 9 e (–3)² = 9                |
| 2                                 | Raiz de número negativo (n par)   | √–16                              | ❌ Não existe em ℝ                 |
| 3                                 | Raiz de número negativo (n ímpar) | ³√–8                              | ✅ –2, pois (–2)³ = –8             |
| 4                                 | Raiz de potência                  | √9⁴ = 9²                          | Regra: ⁿ√a^m = a^(m/n)            |

	1. Raízes múltiplas
		A equação x^2 = 9 tem duas soluções reais:
			√9 = 3 e -3 pois (-3)<sup>2</sup> = 9
	1. Raiz de número par negativo
		Se o índice é par → ❌ não existe no conjunto ℝ
			√-16 = não é real
		
	1. Raiz de número impar negativo
		Se o índice é ímpar → ✅ existe resultado real negativo
			<sup>3</sup>√-8 = -2 pois (-2)<sup>3</sup> = -8
	1. Raiz de potência (expoente dentro da raiz)
		se:
			<sup>n</sup>√a<sup>m</sup> = a<sup>m/n</sup>
		📌Exemplo:
			√9<sup>4</sup> = 9<sup>4/2</sup>
			<sup>3</sup>√8<sup>6</sup> = 8<sup>6/3</sup>
		💬Lembra do truque:
			*"Quem tá no sol (expoente) vai pra sombra (dividido), quem tá na sombra (índice) vai pro sol (embaixo da fração)"
				Prof. Giz, com Gis. 2020™*

## 🚀 **Métodos para Encontrar Raiz Quadrada**
	1. **✅Método Tradicional (MMC)**
		**Exemplo:** √144
			Fatora o número até chegar em 1, depois agrupa de dois em dois (raiz quadrada):
				144 → 2×2×2×2×3×3
			Agrupando: (2×2)×(2×2)×(3×3) → 2×2×3 = **12**

	1. **✅Soma dos Ímpares**
		A soma dos **n** primeiros ímpares = n²
		**Exemplo:**
			Soma até 144:
				1 + 3 + 5 + 7 + ... + 23 = **144** (foram 12 termos)
			⇒ √144 = **12**

	1. ✅Dígito Final (análise rápida)
| Unidade          | Possíveis raízes |
|------------------|------------------|
| 1                | 1 ou 9           |
| 4                | 2 ou 8           |
| 9                | 3 ou 7           |
| 6                | 4 ou 6           |
| 5                | 5                |

		**Exemplo:** √144
			Último dígito = 4 → possíveis: 2 ou 8
		12² = 144 → ✔️
 <span style="font-family: .HiraKakuInterface-W4;">
     			⇒
 </span> Resultado: **12**

	1. **🧠Método Aproximado (quando não é exata)**
		**Exemplo:** √140
			Quadrado perfeito próximo = 144 (12²)
		Fórmula:
			(140 + 144) / (2 × 12) = **11,8** (aproximadamente)

 <span style="font-family: .AppleColorEmojiUI;">
     ## 🧩
 </span>**Regras de Ouro**
| Regra                        | Correto?                     | Exemplo                      |
|------------------------------|------------------------------|------------------------------|
| √(a * b) = √a * √b           | ✅                            | √18 = √9 * √2 = 3√2          |
| √(a + b) = √a + √b           | ❌                            | √(9+16) ≠ √9 + √16 → 5 ≠ 3+4 |


## 🧮 Operações com Raízes
	* ➕ Adição/Subtração
| Expressão               | Resultado               | Observação              |
|-------------------------|-------------------------|-------------------------|
| √10 + √10               | 2√10                    | Raízes iguais           |
| √10 - √10               | 0                       | Subtração normal        |
| 2√10 + 3√10             | 5√10                    | Soma coeficientes       |
| 2√10 - 3√10             | –√10                    | Subtração coeficientes  |
| √2 + √3                 | √2 + √3                 | ❌ Radicandos diferentes |

	* ✖️ Multiplicação
| Expressão                            | Resultado                            | Observação                           |
|--------------------------------------|--------------------------------------|--------------------------------------|
| √10 × √10                            | 10                                   | √a × √a = a                          |
| 2√10 × 3√10                          | 6 × √100 = 60                        | Multiplica coeficientes e radicandos |
| √2 × √5                              | √10                                  | Multiplica radicandos                |

	* ➗ Divisão
| Expressão                       | Resultado                       | Observação                      |
|---------------------------------|---------------------------------|---------------------------------|
| √10 ÷ √10                       | 1                               | Raízes iguais se anulam         |
| 2√10 ÷ 3√10                     | 2/3                             | Radicando anula, sobra a fração |
| √50 ÷ √2                        | √25 = 5                         | Usa √(a/b) = √a ÷ √b            |


 <span style="font-family: .AppleColorEmojiUI;">
     ## 💡
 </span>**Resumo de Prova**
| Você TEM que saber                      | Exemplo                                 |
|-----------------------------------------|-----------------------------------------|
| Raiz é o inverso da potência            | ³√27 = 3 porque 3³ = 27                 |
| Índice par de negativo = proibido       | √–1 = ❌ (não existe em ℝ)               |
| Raiz de potência = expoente fracionário | ³√8⁴ = 8^(4/3)                          |
| Produto pode separar                    | √(a·b) = √a · √b                        |
| Soma NÃO pode separar                   | √(a + b) ≠ √a + √b                      |



