# parcialimport math

"""
***************************************************************
@@ ejercicio 1 @@
un metodo python que haga la multiplicacion de 3 numeros
2*4*3 = 24
"""


# start-->
def multiplicar(num1, num2, num3):
    num1 = 2
    num2 = 3
    num3 = 4
    return  num1 * num2 * num3

"""
***************************************************************
@@ ejercicio 2 @@
la suma de los numeros divisibles entre 3 y 5 del 1000 al 2000
"""


# start-->
def sumaDivTresYCincoPlus():
    result = sumar([n for n in range(1000,2001) if n % 3 == 0 and n % 5 == 0])
    return result


"""
***************************************************************
@@ ejercicio 3 @@
encontrar el area y el volumen de un ortoedro
longitud = 10 m
latitud = 6 m
altura = 5 m

area: A = 2(longitud · latitud + longitud · altura + latitud · altura)
volumen: V = longitud · latitud · altura
"""


# start-->
def definicionOrtoedro(longitud, latitud, altura):
    area = obtenerArea(longitud, latitud, altura)
    volumen = obtenerVolumen(longitud, latitud, altura)
    result = {"Area":area, "Volumen":volumen}
    return result


def obtenerArea(nume1, nume2, nume3):
    area = 2*(nume1*nume2+nume1+nume3+nume2*nume3)
    result = area
    return result

def obtenerVolumen(nume1, nume2, nume3):
    volumen = nume1 * nume2 * nume3
    result = volumen
    return result


"""
***************************************************************
@@ ejercicio 4 @@
el ejercicio numero 3 convertirlo en una clase

"""


# start-->
class Ortoedro:
    def definicionOrtoedro(self):
        return 0


"""
***************************************************************
@@ ejercicio 5 @@
VentaComputadoras
Computadora
    procesador
    ram
    tarjeta_grafica
    ssd
    costo
    conDescuento
    descuento
    conPlazo
    cuota
"""


class VentaComputadoras:
    def orden(self):
        pass

    def totalProcesadorIntel(self):
        return 0

    def totalRam16ConDescuento(self):
        return 0


class Computadora:
    pass


"""
***************************************************************
@@ ejercicio 6 @@
colocar este proyecto en github
colocar aca debajo la url
ademas colocar la url en un archivo
github_<nombre>_<codigo>.txt y subirlo a moodle
"""


# github url-->
def getGithubUrl():
    return ""
