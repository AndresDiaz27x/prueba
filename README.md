# prueba
class Program
{
    static void Main(string[] args)
    {
       //Declaracion de Variables
       int num1, nu2, suma; 

       //Explicacion del Ejercicio
       Console.Write("\n\tSuma de Dos Numeros");

       //Ingresando el primer numero
       Console.Write("\nIngrese un numero: ");
       num1 = Int32.Parse(Console.ReadLine());

       //Ingresando el primer numero 
       Console.Write("\nIngrese el numero 2: ");  
       num2 = Int32.Parse(Console.ReadLine());

       //Realizando la Suma
       suma = num1 + num2;

       //Mostrando Resultado
       Console.WriteLine("El Resultado es: " + suma); 

       //Detener pantalla
       Console.WriteLine("\n\n\tPresione < ENTER > para salir . . .");
       Console.ReadKey();

    }
}
