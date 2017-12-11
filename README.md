# OguzcanAsilioglu
Oğuzcan AŞILIOĞLU/174410061
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication10
{
    class Program
    {
        static void Main(string[] args)
        {
            char i; int a = 10, t, u; string c, kelime = "";
            Console.WriteLine("isminizi giriniz"); c = Console.ReadLine();
            u = c.Length;
            for (int p = 0; p < u; p++)
            {
                Console.Write("isminizin{0}. harfini giriniz:", p + 1); i = char.Parse(Console.ReadLine());
                t = a + (int)i;
                kelime += (char)t;

            }
            Console.WriteLine("ASCII kodunun 10 fazlası :" + kelime);
            Console.ReadKey();
        }
    }
}
