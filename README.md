# PYTHON - Alguns dos meus estudos sobre a linguagem
***
# PROGRAMA DE CONVERSAO DE REAIS EM DOLAR
print ("PROGRAMA DE CONVERSAO DE REAIS EM DOLAR")
valor=float(input("quantos reais deseja converter? "))

dolar=5.41
conversao=valor/dolar

print (" O valor em reais R$:{} se convertido para dolares ficaria US: {}.".format(valor,conversao))
***
# PROGRAMA DE CALCULO DE DESCONTOS
print("PROGRAMA DE CALCULO DE DESCONTOS")

valor=float(input("qual o valor do produto ?"))

desconto=float(input("qual o valor do desconto ofertado?"))

descontado= valor-valor*desconto/100

print("O produto de {} reais saira por {} com esses descontos.".format(valor,descontado))
***
# PROGRAMA DE VERDADEIRO OU FALSO
print("VERDADEIRO OU FALSO")
print("saiba se é alfanumerico,numerico,decinal,letra minuscula,espaço em branco e letras maisculas")

n=input("digite alguma coisa para saber se é verdadeiro ou falso: ")
print("tipo primitivo:{}.".format(type(n)))

print("É alfanumerico?{}.".format(n.isalpha()))

print("É numerico?{}.".format(n.isnumeric()))

print("É decimal?{}.".format(n.isdecimal()))

print("Esta em caixa alta?{}.".format(n.isupper()))

print("Esta em caixa baixa?{}.".format(n.islower()))

print("Esta em branco?{}.".format(n.isspace()))

***
# PROGRAMA DE CALCULO DA HIPOTENUSA
print("PROGRAMA DE CALCULO DA HIPOTENUSA")
from math import hypot

cateto_oposto=int(input("Quanto mede o cateto oposto? "))

cateto_adjacente=int(input("Quanto mede o cateto adjacente? "))

hi= hypot(cateto_oposto, cateto_adjacente)

print("Dessa forma, atraves dos lados {} e {} nos temos uma hipotenusa {}.".format(cateto_oposto,cateto_adjacente,hi))
***
# PROGRAMA DE SORTEIOS E CHAVES DE CODIGO
print("PROGRAMA DE SORTEIOS E CHAVES CRIPTOGRAFADAS")

import random
import string

def lin():

    print("--"*40)
    
lin()

nome=input("qual sera o primeiro nome? ")
nome2=input("qual sera o segundo nome? ")
nome3=input("qual sera o terceiro nome do sorteio? ")

lista= (nome,nome2,nome3)
sorteio=random.choice(lista)

print("O sorteio tera como ganhador o:", sorteio)

import random

sorte=random.randint(1,50)
print("o numero sorteado sera: ",sorte)

import math

num= int(input("Escolha um numero para descobrir a raiz dele: "))
raiz=math.sqrt(num)

print("A raiz do numero {} será:{}.De acordo com a formula SQRT do programa".format(num,raiz))
lin()

print("Estarei testando a quebra de linha estudada no dia 21/07 \nteste numero 1 da quebra.... concluido!!")
print("Agora estarei testando uma forma de nao quebrar mais a linha")
***
# PROGRAMA DE GOTEJAMENTO E CALCULO PARA ENFERMAGEM
import math
import random

def lin():

    print("///"*50)
    
lin()

print("PROGRAMA DE ENFERMAGEM -- REGRA DE 3")

### X ---------------------------- variavel

### variavel_multiplicadora ------ variavel_divisora

variavel=float(input("qual valor da variavel?\n"))

variavel_multiplicadora=float(input("qual o valor multiplicador?\n"))

variavel_divisora=float(input("qual o valor divisor da igualdade?\n"))

x=variavel*variavel_multiplicadora/variavel_divisora

print("Desta forma, o numero de colheres de chá que devem ser feitas:{}".format(x))
lin()

print("PROGRAMA DE CALCULO DE GOTAS E MICROGOTAS DA AREA DE ENFERMAGEM")

ml=int(input("quantos ml?\n"))

t=int(input("quantos horas?\n"))

gotas= (ml/t)*1/3

print("O numero de gotas que sera administrado ml será de:{} gotas p/minuto".format(gotas))

print("Agora calculo de Gotejamento")

ml2=int(input("quantos ml?\n"))

t2=int(input("quantas horas?\n"))

microgotas= ml2/t2

print("A quantidade de Microgotas por minuto será de {} microgotas p/minuto".format(microgotas))
lin()
***
# PROGRAMA DE NOMES ALEATORIOS EM ORDEM...
import random 
  
listaa = ['A', 'B', 'C', 'D', 'E'] 
  
print("Original list : ") 
print(listaa) 
random.shuffle(listaa) 
print("\nAfter the first shuffle : ") 
print(listaa) 
random.shuffle(listaa) 
print("\nAfter the second shuffle : ") 
print(listaa)

nomes = ["Black Panther", "Solid Snake", "Kendrick Lamar", "Shadow the Hedgehog"]
random.shuffle(nomes)
print("\nA lista de apresentação é {}.",nomes)

#PROGRAMA DE REVISAO
***

import random
def lin():
    print("=="*30)
from time import sleep

lin()
print("Sorteio de numeros e nomes")
lin()
num=random.randint(1,4)
numero= int(input("escolha um numero de 1 a 4:\n"))
print("sorteando o numero...")
sleep(2)
lin()

if numero > 1 or numero < 4:
    if numero == num:
        print("Parabens por escolher o numero certo !!! {}".format(numero))
    else:
        print("Nao foi dessa vez !! voce errou o numero, pois o sorteado foi {}".format(num))
if num == numero:
    if num == 1:
        print("bryam")
if num == numero:
    if num == 2:
        print("brendon")
if num == numero:
    if num == 3:
        print("bruno")
if num == numero:
    if num == 4:
        print("bruna")
sleep(3)
lin()
print("\nCALCULO DE MULTA NA RODOVIA")
lin()
print("Um determinado carro, percorrendo uma rodovia corre a 90km/hora,\nsupondo que o limite dela fosse 80km e que sera cobrado R$:12,00 por km a mais. \nquanto o motorista devera pagar se dirigir a 90km/hora ?")
multa=12*(90-80)

if multa > 80:
    print("O motorista terá que pagar:",multa)
else:
    print("Esta dentro do limite de velocidade !!")
lin()
sleep(3)

print("\nPROGRAMA DE AUMENTO DE SALARIO")
lin()
sal=float(input("Digite seu salario:\n"))

if sal > 1250:
    aumento =(sal/100)*10
    print("O salario ira aumentar:{}".format(aumento))
else:
    aumento =(sal/100)*15
    print("O salario vai aumentar mais entao ficará:{}".format(aumento))
lin()
sleep(4)
***
#USO DE ELIF E IF 

import random
from time import sleep
def lin():
    print("=="*30)

lin ()
print("PROGRAMA DE EXERCICIOS")
lin()
sleep(3)

print("Descubra se voce precisa ou nao fazer o alistamento militar !!")
idade=int(input("Quantos anos voce tem?\n"))
lin()
sleep(4)

if idade > 18:
    print("Voce passou da idade para se alistar...")
    print("Passou {} ano(s) que era pra ter se alistado".format(idade-18))

elif idade < 18:
    print("Voce ainda nao tem idade para se alistar")
    print("Falta {} ano(s) para voce se alistar".format(18-idade))

else:
    print("Voce esta na idade certa para se alistar no alistamento militar")
    print("boa sorte no alistamento !!!")
    
***
# NOVA REVISAO 

from random import choice
import random
from time import sleep

for começa in range (10,-2,-2):
    print(começa)
    sleep(1)

print("PROGRAMA NOVO INICIADO\n")

print ("vamos escolher um dos nomes ??")
lista=["bryam","brendon","bruno","bruna"]
print("lista: {}",format (lista))

escolha=random.choice(lista)
print(" o nome escolhido será:",escolha)

if escolha ==
"bruno":
    print ("viado !!")


