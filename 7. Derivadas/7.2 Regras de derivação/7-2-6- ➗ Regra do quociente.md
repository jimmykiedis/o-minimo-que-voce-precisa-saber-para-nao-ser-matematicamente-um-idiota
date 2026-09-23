# 7.2.6. ➗ Regra do quociente
```
Quando uma coisa depende de outra, dividir pode revelar a relação entre elas.
```

# 🎯 Introdução

Até agora, das 4 principais operações matemáticas, falta apenas a divisão para aprendermos, ou seja, o que acontece quando tempos que dividir uma função por outra?

Vamos imaginar que você queira descobrir ingormações como:

> "Quantos visualizações eu tenho pra cada seguidor?"

# 🧠 Exemplo lógico

Imagine que você tenha um perfil em uma rede social.

Você pode observar duas coisas:

* quantas **pessoas assistiram aos seus vídeos**;
* quantas **pessoas começaram a seguir você**.

Agora imagine que o seu perfil continue crescendo.

Com o passar do tempo, podem acontecer duas coisas ao mesmo tempo: **o número de visualizações aumenta e o número de seguidores também aumenta**.

Então podemos fazer uma pergunta:

> **“A relação entre visualizações e seguidores está mudando com o tempo?”**

Por exemplo, talvez no começo você tivesse muitas visualizações em relação ao número de seguidores. Depois, seu perfil pode começar a ganhar seguidores mais rapidamente — ou pode acontecer o contrário.

Ou seja, não estamos interessados apenas em saber **quantas visualizações e quantos seguidores existem**.

Queremos saber **como a relação entre essas duas quantidades está mudando**.

É aqui que entra a **Regra do Quociente**.

Ela é usada quando temos uma quantidade que depende da **divisão entre duas outras quantidades** e queremos descobrir **como essa relação muda**.

> 💡 **Ideia principal:**
> **Duas quantidades estão mudando → existe uma relação entre elas → queremos saber como essa relação está mudando.**

No **Exemplo Prático**, aí sim podemos colocar os números, fazer as divisões e mostrar como a Regra do Quociente funciona.

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

**obs.: 1.000 você já tinha contando todos os demais vídeos antigos*

E o número de seguidores seja representado por:

$$
g(t)=18.000t+2.000
$$

**obs.: 2.000 são seus seguidores que você tinha antes do seu vídeo viralizar*

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