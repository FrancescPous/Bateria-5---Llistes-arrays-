# Bateria-5---Llistes-arrays-

# Problema nº1

llista = []
while True:
    valor = input("Fica un numero: ")
    if valor == "final":
        break
    else:
        llista.append(int(valor))
    resultat = 0
    for numero in llista:
        resultat = resultat + numero
    print("La suma dels elements de la llista és: ", resultat)
