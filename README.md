
    class Program
    {
        static void Main(string[] args)
        {
            int birinciTerim = 0;
            int ikinciTerim = 0;
            int carpim = 1;

            for (birinciTerim = 1; birinciTerim <= 9; birinciTerim++)
            {
                for (ikinciTerim = 1; ikinciTerim <= 9; ikinciTerim++)
                {
                    carpim = birinciTerim * ikinciTerim;
                    Console.Write("{0}x{1}={2}\t", birinciTerim, ikinciTerim, carpim);
                }
                Console.WriteLine();
            }


            Console.ReadLine();
            Console.Clear();
        }
    }
