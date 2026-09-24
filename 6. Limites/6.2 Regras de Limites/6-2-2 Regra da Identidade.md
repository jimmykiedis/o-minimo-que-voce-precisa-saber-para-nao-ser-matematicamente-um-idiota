# 6.2.2 Regra da Identidade

# 🛣️ Introdução

Lembra que um limite pergunta "para qual valor essa coisa está indo, enquanto $x$ chega pertinho de um número $a$?"

A regra da identidade trata do caso mais simples de todos: Quando dentro do limite **existe só o próprio $x$**, sem mais nada.

> "Quando temos apenas $x$ dentro de um limite, o resultado é o número para qual o $x$ está indo.

Em matemática escrevemos assim:

$$
\lim_{x \to a}x=a
$$

Nesta fórmula, $x$ é a quantidade que está variando, e $a$ é o número para onde ela está indo.

A palavra "identidade" vem de algo que **devolve exatamente o que recebeu**, do mesmo jeito que um espelho. 🪞 Você mostra o $x$ e ele devolve o $x$.

# 🚗 Exemplo Lógico

Agora que estamos na estrada, percebemos que na rodovia há **placas que informam o quilômetro onde estamos**:

- Km 10
- Km 20
- Km 30
- Km 40
- ...

📍 **"Onde estamos?"**

Digamos que o carro está bem na frente da placa de **Km 30**. Lá do banco de trás alguém pergunta (como toda criança em uma viagem):

> "Em qual quilômetro o carro está?"

E a resposta é:

> "No Km 30!"

Prepare que **a reposta é a própria posição**. Você pergunta "onde está o carro?", e a estrada responde com o lugar em que ele está. Não tem truque, não tem transformação, não tem conta escondida. 😄

Se o carro estiver no Km 40, a resposta é **Km 40**. Se estiver no Km 10, a respota é **Km 10**. A posição entra, e a mesma posição sai. E é por isso que a regra se chama **Identidade**

🔍 **Qual a difenreça para a constante?**

No capítulo anterior, o número de rodas sempre **era o mesmo**, não importava onde o carro estivesse. Já o **Quilômetro muda o tempo todo**: No começo da viagem é um número, no meio é outro, na chegada é outro. 🛣️

Mas note uma coisa importante: Mesmo mudando, ele **nunca é uma surpresa**. O quilômetro informado é sempre exatamente o lugar onde o carro está

## 📞 A ligação com os limites

Agora imagine que o carro está **se aproximando da placa Km 50**. Ele ainda não chegou, mas está chegando perto, cada vez mais perto...

Se olharmos o quilômetro que o carro marca durante essa aproximação, o que vemos? **Números cada vez mais próximos de 50**.

>Se a resposta é sempre a própria posição, então, quando a posição está chegando perto de um lugar, a resposta também está chegando perto desse mesmo lugar.

**Essa é a ideia da Regra da Identidade**. O limite pergunta:

> "para onde essa quantidade está indo?" 

E, como a quantidade é a própria posição, ela vai para o lugar aonde o carro está indo. 😉

# 🧮 Exemplo Prático

Hora de transformar a história em matemática!

Vamos chamar de $x$ **o quilômetro em que o carro está**. Como a resposta é a própria posição, criamos uma "regra do quilômetro":

$$
f(x)=x
$$

Lemos: "Se o carro está no quilômetro $x$, a reposta é $x$".

## 📍 Exemplo 1: o carro parado no Km 30

$$
f(30)=30
$$

Lemos: "Se o carro está no quilômetro `30`, a reposta é `30`".

## 🚗 Exemplo 2: chegando pertinho do Km 50

Veja o que acontece quando o carro vai se aproximando da placa do Km 50:

O carro está no...	|A resposta é...|
|---|---|
Km 48	|48
Km 49	|49
Km 49,9	|49,9
Km 49,99	|49,99

Os números vão chegando cada vez mais perto de 50. Por isso escrevemos:

$$
\lim_{x \to 50}x=50
$$

**Em linguagem simples**: "Quando o carro chega pertinho do Km 50, o quilômetro marcado chega pertinho de 50."

## 🛣️ Exemplo 3: outros pontos da viagem

$$
\lim_{x \to 10}x=10
$$

"Chegando pertinho do Km 10, a resposta chega pertinho de 10."

$$
\lim_{x \to 0}x=0
$$

"Chegando pertinho do Km 0 (a saída da viagem!), a resposta chega pertinho de 0."

$$
\lim_{x \to 200}x=200
$$

"Chegando pertinho do Km 200, a resposta chega pertinho de 200."

## 🔍 O que todos esses exemplos têm em comum?

Olhe com atenção: para onde $x$ ia, o resultado ia junto!

- $x\to 50$ deu 50
- $x\to 10$ deu 10
- $x\to 0$ deu 0
- $x\to 200$ deu 200

**O resultado é sempre o número para o qual $x$ está indo**. Como o que está dentro do limite é só o próprio $x$, a resposta acompanha ele.

Então podemos escrever a regra para qualquer valor $a$:

$$
\lim_{x \to a}x=a
$$

Lendo em voz alta: **"O limite, quando $x$ tende a $a$, de $x$ é igual a $a$.**"

# 📌 Resumo

$$
\lim_{x \to a}x=a
$$

> O limite de $x$, quando $x$ tende a $a$, é o próprio $a$.

Como usar:

1. Olhe o que está dentro do limite.
2. Se for só o $x$ (sem mais nada), a resposta é o número para o qual $x$ está indo.
3. Basta olhar o que aparece embaixo de "lim": é ali que está a resposta.

🧠 **Dica para memorizar**

> 🚗 Para onde o carro vai, o quilômetro marcado vai junto.