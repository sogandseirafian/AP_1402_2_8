# AP_1402_2_8
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace AP_1402_2_5_CS
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Enter the size of the array 100:");
            int[] arr = new int[100];
            int min = 1;
            int max = 0;
            for(int i=0;i<100;i++)
            {
                arr[i] = Convert.ToInt32(Console.ReadLine());
                if (arr[i]>max)
                {
                    max = arr[i];
                }
                if (arr[i]<min)
                {
                    min = arr[i];
                }
            }
            Console.WriteLine("max is :" + max);
            Console.WriteLine("min is :" + min);

        }
    }
}
