# PYTHON - Alguns dos meus estudos sobre a linguagem
***
print ("PROGRAMA DE CONVERSAO DE REAIS EM DOLAR")
valor=float(input("quantos reais deseja converter? "))
dolar=5.41
conversao=valor/dolar
print (" O valor em reais R$:{} se convertido para dolares ficaria US: {}.".format(valor,conversao))
def lin():
    print("-"*40)
lin()
print("PROGRAMA DE CALCULO DE DESCONTOS")
valor=float(input("qual o valor do produto ?"))
desconto=float(input("qual o valor do desconto ofertado?"))
descontado= valor-valor*desconto/100
print("O produto de {} reais saira por {} com esses descontos.".format(valor,descontado))
lin()
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
lin()
