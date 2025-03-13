
def suma (a,b):
    resultado = a + b 

def resta (a,b):
    resultado = a - b

def multiplicasion (a,b):
    resultado = a * b
    
def division (a,b):
    resultado = a / b

print("CALCULADORA")
while True: 

    opcion = int(input("que operación desea hacer : \n 1.- SUMAR [1] : \n 2.- RESTAR [2] : \n 3.- MULTIPLICAR [3] : \n 4.- DIVIDIR [4] : \n 5.-SALIR [5] \n " ))

    if opcion == 1 : 

        print (" ESCOGIO LA OPERACIÓN SUMA ")
        sumnum1 = int(input("INGRESE EL PRIMER NÚMERO \n "))
        sunmun2 = int(input("INGRESE EL SEGUNDO NÚMERO \n "))
        sum = suma(sumnum1 , sunmun2 ) 
        print ("LA SUMA ES : ", sum)

        print ("")
    if opcion == 2 :

        print (" ESCOGIO LA OPERACIÓN RESTA")
        resnum1 = int(input("INGRESE EL PRIMER NÚMERO \n "))
        resmun2 = int(input("INGRESE EL SEGUNDO NÚMERO \n"))
        res = resta(resnum1 , resmun2) 
        print ("LA RESTA ES : ", res)
        
        print ("")
    if opcion == 3 :

        print (" ESCOGIO LA OPERACIÓN MULTIPLICACIÓN \n")
        mulnum1 = int(input("INGRESE EL PRIMER NÚMERO \n"))
        mulmun2 = int(input("INGRESE EL SEGUNDO NÚMERO \n"))
        mul = multiplicasion(mulnum1 ,mulmun2 ) 
        print ("LA MULTIPLICACIÓN ES : ", mul)

        print ("")
    if opcion == 4 :

        print (" ESCOGIO LA OPERACIÓN DIVISIÓN \n")
        divnum1 = int(input("INGRESE EL PRIMER NÚMERO \n"))
        divmun2 = int(input("INGRESE EL SEGUNDO NÚMERO \n"))
        div = division(divnum1 , divmun2 ) 
        print ("LA DIVISIÓN ES : ", div)
        
        print ("")
    if opcion == 5 :
        print (" ESCOGIO SALIR ")
        break
