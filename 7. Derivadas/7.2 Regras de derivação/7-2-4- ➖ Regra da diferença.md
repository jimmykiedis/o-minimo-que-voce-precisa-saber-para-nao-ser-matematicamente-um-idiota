# 7.2.4. ➖ Regra da diferença
```
Nem toda mudança é só sobre o que entra. Às vezes, precisamos descobrir também o que está saindo.
```

# 🎯 Introdução

Antes de entender a regra da diferença, precisamos relembrar óbvio. Quando temos duas quantidades e queremos saber a diferena entre elas, precisamos subtrair uma da outra. 

Sei que não precisa, mas aí vai um exemplo:

Você tem $1.000$ de alguma coisa, mas deve $200$.

Quantos sobra?

$$
\boxed{1.000 - 200 = 800}
$$

Parece ridículo, mas agora pense no que acontece quando essas duas quantidades estão **mudando com o tempo**. Se uma quantidade está aumentando enquanto outra também está aumentando, mas repreesnta algo que estamos descontando, precisamos acompanhar as **duas mudanças ao mesmo tempo**. 

É justamente aí que a derivada entra. A **Regra da Diferença** nos permite descobrir **como uma diferença está mudando**, observando separadamente como cada uma das quantidades está mudando.

# 🧠 Exemplo lógico

Lembra daquele vídeo qe você postou e que começou a viralizar? 🎥🔥

As visializações continuam subindo e, conforme mais pessoas assistem ao vídeo, elas também começam a avaliá-lo. Você abre as estatísticas e percebe que, a cada hora, o vídeo está recebendo:

- 👍 $1.000$ *likes* por hora;
- 👎 $200$ *dislikes* por hora.

Então surge uma pergunta:

> "Qual é o aumento líquido de avaliações positivas por hora?"

Para descobrir isso, não basta apenas olhar para os *likes*, também precisamos considerar os *dislikes*. Então:

$$
\boxed{1.000 - 200 = 800}
$$

Ou seja, o saldo líquidod e avaliações positivas está aumentando em 800 por hora. Percebe o que aconteceu? Você tem uma quantidade aumentando:

- 👍 *Likes* $\rightarrow + 1.000$ por hora

E outra quantidade que representa uma redução no saldo:

- 👎 *Dislikes* $\rightarrow + 200$ por hora
Para descobrir a mudança líquida, você precisa subtrair uma da outra. E é Justamente essa ideia que está por trás da Regra da diferença.

## ➖ E é exatamente isso que a Regra da Diferença faz

Agora vamos tranformar essa ideia em matemática. Imagine que:

- $f(t)$ representa a quantidade de *likes* recebidos pelo vídeo.
- $g(t)$ representa a quantidade de *dislikes* recebidos pelo vídeo.

Se quisermos descobrir o saldo líquido de avaliações positivas, podemos fazer:

$$
f(t)−g(t)
$$

E quando queremos descobrir a **velocidade com que esse saldo está mudando**, podemos derivar essa diferença

$$
(f(t)−g(t))'=f'(t)−g'(t)
$$

Ou seja:

> 🚀 A derivada da diferença é a diferença das derivadas.

Isso significa que podemos descobrir a velocidade com que os *likes* estão aumentando e a velocidade coim que os *dislikes* estão aumentando e, podeis subtrair uma da outra.

# 🌎 Exemplo prático

Imagine que, em determinado momento, seu vídeo esteja recebendo:

- 👍 $1.200$ *likes* por hora;
- 👎 $300$ *dislikes* por hora.

Podemos representar a quantidade de **likes** por:

$$
f(t)=1.200t
$$

E a quantidade de *dislikes* por:

$$
g(t)=300t
$$

Aqui temos $t$ representando o tempo em horas. O saldo líquido de avaliações positivas será:

$$
f(t)−g(t)
$$

Substituindo as funções:

$$
f(t)−g(t)=1.200t−300t
$$

Sua diferença vai ficar:

$$
f(t)-g(t)=900
$$

Agora queremos descobrir a velocidade com que o número total de visualizações está aumentando. Derivando Cada função:

$$
\boxed{f'(t)=1.200}
\qquad\text{e}\qquad
\boxed{f'(t)=300}
$$

Aplicamos a regra da soma:

$$
(f+g)'(t)=f'(t)+g'(t)
$$

Então:

$$
\boxed{(f+g)'(t)=1.200−300=900}
$$

🎯 **Resultado: o saldo líquido de avaliações positivas está aumentando em 900 por hora.**

# 🧩 Resumindo

A Regra da Diferença diz:

> "Quando subtraímos duas funções, podemos derivar cada uma separadamente e depois subtrair os resultados."

Em símbolos:

$$
(f−g)'=f'−g'
$$

## 💡 Pense assim:

Taxa de crescimento da primeira quantidade − taxa de crescimento da segunda quantidade = taxa de crescimento da diferença