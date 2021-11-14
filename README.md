# Avidine el número, segundo intento. 


Como la última vez, cuando reescribo el codigo, no me funcionan los if de si el intento elejido es demasiado pequeño o grande, me da error en los símbolos (<>). En cambio cuando copio y pego algún ejemplo de internet, que tenga <>, y lo ejecuto funciona. 

esta es otra versión de mi código 


``` import random 

intentosRealizados = 0

numero = random.randint (1, 100)

print ("!Se generará un número entre 0 y 100, incluidos!")

while intentosRealizados < 6:
    print ("¡Intente adivinar el númer!")

    intento = input ()
    intetno = int(intento)

    intetnosRealizados = intentosRealizados + 1

    if intento < numero:

        print('Muy bajo.') 

    if intento > numero:

        print('Muy alto.')

    if intento == numero:

        break

if intento == numero: 
    
    intentosRealizados = str(intentosRealizados )

    print ("!Enhorabuena, acertaste en " + intentosRealizados + " intentos!")

if intento != numero: 

    numero = str(numero)

    print ("Fallaste, el numero era " + numero)import random ```

