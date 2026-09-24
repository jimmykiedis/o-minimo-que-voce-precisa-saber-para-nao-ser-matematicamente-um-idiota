# 7.2.8. 📈 Derivadas das funções exponenciais
```
🚀  Se algo cresce cada vez mais rápdio, como descobrimos a velocidade desse crescimento?
```

# 🎯 Objetivo
Entender como calcular a derivada de uma expressão exponencial e, principalmente, entender o que essa derivada está nos dizendo sobre a velocidade de crescimento.

## 🧠 Uma lembrança rápida 
Antes de falar de derivada, só precisamos lembrar de uma coisa:

Quando a variável aparece no exponente, temos uma expressão exponencial.

Por exemplo

$$
f(x)=2^x
$$

E pronto. Não precisamos ficar aqui fazendo uma "reunião de condomínio" sobre funções. 😂

O que realmente nos interessa agora é outra pergunta:

> "Se essa quantidade está crescendo exponencialmente, quão rápido ele está crescendo?"

É aí que entra a derivada.

# 🎬 Exemplo lógico

Vamos continuar na sua saga de se tornar um *digital influencer*. Imagine que você acabou de postar seu terceiro vídeo. Os dois primeiros bombaram, como a gente já viu nos capítulos anteriores, mas o terceiro você quer fazer algo especial.

**Um conteúdo família** ❤️

No final do vídeo você descide fazer uma experiência:

> "Se cada pessoa comparilhar esse video com os seus dois pais, até onde isso pode chegar?"

Uma pessoa manda para dois pais. ❤️

Esses dois pais mandar para os pais deles. 👥

Agora são quatro pessoa. 🔥

Essas quatro mandaram para seus pais. 👴

Agora são oito.

Percebe o que está acontecendo?

$$
1 \rightarrow 2 \rightarrow 4 \rightarrow 8 \rightarrow 16 \rightarrow 32 \rightarrow 64 \rightarrow …
$$

<div align="center">
👤 Você

$\downarrow$

👥 Pais

$\downarrow$

👥👥 Avós

$\downarrow$

👥👥👥👥 Bisavós

$\downarrow$

👥👥👥👥👥👥👥👥 Trisavós

$\downarrow$

…

</div>

A cada geração, a quantidade dobra. E é justamente esse tipo de crescimento que podemos representar por:

$$
2^x
$$

## 🤔 Mas agora vem a pergunta importante
Até aqui, podemos descobrir quantas pessoas existem depois de determinada quantidade de gerações. Mas isso não é o que queremos investigar agora. A pergunta que interessa para **Cálculo** é:

> 🚀 "Quão rapidamente essa quantidade está crescendo?"

Por que existe uma diferença enorme entre:

> "Temos 1.000 pessoas."

e: 

> "Estamos aumentando em terminada velocidade"

É exatamente essa diferença que a **derivada** consegue revelar.

# 🧮 Exemplo prático

Considere:

$$
f(x)=2^x
$$

Neste caso:
- `2` é a quantidade de pais;
- `x` é a geração que estamos alcançando.

A derivada não é simplesmente:

$$
f(x)=x2^{x-1}
$$

❌ Não.

Nem:

$$
f(x)=1(2) \times 0 
$$

❌ Não mesmo!

Para uma exponencial desse tipo, usamos uma regra específica:

$$
\boxed{f'(x)=2^x\ln(2)}
$$

E aqui aparece um padrão mutio importante.

💡 Pense assim:
> "Para $f'(x)=n^x$, a exponencial fica. O $\ln$ da base aparece multiplicando.

Visualmente:

$$
\boxed{n^x\quad\longrightarrow\quad n^x\ln(n)}
$$

É praticamente como colocar um "acessório" na expressão. A parte exponencial continua exatamente ali. Só acrecentamos:

$$
\ln(n)
$$

Sabendo disso, a gente passa a entender que:

$$
\boxed{f'(x)=2^x\ln(2)}
$$

É a nossa **derivada**!

Essa é a parte mais imporante do que simplesmente decorar fórmula. A expressão:

$$
\boxed{2^x}
$$

Já:

$$
\boxed{2^x\ln(2)}
$$

representa a **taxa de crescimento**!

## ⚡ E por que aparece o ($\ln$)?

Aqui entra uma informação importante:

A função exponencial de base $e$ possui uma propriedade especial:

$$
\frac{d}{dx}e^x=e^x
$$

Ou seja, quando derivamos ($e^x$), ele permanece igual. Já quando a base é outra, como 2, 3 ou 100, aparece um fator extra:

$$
\frac{d}{dx}2^x=2^x\ln(2)
$$

ou

$$
\frac{d}{dx}3^x=3^x\ln(3)
$$

ou

$$
\frac{d}{dx}10^x=10^x\ln(10)
$$

🧠 Então o ($\ln$) está relacionado justamente à base da exponencial.

Você não precisa decorar uam explicação gigantesca para isso agora. Para esse capítulo, basta guardar:

> "A base aparece dentro do ($\ln$)"

# 📝 Resumo

🟦 **Regra principal**

Se:

$$
\boxed{f(x)=n^x}
$$

então:

$$
\boxed{f'(x)=n^x\ln(n)}
$$

🟩 **Macete**

> Mantenha a exponencial e multiplique pelo ($\ln$) da base.

$$
\boxed{n^x\rightarrow n^x\ln(n)}
$$

📈 **Quanto maior a taxa de crescimento, maior será o valor da derivada naquele ponto.**

Não pense que é apenas:

> "A resposta é essa fórmula".

Pense:

> "A derivada mede a velocidade com que o crescimento exponencial está acontecendo!"
