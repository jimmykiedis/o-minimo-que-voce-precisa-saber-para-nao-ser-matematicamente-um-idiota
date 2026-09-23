# 7.2.2. 🔺 Regra da potência

```
Se a Regra da Constante foi o tutorial, a Regra da Potência é a primeira fase de verdade: os controles continuam os mesmos, mas agora o jogo começa a ficar interessante. 🎮🔥
```

# 🎯 O que é uma potência?

Se você já esqueceu dos primeiro capítulos, lá quando agente aprendeu "1.3 Operações Fundamentais", uma potência é uma forma abreviada de representar uma multiplicação repetitiva:

$$
x^3= x\cdot x\cdot x
$$

O número $3$ é o expoente e indica quantas vezes a base $x$ aparece multiplicando. Na **Regra da Potência**, nós queremos descobrir o que acontece com uma expressão como:

$$
f(x)=x^n
$$

A regra é:

$$
\boxed{\frac{d}{dx}\left(x^n\right)=n x^{n-1}}
$$

💡 **A receita é simples**:

O expoente desce multiplicando e depois diminui $1$.

## 🚗 Exemplo lógico

Vamos abstrair essa ideia para um exemplo de aplicação no mundo real.

Imagine que precisamos adivinhar uma senha de **4 caracteres**, de um celular, por exemplo. Parece fácil, não? 😅

Talvez você tente algumas combinações:

$$
\boxed{1,2,3,4}
\qquad
\boxed{4,3,2,1}
\qquad
\boxed{0,0,0,0}
\qquad
\boxed{1,1,1,1}
$$

Mas, se a senha realmente for desconhecida, testar combinações manualmente rapidamente se torna cansativo. 😵‍💫

E se fizéssemos isso automaticamente com um algoritmo de **força bruta**?

### 🔐 Aumentando o conjunto de caracteres

Para simplificar, imagine que começamos com apenas os **10 números**:

```text
0–9
```

Como nossa senha possui 4 posições, cada posição pode receber qualquer um dos 10 caracteres.

Portanto, temos:

$$
10\cdot10\cdot10\cdot10=10^4
$$

Ou seja:

$$
10^4=10.000
$$

Já são **10.000 combinações possíveis**.

Agora imagine que adicionamos **uma letra** ao conjunto de caracteres.

Passamos a ter:

$$
11
$$

caracteres disponíveis.

Então:

$$
11^4=14.641
$$

Adicionamos mais uma letra:

$$
12^4=20.736
$$

E mais uma:

$$
13^4=28.561
$$

Perceba o que está acontecendo:

$$
10^4
\rightarrow
11^4
\rightarrow
12^4
\rightarrow
13^4
\rightarrow\cdots
$$

A quantidade de combinações está aumentando conforme aumentamos a quantidade de caracteres disponíveis.

### 🧠 Mas a "pergunta do milhão" é:

> **À medida que adicionamos novos caracteres ao conjunto disponível, com que velocidade cresce a quantidade de combinações que o algoritmo precisa testar?**

## 🧮 Exemplo prático

Vamos continuar no nosso algoritmo de quebra de senhas por força bruta. Já descobrimos que, para uma senha de 4 caracteres, a quantidade de combinações possíveis, pode ser representada por:

$$
f(x)=x^4
$$

Onde $x$ é a quantidade de caracteres disponíveis. Agora vamos observar alguns valores.

Se Tivermos **10 caracteres**:

$$
f(10)=10^4=10.000
$$

Se aumentarmos para **11 caracteres**:

$$
f(11)=11^4=14.641
$$

Então ao adicionarmos apenas **1 caractere**, passamos de:

$$
10.000\rightarrow14.641
$$

Isso representa um aumento de **4.641** combinações possíveis.

Agora vamos fazer a mesma coisa partindo de **20 caracteres**. Temos:

$$
f(20)=20^4=160.000
$$

E adicionando **1 caractere**:

$$
f(21)=21^4=194.481
$$

O aumento foi:

$$
194.481-160.000=34.481
$$

Perceba algo interessante.👀

Nos dois casos adicionamos **1 caractere**: 

$$
10\rightarrow11
$$

e

$$
20\rightarrow21
$$

Mas os aumentos foram diferentes:

$$
4.641
\qquad\text{e}\qquad
34.481
$$

### 🧠 Mas por que isso acontece?

Por que a quantidade de combinações não está crescendo de maneira constante? Quanto maior é o $x$, **maior maior é o aumento provacado pela adição de um novo caractere.** 

Então Suege a pergunta:

>       "Existe uma maneira de descobrir a taxa de crescimento da função em um determinado ponto, sem precisar calcular dois valores e subtrair um de outro?"

Sim! E é justamente para isso que usamos a derivada! Temos:

$$
f(x)=x^4
$$

Aplicamos a regra da potência:

$$
\boxed{f'(x)=4x^3}
$$

Agora podemos descobrir a taxa de crescimento em diferentes valores de $x$.

Para $x=10$

$$
f(10)=10^4
\qquad\rightarrow\qquad
f'(10)=4(10)^3
$$

$$
f'(10)=4.000
$$

Para $x=20$

$$
f(20)=20^4
\qquad\rightarrow\qquad
f'(20)=4(20)^3
$$

$$
f'(20)=32.000
$$

Perceba que:

$$
\boxed{f'(10)=4.000}
\qquad\text{e}\qquad
\boxed{f'(20)=32.000}
$$

A taxa de crescimento é muito maior quando já temos mais caracteres disponíveis.

### 🔍 Mas espere... por que $4.000$ não é igual aos $4.641$?

Quando calculamos:

$$
\boxed{f(11)-f(10)=4.641}
\qquad\text{ou}\qquad
\boxed{f'(10)=4.000}
$$

Percebe-se que não é o mesmo resultado. Mas por que? Porque estas são respostas claramente diferentes, para duas perguntas totalmente diferentes.

**📈 'Crescimento real' é feito entre dois pontos:**

Primeiro, vamos descobrir quanto a função realmente cresceu quando passamos de (x=10) para (x=11):

$$
f(11)-f(10)=4.641
$$

Aqui estamos perguntando:

"Quanto o valor de (f(x)) aumentou entre (x=10) e (x=11)?"

Resposta: **4.641 combinações**. E esse é o crescimento real!


📐 **'Taxa de crescimento' é feito em um único ponto**

Agora fazemos uma pergunta diferente:

> "Quanto $f(x)$ cresce, em média, para cada **1** unidade que $(x)$ aumenta?"

Como $(x)$ passou de $(10)$ para $(11)$, ele aumentou:

$$
11-10=1
$$

Então, nesse intervalo, a taxa média de crescimento é:

$$
\frac{f(11)-f(10)}{11-10}
=
\frac{4.641}{1}
=
4.641
$$

Perceba que **crescimento real e taxa de crescimento** podem até dar o mesmo número quando $(x)$ varia exatamente $(1)$ unidade. Mas isso não significa que sejam a mesma coisa.

🎯 **E onde entra a derivada?**

A derivada faz uma pergunta ainda mais específica:
> "Qual é a taxa de crescimento exatamente no ponto $(x=10)$?"

Por isso:

$$
f'(10)=4.000
$$

A derivada não está calculando o crescimento entre (10) e (11). Ela está calculando a **taxa de crescimento naquele ponto específico**.

## 📌 Analogia Rápida

Imagine que estamos contando quantas combinações diferentes podem ser formadas conforme aumentamos a quantidade de caracteres disponíveis.

Se a quantidade de combinações passa de:

$$
2 \rightarrow 5
$$

o crescimento real é:

$$
5-2=3
$$

Ou seja, surgiram 3 novas combinações.

Agora, se a quantidade de caracteres também aumentou de (1) para (2):

$$
\frac{5-2}{2-1}=3
$$

A **taxa de crescimento** foi de **3 combinações para cada 1 unidade de $(x)$**.

A diferença é simples:

- Crescimento real: quanto (y) mudou.
- Taxa de crescimento: quanto (y) mudou em relação à mudança de (x).
- Derivada: qual é essa taxa exatamente naquele ponto.

> "O crescimento real mede a mudança. A taxa de crescimento relaciona essa mudança à mudança de $(x)$. A derivada mede essa taxa quando analisamos um único ponto."