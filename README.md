#inicio 
 = int(input("Digite um número inteiro: "))

if n>=0:
    print("Positivo")
else:
    print("Negativo")
#fim

#inicio
n=int(input("Digite um número: "))
print("Dobro:",n * 2)
#fim

#inicio
valor=input("Digite um valor: ")
print("Valor digitado:",valor)
print("Tipo:",type(valor))
#fim

#inicio
n=int(input("Digite um número: "))
if n%2==0:
    print("Par")
else:
    print("Ímpar")
#fim

#inicio
texto=input("Digite um número: ")
n = int(texto)
print("Triplo:",n * 3)
#fim

#inicio
a=int(input("Digite o primeiro número: "))
b=int(input("Digite o segundo número: "))
print("Maior:", a if a > b else b)
#fim

#inicio
n=int(input("Digite um número: "))
ifn>10:
    print("Maior que 10")
else:
    print("Menor ou igual a 10")
#fim 

#inicio
n=int(input("Digite um número: "))
ifn>0:
    print("Raiz aproximada:",n ** 0.5)
else:
    print("Número inválido")
#fim

#inicio
valor=float(input("Digite um valor: "))
print("Metade:", valor/2)
#fim

#inicio
n=int(input("Digite um número: "))
if 0<= n <= 10:
    print("Dentro do intervalo")
else:
    print("Fora do intervalo")
#fim 

#inicio
n=int(input("Digite um número: "))

if n % 2 == 0:  # é par
    if n >= 0:
        print("Par positivo")
    else:
        print("Par negativo")
else:
    print("Ímpar")
#fim

#inicio
a = float(input("digite o primeiro número: "))
b = float(input("digite o segundo número: "))

soma = a + b
print("soma:", soma)

if a > b:
    print("o primeiro número é maior")
elif b > a:
    print("o segundo número é maior")
else:
    print("os números são iguais")
# fim


#inicio
num = float(input("digite um número: "))
if num > 100:
    print("metade:", num / 2)
else:
    print("dobro:", num * 2)
# fim

#inicio
valor = float(input("digite um valor: "))
valor_int = int(valor)
if valor_int % 3 == 0:
    print("múltiplo de 3")
else:
    print("não é múltiplo")
# fim

#inicio
num = float(input("digite um número: "))
if 10 <= num <= 20:
    print("dentro")
else:
    print("fora")
# fim

#inicio
valor = input("digite um valor: ")
print("tipo:", type(valor))
try:
    num = float(valor)
    print("quadrado:", num ** 2)
except:
    print("não é numérico")
# fim

#inicio
idade = int(input("digite sua idade: "))
if idade < 18:
    print("menor de idade")
elif idade < 60:
    print("adulto")
else:
    print("idoso")
# fim

#inicio
num = int(input("digite um número: "))
if num == 0:
    print("neutro")
elif num % 2 == 0 and num > 0:
    print("par positivo")
elif num % 2 == 0 and num < 0:
    print("par negativo")
elif num % 2 != 0 and num > 0:
    print("ímpar positivo")
else:
    print("ímpar negativo")
# fim

#inicio
a = float(input("digite o primeiro número: "))
b = float(input("digite o segundo número: "))
if a == b:
    print("são iguais")
else:
    print("são diferentes")
    print("diferença:", abs(a - b))
# fim

#exemplo20
#inicio
num = float(input("digite um número: "))
if 0 <= num <= 100:
    print("dentro do intervalo")
else:
    print("fora do intervalo:", num)
#fim


