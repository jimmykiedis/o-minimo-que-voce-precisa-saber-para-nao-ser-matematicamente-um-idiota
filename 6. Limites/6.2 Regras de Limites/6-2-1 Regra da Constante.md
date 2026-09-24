# 6.2.1 Regra da Constante

# 🔒 Introdução

Antes de tudo, uma ideia rápida: Um **limite** pergunta "para qual valor esta coisa está indo, enquanto $x$ chega pertinho de um número $a$.

A **Regra da Constante** diz o seguinte:

> "Quando temos uma constante dentro de um limite, o resultado do limite continua sendo aquela mesma constante."

Em matématica escrevemos assim

$$
\lim_{x \to a}c = c
$$

Nesta fórmula a letra $c$ representa qualquer número que não muda. Pode ser:

$$
4, 1, 100, ...
$$

Se o número fica sempre igual, ele é uma **constante**!

Só isso! Agora vamos entender **por que** isso é verdade, com uma viagem de carro. 🚗💨

# 🔧 Exemplo Lógico

Imagina que você e sua família vão viajar. Antes de ligar o motor, o Papai, ou mamãe (ou o titio que sempre acha que entende de carro 😄) resolve dar uma olhada geral no veículo. Vamos conferir o que existe no carro e não muda:

- 🚗 O carro tem 4 rodas;
- 🛞 Tem 1 estepe;
- 🚪 Tem 4 portas;
- 🎡 Tem 1 volante;
- 💺 tem 5 assentos.

🛞 **A pegadinha do estepe**

> "Mas o estepe é uma roda, certo? Não deveria ter 5 rodas na contagem?"

Será que o carro tem 5 rodas? 

$$
\boxed{\text{Não! 🙅}}
$$

O estepe é só um reserva, guardadinho no porta-malas, esperando um dia de furo. O carro continua tendo 4 rodas e continua rodando sobre 4 pneus. Ter um pneu de reserva não muda a quantidade de rodas.

Então, na revisão, a conclusão é:

- O carro **não passou a ter 5 rodas por causa do estepe**;
- Continua **4 Rodas**;
- Continua **4 portas**;
- Continua **1 volante**
- Continua **5 assentos**

## 🛣️ E quando a viagem começa?

O carro sai da garagem, pega a estrada, passa pelo pedágio, para no posto e pega trânsito. 🚦

Durante tudo isso, **a quantidade de rodas mudou?**

$$
\boxed{\text{Não! 🙅}}
$$

**A quantidade de portas mudou?**

$$
\boxed{\text{Também não! 🙅}}
$$

**Ganhamos outro volante no meio do caminho?**

$$
\boxed{\text{De maneira alguma! 🙅}}
$$

Essas quantidades não mudam só por que a viagem começou.

> Algumas características do carro permanecem iguais durante toda a viagem. Elas são constantes"

## 🔗 A ligação com os limites

Agora imagine que alguém pergunte:

> "Quantas rodas o carro tem chegando pertinho da casa da vovó?

Nem precisa pensar muito: 

**4 rodas!**

E na saída da Garagem? 

**4 rodas!**

E quantas rodas o carro teve o caminho todo até aqui?

**4 rodas!**

> "Se uma quantidade permanece constante, não importa para qual momento da viagem estamos olhando: Ela continua tendo o mesmo valor!

**Essa é exatamente a regra da constante**. Um limite pergunta:

> "Para onde esta quantidade está indo?"

Se ela nunca muda, ela só pode estar se mudando para ela mesmo!

# 🚗 Exemplo Prático

Chegou a hora de transformar a história em matemática!

Vamos imaginar que $x$ **é o quilômetro da estrada** em que o carro está. Quando escrevemos $x \to 10$, lemos **"$x$ está chegando perto do quilômetro 10"**.

## 🚗 Exemplo 1: as rodas

$$
\lim_{x \to 10}4=4
$$

**Em linguagem natural seria:** 

> "Quando o carro chega pertinho do quilômetro 10, quantas rodas ele tem?

**Quatro!** O número quatro não depende do quilômetro, então continua sendo 4!

## 🎡 Exemplo 2: o volante

$$
\lim_{x \to 10}1=1
$$

> "Quando o carro chega pertinho do quilômetro 10, quantos volantes ele tem?

**Um!** O número quatro não depende do quilômetro, então continua sendo 1!

## 🎡 Exemplo 3: Os assentos

$$
\lim_{x \to 10}5=5
$$

> "Quando o carro chega pertinho do quilômetro 10, quantos assentos ele tem?

**Cinco!** O número quatro não depende do quilômetro, então continua sendo 5!

## 🔍 O que todos esses exemplos têm em comum?

Olhe com atenção: O número para qual $x$ estava indo poderia ser `10`, `20`, `50`, `200`, `0`, $\infty$. Em nenhum caso ele mudou o resultado!

Isso aconcetece porque **o número dentro do limite não depende, nem nunca dependeu de** $x$.

Então podemos escrever a regra para qualquer constante $c$ e qualquer valor $a$:

$$
\lim_{x \to a}c=c
$$

Lendo em "voz alta":

> "O limite, quando $x$ tende a $a$, de uma constante $c$ é igual a própria constante $c$".

# 📌 Resumo

$$
\lim_{x \to a}c=c
$$

> O limite de uma constante é a própria constante.

**Como usar:**

1. Olhe o que está dentro do limite.
2. Se **for só um número** (sem $x$ nenhum), este número é a resposta!
3. O valor para onde $x$ vai ($a$) não importa neste caso!

**🧠 Dica para memorizar**

> 🚗 "Se a quantidade não muda durante a viagem, o limite também não muda!"