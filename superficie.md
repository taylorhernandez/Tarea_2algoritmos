using System;
using System.Collections.Generic;
using System.Text;
namespace Volumen
{
    class Program
    {
        static void Main(string[] args)
        {
            double radio, vol, pi;
            vol = 0.0;
            pi = 3.141592654;
            Console.WriteLine("Calcular volumen de una Esfera \n");
            Console.WriteLine("Introduce radio");
            radio = double.Parse(Console.ReadLine());
            vol = ((4 * pi) * (radio * radio * radio)) / 3;
            Console.WriteLine("El volumen es: " + vol);
            Console.ReadKey();
        }
    }
}

