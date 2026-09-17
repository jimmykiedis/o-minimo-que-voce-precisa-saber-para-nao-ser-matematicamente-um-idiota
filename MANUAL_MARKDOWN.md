# Manual Rápido de Markdown ✍️

Markdown (`.md`) é uma forma simples de escrever textos organizados usando símbolos comuns do teclado. Ele serve para criar apostilas, anotações, resumos, listas, exemplos de código e materiais de estudo sem depender de programas pesados.

> Ideia principal: escreva o texto normalmente e use pequenos sinais para indicar títulos, destaques, listas e blocos.

---

## 1. Títulos 🧱

Use `#` no começo da linha. Quanto mais `#`, menor o título.

```md
# Título principal
## Seção
### Subtítulo
#### Detalhe menor
```

Exemplo:

```md
# Razão e Proporção
## O que é razão?
### Exemplo com dinheiro
```

---

## 2. Negrito, Itálico e Tachado 🔤

Use marcações ao redor da palavra ou frase.

```md
**negrito**
*itálico*
~~tachado~~
```

Exemplo:

```md
O conceito **mais importante** aqui é entender a *comparação entre grandezas*.
~~Decorar sem entender~~ não ajuda no estudo.
```

Resultado esperado:

O conceito **mais importante** aqui é entender a *comparação entre grandezas*.
~~Decorar sem entender~~ não ajuda no estudo.

---

## 3. Listas 📋

### Lista com marcadores

```md
- Entender a ideia
- Ver um exemplo
- Resolver um exercício
```

### Lista numerada

```md
1. Ler o conceito
2. Resolver o exemplo
3. Fazer um exercício sozinho
```

Use listas quando quiser organizar passos, itens ou ideias importantes.

---

## 4. Links 🔗

Use este formato:

```md
[texto do link](https://exemplo.com)
```

Exemplo:

```md
[Pesquisar no Google](https://www.google.com)
```

---

## 5. Imagens 🖼️

Use quase a mesma estrutura dos links, mas com `!` antes.

```md
![descrição da imagem](caminho/da/imagem.png)
```

Exemplo:

```md
![Gráfico de uma função crescente](imagens/grafico-funcao-crescente.png)
```

A descrição ajuda a lembrar o que a imagem representa.

---

## 6. Citações 💬

Use `>` no começo da linha.

```md
> A matemática fica mais fácil quando entendemos o que cada símbolo quer dizer.
```

Bom uso para frases importantes, observações e ideias de destaque.

---

## 7. Código Inline 💻

Use crases simples para destacar comandos, símbolos ou pequenos trechos.

```md
A fórmula `v = d / t` calcula a velocidade média.
```

Resultado:

A fórmula `v = d / t` calcula a velocidade média.

---

## 8. Expressões Matemáticas 🧮

Markdown puro organiza o texto, mas não cria fórmulas bonitas sozinho. Para representar matemática, normalmente usamos **LaTeX dentro do Markdown**.

### Fórmula no meio do texto

Use `$` antes e depois da expressão.

```md
A razão $\frac{1}{1}$ representa uma parte para uma parte.
```

### Fórmula em destaque

Use `$$` antes e depois da expressão.

```md
$$
\frac{1}{1}
$$
```

### Fração

Use `\frac{numerador}{denominador}`.

```md
$\frac{1}{1}$
$\frac{7}{7}$
$\frac{77}{7}$
```

### Potenciação

Use `^` para expoente. Quando o expoente tiver mais de um caractere, use `{}`.

```md
$7^2$
$7^{10}$
$x^{2 + 1}$
```

### Radiciação

Use `\sqrt{}` para raiz quadrada e `\sqrt[n]{}` para outras raízes.

```md
$\sqrt{49}$
$\sqrt[3]{27}$
```

### Subscrito

Use `_` para escrever algo embaixo, como índices.

```md
$x_1$
$a_n$
$P_0$
```

### Símbolos úteis

```md
$7 \cdot 7$
$x \le 7$
$x \ge 7$
$x \neq 7$
$\pi$
$\Delta x$
```

### Resumo rápido

| O que quero escrever | Como escrever |
|---|---|
| Fração | `$\frac{1}{1}$` |
| Potência | `$7^2$` |
| Potência maior | `$7^{10}$` |
| Raiz quadrada | `$\sqrt{49}$` |
| Raiz cúbica | `$\sqrt[3]{27}$` |
| Índice | `$x_1$` |
| Multiplicação | `$7 \cdot 7$` |
| Menor ou igual | `$x \le 7$` |
| Maior ou igual | `$x \ge 7$` |
| Diferente | `$x \neq 7$` |

> Atenção: nem todo editor Markdown mostra LaTeX renderizado. Se a fórmula não aparecer bonita, o texto ainda pode ser lido pelo código LaTeX.

---

## 9. Blocos de Código 🧩

Use três crases antes e depois do bloco.

````md
```python
distancia = 77
tempo = 7
velocidade = distancia / tempo
print(velocidade)
```
````

Use blocos de código para exemplos maiores, fórmulas organizadas ou comandos.

---

## 10. Tabelas 📊

Use `|` para separar colunas.

```md
| Conceito | Significado | Exemplo |
|---|---|---|
| Razão | Comparação entre grandezas | 77 / 7 |
| Proporção | Igualdade entre razões | 7 / 14 = 1 / 2 |
```

Resultado:

| Conceito | Significado | Exemplo |
|---|---|---|
| Razão | Comparação entre grandezas | 77 / 7 |
| Proporção | Igualdade entre razões | 7 / 14 = 1 / 2 |

---

## 11. Linha Horizontal ➖

Use três traços para separar partes do texto.

```md
---
```

Boa para dividir capítulos, seções grandes ou mudanças de assunto.

---

## 12. Combinações Úteis ⚡

### Destaque com citação

```md
> **Ideia-chave:** razão é uma comparação entre duas grandezas.
```

### Lista com termos importantes

```md
- **Razão:** compara duas grandezas.
- **Proporção:** mostra que duas razões são equivalentes.
- **Variável:** representa um valor que pode mudar.
```

### Fórmula explicada

```md
A velocidade média é calculada por `v = d / t`, em que:

- `v` é a velocidade;
- `d` é a distância;
- `t` é o tempo.
```

### Título + resumo curto

```md
## Resumo de Prova 🧠

- **Definição:** razão é uma divisão usada para comparar grandezas.
- **Fórmula comum:** `a / b`
- **Cuidado:** a ordem dos valores muda o significado da comparação.
```

---

## 13. Modelo Simples para um Arquivo `.md` 📝

```md
# Nome do Assunto

## Introdução

Explique a ideia principal com palavras simples.

## Exemplo

Mostre uma situação prática.

## Cálculo

Escreva a fórmula e resolva passo a passo.

## Resumo de Prova

- Definição:
- Fórmula:
- Quando usar:
- Erros comuns:
```

---

## Regra de Ouro ⭐

Markdown não é sobre enfeitar o texto. É sobre deixar o pensamento organizado.

Use títulos para separar ideias, listas para organizar passos, negrito para destacar conceitos e blocos de código para exemplos que precisam ficar exatamente como foram escritos.
