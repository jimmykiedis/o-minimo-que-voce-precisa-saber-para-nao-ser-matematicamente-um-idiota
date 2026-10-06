# 1.3.2. Radiciação

> 📍 Radiciação é a operação inversa da potenciação. Em vez de multiplicar várias vezes, agora queremos descobrir qual número foi multiplicado por ele mesmo para dar certo resultado.

## 🤔 Introdução

Você já olhou para um quadrado de 25 m² e se perguntou "quanto mede cada lado?". Ou tentou descobrir o lado de um terreno sabendo só a área? Ou já fez o caminho inverso de uma conta, partindo do resultado para achar o número original? Sempre que você faz essa pergunta, está usando uma **raiz**, mesmo sem perceber.

Radiciação é a ferramenta que **desfaz uma potência**. Se a potenciação pergunta "o que acontece quando multiplico 5 por ele mesmo?", a radiciação pergunta "qual número, multiplicado por ele mesmo, deu 25?". Em Cálculo ela aparece em funções como $\sqrt{x}$, em distâncias, em limites e em derivadas.

A ideia principal é: **raiz é o caminho de volta da potência**. E aqui mora um erro muito comum. Você pode pensar que $\sqrt{25}$ significa "25 dividido por 2". Parece correto, mas não está. O certo é perguntar: "que número, multiplicado por ele mesmo, dá 25?". A resposta é 5.

---

## 🚀 Exemplo Lógico

Depois de religar o farol e cruzar o primeiro planeta, você e Cálculo-Zero chegam a uma estrutura estranha: **a Câmara dos Ecos**. É uma sala circular, com paredes metálicas que repetem cada som duas, três, quatro vezes. Na parede do fundo há uma porta selada e, ao lado dela, um painel que mostra um número brilhando: **144**.

— Esse número é a **energia registrada** — explica Cálculo-Zero. — A porta só abre se descobrirmos **qual carga, multiplicada por ela mesma, produz essa energia**.

Você já conhece a lógica do farol: uma carga multiplicada por ela mesma é uma potência. Mas agora a pergunta está **ao contrário**. Antes vocês sabiam a carga e calculavam a energia. Agora a energia é conhecida, e a carga é o mistério.

⚠️ Você pensa: "144... então é só dividir por 2 e pronto, 72". Cálculo-Zero grava um eco na parede e deixa a sala devolver a resposta: "**Se fosse 72, a energia seria 72 × 72, muito maior que 144.**" Dividir por 2 não desfaz uma multiplicação de um número **por ele mesmo**.

### 🧩 Os personagens da história

* A **energia no painel** é o **radicando**: o número do qual queremos a raiz (aqui, 144).
* O **número de repetições da carga** é o **índice** da raiz. Nesta porta, a carga se multiplica por ela mesma **2 vezes** (índice 2, raiz quadrada).
* A **carga misteriosa** é a **raiz**: o resultado que procuramos.

### 🔧 Quatro pistas para encontrar a carga

Cálculo-Zero mostra que há mais de um caminho para descobrir a carga misteriosa:

**1. Desmontar a energia.** O robô propõe quebrar 144 em peças menores, fatorando até só sobrarem números primos, e depois **agrupar as peças em pares iguais**, já que a carga aparece duas vezes.

**2. Contar degraus ímpares.** Na câmara há uma escada de degraus ímpares: 1, 3, 5, 7... Cálculo-Zero diz que, somando degraus ímpares em sequência a partir do 1, o total é sempre uma energia "quadrada". **Quantos degraus** são necessários para chegar em 144?

**3. Olhar o último dígito.** O painel mostra que o número termina em **4**. O robô diz que isso já elimina muitas possibilidades: só **duas cargas** terminam de um modo que produz energia terminada em 4.

**4. Aproximar quando o número não é exato.** Um segundo painel, de uma porta lateral, mostra **140**. Não existe carga inteira que produza essa energia, mas Cálculo-Zero lembra que 140 está bem perto de 144. Dá para **estimar** a carga usando o número exato mais próximo.

### ⚠️ Armadilhas da câmara

* **Duas respostas.** Em uma parede, o painel mostra uma equação: carga multiplicada por ela mesma é 9. Você descobre que a carga é 3, mas Cálculo-Zero lembra que **a carga também poderia ser −3**, porque o produto de dois negativos é positivo.
* **Energia negativa.** Um painel quebrado mostra energia **−16** para a mesma porta de dois ecos. Pode haver carga que, multiplicada por ela mesma, dê −16? E se a porta fosse de **três ecos** com energia −8?
* **Somar dentro da raiz.** Uma porta mostra **9 + 16** dentro do radical. Você pensa: "separo em duas raízes, a de 9 e a de 16, e somo". Parece correto, mas deixa a resposta errada. Já **multiplicar** dentro da raiz funciona de outro jeito.

Repare no que a história mostra:

* A raiz **desfaz a potência**: sai a energia, volta a carga.
* O índice diz quantas vezes a carga se multiplica por ela mesma.
* Há vários caminhos para achar a raiz, e alguns números só aceitam **estimativa**.
* Nem toda raiz existe nos números reais, e nem toda equação tem uma resposta só.

---

## 🧮 Exemplo Prático

Agora vamos transformar a Câmara dos Ecos em matemática, passo a passo.

### 🧠 Passo 1: a definição

A radiciação é a operação inversa da potenciação:

$$a^n = b \iff \sqrt[n]{b} = a$$

🚀 **Na câmara:** a carga $a$ multiplicada $n$ vezes por ela mesma dá a energia $b$. A raiz percorre o caminho inverso: parte de $b$ e devolve $a$.

🔹 **Exemplo:** como $12^2 = 144$, temos $\sqrt{144} = 12$.

⚠️ **Conferindo a armadilha:** $\sqrt{144} \neq 144 \div 2 = 72$. Para conferir, $72^2 = 5184$, que é muito maior que 144.

### 🧩 Passo 2: os elementos da raiz

$$\sqrt[n]{a} = b \iff b^n = a$$

| Termo | Nome técnico | Exemplo | Na câmara |
|---|---|---|---|
| $\sqrt{\phantom{a}}$ | Radical | O símbolo da raiz | O sinal de "desfazer" |
| $a$ | Radicando | $\sqrt{144}$ → 144 | A energia no painel |
| $n$ | Índice | $\sqrt[3]{a}$ → 3 | Quantas vezes a carga se repete |
| $b$ | Raiz (resultado) | $\sqrt{144} = 12$ | A carga misteriosa |

Quando o índice é 2, ele não é escrito: $\sqrt{a}$ significa $\sqrt[2]{a}$.

### 🔢 Passo 3: tipos comuns de raiz

| Tipo | Exemplo | Justificativa |
|---|---|---|
| Raiz quadrada | $\sqrt{25} = 5$ | $5^2 = 25$ |
| Raiz cúbica | $\sqrt[3]{27} = 3$ | $3^3 = 27$ |
| Raiz quarta | $\sqrt[4]{16} = 2$ | $2^4 = 16$ |

💡 De forma geral, a **raiz n-ésima** de $b$ é o número $a$ tal que $a^n = b$.

### 🔧 Passo 4: os quatro métodos para $\sqrt{144}$

#### 1. ✅ Método tradicional (fatoração)

Fatoramos 144 até só restarem primos:

$$144 = 2 \times 2 \times 2 \times 2 \times 3 \times 3$$

Como o índice é 2, agrupamos de **dois em dois**:

$$(2 \times 2) \times (2 \times 2) \times (3 \times 3)$$

De cada par, sai **um** número para fora da raiz:

$$\sqrt{144} = 2 \times 2 \times 3 = \mathbf{12}$$

🚀 **Na câmara:** cada par de peças iguais é um "eco" da mesma carga. Tirar um representante de cada par é descobrir a carga.

#### 2. ✅ Soma dos ímpares

A soma dos $n$ primeiros números ímpares é $n^2$:

$$1 + 3 + 5 + 7 + \dots + 23 = 144 \quad \text{(12 termos)}$$

Como foram necessários 12 degraus, $\sqrt{144} = \mathbf{12}$.

🚀 **Na câmara:** a escada tem 12 degraus até a energia 144, então a carga é 12.

#### 3. ✅ Dígito final

| Unidade | Possíveis raízes |
|---|---|
| 1 | 1 ou 9 |
| 4 | 2 ou 8 |
| 9 | 3 ou 7 |
| 6 | 4 ou 6 |
| 5 | 5 |

O número 144 termina em **4**, então a raiz termina em **2 ou 8**. Como $8^2 = 64$ é pequeno demais e $12^2 = 144$ ✔️, o resultado é **12**.

🚀 **Na câmara:** o último dígito do painel elimina candidatos antes mesmo de testar.

#### 4. 🧠 Método aproximado (quando não é exata)

Para $\sqrt{140}$, usamos o quadrado perfeito mais próximo, $144 = 12^2$:

$$\sqrt{140} \approx \frac{140 + 144}{2 \times 12} = \frac{284}{24} \approx \mathbf{11{,}8}$$

🚀 **Na câmara:** a porta lateral de energia 140 tem uma carga quase 12, um pouco menor, em torno de 11,8.

✅ **Conferindo:** $11{,}8^2 = 139{,}24$, muito perto de 140.

### ⚠️ Passo 5: os casos especiais

#### 1. Raízes múltiplas

A equação $x^2 = 9$ tem duas soluções reais: $x = 3$ e $x = -3$, pois $3^2 = 9$ e $(-3)^2 = 9$.

> A raiz quadrada em si é sempre a **positiva**: $\sqrt{9} = 3$. O $\pm$ aparece quando resolvemos a equação.

🚀 **Na câmara:** a parede aceita duas cargas, +3 e −3, mas o símbolo $\sqrt{\phantom{a}}$ devolve apenas a positiva.

#### 2. Raiz de número negativo com índice par

$$\sqrt{-16} \notin \mathbb{R}$$

Nenhum número real multiplicado por ele mesmo dá negativo, pois $4 \times 4 = 16$ e $(-4) \times (-4) = 16$.

🚀 **Na câmara:** o painel com energia −16 está quebrado. Nenhuma carga real produz isso com dois ecos.

#### 3. Raiz de número negativo com índice ímpar

$$\sqrt[3]{-8} = -2 \quad \text{pois} \quad (-2)^3 = -8$$

Com três multiplicações, o sinal negativo se mantém: $(-2) \times (-2) \times (-2) = 4 \times (-2) = -8$.

🚀 **Na câmara:** na porta de três ecos, a energia −8 é possível, com carga **−2**.

#### 4. Raiz de potência

$$\sqrt[n]{a^m} = a^{m/n}$$

📌 **Exemplos:**

* $\sqrt{9^4} = 9^{4/2} = 9^2 = 81$
* $\sqrt[3]{8^6} = 8^{6/3} = 8^2 = 64$

💬 **Truque:**

> *"Quem tá no sol (expoente) vai pra sombra (dividido), quem tá na sombra (índice) vai pro sol (embaixo da fração)"*
> — Prof. Giz, com Gis. 2020™

### 🧩 Passo 6: regras de ouro

| Regra | Correto? | Exemplo |
|---|---|---|
| $\sqrt{a \cdot b} = \sqrt{a} \cdot \sqrt{b}$ | ✅ | $\sqrt{18} = \sqrt{9} \cdot \sqrt{2} = 3\sqrt{2}$ |
| $\sqrt{a + b} = \sqrt{a} + \sqrt{b}$ | ❌ | $\sqrt{9+16} = \sqrt{25} = 5$, mas $\sqrt{9} + \sqrt{16} = 3 + 4 = 7$ |

🚀 **Na câmara:** a porta com $9 + 16$ dentro do radical pede primeiro a **soma** (25) e depois a raiz (5). Separar em duas raízes daria 7, e a porta não abriria.

### 🧮 Passo 7: operações com raízes

#### ➕ Adição e subtração

| Expressão | Resultado | Observação |
|---|---|---|
| $\sqrt{10} + \sqrt{10}$ | $2\sqrt{10}$ | Raízes iguais |
| $\sqrt{10} - \sqrt{10}$ | $0$ | Subtração normal |
| $2\sqrt{10} + 3\sqrt{10}$ | $5\sqrt{10}$ | Soma coeficientes |
| $2\sqrt{10} - 3\sqrt{10}$ | $-\sqrt{10}$ | Subtrai coeficientes |
| $\sqrt{2} + \sqrt{3}$ | $\sqrt{2} + \sqrt{3}$ | ❌ Radicandos diferentes |

#### ✖️ Multiplicação

| Expressão | Resultado | Observação |
|---|---|---|
| $\sqrt{10} \times \sqrt{10}$ | $10$ | $\sqrt{a} \times \sqrt{a} = a$ |
| $2\sqrt{10} \times 3\sqrt{10}$ | $6 \times 10 = 60$ | Coeficientes × coeficientes, raízes × raízes |
| $\sqrt{2} \times \sqrt{5}$ | $\sqrt{10}$ | Multiplica radicandos |

#### ➗ Divisão

| Expressão | Resultado | Observação |
|---|---|---|
| $\sqrt{10} \div \sqrt{10}$ | $1$ | Raízes iguais se anulam |
| $2\sqrt{10} \div 3\sqrt{10}$ | $\dfrac{2}{3}$ | Radical anula, sobra a fração |
| $\sqrt{50} \div \sqrt{2}$ | $\sqrt{25} = 5$ | Usa $\sqrt{\dfrac{a}{b}} = \dfrac{\sqrt{a}}{\sqrt{b}}$ |

### 🎯 Passo 8: interpretação final

A porta da câmara abre com a carga **12**, porque $12^2 = 144$. Para chegar nela, você pode **fatorar**, **contar degraus ímpares** ou **usar o último dígito**. Quando o número não é exato, como 140, a carga é **estimada** perto do quadrado perfeito mais próximo. E sempre vale checar: o índice é par? O radicando é negativo? A soma está dentro da raiz?

---

## 💡 Resumo estilo prova

### 📝 O que preciso saber?

**Definição:** raiz é a operação inversa da potência. Ela descobre qual número, multiplicado por ele mesmo $n$ vezes, resulta no radicando.

$$a^n = b \iff \sqrt[n]{b} = a$$

| Termo | Nome | Exemplo | Na câmara |
|---|---|---|---|
| $\sqrt{\phantom{a}}$ | Radical | Símbolo | Sinal de "desfazer" |
| $a$ | Radicando | $\sqrt{144}$ → 144 | Energia no painel |
| $n$ | Índice | $\sqrt[3]{a}$ → 3 | Número de ecos |
| $b$ | Raiz | $\sqrt{144} = 12$ | Carga misteriosa |

### 🔢 Tipos de raiz

| Tipo | Exemplo | Por quê |
|---|---|---|
| Quadrada | $\sqrt{25} = 5$ | $5^2 = 25$ |
| Cúbica | $\sqrt[3]{27} = 3$ | $3^3 = 27$ |
| Quarta | $\sqrt[4]{16} = 2$ | $2^4 = 16$ |

### 🔧 Métodos para $\sqrt{144}$

| Método | Ideia | Na câmara |
|---|---|---|
| Fatoração | Agrupa os primos de $n$ em $n$ | Pares de ecos |
| Soma dos ímpares | $n$ ímpares somam $n^2$ | Degraus da escada |
| Dígito final | Último dígito limita as raízes | Candidatos eliminados |
| Aproximação | Usa o quadrado perfeito mais próximo | Estimar 140 |

### ⚠️ Erros clássicos de prova

| ❌ Erro | ✅ Certo |
|---|---|
| $\sqrt{144} = 144 \div 2 = 72$ | $\sqrt{144} = 12$, pois $12^2 = 144$ |
| $\sqrt{a+b} = \sqrt{a} + \sqrt{b}$ | $\sqrt{9+16} = 5$, não $3 + 4 = 7$ |
| $\sqrt{-16} = -4$ | $\sqrt{-16} \notin \mathbb{R}$ (índice par de negativo) |
| $\sqrt{9} = \pm 3$ | $\sqrt{9} = 3$; o $\pm$ aparece só em $x^2 = 9$ |
| $\sqrt{2} + \sqrt{3} = \sqrt{5}$ | Radicandos diferentes não se somam |

### 🧠 Você TEM que saber

| Conceito | Exemplo |
|---|---|
| Raiz é o inverso da potência | $\sqrt[3]{27} = 3$ porque $3^3 = 27$ |
| Índice par de negativo = proibido | $\sqrt{-1}$ ❌ (não existe em $\mathbb{R}$) |
| Índice ímpar de negativo = permitido | $\sqrt[3]{-8} = -2$ ✅ |
| Raiz de potência = expoente fracionário | $\sqrt[3]{8^4} = 8^{4/3}$ |
| Produto pode separar | $\sqrt{a \cdot b} = \sqrt{a} \cdot \sqrt{b}$ |
| Soma NÃO pode separar | $\sqrt{a + b} \neq \sqrt{a} + \sqrt{b}$ |

### 🧠 Frases para lembrar

> **"Raiz é o eco da potência: ela devolve a carga que gerou a energia."**

> **"Produto separa, soma não separa. Índice par não aceita negativo, índice ímpar aceita."**

> **"Na Câmara dos Ecos, a porta só abre quando você descobre qual carga, multiplicada por ela mesma, dá a energia do painel."**