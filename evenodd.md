# Code


using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int num1, rem1;
            Console.WriteLine("Enter a number");
            num1 = Convert.ToInt32(Console.ReadLine());
            rem1 = num1 % 2;
            if (rem1 == 0)
                Console.WriteLine("This number is Even.");
            else
                Console.WriteLine("This number is odd.");
            Console.ReadLine();

        }
    }
}

