# 7.2.6. ➗ Regra do quociente
```
Quando uma coisa depende de outra, dividir pode revelar a relação entre elas.
```

# 🎯 Introdução

Até agora, das 4 principais operações matemáticas, falta apenas a divisão para aprendermos, ou seja, o que acontece quando tempos que dividir uma função por outra?

Vamos imaginar que você queira descobrir ingormações como:

> "Quantos visualizações eu tenho pra cada seguidor?"

Suponhamos então que você queira saber quantas vezes a quantidade de visualizações é maior do que a quantidade de seguidores. Neste caso, não basta saber quantas visualizações você tem, também precisamos saber **quantos segudores você tem**.

Por exemplo, se seu perfil possui $10.000$ visualizações e $1.000$ seguidores, podemos dividir:

$$
\boxed{\frac{10.000}{1.000}=10}
$$

Isso significa que temos, em média, **10 vezes mais vizualizações que a quantidade de segudores**

A divisão está mostrando uma relação entre duas quantidades. Agora imagine que tanto o número de visualizações quanto o número de seguidores esteja mudando com o tempo. A pergunta passa a ser:

> "Como essa relação está mudando?"

É justamente aí que entra a *Regra do Quociente**.

# 🧠 Exemplo lógico

**Voltando ao seu vídeo viral** 🎥🔥

Depois de 1 ou 2 dias, ele já acumulou:

- 👀 $199.000$ **novas visualizações**;
- 👁️​ $1.000$ **visualizações dos vídeos anteriores**;
- 👤 $18.000$ **novos segudores**.
- 👥​ $2.000$ **antigos seguidores**.

Você quer saber a relação entre essas duas quantidades. Então divide:

$$
\boxed{\frac{199.000+1.000}{18.000+2.000} = 10}
$$

Ou seja:

> "Existem, 10 visualizações para cada seguidor que você tem no perfil."

Agora imagine que o vídeo continue crescendo. Depois de 5 dias, ele chega:

- 👀 $250.000$ **novas visualizações**;
- 👁️​ $50.000$ **visualizações dos vídeos anteriores**;
- 👤 $23.000$ **novos segudores**.
- 👥​ $2.000$ **antigos seguidores**.

A relação agora é:

$$
\boxed{\frac{250.000+50.000}{23.000+2.000} = 12}
$$

A relaçõa mudou. Antes eram **10 visualizações por seguidor** agora são **12 visualizações por seguidor**.

Perceba que estamos acompanhando uma quantidade que é formada pela divisão de duas outras quantidades. E quando essas quantidades mudam com o tempo, podemos usar derivadas para descobrir como essas relação está mudando.

## ➗ E é exatamente isso que a Regra do Quociente faz

Imagine duas funções:

- $f(t)$ **representa uam quantidade**;
- $g(t)$ **representa outra quantidade**.

Se quisermos dividir uma pela outra, temos:

$$
\frac{f(t)}{g(t)}
$$

Agora queremos descobrir como eessa divisão está mudando. Não podemos simplesmente fazer:

$$
\frac{f'(t)}{g'(t)}
$$

❌ **Isso não funciona.**

Quando temos uma divisão de funções, precisamos usar uma regra específica: A **Regra do Quaociente**. Ela diz:

> 🚀 A derivada de uma divisão não é simplesmente a divisão das derivadas.

A fórmula é:

$$
\left(\frac{f}{g}\right)' = \frac{f'g - fg'}{g^2}
$$

# 🌎 Exemplo prático

Imagine que o número de visualizações do seu vídeo seja representado por:

$$
f(t)=199.000t+1.000
$$

E o número de seguidores seja representado por:

$$
g(t)=18.000t+2.000
$$

A relação entre visualizações e seguidores é:

$$
\frac{f(t)}{g(t)}
$$

Substituindo as funções:

$$
\frac{199.000t+1.000}{18.000t+2.000}
$$

Perceba que agora não podemos simplesmente simplificar a expressão. A relação entre as duas quantidades muda conforme o tempo passa.

É justamente aqui que precisamos da Regra do Quociente:

$$
\left(\frac{f}{g}\right)'=
\frac{f'g-fg'}{g^2}
$$

Primeiro, encontramos as derivadas de cada função:

$$
f'(t)=199.000
$$


$$
g'(t)=18.000
$$


Depois separamos os valores necessários para o cálculo:

$$
f(t)=199.000t+1.000
$$

$$
g(t)=18.000t+2.000
$$

Agora aplicamos a regra:

$$
\frac{199.000(18.000t+2.000)-(199.000t+1.000)(18.000)}
{(18.000t+2.000)^2}
$$

Simplificando:

$$
\frac{380.000.000}{(18.000t+2.000)^2}
$$

Agora podemos descobrir como essa relação está mudando em um determinado momento.

Por exemplo, quando $t=1$:

$$
\frac{380.000.000}{20.000^2}
$$

$$
\boxed{0,95}
$$

Isso significa que, naquele momento, a relação entre visualizações e seguidores está aumentando a uma taxa de aproximadamente 0,95 visualização por seguidor a cada unidade de tempo.

Perceba a ideia principal: não estamos simplesmente descobrindo quantas visualizações existem para cada seguidor. Estamos descobrindo como essa relação está mudando.

E quando uma quantidade é formada pela divisão de duas funções que também estão mudando, usamos a Regra do Quociente.