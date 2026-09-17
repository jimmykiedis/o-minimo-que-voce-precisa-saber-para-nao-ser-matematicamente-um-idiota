# 3.5.1 Função Logarítmica

# 
## 🔑📊Definição
	A função logarítmica é definida como a função inversa da função exponencial. Matematicamente, ela é representada assim:
		𝑓(𝑥) = log <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑎</sub>
 </span> <span style="font-family: STIXTwoMath-Regular;">
     𝑥
	
 </span>Onde:
 <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     	* 𝑎
 </span> (base) > 0 e  <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     𝑎
 </span> ≠ 1 (A base do logaritmo, sempre positiva e diferentes de 1);
 <span style="font-family: STIXTwoMath-Regular;text-align: left;">
     	* 𝑥
 </span> (logaritmando) > 0 (O argumento  do logaritmo, também é sempre positivo);
	* 𝑓(𝑥) (logaritmo) ∈ ℝ (Desde que não estejamos trabalhando com números complexos).

## 🛠️Aplicações da Função Logarítmica na vida real:
	* **Escalas logarítmicas**, como a escala Richter (para medir terremotos) e a escala de decibéis (para medir intensidade sonora);
	* C**rescimento populacional** e **decaimento radioativo**;
	* **Ciência de dados**, como pesquisas binárias, por exemplo;
	* **pH de soluções químicas**.

## 📚Relação com a função exponencial
	Se:
		𝑦 = log <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑎</sub>
 </span> <span style="font-family: STIXTwoMath-Regular;">
     𝑥
 </span>
	Isso significa:
		𝑥 =  <span style="font-family: STIXTwoMath-Regular;">
     𝑎
 </span> <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sup>𝑦

	</sup>
 </span>👉 Ou seja: **O logaritmo de um número** 𝑥 **na base**  <span style="font-family: STIXTwoMath-Regular;">
     𝑎
 </span> **é o expoente** 𝑦 **ao qual devemos elevar**  <span style="font-family: STIXTwoMath-Regular;">
     𝑎 
 </span>**para obter** 𝑥**.** 
		Em outras palavras**, temos** o **valor** da **base** e do **resultado,** mas **não temos** o **valor do expoente.**
	
	Exemplo:
		log <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>2</sub>
 </span>8 = 3
	Porque:
		2<sup>3</sup> = 8

## 
## 📚Propriedades importantes dos logaritmos
		1. Produto de dois números:
			log <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑎</sub>
 </span>(𝑚𝑛) = log <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑎</sub>
 </span>(𝑚) + log <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑎</sub>
 </span>(𝑛)

		1. Produto de dois números:
			log <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑎</sub>
 </span>(𝑚/𝑛) = log <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑎</sub>
 </span>(𝑚) - log <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑎</sub>
 </span>(𝑛)

		1. Potência de um número:
			log <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑎</sub>
 </span>𝑚 <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sup>𝑘</sup>
 </span> = 𝑘⋅log <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑎</sub>
 </span> <span style="font-family: STIXTwoMath-Regular;">
     𝑚
 </span>

		1. Logaritmo de própria base:
			log <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑎</sub>
 </span>𝑎 = 1

		1. Logaritmo de 1:
			log <span style="font-family: STIXTwoMath-Regular; font-size: 13.0;">
     <sub>𝑎</sub>
 </span>1 = 0
## 
## ✍️Exemplo prático:
	Resolva:
	> log> <sub>3</sub>> (𝑥 − 1)> <sup>2 </sup>> = 2
		
	> 📚> **Método potência de um número:**
		> 🧮> **Passo 1: Passando o expoente do logaritimando**
			> 2 ⋅ log> <sub>3</sub>> (𝑥 − 1)> <sup> </sup>> = 2
		
		🧮> **Passo 2: Dividimos ambos os lados por 2:**
			> log> <sub>3</sub>> (𝑥 − 1)> <sup> </sup>> = 1
				🔎Agora sabemos que 3> <sup>1</sup> > é igual a (x−1)

		🧮> **Passo 3:Agora é só passar para a equação de primeiro grau:**
			> 𝑥 - 1 = 3> <sup>1  </sup>> ==  𝑥 - 1 = 3> <sup>
</sup>				> 🔎Usando a propriedade de potenciação, todo numero elevado a 1, é igual a ele mesmo.

		🧮> **Passo 4: Organizando:**
			> 𝑥 = 3 + 1

		✅ > **Resposta final:**
			> 𝑥 = 4
	
	📚> **Método por definição:**
		> 🧮> **Passo 1: Interpretando:**
			> log> <sub>3</sub>> (𝑥 - 1)> <sup> </sup>> = 2  ==  (𝑥 - 1)> <sup>2 </sup>> = 3> <sup>2</sup>
				> 🔎Aqui tínhamos a base o expoente, e sabemos que o resultado é (𝑥 − 1)> <sup>2
</sup>
		> 🧮> **Passo 2: Aplicando a propriedade da "raiz 🔄 potencia":**
			 > (𝑥 − 1)> <sup>2 </sup>> = 3> <sup>2  </sup>> ==  √(𝑥 − 1)> <sup>2 </sup>> = √3> <sup>2 
				</sup>> 🔎O que vc fizer de um lado, você deve fazer do outro. Usamos colocar uma raiz de cada lado da função para remover seus expoentes quadráticos.
			
		🧮> **Passo 3: Organizando:**
			> 𝑥 − 1 = ±3  ==  𝑥 =  ±3 + 1
				🔎Usamos o ±3, pois 9 tem 2 raízes, -3 e +3. Ambas as raízes quando elevadas ao quadrado será 9 (dado a definição de potenciação vista anteriormente)

		✅ > **Resposta final:**
			> 𝑥 = 4 ou 𝑥 = -2
				🔎 As duas raízes geram 2 resultados reais, e ambas as soluções são válidas. 				

## 📝 **Atenção Importante:**
	Ao resolver equações logarítmicas com potências no argumento, o método mais seguro é sempre transformar diretamente para a forma exponencial para garantir que todas as soluções sejam encontradas.
	Se optar por usar as propriedades dos logaritmos, sempre verifique antes se o argumento é positivo, para não perder soluções válidas.

