# Conceito Intuitivo de derivadas

```
 Tá, mas quão rápido isso está mudando agora?
```

# 🎯 O que é derivada?
Imagine que você acabou de postar um vídeo nas redes sociais. Você não espera muita coias, mas algumas horas depois você percebe que ele comelççou a viralizar. Você abre o aplicativo e vê:

**10.000 seguidores.**

Alguns minutos depois:

**10.200 seguidores.**

Você atualiza a página:

**10.250 segudores.**

Mais alguns minitos:
    
**11.000 seguidores.**

"Caramba…" – Você pensa.
Você  continua acompanhando o número subir. O vídeo esta sendo compartilhado, as notificações não para de chegar e, em pouco tempo você já está em 15.000 Seguidores.
Você poderia fazer uma pergunta simples:
>       "Quantos seguidores eu ganhei desde que postei o vídeo?"
Fácil! Basta comparar o número de seguidores antes e depois de postar o vídeo.
    Mas , enquanto você vê auqle número subir na tela, uma pergunta mais interessante começa a aparecer:
>       "Tá, mas a que velocidade eu estou ganhando seguidores agora?"
A diferença é sutil, mas importante!
Você não qiuer mais saber apenas quanto o número mudou. Você quer saber quão rapidamente ele está mudando neste exato momento. Talves você tenha ganhando 2.000 seguidores durante duas horas. Mas isso não significa que ganhou 1.000 segudiires em cada hora. Talves tenha passado a primeira hora ganhando apenas 100 e, depois, o vídeo tenha explodido de verdade, fazendo você ganhar os outros 1.900 em poucos minutos. 
A quantidade de seuifores diz onde você está. A taxa de crescimento diz quão rápido você está avançando. E é justamente essa ideia que "Quão rápido algo está mudando agora?" que está por trás da derivada.

---

## 🚗 Uma espécie de "Velocímetro"
Pense no velocímetro de um carro. Se você percorreu 100 km em douas horas, podemos dizer que sua velçocidade média foi de 50 km/h. Mas isso não significa que você tenha passado cada segundo exatamente a 50 km/h. Talvez tenha ficado parado no trânsito. Depois tenha acelerado para 100 km/h, depois reduzido para 40 km/h. O 50 km/h descreve uma média do percurso. O velocimetro, por outro lado, tenta responder:
>       "Qual a velocidade do carro agora?"

A derivada faz algo parecido. Ela funciona como uma espécie de velocímetro de uma função. Se uma função representa uma quantidade que está mudando, sua derivada no diz **quão rapidamente essa quantidade está mudando naquele ponto.**

---
## 🧑🏽‍💻 Voltando aos seguidores

Imagine que sua quantidade de seguidores esteja aumentando. No começo do dia, você ganha pouco seguidores. Então publica um vídeo. De repente:

>       +10 seguidores por minuto
>       +50 seguidores por minuto
>       +200 seguidores por minuto

A quantidade de seguidores está aumentando o tempo todo. Mas a velocidade desse crescimento também está mudando. Esse é justamente o tipo de informação que uma derivaida consegue representar. 

Podemos pensar assim:

| O que queremos saber | Ideia
|---|---|
Quantos segudiores você tem? | Valor da função
Quantos segudires ganhou durante o dia? | Variação
Quantos ganhou, em média, por hora? | Taxa média de variação
Quantos está ganhando agora? | Derivada

---

### ⚡️ Uma pequena tradução matemática

Suponha que *S(t)* represente a quantidade de seguidores de *(t)* horas. Então:

**S(t)**

Representa quantos seguidores você tem. Já:

**S'(t)**

Representa a velocidade com que essas quantidade está mudando, seja aumentando ou diminuindo. POr exemplo, se em determinaod momento:

**S'(3)=120**

Podemos interpretar isso aproximadamente como:
>       Na terceira hora, sua conta estava crescendo a uma taxa de 120 seguidores por hora.

Perceba a diferença:

**S(3)=10.000**

Poderia dizer que você tinha 10.000 ao fim da 3 h. Enquanto:

**S'(3)=120**

Diz que **você está ganhando 120 seguidores por hora** naquele momento. Uma coisa fala **"quanto existe"**, a outra fala **"quão rápido está mudando"**.


# ↔️ E onde entra o limite?

E se, do nada, você decide que vai se tornasse uma analista de crescimento de seguidores na rede social. Você provavelmente ia querer saber:

>       "Quantos seguidres eu ganhei na última hora?"

E se você quisse diminuir mais ainda o parametro do calculo? E se você quisesse contar quantos você está ganhando minuto? E por segundo? E por sentésimo de segundo?

>       "Parece que subiu à cabeça, não?"

Entende agora? Estamos usando limites para tentando observar a mudança em um intervalo cada vez menor. E é justamente aqui que a ideia de limite começa a trabalhar junto com a derivada. A derivada nasce da tentativa de transformar uma **taxa médida de mudanças** em uma **taxa instantânea de mudança**. E a definição formar vai mostrar exatamente isso, por quanto, basta guarda a pergunta:

>       "Se eu diminuri o intervalo até ficar infinitamente pequeno, qual é a taxa de mudanças naquele instante?"

---

## 🧠 Última imagem mental

Imagine três coisas:

**Função:**

>       "Quantos seguidores eu tenho?"

**Variação média:**

>       "Quantos seguidores ganhei durante esse período?"

**Derivada**

>       "Quantos seguidores estou ganhando neste exato momento?"

A **derivada** não está interessada apenas em **onde você está**. Ela está interessada em como você está se movendo naquele momento. E essa ideia parece em praticamente qualquer coisa que possa mudar:

- Velocidade instântanea;
- Temperatura do café;
- Variação de água em uma caixa d'água;
- Saldo de uma conta;
- População de uma cidade;
- Velocidade de crescimento de uma planta;
- Número de seguidores de uma rede social.

Sempre que existir uma quantidade mudando, podemos fazer a mesma pergunta:

>       "Quão rápido isso está mudando agora?"

Essa é a intuição fundamental por trás da derivada.


