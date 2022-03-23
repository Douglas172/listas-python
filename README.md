# listas-python
#estrutura de lista com verificação em python
numeros = []
r = 'S'
while r == 'S':
    n = int(input("digite um valor:\n"))
    if n in numeros:
        print(f"{n} ja esta na lista numeros")
        break
    numeros.append(n)
    r = str(input("quer continuar? [sair/s]\n")).upper()
print("fim!")
print(numeros)
numeros.sort()
print(f"lista em ordem crescente\n{numeros}")
