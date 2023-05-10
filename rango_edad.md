# Thonny
def comparacion_edad(edad):
    if(edad < 18):
        return "Esta persona es menor de edad"
    if(edad > 18 and edad < 65):
        return "Esta persona es adulta"
    if(edad > 65 and edad <110):
        return "Esta persona esta jubilad@"
    if(edad > 110):
        return "Esta persona esta muerta"
    
anos = int(input("Dime tu edad: "))

print (comparacion_edad(anos))
