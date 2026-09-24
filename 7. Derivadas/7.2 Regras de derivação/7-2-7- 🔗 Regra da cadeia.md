# 7.2.7. 🔗 Regra da cadeia


# 🚗 Introdução

Vamos deixar um pouco sua rede social de lado, e vamos falar sobre seu carro. Imagina que você está dirigindo-o.

O carro está andando pela estrada, mas existe uma coisa importante acontecendo no caminho: Você está passando por uma subida.

Agora pense:

- O movimento do carro depende da estrada;
- A estrada muda conforme você avança;
- E queremos descobrir **como o movimento do carro está mudando naquele momento**.

No cáculo, algo parecido acontece quando uma função está **dentro da outra**.

É como uma função dentro de ourta função:

> 🚗 **Entrada → primeira função → resultado → segunda função → resultado final**

O problema é:

> **"Como o resultado final está mudando quando a entrada muda?"**

Quando temos esse tipo de situação, usamos a Regra da Cadeia. 🔗

# 🧠 Exemplo Lógico

Imagine que você esteja dirigindo um carro.

A velocidade do carro depende de uma coisa que está acontecendo primeiro: a posição do carro na estrada.

Mas a posição do carro também muda conforme o **tempo passa**.

Então temos uma sequência:

- ⏱️O **tempo** muda;
- 🚗 a mudança do tempo faz a **posição do carro** mudar;
- 🛣️ a mudança da posição faz outra quantidade relacionada ao carro mudar.

Ou seja, uma coisa está causando uma mudança na outra:

> tempo → posição → resultado

Se quisermos descobrir como o resultado final está mudando em relação ao tempo, precisamos acompanhar cada etapa dessa cadeia.

É justamente essa ideia que a **Regra da Cadeia** organiza.

### 💡 A ideia principal é simples:

> Quando uma coisa muda e essa mudança provoca outra mudança, precisamos acompanhar as duas mudanças.

É como uma fila de dominós. 🁢🁢🁢

O primeiro dominó cai, derruba o segundo, que derruba o terceiro.

Para saber como o terceiro está sendo afetado, precisamos considerar cada etapa do caminho.

# 🔢 Exemplo Prático

Agora vamos colocar números nessa ideia.

Imagine a função:

$$
f(x) = (2x+1)^3
$$

À primeira vista, ela pode parecer meio assustadora. 😅

Mas vamos desmontá-la em duas etapas.

1. 🔵 Função interna  
Primeiro fazemos:

$$
2x+1
$$

Vamos chamar esse resultado de:

$$
u = 2x+1
$$

2. 🟢 Função externa  
Depois pegamos esse resultado e elevamos ao cubo:

$$
u^3
$$

Então a função completa é:

$$
f(x) = (2x+1)^3
$$

Perceba a cadeia:

$$
x \rightarrow 2x+1 \rightarrow (2x+1)^3
$$

Agora queremos descobrir a derivada dessa função.

### 📘 Roteiro prático da Regra da Cadeia

Para encontrarmos o derivada de $f(x)=(2x+1)^3$ temos primeiro que indentifica a função que está dentro da outra, e para isso podemos seguir um simples roteiro:

#### Passo 1 — Monte a tabela de 4 posições

Vamos preencher, ao longo do roteiro, os valores necessários para montar a fórmula:

$$
f'(x)=g'(h(x)) \times h'(x)
$$

| Elementos | Valores |
|---|---|
| Função da interna     $\rightarrow h(x)$: | |
| Função da externa     $\rightarrow g(x)$:| |
| Derivada da interna   $\rightarrow h'(x)$:| |
| Derivada da externa   $\rightarrow g'(x)$: | |

---

#### Passo 2 — 🔵 Identifique a função externa

A parte de fora é:

$$
(\quad)^3
$$

$$
\boxed{\text{Função externa = }(\quad)^3}
$$

Ou seja, estamos elevando alguma coisa ao cubo.

---

#### Passo 3 — 🟡 Identifique a função interna

A parte de dentro é:

$$
2x+1
$$

Ela está dentro da função externa. Logo:

$$
\boxed{\text{Função interna = }2x+1}
$$

---

#### Passo 4 — ✏️ Derive a função externa mantendo a interna

A derivada de algo elevado ao cubo é:

$$
3(\text{algo})^2
$$

Como "algo" é **2x+1**, e esta é a função interna, manteremos ela no lugar:

$$
3(2x+1)^2
$$

⚠️ Não derivamos a parte de dentro ainda.

$$
\boxed{\text{Derivada externa = }3(\quad)^2}
$$

---

#### Passo 5 — 🟡 Derive a interna

$$
2x+1
$$

Pela regra da **Soma**, poderemos derivar cada parte separadamente:

$$
(2x+1)' = (2x)' + (1)'
$$

- 🔵 A derivada de `2x` é `2` (já que a derivada de `x` é `1`, então $2\times1=2$).
- 🟡 O `1` é uma constante — não muda quando `x` muda. Por isso:

$$
(1)' = 0
$$

Portanto:

$$
(2x+1)' = 2 + 0 = \boxed{2}
$$

💡 **Importante**: não é o `2x+1` inteiro que é a constante. Apenas o `+1` é a constante.

- `x` muda → sua derivada é `1`;
- `1` não muda → sua derivada é `0`.

$$
\boxed{\text{Derivada interna = }2}
$$

---

#### Passo 6 — ✖️ Multiplique pela derivada da função interna

🎉 **Pronto!** Com o quadro completo, temos:

| Elementos | Valores |
|---|---|
| Função da interna     $\rightarrow h(x)$: | $2x+1$ |
| Função da externa     $\rightarrow g(x)$:| $(\text{algo})^3$ |
| Derivada da interna   $\rightarrow h'(x)$:| $2$ |
| Derivada da externa   $\rightarrow g'(x)$: | $3(\text{algo})^2$ |

A **Regra da Cadeia** nos permitiu descobrir como a mudança da entrada `x` passa pela função interna e chega até o resultado final!

---

### 🧩 O que aconteceu?

Podemos enxergar a função como uma pequena máquina, onde `x` passa por duas etapas até chegar ao resultado final:

$$
x \;\rightarrow\; \boxed{2x+1} \;\rightarrow\; (\ )^3 \;\rightarrow\; f(x)
$$

Primeiro, `x` entra na função interna ($2x+1$); depois, o resultado dessa etapa é elevado ao cubo pela função externa.

Como a mudança precisa passar por essas 2 etapas, a derivada também precisa "passar" por cada uma delas — por isso calculamos:

- 🟦 A derivada da parte de fora (função externa);
- 🔵 A derivada da parte de dentro (função interna);

E multiplicamos as duas. Ou, de forma bem curta:

$$
\boxed{\text{Regra da Cadeia = Derivada de fora} \times \text{Derivada de dentro}}
$$

# 📝 Resumo

Usamos a **Regra da Cadeia** quando temos uma função dentro de outra função.

Roteiro prático:

1. 🔗 Cria uma tabela de 4 poisções
2. 🟦 Indentifica a função externa e separa ela na posição 1;
3. 🟨 Deriva ela e separa na posição 2;
4. 🔵 Indentifica a função interna e separa ela na posição 3;
5. 🟡 Deriva ela e separa na posição 4;
6. 🟩 Monta a fórmula $\boxed{f'(x)=g'(h(x))\cdot h'(x)}$
7. 🟢 Obtém a derivada desejada

💡**Pra lembrar na hora da prova**
> Deriva a de fora, mantém a de dentro e multiplica pela derivada da de dentro. 🔗


