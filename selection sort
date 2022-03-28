namespace sort
{
    class Program
    {
        //selection sort
        static void sorting()
        {
            //creating an array and inserting numbers 
            Console.WriteLine("insert 10 numbers");
            int[] tab = new int[10];
            for(int i = 0; i < tab.Length; i++)
            {
                tab[i] = Convert.ToInt32(Console.ReadLine());
            }

            //displaying user's array
            Console.Write("your array is: [ ");
            for (int i = 0; i < tab.Length; i++)
            {
                Console.Write(tab[i] + " ");
            }
            Console.WriteLine("]");

            //sorting logic
            for (int k = 0; k < tab.Length-1; k++)
            {
                int min = tab[k];
                int minpos = k;
                for (int i = k; i < tab.Length; i++) 
                {
                    if (min > tab[i])
                    {
                        min = tab[i];
                        minpos = i;
                        int temp = tab[k];
                        tab[k] = min;
                        tab[minpos] = temp;
                    }
                }
            }

            //displaying a sorted array
            Console.Write("array was sorted ascending: [");
            for (int i = 0; i < tab.Length; i++)
            {
                Console.Write(tab[i] + " ");
            }
            Console.WriteLine("]");
            Console.WriteLine();
        }
        static void Main(string[] args)
        {
            while(true)
            {
                sorting();
            }
        }
    }
}
