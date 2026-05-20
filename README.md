# Calculatrice-python
# Calculatrice simple Python

print("=== Calculatrice ===")

# Demande des nombres
a = float(input("Premier nombre : "))
b = float(input("Deuxième nombre : "))

# Demande de l'opération
operation = input("Choisis une opération (+, -, *, /) : ")

# Calculs
if operation == "+":
    resultat = a + b
    print("Résultat :", resultat)

elif operation == "-":
    resultat = a - b
    print("Résultat :", resultat)

elif operation == "*":
    resultat = a * b
    print("Résultat :", resultat)

elif operation == "/":
    if b != 0:
        resultat = a / b
        print("Résultat :", resultat)
    else:
        print("Erreur : division par zéro impossible")

else:
    print("Opération invalide")
