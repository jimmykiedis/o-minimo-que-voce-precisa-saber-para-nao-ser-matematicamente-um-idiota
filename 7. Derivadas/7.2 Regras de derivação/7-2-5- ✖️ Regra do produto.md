# 7.2.5. ✖️ Regra do produto

```
Quando duas coisas mudam ao mesmo tempo e são multiplicadas, a mudança no resultado depende das duas.
```

# 🎯 Introdução
Até agora, já vimos o que acontece quando somamos ou subtraimos funções. Agora falta entender o que acontece quando **multiplicamos uma função por outra**

# 🧠 Exemplo lógico

Vamos imaginar que seu vídeo viral está trazendo muitas visualizações. 👀🔥

Conforme o tempo passa, o vídeo recebe cada vez mais visualizações. Mas existe outro detalhe: **o número de seguidores do perfil também pode mudar**.

Então temos duas coisas variando ao mesmo tempo:

* 👀 **Número de visualizações**

* 👤 **Número de seguidores**

Isso significa que, conforme o tempo passa, a **relação entre visualizações e seguidores também pode mudar**.

A pergunta que queremos responder é:

> **"Como a relação entre visualizações e seguidores está mudando?"**

Para descobrir isso, precisamos analisar **a mudança das duas quantidades ao mesmo tempo**.

É justamente aí que entra a **Regra do Quociente**.

# 🧮 Exemplo prático

Vamos colocar alguns dados do seu vídeo viral para descobrir quanto ele está gerando de receita:

- `100.000` **visualizações**;
- `R$ 0,002` **por cada visualização**

Então, a receita total é:

$$
100.000\times0,002=\boxed{200}
$$

Ou seja:

$$
\boxed{R\$200,00}
$$

Matematicamente, podemos representar essa relação como:

$$
R(t)=f(t)\cdot g(t)
$$

Onde:

- $f(t)$ = número de visualizações;
- $g(t)$ = valor de cada visualização.

## 🎯 E se quisermos descobrir como essa receita está mudando?

**Aqui começa a ficar interessante! 🤣**

Imagine que a rede social tenha várias faixas de monetização. Até `100.001` visualizações, você recebe o valor da tabela `A`. Acima disso e abaixo de `500.001`, passa a receber os valores da tabela `B`.

Conforme o vídeo continua crescendo, novos valores vão aparecer.

Em algum momento:

- 👀 **o número de visualizações muda**;
- 💰 **o valor recebido por cada visualização também muda**.


Talvez você pense:

> "Se $R(t) = f(t)g(t)$, então é só derivar cada um e multiplicar, que a gente descobre o quanto os valores estão variando"

Ou seja:

$$
\cancel{R'(t)=f'(t)g'(t)}
$$

**❌ Não! Se você achava que era assim, se enganou, meu amigo 😎.**

Quando duas funções estão sendo multiplicadas, a **derivada** é calculada de outra forma:

$$
\boxed{(fg)'=f'g+fg'}
$$

Isso acontece porque precisamos considerar as duas coisas que estão mudando: o número de visualizações e o valor de cada visualização.

É exatamente isso que a Regra do Produto nos permite calcular.

### Vamos aos valores"

Temos inicialmente:

- `100.000` visualizações;
- `R$ 0,002` por visualização.

Depois, o vídeo chega a:

- `200.000` visualizações;
- `R$ 0,003` por visualização.

Esses valores nos mostram que **as duas quantidades mudaram**.

A mudança nas visualizações foi:

$$
200.000-100.000=\boxed{100.000}
$$

Como estamos considerando essa mudança em 1 unidade de tempo:

$$
f'=\boxed{100.000}
$$

A mudança no valor por visualização foi:

$$
0,003-0,002=\boxed{0,001}
$$

Então:

$$
g'=\boxed{0,001}
$$

Agora podemos usar a Regra do Produto:

$$
(fg)'=f'g+fg'
$$

Substituindo os valores iniciais:

$$
(fg)'=(100.000)(0,002)+(100.000)(0,001)
$$

Calculando:

$$
200+100=\boxed{300}
$$

Ou seja, nesse intervalo, a receita aumentou em:

$$
\boxed{R\$300,00}
$$

Perceba o que aconteceu:

- `f'g` $\rightarrow$ representa a mudança causada pelo aumento das visualizações;
- `fg'` $\rightarrow$ representa a mudança causada pelo aumento do valor por visualização.
- 
Por isso não fazemos `f'g'`. Precisamos considerar as duas contribuições e somá-las.

🧠 Resumo

A Regra do Produto serve quando temos duas quantidades variando ao mesmo tempo.

Se:

$$
R=f\cdot g
$$

então:

$$
\boxed{R'=f'g+fg'}
$$

Neste exemplo, a receita aumentou R$300 porque as visualizações aumentaram e o valor por visualização também aumentou.