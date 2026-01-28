def trouver_maximum(liste):
    maximum = liste[0]
    for nombre in liste:
        if nombre > maximum:
            maximum = nombre
    return maximum


# Exemple
nombres = [4, 10, 2, 18, 7]
print(trouver_maximum(nombres))

