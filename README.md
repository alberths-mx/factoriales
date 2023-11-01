print ("CALCULEMOS UN NÚMERO FACTORIAL N!")
print ("")
print ("Un número factorial es aquel producto de un número natural, el cual resultara de la multiplicación")
print ("de los números consecutivos que lo anteceden. Ej. 4! (cuatro factorial) = 4x3x2x1")
print ("")
numero = int(input("Introduzca un número entero cualquiera: "))
factorial = 1
i = 1
while (i <= numero):
    factorial = factorial * i
    i = i + 1
print ("El factorial de " + str(numero) + " es " + str(factorial))
