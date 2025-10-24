C#
// See https://aka.ms/new-console-template for more information
// Declarar variables
double nota1, nota2, nota3, promedio;

// Pedir las tres notas
Console.Write("Ingrese la primera nota: ");
nota1 = Convert.ToDouble(Console.ReadLine());

Console.Write("Ingrese la segunda nota: ");
nota2 = Convert.ToDouble(Console.ReadLine());

Console.Write("Ingrese la tercera nota: ");
nota3 = Convert.ToDouble(Console.ReadLine());

// Calcular el promedio
promedio = (nota1 + nota2 + nota3) / 3;

// Mostrar el resultado
Console.WriteLine("El promedio de las tres notas es: " + promedio);

#PYTHON
from posixpath import realpath
#INGRESAR LA TRES NOTAS
n1 = int(input("INGRESE EL PRIMER NUMERO: "))
n2 = int(input("INGRESE EL SEGUNDO NUMERO: "))
n3 = int(input("INGRESE EL TERCER NUMERO: "))
#OPERACION PROMEDIO
suma = n1 + n2 + n3
promedio = suma /3

print ("El promedio de las notas es: ", promedio)

if promedio >= 11:
    mje = "Aprobó"
else:
    mje = "Desaprobó"

print(mje)
