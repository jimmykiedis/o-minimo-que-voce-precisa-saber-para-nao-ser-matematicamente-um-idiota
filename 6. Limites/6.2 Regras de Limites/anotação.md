| Subcapítulo                           | Aspecto da viagem                            | Ideia matemática                                |
| ------------------------------------- | -------------------------------------------- | ----------------------------------------------- |
| **6.1.1 Regra da Constante**          | 🚗 O carro possui 4 rodas                    | Uma quantidade que não muda                     |
| **6.1.2 Regra da Identidade**         | 📍 Posição do carro                          | `x` acompanha `x`                               |
| **6.1.3 Regra da Soma**               | 🛣️ Distância de dois trechos                | Somamos duas quantidades                        |
| **6.1.4 Regra da Diferença**          | 📏 Quanto falta para chegar                  | Subtraímos uma quantidade da outra              |
| **6.1.5 Regra do Múltiplo Constante** | 💰 Custo por quilômetro                      | Uma quantidade é multiplicada por um valor fixo |
| **6.1.6 Regra do Produto**            | ⛽ Distância × consumo                        | Duas quantidades variando juntas                |
| **6.1.7 Regra do Quociente**          | 📊 Consumo médio                             | Uma quantidade dividida por outra               |
| **6.1.8 Regra da Potência**           | 📐 Uma medida elevada ao quadrado            | Potência                                        |
| **6.1.9 Regra da Raiz**               | 📐 Descobrir uma medida a partir do quadrado | Raiz                                            |
| **6.1.10 Regra da Composição**        | 🔗 Uma informação depende de outra           | Função dentro de função                         |



**Sim — e eu acho que essa abordagem pode deixar o capítulo de Limites muito mais fácil de aprender.** 🚗💨

Em vez de cada regra parecer uma regra isolada, podemos criar **uma única história que vai evoluindo**. A cada subcapítulo, acontece alguma coisa nova com o carro, e isso naturalmente introduz a próxima regra.

Por exemplo, poderíamos usar uma viagem de carro inteira como a “história principal”.

---

# 🚗 A história: uma viagem de carro

Imagine que estamos acompanhando um carro durante uma viagem.

No começo, queremos apenas descobrir algumas coisas simples:

> **“O que está acontecendo com o carro quando nos aproximamos de determinado momento da viagem?”**

Isso introduz a ideia de **limite**.

Depois, cada capítulo usa uma situação diferente da mesma viagem.

---

## **6.2.1 Regra da Constante**

O carro possui uma quantidade fixa de combustível registrada no painel.

Essa quantidade não depende do tempo que estamos observando.

Se o painel mostra **50 litros**, não importa para qual instante estamos nos aproximando: o valor continua sendo 50.

$$
\lim_{x\to a}50=50
$$

💡 **Ideia:** uma constante não muda, então seu limite continua sendo ela mesma.

---

## **6.2.2 Regra da Identidade**

Agora queremos acompanhar a **posição do carro**.

Se chamarmos a posição de `x`, quando `x` se aproxima de determinado valor, a própria posição também se aproxima desse valor.

$$
\lim_{x\to 10}x=10
$$

💡 **Ideia:** quando a função é simplesmente `x`, o limite acompanha o valor para o qual `x` está indo.

---

## **6.2.3 Regra da Soma**

Agora temos duas informações sobre a viagem:

* 🚗 distância percorrida;
* 🛣️ distância que ainda falta percorrer.

Queremos juntar essas duas quantidades para descobrir uma nova informação.

Quando temos duas funções somadas, podemos calcular o limite de cada uma separadamente e depois somar os resultados.

$$
\lim_{x\to a}[f(x)+g(x)]
=
\lim_{x\to a}f(x)
+
\lim_{x\to a}g(x)
$$

💡 **Ideia:** o limite de uma soma pode ser separado em dois limites.

---

## **6.2.4 Regra da Diferença**

Imagine que sabemos a distância total da viagem e queremos descobrir **quanto ainda falta**.

Para isso, podemos tirar a distância já percorrida da distância total.

A mesma lógica funciona com limites: podemos calcular os dois limites separadamente e depois fazer a subtração.

---

## **6.2.5 Regra do Múltiplo Constante**

Agora imagine que estamos calculando o custo da viagem.

Cada quilômetro custa uma quantidade fixa de dinheiro.

Então, se a distância aumenta, o custo aumenta proporcionalmente.

💡 Aqui aparece uma ideia importante:

> Uma constante que está multiplicando uma função pode continuar fora do limite.

---

## **6.2.6 Regra do Produto**

Agora temos duas coisas variando:

* 🚗 quantidade de quilômetros percorridos;
* ⛽ custo por quilômetro.

Queremos descobrir como o **custo total** está se comportando.

Como temos uma quantidade multiplicando outra, usamos a **Regra do Produto para limites**.

---

## **6.2.7 Regra do Quociente**

Agora queremos descobrir o **consumo médio do carro**.

Temos:

* ⛽ combustível utilizado;
* 🚗 distância percorrida.

Uma quantidade é dividida pela outra.

Então temos uma relação de **divisão**.

💡 É aqui que aparece a Regra do Quociente.

---

## **6.2.8 Regra da Potência**

Agora imagine que precisamos trabalhar com uma quantidade elevada ao quadrado.

Por exemplo, uma medida relacionada ao espaço que depende de uma distância ao quadrado.

Se temos uma função elevada a uma potência, podemos aplicar a regra da potência ao limite.

---

## **6.2.9 Regra da Raiz**

Agora imagine que uma informação do carro aparece dentro de uma raiz.

Por exemplo, temos uma medida que precisa ser transformada usando uma raiz quadrada.

A ideia continua sendo a mesma: observar para onde o resultado está caminhando.

---

# 🔗 E então podemos chegar à composição

Aqui fica **muito interessante**, porque podemos reutilizar a própria história.

Imagine que:

> o **tempo** determina a posição do carro;

e depois:

> a **posição do carro** determina outra informação.

Temos:

$$
tempo\rightarrow posição\rightarrow resultado
$$

Uma função está entrando dentro de outra.

Isso prepara naturalmente o terreno para a ideia de **função composta**, que depois será importantíssima para a **Regra da Cadeia**. 🔗

---

# 🎯 O mais legal dessa abordagem

Em vez de fazer:

> “Agora vamos aprender a Regra da Constante.”
> “Agora outra regra.”
> “Agora outra regra.”
> 😵‍💫

podemos fazer:

> 🚗 **Estamos viajando...**
>
> O combustível não muda → **Constante**.
>
> A posição acompanha `x` → **Identidade**.
>
> Juntamos duas distâncias → **Soma**.
>
> Tiramos uma distância da outra → **Diferença**.
>
> O preço depende da distância → **Múltiplo Constante**.
>
> Quilômetros × preço → **Produto**.
>
> Combustível ÷ distância → **Quociente**.
>
> Uma quantidade ao quadrado → **Potência**.
>
> Uma quantidade dentro de uma raiz → **Raiz**.
>
> Uma função depende do resultado de outra → **Composição**.

Assim, **cada regra resolve um problema diferente dentro da mesma história**.

E isso combina muito bem com a forma como estamos construindo os capítulos anteriores: **Exemplo Lógico → Exemplo Prático → Resumo estilo prova**.

Se fizermos o capítulo inteiro assim, a pessoa não precisa decorar uma lista de regras soltas. Ela começa a reconhecer:

> **“Ah! Esse problema é uma divisão → Quociente.”**
> **“Isso aqui é uma multiplicação → Produto.”**
> **“Isso aqui é uma função dentro de outra → Composição.”**

A matemática começa a parecer menos uma lista de feitiços e mais um **manual de diagnóstico do carro**. 😂🚗🔧
