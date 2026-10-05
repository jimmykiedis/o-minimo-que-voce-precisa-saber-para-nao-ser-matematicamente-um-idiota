# 1.3.2. Radiciação

> 📍 Radiciação é a operação inversa da potenciação. Em vez de multiplicar várias vezes, agora queremos descobrir qual número foi multiplicado por ele mesmo para dar certo resultado.

## 🧠 O que é?

É a operação inversa da potenciação. Ou seja:

$$a^n = b \iff \sqrt[n]{b} = a$$

## 📌 Notação e elementos

$$\sqrt[n]{a} = b \iff b^n = a$$

|Termo|Nome técnico|Exemplo|
|---|---|---|
|$\sqrt{\phantom{a}}$|Radical|—|
|$a$|Radicando|$\sqrt{a}$|
|$n$|Índice da raiz|$\sqrt[3]{a}$|
|$b$|Raiz (resultado)|$b = \sqrt[3]{a}$|

## 🧮 Tipos comuns

|Tipo|Exemplo|Justificativa|
|---|---|---|
|Raiz quadrada|$\sqrt{25} = 5$|$5^2 = 25$|
|Raiz cúbica|$\sqrt[3]{27} = 3$|$3^3 = 27$|
|Raiz quarta|$\sqrt[4]{16} = 2$|$2^4 = 16$|

## 💡 Raiz n-ésima

A raiz n-ésima de $b$ é o número $a$ tal que $a^n = b$:

$$\sqrt[n]{b} = a \iff a^n = b$$

## ⚠️ Casos especiais

|#|Caso|Exemplo|Resultado|
|---|---|---|---|
|1|Raízes múltiplas|$x^2 = 9$|$x = \pm 3$, pois $3^2 = 9$ e $(-3)^2 = 9$|
|2|Raiz de número negativo ($n$ par)|$\sqrt{-16}$|❌ Não existe em $\mathbb{R}$|
|3|Raiz de número negativo ($n$ ímpar)|$\sqrt[3]{-8}$|✅ $-2$, pois $(-2)^3 = -8$|
|4|Raiz de potência|$\sqrt{9^4} = 9^2$|Regra: $\sqrt[n]{a^m} = a^{m/n}$|

### 1. Raízes múltiplas

A equação $x^2 = 9$ tem duas soluções reais: $x = 3$ e $x = -3$, pois $(-3)^2 = 9$.

> A raiz quadrada em si é sempre a raiz **positiva**: $\sqrt{9} = 3$. O $\pm$ aparece quando resolvemos a equação.

### 2. Raiz de número negativo com índice par

Se o índice é par → ❌ não existe no conjunto $\mathbb{R}$.

$$\sqrt{-16} \notin \mathbb{R}$$

### 3. Raiz de número negativo com índice ímpar

Se o índice é ímpar → ✅ existe resultado real negativo.

$$\sqrt[3]{-8} = -2 \quad \text{pois} \quad (-2)^3 = -8$$

### 4. Raiz de potência (expoente dentro da raiz)

$$\sqrt[n]{a^m} = a^{m/n}$$

📌 **Exemplos:**

- $\sqrt{9^4} = 9^{4/2} = 9^2 = 81$
- $\sqrt[3]{8^6} = 8^{6/3} = 8^2 = 64$

💬 **Lembra do truque:**

> *"Quem tá no sol (expoente) vai pra sombra (dividido), quem tá na sombra (índice) vai pro sol (embaixo da fração)"*
> — Prof. Giz, com Gis. 2020™

## 🚀 Métodos para encontrar raiz quadrada

### 1. ✅ Método tradicional (fatoração / MMC)

**Exemplo:** $\sqrt{144}$

Fatora o número até chegar em 1, depois agrupa de dois em dois (raiz quadrada):

$$144 = 2 \times 2 \times 2 \times 2 \times 3 \times 3$$

Agrupando: $(2 \times 2) \times (2 \times 2) \times (3 \times 3)$ → $2 \times 2 \times 3 = \mathbf{12}$

### 2. ✅ Soma dos ímpares

A soma dos $n$ primeiros ímpares é $n^2$.

**Exemplo:**

$$1 + 3 + 5 + 7 + \dots + 23 = 144 \quad \text{(12 termos)}$$

$$\Rightarrow \sqrt{144} = \mathbf{12}$$

### 3. ✅ Dígito final (análise rápida)

|Unidade|Possíveis raízes|
|---|---|
|1|1 ou 9|
|4|2 ou 8|
|9|3 ou 7|
|6|4 ou 6|
|5|5|

**Exemplo:** $\sqrt{144}$

Último dígito = 4 → possíveis: 2 ou 8.

$12^2 = 144$ ✔️ $\Rightarrow$ Resultado: **12**

### 4. 🧠 Método aproximado (quando não é exata)

**Exemplo:** $\sqrt{140}$

Quadrado perfeito próximo: $144 = 12^2$.

Fórmula:

$$\sqrt{140} \approx \frac{140 + 144}{2 \times 12} = \frac{284}{24} \approx \mathbf{11{,}8}$$

## 🧩 Regras de ouro

|Regra|Correto?|Exemplo|
|---|---|---|
|$\sqrt{a \cdot b} = \sqrt{a} \cdot \sqrt{b}$|✅|$\sqrt{18} = \sqrt{9} \cdot \sqrt{2} = 3\sqrt{2}$|
|$\sqrt{a + b} = \sqrt{a} + \sqrt{b}$|❌|$\sqrt{9+16} \neq \sqrt{9} + \sqrt{16}$, pois $5 \neq 3 + 4$|

## 🧮 Operações com raízes

### ➕ Adição/Subtração

|Expressão|Resultado|Observação|
|---|---|---|
|$\sqrt{10} + \sqrt{10}$|$2\sqrt{10}$|Raízes iguais|
|$\sqrt{10} - \sqrt{10}$|$0$|Subtração normal|
|$2\sqrt{10} + 3\sqrt{10}$|$5\sqrt{10}$|Soma coeficientes|
|$2\sqrt{10} - 3\sqrt{10}$|$-\sqrt{10}$|Subtrai coeficientes|
|$\sqrt{2} + \sqrt{3}$|$\sqrt{2} + \sqrt{3}$|❌ Radicandos diferentes|

### ✖️ Multiplicação

|Expressão|Resultado|Observação|
|---|---|---|
|$\sqrt{10} \times \sqrt{10}$|$10$|$\sqrt{a} \times \sqrt{a} = a$|
|$2\sqrt{10} \times 3\sqrt{10}$|$6 \times \sqrt{100} = 60$|Multiplica coeficientes e radicandos|
|$\sqrt{2} \times \sqrt{5}$|$\sqrt{10}$|Multiplica radicandos|

### ➗ Divisão

|Expressão|Resultado|Observação|
|---|---|---|
|$\sqrt{10} \div \sqrt{10}$|$1$|Raízes iguais se anulam|
|$2\sqrt{10} \div 3\sqrt{10}$|$\dfrac{2}{3}$|Radical anula, sobra a fração|
|$\sqrt{50} \div \sqrt{2}$|$\sqrt{25} = 5$|Usa $\sqrt{\dfrac{a}{b}} = \dfrac{\sqrt{a}}{\sqrt{b}}$|

## 💡 Resumo de prova

|Você TEM que saber|Exemplo|
|---|---|
|Raiz é o inverso da potência|$\sqrt[3]{27} = 3$ porque $3^3 = 27$|
|Índice par de negativo = proibido|$\sqrt{-1}$ ❌ (não existe em $\mathbb{R}$)|
|Raiz de potência = expoente fracionário|$\sqrt[3]{8^4} = 8^{4/3}$|
|Produto pode separar|$\sqrt{a \cdot b} = \sqrt{a} \cdot \sqrt{b}$|
|Soma NÃO pode separar|$\sqrt{a + b} \neq \sqrt{a} + \sqrt{b}$|