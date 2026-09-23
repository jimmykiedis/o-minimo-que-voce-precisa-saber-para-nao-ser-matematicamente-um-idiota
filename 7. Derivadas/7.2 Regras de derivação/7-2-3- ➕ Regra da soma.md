# 7.2.3. ➕ Regra da soma
```
A ideia é simples: Se duas coiass estão mudando ao mesmo tempo, a mudança total é a soma das mudanças
```

# 🎯 Introdução

Lembra daquele vídeo que viralizou? 🎥🔥

Agora imagine que você está acompanhando o número total de visualizações do seu perfil quando percebe algo inesperado: seus novos seguidores começaram a encontrar outro vídeo, um pouco mais antigo, que também começa a viralizar.

De repente, você tem **duas fontes diferentes gerando visualizações ao mesmo tempo**.

O vídeo novo está recebendo visualizações, enquanto o vídeo antigo também está atraindo cada vez mais pessoas. Então você poderia se perguntar:

> **"Qual é a velocidade total com que minhas visualizações estão aumentando?"**

A resposta parece intuitiva: Basta descobrir quanto cada uma das partes está contribuindo e **somar**. 
É exatamente essa ideia por trás da **Regra da Soma**.

# 🧠 Exemplo lógico

Você abre as estatisticas do seu perfil e percebe que os dois estão recebendo um maçante número de vizualizações ao mesmo tempo. O video mais recente está recebendo cerca de $5.000$ vizualizações por hora, e o segundo $2.000$. Então surge uma pergunta uma pergunta mais específica:

> "Quantas visualizações meu perfil perfil está ganhando por hora no total?"

É simples:

$$
\boxed{5.000 + 2.000 = 7.000}
$$

Ou seja, seus dois vídeos juntos estão fazendo seu perfil ganhar $7.000$ vizualizações por hora. Perceba o que está acontecendo:

Você tinha duas fontes diferentes de vizualização acontecendo ao mesmo tempo.
- 🎥 Video recente $\rightarrow +5.000$ vizualização/h.
- 🎥 Video antigo $\rightarrow +2.000$ vizualização/h.

Para descobrir a velocidade total de crescimento das visualizações, você simplesmente somou as duas velocidades.

## ➕ E é exatamente isso que a Regra da Soma faz
Agora vamos deixar o exemplo um pouco mais matemático. Imagine que:

- $f(t)$ represente o número de visualizações do vídeo mais recente;
- $g(t)$ represente o número de visualizações do vídeo mais antigo.

Se quisermos descobrir o **número total de visualizações dos dois vídeos**, podemos somar as duas funções:

$$
\boxed{f(t)+g(t)}
$$

E quando Queeremos descobrir a **velocidade com que esse total está aumentando**, podemos derivar essa soma:

$$
\boxed{(f(t)+g(t))'=f'(t)+g'(t)}
$$

Ou seja:

> 🚀 A derivada da soma é a soma das derivadas.

Isso significa que podemos descobrir a velocidade de crescimento das visualizações de cada vídeo separadamente e depois somar as duas.

# 🌎 Exemplo prático

Agora vamos transformar aquela situaçõa em funções matemáticas. Imagine que o vídeo mais recentes esteja recebendo visualizações a uma taxa de **$5.000$ por hora**. Podemos representar isso por:

$$
f(t)=5.000
$$

E o vídeo mais antigo esteja recebendo **$2.000$ visualizações por hora**:

$$
f(t)=2.000
$$

Aqui, $t$ representa o tempo em horas. O número total de visualizações dos dois vídeos será:

$$
f(t) + g(t)
$$

Subistituindo as funções:

$$
f(t) + g(t) =  5.000t + 200t
$$

Sua soma vai ficar:

$$
f(t) + g(t) = 7.000
$$

Agora queremos descobrir a velocidade com que o número total de visualizações está aumentando. Derivando Cada função:

$$
\boxed{f'(t)=5.000}
\qquad\text{e}\qquad
\boxed{f'(t)=2.000}
$$

Aplicamos a regra da soma:

$$
(f+g)'(t)=f'(t)+g'(t)
$$

Então:

$$
\boxed{(f+g)'(t)=5.000+2.00=7.000}
$$

🎯 **Resultado: os dois vídeos juntos estão gerando 2.500 visualizações por hora.**

# 🧩 Resumindo

A regra da soma diz:

> "Quando somamos duas funções, podemos derivar cada uma separadamente e depois somar os resultados.

Em simbolos:

$$
(f+g)'=f'+g'
$$

## 💡 Pense assim:

Taxa de crescimento do vídeo 1 + taxa de crescimento do vídeo 2 = taxa de crescimento total.