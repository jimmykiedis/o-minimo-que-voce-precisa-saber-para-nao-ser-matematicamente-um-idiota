# 1.3.5. Frações

> ➗ A arte de dividir sem perder a classe (ou o numerador)

## 🤔 Introdução

Você já dividiu uma pizza entre amigos e alguém disse "fico com dois pedaços de oito"? Ou leu numa receita "meia xícara" ou "um terço do tanque"? Ou percebeu que "2 de 4 pedaços" e "1 de 2" são, na prática, a mesma quantidade? Quantas vezes você já usou frações sem nem perceber?

Uma **fração** é a forma de representar **uma parte de um todo que foi dividido em partes iguais**. Ela serve para dizer quanto temos, quanto sobrou e quanto precisa ser repartido, mesmo quando a quantidade não é um número inteiro. Em Cálculo, frações aparecem em taxas, em limites, em derivadas de quocientes e em quase toda simplificação de expressões.

A ideia principal é: **a fração diz em quantas partes o todo foi dividido e quantas dessas partes estamos considerando**. E aqui mora um erro muito comum. Você pode pensar que, para somar $\frac{1}{4} + \frac{1}{6}$, basta somar em cima e embaixo, resultando em $\frac{2}{10}$. Parece correto, mas não está. Só dá para somar partes quando elas têm o **mesmo tamanho**, e isso exige um denominador comum.

---

## 🚀 Exemplo Lógico

Depois de organizar a estação, você e Cálculo-Zero retomam a viagem, mas o painel da nave acende um alerta vermelho: **os suprimentos estão acabando**. No **estoque da nave** há três recursos que precisam ser repartidos com cuidado até o próximo planeta: **combustível, comida e peças**.

— Precisamos de um plano — diz Cálculo-Zero. — E o plano começa por entender **quanto de cada coisa nós temos**, não só quantas unidades.

### 🍰 Parte 1: o que é cada número da fração

O tanque de combustível está dividido em **8 compartimentos iguais**, e **5 deles** ainda estão cheios. Cálculo-Zero explica que o número de compartimentos totais diz **em quantas partes o todo foi dividido**, e o número de compartimentos cheios diz **quantas partes ainda temos**.

### ➕ Parte 2: juntar suprimentos

A nave tem dois depósitos de comida. Um deles está dividido em **5 compartimentos iguais**, e a dupla usou **2** no café da manhã e **1** no almoço. Como os compartimentos têm o **mesmo tamanho**, dá para juntar o que foi gasto direto.

Depois, você descobre outros dois depósitos de peças: um dividido em **4 partes** e outro em **6 partes**, com **1 parte** de cada separada para conserto. ⚠️ Você pensa: "é só somar as partes e os totais". Cálculo-Zero balança a cabeça: **pedaços de tamanhos diferentes não se somam diretamente**. Antes, é preciso **cortar os dois depósitos em fatias do mesmo tamanho**.

### ✖️ Parte 3: pegar uma parte de uma parte

Do combustível restante, vocês precisam reservar **uma parte para o sistema de emergência**. Em vez de pegar um tanque inteiro, pegam **2 partes de 3** do que sobrou de uma reserva que, por sua vez, representa **4 partes de 5** de um reservatório maior. É uma parte **de** outra parte.

### ➗ Parte 4: repartir entre pacotes

Cálculo-Zero quer saber **quantos pacotes de ração de tamanho 4/5 cabem em uma reserva de 2/3**. Em vez de contar um a um, ele propõe uma estratégia: transformar a pergunta "quantas vezes cabe?" em uma conta mais simples.

### 🔍 Parte 5: arrumar o estoque

O inventário de peças diz que **12 de 20 parafusos** estão em bom estado. Cálculo-Zero diz que dá para **escrever isso de forma mais enxuta**, mantendo exatamente a mesma quantidade, só com números menores.

### ⚡ Parte 6: o motor que repete frações

O motor da nave consome combustível em **ciclos**. Em cada ciclo, uma fração do tanque se repete: **2/5 do tanque** por vez. Se o motor faz **2 ciclos**, quanto do tanque é gasto? E se a regra do motor for invertida, com expoentes **negativos**? Por fim, um painel mostra uma carga **negativa** (**−2/3**), com expoentes negativos de **2** e de **3**. O sinal do resultado vai depender de algo que Cálculo-Zero chama de "paz ou treta".

Repare no que a história mostra:

* A fração diz **em quantas partes** o todo foi dividido e **quantas** estamos usando.
* Só se somam partes **do mesmo tamanho**.
* Pegar uma parte de uma parte é **multiplicar**; repartir é **dividir**.
* Dá para **simplificar** sem mudar a quantidade.
* Potência de fração aplica o expoente **nos dois lados**, e expoente negativo **inverte**.

---

## 🧮 Exemplo Prático

Agora vamos transformar o estoque da nave em matemática, passo a passo.

### 🍰 Passo 1: o que é uma fração?

$$\frac{a}{b}$$

| Termo | Definição | Exemplo | No estoque |
|---|---|---|---|
| Numerador ($a$) | Número de partes que você tem | $5$ em $\dfrac{5}{8}$ | Compartimentos cheios |
| Denominador ($b$) | Em quantas partes o todo foi dividido | $8$ em $\dfrac{5}{8}$ | Total de compartimentos |

🚀 **No estoque:** o tanque com 5 de 8 compartimentos cheios tem $\dfrac{5}{8}$ do combustível.

### ➕ Passo 2: adição e subtração

#### Denominadores iguais

Mantém o denominador e soma (ou subtrai) os numeradores:

$$\frac{2}{5} + \frac{1}{5} = \frac{2+1}{5} = \frac{3}{5}$$

🚀 **No estoque:** a dupla gastou 2 compartimentos no café e 1 no almoço, num depósito de 5. No total, usou $\dfrac{3}{5}$ da comida.

#### Denominadores diferentes

Usa o **MMC** para reescrever as frações com o mesmo denominador, e depois soma.

**Peças separadas:** $\dfrac{1}{4} + \dfrac{1}{6}$

* **MMC de 4 e 6:** 12
* **Reescrevendo:** $\dfrac{1}{4} = \dfrac{3}{12}$ (multiplicamos em cima e embaixo por 3) e $\dfrac{1}{6} = \dfrac{2}{12}$ (multiplicamos por 2)

$$\frac{1}{4} + \frac{1}{6} = \frac{3}{12} + \frac{2}{12} = \frac{5}{12}$$

🚀 **No estoque:** cortamos os dois depósitos em 12 fatias iguais. Agora dá para somar: $\dfrac{5}{12}$ das peças foram separadas.

⚠️ **Conferindo a armadilha:** $\dfrac{1}{4} + \dfrac{1}{6} \neq \dfrac{2}{10}$. Aliás, $\dfrac{2}{10} = 0{,}2$ é menor que $\dfrac{1}{4} = 0{,}25$, o que não faz sentido para uma soma.

### ✖️ Passo 3: multiplicação

Multiplica numerador por numerador e denominador por denominador (multiplicação **em linha**):

$$\frac{2}{3} \times \frac{4}{5} = \frac{2 \times 4}{3 \times 5} = \frac{8}{15}$$

🚀 **No estoque:** pegar $\dfrac{2}{3}$ **de** $\dfrac{4}{5}$ da reserva equivale a $\dfrac{8}{15}$ do reservatório maior. A palavra "de" pede multiplicação.

### ➗ Passo 4: divisão

Inverte a segunda fração e multiplica (multiplicação **cruzada**):

$$\frac{2}{3} \div \frac{4}{5} = \frac{2}{3} \times \frac{5}{4} = \frac{2 \times 5}{3 \times 4} = \frac{10}{12} = \frac{5}{6}$$

🚀 **No estoque:** em uma reserva de $\dfrac{2}{3}$, cabem $\dfrac{5}{6}$ do pacote de ração de tamanho $\dfrac{4}{5}$. Ou seja, **não cabe um pacote inteiro**.

### 🔍 Passo 5: simplificação

Divide numerador e denominador pelo **MDC** (maior divisor comum):

$$\frac{12}{20} = \frac{12 \div 4}{20 \div 4} = \frac{3}{5}$$

* **MDC de 12 e 20:** 4

🚀 **No estoque:** "12 de 20 parafusos bons" é o mesmo que "3 de cada 5". A quantidade não mudou, só ficou mais enxuta.

✅ **Conferindo:** $\dfrac{12}{20} = 0{,}6$ e $\dfrac{3}{5} = 0{,}6$.

### ⚡ Passo 6: potenciação de frações

#### 🔼 Expoente positivo

Eleva numerador e denominador separadamente:

$$\left(\frac{2}{5}\right)^2 = \frac{2^2}{5^2} = \frac{4}{25}$$

🚀 **No motor:** 2 ciclos de $\dfrac{2}{5}$ do tanque consomem $\dfrac{4}{25}$ do tanque.

#### 🔁 Expoente negativo

Inverte a fração e eleva normalmente:

$$\left(\frac{2}{3}\right)^{-1} = \frac{3}{2} \qquad\qquad \left(\frac{3}{4}\right)^{-2} = \left(\frac{4}{3}\right)^2 = \frac{16}{9}$$

🚀 **No motor:** com a regra invertida, o motor "descarrega" em vez de consumir, e a fração vira de ponta-cabeça antes de ser elevada.

### ⚠️ Passo 7: fração negativa com expoente negativo

| Exemplo | Inversão | Resultado |
|---|---|---|
| $\left(-\dfrac{2}{3}\right)^{-2}$ | $\left(-\dfrac{3}{2}\right)^2$ | $\dfrac{9}{4}$ (positivo) |
| $\left(-\dfrac{2}{3}\right)^{-3}$ | $\left(-\dfrac{3}{2}\right)^3$ | $-\dfrac{27}{8}$ (negativo) |

📌 **Regra de sinal:**

* Expoente **par** → resultado **positivo**
* Expoente **ímpar** → resultado **negativo**

🚀 **No painel da carga negativa:** com expoente 2, os dois sinais negativos se cancelam ("paz"). Com expoente 3, sobra um sinal negativo ("treta").

### 🎯 Passo 8: interpretação final

Para repartir o estoque da nave: **some** só partes do mesmo tamanho (MMC se for preciso), **multiplique** em linha quando for "parte de uma parte", **divida** invertendo a segunda fração, **simplifique** pelo MDC para deixar os números enxutos, e **eleve** numerador e denominador quando houver potência. Se o expoente for negativo, inverta antes.

---

## 💡 Resumo estilo prova

### 📝 O que preciso saber?

**Definição:** fração é a representação de uma parte de um todo dividido em partes iguais. O **denominador** diz em quantas partes o todo foi dividido, e o **numerador** diz quantas partes temos.

| Termo | Definição | No estoque |
|---|---|---|
| Numerador | Partes que você tem | Compartimentos cheios |
| Denominador | Total de partes iguais | Compartimentos totais |

### 🛠️ Operações com frações

| Operação | Regra | Exemplo | No estoque |
|---|---|---|---|
| $+$ / $-$ (denominador igual) | Soma/subtrai numeradores | $\dfrac{2}{5} + \dfrac{1}{5} = \dfrac{3}{5}$ | Depósito de comida |
| $+$ / $-$ (denominador diferente) | MMC, reescreve e soma | $\dfrac{1}{4} + \dfrac{1}{6} = \dfrac{5}{12}$ | Cortar peças em fatias iguais |
| $\times$ | Numerador × numerador, denominador × denominador | $\dfrac{2}{3} \times \dfrac{4}{5} = \dfrac{8}{15}$ | Parte de uma parte |
| $\div$ | Inverte a 2ª e multiplica | $\dfrac{2}{3} \div \dfrac{4}{5} = \dfrac{5}{6}$ | Pacotes de ração |
| Simplificar | Divide pelo MDC | $\dfrac{12}{20} = \dfrac{3}{5}$ | Parafusos bons |

### ⚡ Potenciação de frações

| Caso | Regra | Exemplo |
|---|---|---|
| $\left(\dfrac{a}{b}\right)^n$ | Eleva numerador e denominador | $\left(\dfrac{2}{5}\right)^2 = \dfrac{4}{25}$ |
| $\left(\dfrac{a}{b}\right)^{-n}$ | Inverte e eleva | $\left(\dfrac{3}{4}\right)^{-2} = \dfrac{16}{9}$ |
| Fração negativa | Expoente par = $+$ / ímpar = $-$ | $\left(-\dfrac{2}{3}\right)^{-3} = -\dfrac{27}{8}$ |

### ⚠️ Erros clássicos de prova

| ❌ Erro | ✅ Certo |
|---|---|
| $\dfrac{1}{4} + \dfrac{1}{6} = \dfrac{2}{10}$ | $\dfrac{1}{4} + \dfrac{1}{6} = \dfrac{5}{12}$ (use o MMC) |
| Dividir frações sem inverter | $\dfrac{2}{3} \div \dfrac{4}{5} = \dfrac{2}{3} \times \dfrac{5}{4}$ |
| $\left(\dfrac{2}{3}\right)^{-2} = \dfrac{4}{9}$ | $\left(\dfrac{2}{3}\right)^{-2} = \dfrac{9}{4}$ (inverte antes) |
| Ignorar o sinal em $\left(-\dfrac{2}{3}\right)^{-3}$ | Expoente ímpar mantém o sinal negativo |
| Deixar $\dfrac{12}{20}$ sem simplificar | Simplifique pelo MDC: $\dfrac{3}{5}$ |

### 🧠 Frases para lembrar

> **"Some só se tiver o mesmo denominador. Se não, acha o MMC. Multiplicou? Vai em linha. Dividiu? Vira e vai. Potência? Sobe cada um. Negativa? Inverte antes. Sinal? Par é paz, ímpar é treta."**

> **"No estoque da nave, a fração diz quantas partes temos do todo, e só se somam fatias do mesmo tamanho."**