#inicio 
 = int(input("Digite um número inteiro: "))
if n >= 0:
    print("Positivo")
else:
    print("Negativo")
#fim

#inicio

n = int(input("Digite um número: "))
print("Dobro:", n * 2)
#fim

#inicio

valor = input("Digite um valor: ")
print("Valor digitado:",valor)
print("Tipo:", type(valor))
#fim

#inicio

n = int(input("Digite um número: "))
if n % 2 == 0:
    print("Par")
else:
    print("Ímpar")
#fim

#inicio

texto = input("Digite um número: ")
n = int(texto)
print("Triplo:",n * 3)
#fim

#inicio

a = int(input("Digite o primeiro número: "))
b = int(input("Digite o segundo número: "))
print("Maior:", a if a > b else b)
#fim

#inicio

n = int(input("Digite um número: "))
if n > 10:
    print("Maior que 10")
else:
    print("Menor ou igual a 10")
#fim 

#inicio

n = int(input("Digite um número: "))
if n > 0:
    print("Raiz aproximada:",n ** 0.5)
else:
    print("Número inválido")
#fim

inicio

valor = float(input("Digite um valor: "))
print("Metade:", valor/2)
#fim

#inicio

n = int(input("Digite um número: "))
if 0 <= n <= 10:
    print("Dentro do intervalo")
else:
    print("Fora do intervalo")
#fim 

#inicio

n = int(input("Digite um número: "))

if n % 2 == 0:  # é par
    if n >= 0:
        print("Par positivo")
    else:
        print("Par negativo")
else:
    print("Ímpar")
#fim

#inicio
a = int(input("Digite o primeiro número: "))
b = int(input("Digite o segundo número: "))

soma = a + b
print("Soma:",soma)

if a > b:
    print("O maior é:", a)
elif b > a:
    print("O maior é:", b)
else:
    print("Os números são iguais")
#fim
