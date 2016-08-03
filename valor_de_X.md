using System;

    class Ejercicio2
    {
        static void Main()
        {
            float num;

            Console.Write("Ingrese el valor de Y:");
            num = float.Parse(Console.ReadLine());

            if (num >=-5 && num<=5)
            {
                Console.Write("El valor de es {0} ", (num * num)+(num*2)+1);
                Console.Read();
               
            }
            else
           

            Console.Write("ERROR.Reingrese número:");
            Console.ReadLine();
            Console.Write ("presione una tecla para continuar");
            Console.ReadLine();
            
        }

    }
