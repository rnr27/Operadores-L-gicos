# Operadores-Logicos

**Na lógica de programação os operadores lógicos são aqueles que analisam condições, são operadores que analisaram operandos 
com valores lógicos 1 ou 0, ou então, Verdadeiro ou Falso. Uma situação pode ou não ser verdadeira, 
ou falsa, dependendo da condição em que se encontra.**

**Os operadores são aritméticos, lógicos e relacionais. Alguns operadores variam em funcionalidade 
de acordo com o tipo de dados dos operandos especificados na expressão. 
Os operadores aritméticos executam operações matemáticas, como adição e subtração com operandos.**

Exemplo:

**2+5>4 resulta VERDADEIRO** (2 + 5 MAIOR que 4, resulta em **VERDADEIRO**)

**3<>3 resulta FALSO** (3 DIFERENTE de 3, resulta em **FALSO**)

Os operadores lógicos atuam sobre expressões e também resultam em valores lógicos 
**VERDADEIRO** ou **FALSO**.

<div align="center">
<img src="https://user-images.githubusercontent.com/100056877/204165691-456dd516-9217-4934-b2a6-1e413d4689b7.png"/>
 </div>


A tabela abaixo – chamada **TABELA-VERDADE** – mostra os resultados das aplicações dos 
operadores lógicos conforme os valores dos operadores envolvidos.


<div align="center">
<img src="https://user-images.githubusercontent.com/100056877/204165797-edee38c6-525e-4ccb-bae7-b091519f761f.png"/>
 </div>


De acordo com a necessidade, as expressões podem ser unidas pelos operadores lógicos. 

Exemplo: 
(2+5>4) e (3<>3) resulta **FALSO**, pois **VERDADEIRO** e **FALSO** resulta **FALSO**.

# Estruturando o Pensamento

Na vida real tomamos decisões a todo o momento baseadas em uma situação existente. 
Em um algoritmo, chamamos esta situação de condição. Associada a uma condição, existirá 
uma alternativa possível de ações.

Exemplo - 1.1: 
 
 "se tiver R$ 10,00 sobrando então irei ao cinema hoje à noite.”

A condição nesta frase é "tiver R$ 10,00 sobrando". Ela é uma expressão lógica, pois a 
pergunta "Tenho R$ 10,00 sobrando?" Pode (tem que) ser respondida com "Sim" ou "Não". 
**Lembre-se, então:** em um algoritmo, toda condição tem que ser uma expressão lógica, algo 
que possa-se pensar como “ isto é **VERDADEIRO**” ou “isto é **FALSO**”. Se a condição for 
verdadeira, a ação a ser executada é "irei ao cinema", se a resposta à pergunta "Tenho 
dinheiro suficiente?" for "Sim". Então, em um algoritmo, as ações são um ou mais comandos 
que serão realizados apenas se a avaliação da condição resulta **VERDADEIRO**. 
Vamos colocar agora a frase do exemplo anterior em outra forma, mais parecida com 
nosso Português Estruturado: 

Exemplo - 1.2: 

**se** "tiver R$ 10,00 sobrando" **entao** 
 
 "irei ao cinema" 

**fimse** 


<div align="center">
<img src="https://user-images.githubusercontent.com/100056877/204166325-234e4617-7a39-44fe-a4cd-7e3093623eca.png"/>
 </div>


Exemplo - 1.3: 

**se** Dinheiro >= 10 **entao** 

Ir_ao_Cinema <- **VERDADEIRO** 

**Fimse**


# Exercicios

**1 -** Escreva um programa que pergunte a velocidade de um carro. Caso ultrapasse 
80Km/h, exiba uma mensagem dizendo que o usuário foi multado. Nesse caso, exiba 
o valor da multa, cobrando R$5 por cada Km acima da velocidade permitida.


**2 -** Desenvolva um programa que leia um número inteiro e mostre se ele é PAR ou 
ÍMPAR.


**3 -** Escreva um programa que leia o ano de nascimento de um rapaz e mostre a sua 
situação em relação ao alistamento militar.
 - Se estiver antes dos 18 anos, mostre em quantos anos faltam para o 
alistamento.
 - Se já tiver depois dos 18 anos, mostre quantos anos já se passaram do 
alistamento.


**4 -** Numa promoção exclusiva para o Dia da Mulher, uma loja quer dar descontos 
para todos, mas especialmente para mulheres. Faça um programa que leia nome, 
sexo e o valor das compras do cliente e calcule o preço com desconto. Sabendo 
que:
 - Homens ganham 5% de desconto
 - Mulheres ganham 13% de desconto


**5 -** Faça um algoritmo que pergunte a distância que um passageiro deseja 
percorrer em Km. Calcule o preço da passagem, cobrando R$0,50 por Km para 
viagens até 200Km e R$0.45 para viagens mais longas.
