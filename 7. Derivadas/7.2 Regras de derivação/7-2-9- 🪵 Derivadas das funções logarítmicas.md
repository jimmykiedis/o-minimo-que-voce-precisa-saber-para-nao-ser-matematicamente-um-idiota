# 7.2.9. 🪵 Derivadas das funções logarítmicas
“O logaritmo é aquele sujeito que continua subindo... mas parece que, quanto mais sobe, mais preguiça ele tem de acelerar. 🪵😴”

# 🪵 Introdução

Você já conhece o logaritmo: Ele mostra como um núemro cresce, só que de um jeito bem peculiar – sempre subindo, mas nunca com pressa. 😌

E aqui vema. pergunta boa:

> "Se o logaritmo está sempre crescendo… quão rapido ele crece?"

É isso que a derivada vai responder. 👇

# 👤 Exemplo lógico

Imagine que o seu perfil naquela rede social finalmente alcançou seu apogeu, e agora o histórico deseguidores dela parece um logarítmo – no começo, quando seus vídeos bombaram, ela crescia tão rapidamente que quase não dava pra acompanhar, mas agora ela está muito mais lenta.

 🔍 **Dusca coisas são diferentes aqui, e é importante não misturar**:
- 📊 **Quantos seguidores você tem** (isso é a função, $f(x)$)
- ⚡ **Quão rápido esse número está mudando naquele momento** (isso é a derivada, $f'(x)$)

A Derivada mede a **velocidade** com que algo está mudando em cada momento.

Se o total de seguidores é um logaritmo natural:

$$
f(x)=\ln(x)
$$

Então a velocidade dele é uma das derivadas mais fáceis de lembrar:

$$
f'(x)=\frac{1}{x}
$$

Em palavras: **A velocidade de crescimento é 1 divido por $x$**

$$
f'(1)=\frac{1}{1}=1
$$

$$
f'(2)=\frac{1}{2}=0{,}2
$$

$$
f'(10)=\frac{1}{10}=0{,}1
$$


| Momentos da história | $x$ | $f'(x)=1/x$ | Velocidade
|---|---|---|---|
|O víde acabou de bombar    | 1 | 1 | 🚀 Rápido |
Logo depois                 | 2 | 0.5 | 🚗 Médio |
Bem mais tarde              | 10 | 0.1 | 🐢 lento |

👉 **Quanto maior fica o valor de $x$, menor fica a derivada**

# 📱 Exemplo prático

Vamos supor que:

- $x$ = O dia (dia 1, dia 2, dia 10...)
- $f(x)$ = $\ln(x)$ = O total de seguidores contando em milhares.

Agora a pergunta:
> "Nesse dia, o quão rápido os seguidores estão chegando?"

Para responder essa pergunta usamos a derivada:

$$
f'(x)=\frac{1}{x}
$$

**No dia 1** (o vídeo acabou de bombar):

$$
f'(1)=\frac{1}{1}=1
$$

Chegam **1 mil seguidores por dia**. 🚀

**No dia 10:**

$$
f'(10)=\frac{1}{10}=0{,}1
$$

Chegam **0,1 mil**, ou seja, **100 seguidores por dia**. 🚗

**No dia 100:**

$$
f'(100)=\frac{1}{100}=0{,}01
$$

Chegam **0,01 mil**, ou seja, **10 seguidores por dia**. 🐢


### 💡 O que isso significa?

Seu perfil **continua crescendo** todos os dias, mas o ritmo vai caindo:

**1000 $\rightarrow$ 100 $\rightarrow$ 10 seguidores por dia.**

Ah! **A derivada está dizendo a velocidade com que a quantidade está crescendo naquele ponto.** ✨

E foi isso que você viu na sua história: o perfil nunca parou de subir, só foi ficando mais tranquilo.

# 🧠 Resumo

> ### 🪵 Logaritmo cresce, mas a derivada vai diminuindo.

$$
\frac{d}{dx}\ln(x)=\frac{1}{x}
$$

**`x` aumenta → `1/x` diminui → a velocidade de crescimento diminui.**

Ou seja: **quanto mais alto o `x`, mais devagar o logaritmo sobe.** 🐢

- **Significado:** a derivada mostra a **velocidade de crescimento** do logaritmo em cada ponto.
- **Comportamento:** quando `x` aumenta, `1/x` diminui.
- **Exemplo:** $f'(1)=1$, $f'(2)=\frac{1}{2}$ e $f'(10)=\frac{1}{10}$.

> **A derivada de `ln(x)` é `1/x`. Quanto maior for `x`, menor será `1/x`. Portanto, o logaritmo continua crescendo, mas cresce cada vez mais devagar.** 🪵