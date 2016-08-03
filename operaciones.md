using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace OPERACIONES
{
    class Program
    {
        static void Main()
        {
           
            bool salir = false;
            int num1 = 0;
            int num2 = 0;
            int respuesta=0;
            string operacion = string.Empty;
            while (!salir)
            {
                Console.WriteLine("Ingresar el primer numero");
                num1 = Convert.ToInt32(Console.ReadLine());
                Console.WriteLine("Ingresar el segundo numero");
                num2 = Convert.ToInt32(Console.ReadLine());


                Console.WriteLine("Elija la Operacion aritmetica");
                Console.WriteLine("Oprima s para SUMAR");
                Console.WriteLine("Oprima r para RESTAR");
                Console.WriteLine("Oprima m para MULTIPLICAR");
                Console.WriteLine("Oprima d para DIVIDIR");
                operacion = Console.ReadLine();

                switch (operacion)
                {
                    case "s":
                        respuesta = num1 + num2;
                        break;
                    case "r":
                        respuesta = num1 - num2;
                        break;
                    case "d":
                        respuesta = num1 / num2;
                        break;
                    case "m":
                        respuesta = num1 * num2;
                        break;

                    default:
                        respuesta = 0;
                        break;
                }

                Console.WriteLine(String.Format("La prespuesta es: {0}", respuesta));




                Console.WriteLine("Precione  S  para continuar o ENTER para salir");
                if (Console.ReadLine() != "s")
                    salir = true;
               
            }

        }
    }
  }
}
