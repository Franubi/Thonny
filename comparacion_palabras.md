# Thonny
def comparacion_palabras(pal1,pal2):
    if(pal1==pal2):
        return "Estas palabras son iguales"
    else:
        return "Estas palabras son diferentes"
    
palabra1 = input("Dime una palabra")
palabra2 = input("Dime otra palabra")

print (comparacion_palabras(palabra1,palabra2))
