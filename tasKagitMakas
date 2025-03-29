using Microsoft.Win32;
using System;
using System.Collections.Generic;
using System.Configuration;
using System.Linq;
using System.Runtime.InteropServices;
using System.Text;
using System.Threading.Tasks;
using System.Xml.Schema;

namespace erdos60
{
    internal class Program
    {
        static void Main(string[] args)
        {

   Random random = new Random();

   Console.WriteLine("Toplam Oyun : ");

   int oyun = Convert.ToInt32(Console.ReadLine());

   int secim;
   int randomSecim;
   int kullanici = 0;
   int yapayZeka = 0;
   int i = 0;

   while (i < oyun)
   {

       i++;

       Console.WriteLine("1 : Taş");
       Console.WriteLine("2 : Kağıt");
       Console.WriteLine("3 : Makas");

       secim = Convert.ToInt32(Console.ReadLine());

       randomSecim = random.Next(1 , 4);

          
       if (secim == 1 && randomSecim == 1)
       {

           Console.WriteLine("Beraberlik");

           Console.WriteLine("Hamleniz : " + secim);

           Console.WriteLine("Rakibin Hamlesi : " + randomSecim);

          
       }

       else if (secim == 1 && randomSecim == 2)
       {

           Console.WriteLine("Kaybettiniz!");

           Console.WriteLine("Hamleniz : " + secim);

           Console.WriteLine("Rakibin Hamlesi : " + randomSecim);

           yapayZeka++;


       }

       else if (secim == 1 && randomSecim == 3)
       {

           Console.WriteLine("Kazandiniz!");

           Console.WriteLine("Hamleniz : " + secim);

           Console.WriteLine("Rakibin Hamlesi : " + randomSecim);

           kullanici++;


       }

       else if (secim == 2 && randomSecim == 1)
       {

           Console.WriteLine("Kazandiniz");

           Console.WriteLine("Hamleniz : " + secim);

           Console.WriteLine("Rakibin Hamlesi : " + randomSecim);

           kullanici++;


       }

       else if (secim == 2 && randomSecim == 2)
       {

           Console.WriteLine("Beraberlik!");

           Console.WriteLine("Hamleniz : " + secim);

           Console.WriteLine("Rakibin Hamlesi : " + randomSecim);


       }

       else if (secim == 2 && randomSecim == 3)
       {

           Console.WriteLine("Kaybettiniz!");

           Console.WriteLine("Hamleniz : " + secim);

           Console.WriteLine("Rakibin Hamlesi : " + randomSecim);

           yapayZeka++;


       }

       else if (secim == 3 && randomSecim == 1)
       {

           Console.WriteLine("Kaybettiniz!");

           Console.WriteLine("Hamleniz : " + secim);

           Console.WriteLine("Rakibin Hamlesi : " + randomSecim);

           yapayZeka++;


       }

       else if (secim == 3 && randomSecim == 2)
       {

           Console.WriteLine("Kazandiniz!");

           Console.WriteLine("Hamleniz : " + secim);

           Console.WriteLine("Rakibin Hamlesi : " + randomSecim);

           kullanici++;


       }

       else if (secim == 3  && randomSecim == 3)
       {

           Console.WriteLine("Beraberlik");

           Console.WriteLine("Hamleniz : " + secim);

           Console.WriteLine("Rakibin Hamlesi : " + randomSecim);


       }

       else if (secim > 3 || secim < 0)
       {
           Console.WriteLine("Gecerli Bir Hamle Giriniz!");

           break;
       }

    


   }

   Console.WriteLine("Sonuc : ");

   Console.Write("Siz : " + kullanici);

   Console.Write(" Rakip : " + yapayZeka);



        }


}
}
