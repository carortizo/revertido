# Revertir String
El codigo dentro de este repositorio tiene el objetivo de revertir un string.

    string = input("Ingrese string:") - Lee la entrada del usuario
    string_reverso = string[::-1] - Utiliza un slice que empieza al final del string dirigido a la posicion 0 para dar vuelta el string.
    print("String revertido es: "+string_reverso) - Imprime el string revertido.
    fin = input("Presione enter para finalizar") - Espera la entrada del usuario por si lo ejecuta directamente en python para que no se cierre instantaneamente.
