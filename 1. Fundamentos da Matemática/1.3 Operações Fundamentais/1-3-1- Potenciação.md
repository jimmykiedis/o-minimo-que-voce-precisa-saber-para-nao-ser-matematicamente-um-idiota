# 1.3.1. Potenciação

> 📍 Potenciação é a arte de repetir multiplicação sem ficar escrevendo tudo na mão

## 🧠 Definição

A ideia é simples: dado um número chamado **base**, a gente o multiplica por ele mesmo várias vezes, de acordo com o número chamado **expoente**.

$$a^n = \underbrace{a \times a \times a \times \dots \times a}_{n \text{ vezes}}$$

🔹 **Exemplos:**

- $2^3 = 2 \times 2 \times 2 = 8$
- $4^2 = 4 \times 4 = 16$

## 🧩 Elementos da potência

|Nome|Símbolo|Exemplo $2^3$|
|---|---|---|
|Base|$a$|$2$|
|Expoente|$n$|$3$|
|Potência|$a^n$|$8$|

## 🧮 Propriedades importantes

### 1. Produto de potências de mesma base

$$a^m \times a^n = a^{m+n}$$

📌 **Exemplo:** $x^2 \times x^3 = x^{2+3} = x^5$

### 2. Potência de potência

$$(a^m)^n = a^{m \times n}$$

📌 **Exemplo:** $(3^2)^4 = 3^8$

### 3. Potência de expoente zero

$$a^0 = 1 \quad (a \neq 0)$$

📌 **Exemplos:** $5^0 = 1$ e $x^0 = 1$

🔎 **Por quê?**

- ✅ **Forma 1 (por lógica de divisão):**

$$\frac{a^m}{a^m} = a^{m-m} = a^0 = 1$$

- ✅ **Forma 2 (sequência decrescente):**

$$2^3 = 8, \quad 2^2 = 4, \quad 2^1 = 2, \quad 2^0 = 1$$

### 4. Expoente negativo

$$a^{-n} = \left(\dfrac{1}{a}\right)^n$$

📌 **Exemplos:**

- $5^{-1} = \dfrac{1}{5}$
- $\left(\dfrac{2}{3}\right)^{-2} = \left(\dfrac{3}{2}\right)^2 = \dfrac{9}{4}$

## ⚠️ Casos especiais que geram erro na prova

### ❌ Potência da soma (errado!)

$$(a+b)^2 \neq a^2 + b^2$$

📌 **Correto:**

$$(a+b)^2 = a^2 + 2ab + b^2$$

### ❌ Soma de potências (sem regra direta!)

$$2^2 + 2^3 \neq 2^5$$

📌 **Isso é conta normal:** $2^2 + 2^3 = 4 + 8 = 12$

## 📚 Outras propriedades valiosas

|Regra|Exemplo|
|---|---|
|Potência em frações (expoente positivo)|$\left(\dfrac{2}{3}\right)^2 = \dfrac{4}{9}$|
|Potência em frações (expoente negativo)|$\left(\dfrac{2}{3}\right)^{-2} = \left(\dfrac{3}{2}\right)^2 = \dfrac{9}{4}$|
|Divisão de potências com mesma base|$\dfrac{a^m}{a^n} = a^{m-n}$|
|Multiplicação de potências diferentes|⚠️ Não existe regra direta se as bases forem diferentes|

## 💡 Resumo

|Conceito|Sacada prática|
|---|---|
|$a^0 = 1$|Desde que $a \neq 0$, é o padrão da matemática|
|Expoente negativo|Joga pra baixo: vira fração|
|Potência da potência|Multiplica os expoentes|
|Produto de mesma base|Soma os expoentes|
|⚠️ Cuidado com soma e subtração|Não existe "regra mágica"|