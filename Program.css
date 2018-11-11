using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp10_13_komplex_tömb_feladat
{
    class Program
    {
        static void Main(string[] args)
        {
            //Kérjünk be egy egész számot a felhasználótól, ez legyen N. Hozzunk létre egy N elemű, egész számokból álló tömböt. Kérdezzük meg, a felhasználótól, hogy 
            //milyen intervallumból töltsük fel a tömböt véletlen számokkal. Ezek legyenek a és b. Ügyeljünk rá, hogy a kisebb legyen mint b. Töltsük fel a tömböt 
            //véletlen számokkal, az [a,b] intervallumból. Írjuk ki a tömb elemeit a képernyőre a sorszámukkal és az előjelükkel együtt, táblázatszerűen. 
            //Egy menü segítségével kérdezzük meg a felhasználót, hogy mit szeretne csinálni a tömb elemeivel(Innentől kezdve ismételjük a programot egészen addig, amíg a felhasználó a kilépést nem választja.): 
            //Növelni 
            //Csökkenteni 
            //Szorozni
            //Kilépni
            //A felhasználótól csak a, b, c, vagy d betűt fogadjunk el.Egyéb esetben írjunk ki hibaüzenetet, és kérjük be a választását újra. 
            //Kérjük be a növelés/ csökkentés / szorzás mértékét, majd végezzük el a műveletet a tömb összes elemén.Írjuk ki az új elemeket
            Console.WriteLine("10 13.feladat");
            Console.WriteLine("Kérem adja meg hány elemű tömböt szeretne");
            int N = Convert.ToInt32(Console.ReadLine());
            int[] A = new int[N];
            Random r = new Random();
            int a;
            int b;
            char c;
            int muvelet;
            do
            {
            Console.WriteLine("Melyik szám legyen a tömb legkisebb eleme?");
            a = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Melyik szám legyen a tömb legnagyob eleme?");
            b = Convert.ToInt32(Console.ReadLine());
            }
            while (a>b);
            Console.WriteLine("\tsorszám\t|\telem\t|\telőjel");
            Console.WriteLine("--------------------------------------------------");
            for (int i = 0; i < N; i++)
            {
                A[i] = r.Next(a, b);
                Console.Write("\t{0}\t|\t{1}\t|", i + 1, A[i]);
                if (A[i] < 0)
                {
                    Console.WriteLine("\t-\t|");
                }
                else
                {
                    Console.WriteLine("\t+\t|");
                }
            }
            do
            {
                Console.WriteLine("Mit szeretne csinálni a sorozattal?");
                Console.WriteLine("|a Növelni|b Csökkenteni|c Szorozni|d kilépni");
                c = Convert.ToChar(Console.ReadLine());
                if (c=='a')
                {
                    Console.WriteLine("Mennyivel szeretné növelni a sorozat elemeit?");
                    muvelet = Convert.ToInt32(Console.ReadLine());
                    Console.WriteLine("\tsorszám\t|\telem\t|\telőjel");
                    Console.WriteLine("--------------------------------------------------");
                    for (int i = 0; i < N; i++)
                    {
                        Console.Write("\t{0}\t|\t{1}\t|", i + 1, A[i]+muvelet);
                        if (A[i] < 0)
                        {
                            Console.WriteLine("\t-\t|");
                        }
                        else
                        {
                            Console.WriteLine("\t+\t|");
                        }
                        A[i] = A[i] + muvelet;
                    }
                }
                else if (c == 'b')
                {
                    Console.WriteLine("Mennyivel szeretné csökkenteni a sorozat elemeit?");
                    muvelet = Convert.ToInt32(Console.ReadLine());
                    Console.WriteLine("\tsorszám\t|\telem\t|\telőjel");
                    Console.WriteLine("--------------------------------------------------");
                    for (int i = 0; i < N; i++)
                    {
                        Console.Write("\t{0}\t|\t{1}\t|", i + 1, A[i] - muvelet);
                        if (A[i] < 0)
                        {
                            Console.WriteLine("\t-\t|");
                        }
                        else
                        {
                            Console.WriteLine("\t+\t|");
                        }
                        A[i] = A[i] - muvelet;
                    }
                }
                else if (c == 'c')
                {
                    Console.WriteLine("Mennyivel szeretné szorozni a sorozat elemeit?");
                    muvelet = Convert.ToInt32(Console.ReadLine());
                    Console.WriteLine("\tsorszám\t|\telem\t|\telőjel");
                    Console.WriteLine("--------------------------------------------------");
                    for (int i = 0; i < N; i++)
                    {
                        Console.Write("\t{0}\t|\t{1}\t|", i + 1, A[i] * muvelet);
                        if (A[i] < 0)
                        {
                            Console.WriteLine("\t-\t|");
                        }
                        else
                        {
                            Console.WriteLine("\t+\t|");
                        }
                        A[i] = A[i] * muvelet;
                    }
                }
                else
                {
                    Console.WriteLine("A játék véget ért.");
                }
            }
            while (c!='d');
            Console.ReadKey();
        }
    }
}
