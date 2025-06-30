# Prueba_Renato_Santander_forma-D-
Prueba Renato Santander
import os 

#Funcion para limpiar pantalla.
def limpiar_pantalla ():
    os.system("cls")

def codigo_confirmacion (id):
    if len(id)<6:
        return
    if id in codigo_confirmacion:
        return False
    
    if not any (c.isalpha() for c in id):
     return False

    if not any (c.isdigit() for c in id):    
        return True
    
    if "" in id:
         return

#Datos
def   ingresar_usuario_concepcion(entradas_concepcion):
    while True:
        nombre = input("Ingrese su nombre porfavor:")
        if nombre in "usuario":
            print("Error")
        else:
            break

    while True:
        entradas_ususario_concepcion = int(input("Ingrese la cantidad de entrada que desea comprar:"))    
        print("la cantidad de entradas que desea son"[entradas_concepcion])
        break
    while True:
            entradas_ususario_concepcion = int(input("Ingrese la cantidad de entrada que desea comprar:"))  
            print(input("la cantidad de entradas que desea son"(entradas_ususario_concepcion)))
            print("ID del usuario:"),codigo_confirmacion

            ingresar_usuario_puente_alto[entradas_concepcion] = {"nombre": nombre , "entradas_concepcion": entradas_ususario_concepcion}
        
        

        
def ingresar_usuario_puente_alto():
    while True:
        nombre = input("Ingrese su nombre porfavor:")
        if nombre in "usuario":
            print("Error")
        else:
            break

        while True:
            entradas_ususario_puente_alto = int(input("Ingrese la cantidad de entrada que desea comprar:"))  

            print("----------------------------------------------------------------------------------------")            
            print(input("la cantidad de entradas que desea son"(entradas_ususario_puente_alto)))
        
            ingresar_usuario_puente_alto[ingresar_usuario_puente_alto] = {"nombre": nombre , "entradas_concepcion": entradas_ususario_puente_alto}


def ingresar_usuario_muelle_baron_valparaiso():
    while True:
        nombre = input("Ingrese su nombre porfavor:")
        if nombre in "usuario":
            print("Error")
        else:
            break
        if id in ingresar_usuario_muelle_baron_valparaiso:
            return False

        while True:
            entradas_ususario_muelle_baron_valparaiso = int(input("Ingrese la cantidad de entrada que desea comprar:"))  

            print("----------------------------------------------------------------------------------------")            
            print(input("la cantidad de entradas que desea son"(entradas_ususario_muelle_baron_valparaiso)))
        
            ingresar_usuario_muelle_baron_valparaiso[ingresar_usuario_muelle_baron_valparaiso] = {"nombre": nombre , "entradas": entradas_ususario_muelle_baron_valparaiso}

def ingresar_usuario_muelle_vergara_viña_del_mar():
    while True:
        nombre = input("Ingrese su nombre porfavor:")
        if nombre in "usuario":
            print("Error")
        else:
            break
        if id in ingresar_usuario_muelle_vergara_viña_del_mar:
            return False

        while True:
            entradas_ususario_muelle_vergara_viña_del_mar = int(input("Ingrese la cantidad de entrada que desea comprar:"))  

            print("----------------------------------------------------------------------------------------")            
            print(input("la cantidad de entradas que desea son"(entradas_ususario_muelle_vergara_viña_del_mar)))
        
            ingresar_usuario_muelle_vergara_viña_del_mar[ingresar_usuario_muelle_vergara_viña_del_mar] = {"nombre": nombre , "entradas": entradas_ususario_muelle_vergara_viña_del_mar}
            
def main():
       while True: 
            try:
                limpiar_pantalla()

                print("---Venta de entradas ---")
                print("---- Los Fortificados ----")
                print("-------------------------")
                print("1 - Comprar entrada a “los Fortificados” en Concepción.")
                print("2.- Comprar entrada a “los Fortificados” en Puente Alto")
                print("3.- Comprar entrada a “los Fortificados” en Muelle Barón en Valparaíso.")
                print("4.- Comprar entrada a “los Fortificados” en Muelle Vergara en Viña del Mar")
                print("5 - Salir")
                
                
                opcion = int("Ingrese una de las opciones disponibles:[1 al 5]")
                
            except ValueError:
                 print("Error, debe ingresar valores validos")
                 input("Presione enter para continuar\n\n")
                
            if opcion == 1:
                ingresar_usuario_concepcion()
                break
                    
            elif opcion == 2:    
                ingresar_usuario_puente_alto()
                break
                    
            elif opcion == 3:
                ingresar_usuario_muelle_baron_valparaiso()
                break
            elif opcion == 4:
                ingresar_usuario_muelle_vergara_viña_del_mar
                break
            elif opcion == 5 :
                print ("Salir del programa ")
                
                print
                    
                    
                    
main()
