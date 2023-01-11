# CS_WHILE
 ```cs
 using System;

namespace while_dongusu
{
    class Program
    {
        static void Main(string[] args)
        {
        // While -  1 den başlayarak consoledan girilen sayıya kadar (o sayı dahil) ortalama hesaplayıp console'a yaz 
        Console.WriteLine("bir sayi gir:");
        int sayi1 = int.Parse(Console.ReadLine());
        int sayac= 1;
        int toplam = 0;
        while (sayac <= sayi1)
        {
            toplam+= sayac;
            sayac ++;
        }
        Console.WriteLine(toplam/sayi1);

        // a dan Z ye kadar her türlü harfleri console'a yazdır 

        char charecter = 'a';
        while (charecter< 'z')

        {
            Console.Write(charecter);
            charecter ++;
        }

        Console.Write("******ForEach*******");
        string [] arabalar={"BMW","FORD","VW","Toyota"};

        foreach (var araba in arabalar)
        {
            Console.WriteLine(araba);
        }



        }

    }
}
 ```
