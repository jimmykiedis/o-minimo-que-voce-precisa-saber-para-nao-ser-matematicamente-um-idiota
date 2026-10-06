# 1.3.3. Propriedades das operações

> ⚙️ "Não é bruxaria, é matemática bem comportada."

## 🤔 Introdução

Você já somou 3 + 8 + 7 na cabeça começando pelo 3 + 7, porque "fecha 10" e fica mais fácil? Ou calculou 6 × 12 como 6 × 10 + 6 × 2? Ou percebeu que somar zero ou multiplicar por 1 não muda nada? Quantas vezes você já usou atalhos assim sem saber que existia uma regra por trás deles?

As **propriedades das operações** são as leis que dizem **o que pode ser trocado, reagrupado, espalhado ou ignorado** em uma conta sem mudar o resultado. São como leis da física, só que para os números. Em Cálculo, elas sustentam toda a manipulação de expressões: simplificar, fatorar, derivar.

A ideia principal é: **cada operação tem suas regras, e nem toda regra vale para todas as operações**. E aqui mora um erro muito comum. Você pode pensar que, se dá para trocar a ordem em 3 + 5, também dá para trocar em 3 − 5. Parece correto, mas não está. Trocar a ordem funciona na soma e na multiplicação, mas **não** na subtração e na divisão.

---

## 🚀 Exemplo Lógico

Depois de abrir a porta da Câmara dos Ecos, você e Cálculo-Zero chegam a uma **estação espacial em pleno caos**. Caixas de suprimento flutuam sem rumo, cabos pendem do teto e um painel pisca: *"Organize a carga para liberar a passagem."* Cálculo-Zero escaneia a sala e diz:

— Calma. Em meio à bagunça, existem **regras que mantêm a ordem**. Algumas coisas você pode mexer sem medo. Outras, não.

### 🔄 Regra 1: a troca de lugar

Na entrada, dois contêineres precisam ser empilhados na esteira: um com **3 caixas** e outro com **5 caixas**. Tanto faz qual vai primeiro, a esteira receberá **8 caixas** no total. O mesmo vale para **fileiras de caixas**: 3 fileiras de 5 ou 5 fileiras de 3 formam o mesmo retângulo.

⚠️ Você pensa: "então posso trocar tudo de lugar". Mas o robô mostra a **bomba de combustível**: o painel diz *"retire 5 do tanque de 3"*. Trocar para *"retire 3 do tanque de 5"* muda tudo. Da mesma forma, **repartir 6 caixas entre 2 pessoas** é bem diferente de **repartir 2 caixas entre 6 pessoas**.

### 📦 Regra 2: o agrupamento

Três equipes entregam caixas: 2, 3 e 4. Você pode juntar as duas primeiras e depois somar a terceira, ou juntar as duas últimas e somar à primeira. O **total é o mesmo**, e a ordem das equipes **não muda**; só muda **quem é contado primeiro**.

⚠️ Na subtração, isso falha: *"retire 2 de 10 e depois mais 3"* não é o mesmo que *"retire de 10 o resultado de tirar 3 de 2"*.

### 🌟 Regra 3: espalhar pelo grupo

Um cabo de energia alimenta **4 módulos**, e cada módulo tem **2 baterias grandes e 3 pequenas**. Você pode contar as baterias por módulo (2 + 3) e multiplicar por 4, ou **espalhar o 4** para cada tipo: 4 vezes as grandes e 4 vezes as pequenas. Dá o mesmo total.

⚠️ Mas se o módulo tem **2 baterias, cada uma com 3 células**, não há o que espalhar: é só multiplicar tudo junto.

### 🚗 Regra 4: o passageiro que não muda nada

Cálculo-Zero mostra um **droide ocioso**. Se você o coloca na esteira de soma, ele soma **zero** e nada muda. Se o coloca na linha de multiplicação como "cópia única", ele multiplica por **1**, e a carga continua igual. Esses são os **neutros**: participam da operação, mas deixam tudo como estava.

Repare no que a história mostra:

* Somar e multiplicar **aceitam troca de ordem e de agrupamento**; subtrair e dividir, **não**.
* A multiplicação pode ser **espalhada** sobre uma soma ou subtração.
* Existe um número que **não altera** o resultado em cada operação: 0 para somar e subtrair, 1 para multiplicar e dividir.

---

## 🧮 Exemplo Prático

Agora vamos transformar a estação em matemática.

### 1️⃣ Passo 1: propriedade comutativa

> **"Pode trocar que dá na mesma."**

$$a + b = b + a \qquad\qquad a \times b = b \times a$$

* **a** e **b** são os dois números da operação, e podem ser trocados de lugar.

🚀 **Na estação:** os contêineres de 3 e 5 caixas:

$$3 + 5 = 8 \qquad\text{e}\qquad 5 + 3 = 8$$

As fileiras:

$$3 \times 5 = 15 \qquad\text{e}\qquad 5 \times 3 = 15$$

❌ **Onde NÃO vale:** subtração e divisão.

$$a - b \neq b - a \qquad\qquad a \div b \neq b \div a$$

🚀 **Na bomba de combustível:**

$$5 - 3 = 2 \qquad\text{mas}\qquad 3 - 5 = -2$$

Na partilha das caixas:

$$6 \div 2 = 3 \qquad\text{mas}\qquad 2 \div 6 = \frac{1}{3}$$

⚠️ Ao encontrar uma **subtração ou divisão**, não aplique a comutativa.

### 2️⃣ Passo 2: propriedade associativa

> **"Pode mudar o agrupamento que dá na mesma."**

$$(a + b) + c = a + (b + c) \qquad\qquad (a \times b) \times c = a \times (b \times c)$$

* Os parênteses mostram **quem é calculado primeiro**. Os números continuam **na mesma ordem**.

🚀 **Nas equipes (2, 3 e 4):**

$$(2 + 3) + 4 = 5 + 4 = 9 \qquad\text{e}\qquad 2 + (3 + 4) = 2 + 7 = 9$$

Com multiplicação:

$$(2 \times 3) \times 4 = 6 \times 4 = 24 \qquad\text{e}\qquad 2 \times (3 \times 4) = 2 \times 12 = 24$$

❌ **Onde NÃO vale:** subtração e divisão.

$$(10 - 3) - 2 = 7 - 2 = 5 \qquad\text{mas}\qquad 10 - (3 - 2) = 10 - 1 = 9$$

$$(24 \div 4) \div 2 = 6 \div 2 = 3 \qquad\text{mas}\qquad 24 \div (4 \div 2) = 24 \div 2 = 12$$

🧠 **Cuidado para não confundir:**

> **Comutativa = troca a ordem.** 🔄
> **Associativa = muda o agrupamento.** 📦

### 3️⃣ Passo 3: propriedade distributiva

> **"Espalha o número para quem tá dentro do parênteses."**

$$a \times (b + c) = a \times b + a \times c \qquad\qquad a \times (b - c) = a \times b - a \times c$$

* **a** é o número que está fora e "se espalha";
* **b** e **c** são os termos dentro do parênteses, ligados por soma ou subtração.

🚀 **Nos 4 módulos (2 baterias grandes e 3 pequenas):**

$$4 \times (2 + 3) = 4 \times 5 = 20$$

$$4 \times 2 + 4 \times 3 = 8 + 12 = 20$$

Os dois caminhos chegam a 20 baterias. Com subtração, imagine 4 módulos que tinham 5 baterias e 2 foram retiradas de cada um:

$$4 \times (5 - 2) = 4 \times 3 = 12 \qquad\text{e}\qquad 4 \times 5 - 4 \times 2 = 20 - 8 = 12$$

❌ **Quando NÃO se aplica:** se dentro do parênteses há uma **multiplicação**, não há o que espalhar:

$$a \times (b \times c) = a \times b \times c$$

🚀 **Nas 2 baterias com 3 células cada**, para 4 módulos:

$$4 \times (2 \times 3) = 4 \times 6 = 24 \qquad\text{e}\qquad 4 \times 2 \times 3 = 24$$

Tentar "espalhar" daria $4 \times 2 \times 4 \times 3 = 96$, que está errado.

### 4️⃣ Passo 4: elemento neutro

> **"É o número que não muda nada."**

O elemento neutro é um número que, em determinada operação, **não altera o valor original**. É como um passageiro no carro que não muda nada na viagem. 🚗

| Operação | Elemento neutro | Exemplo | Por quê? |
|---|:---:|---|---|
| Adição | 0 | $a + 0 = a$ | Somar zero não acrescenta nada |
| Subtração | 0 | $a - 0 = a$ | Retirar zero não retira nada |
| Multiplicação | 1 | $a \times 1 = a$ | Multiplicar por 1 mantém o número |
| Divisão | 1 | $\dfrac{a}{1} = a$ | Dividir por 1 mantém o número |

🚀 **Com o droide ocioso, tomando $a = 7$:**

$$7 + 0 = 7 \qquad 7 - 0 = 7 \qquad 7 \times 1 = 7 \qquad 7 \div 1 = 7$$

📌 O neutro **depende da operação**: 0 para somar e subtrair, 1 para multiplicar e dividir.

### 🎯 Passo 5: interpretação final

Para liberar a passagem, Cálculo-Zero mostra que a estação obedece a regras: **trocar ou reagrupar** só é seguro na soma e na multiplicação; **espalhar** só vale com multiplicação sobre soma ou subtração; e o **neutro** é o passageiro que não altera nada. Antes de mexer em uma expressão, pergunte: *qual operação é esta? A regra vale para ela?*

---

## 💡 Resumo estilo prova

### 📝 O que preciso saber?

**Definição:** propriedades das operações são as regras que dizem o que pode ser trocado, agrupado, espalhado ou ignorado em uma conta sem alterar o resultado.

| Propriedade | Fórmula | Vale para | Na estação |
|---|---|---|---|
| 🔄 Comutativa | $a + b = b + a$ e $a \times b = b \times a$ | $+$ e $\times$ | Trocar a ordem dos contêineres |
| 📦 Associativa | $(a+b)+c = a+(b+c)$ e $(a \times b) \times c = a \times (b \times c)$ | $+$ e $\times$ | Mudar quem é contado primeiro |
| 🌟 Distributiva | $a \times (b \pm c) = a \times b \pm a \times c$ | $\times$ sobre $+$ e $-$ | Espalhar o 4 pelos módulos |
| 🚗 Elemento neutro | $a + 0 = a$ e $a \times 1 = a$ | 0 (soma e subtração), 1 (produto e divisão) | O droide ocioso |

### ⚠️ Erros clássicos de prova

| ❌ Erro | ✅ Certo |
|---|---|
| $5 - 3 = 3 - 5$ | $5 - 3 = 2$ e $3 - 5 = -2$ |
| $6 \div 2 = 2 \div 6$ | $6 \div 2 = 3$ e $2 \div 6 = \frac{1}{3}$ |
| $(10 - 3) - 2 = 10 - (3 - 2)$ | $5 \neq 9$ |
| $4 \times (2 \times 3) = 4 \times 2 \times 4 \times 3$ | $4 \times (2 \times 3) = 4 \times 2 \times 3 = 24$ |
| Confundir comutativa com associativa | Comutativa troca a **ordem**; associativa muda o **agrupamento** |

### 🧠 Frases para lembrar

> **"Somar e multiplicar aceitam troca e agrupamento; subtrair e dividir exigem cuidado."**

> **"Distribuir é espalhar a multiplicação por dentro do parênteses de soma ou subtração."**

> **"Na estação do caos, só as regras certas mantêm a carga em ordem, e o neutro é o passageiro que não muda a viagem."**