# String-Metotlar
// String Metotlar
            string degisken = "Rabia Çakmak";
            string degisken1 = "Bursa";

            //Length; İçinde kaç tane harf olduğunu öğrenebiliriz.
            Console.WriteLine(degisken.Length);

            // ToUpper  ,ToLower
            // İçindeki harflerin hepsini büyültür/ küçültür.
            Console.WriteLine(degisken.ToLower());
            Console.WriteLine(degisken.ToUpper());

            // Concat
            Console.WriteLine(String.Concat(degisken,"Merhaba"));


            // Compare , CompareTo
            Console.WriteLine(degisken.CompareTo(degisken1));//0.-1,,1 // İki değişkeni karşılaştırıyor.
            Console.WriteLine(String.Compare(degisken, degisken1, true));//  True büyük küçük harf duyarlı.
            Console.WriteLine(String.Compare(degisken, degisken1, false));

            // Contains
            Console.WriteLine(degisken.Contains(degisken1));// Degiskenin içerisinde degisken1 var mı ? Varsa true dönecek.
            Console.WriteLine(degisken.EndsWith("Çakmak"));// Çakmak ile bitiyor mu ?
            Console.WriteLine(degisken.StartsWith("Rabia"));// Rabia ile başlıyor mu ?
            // Index Of
            Console.WriteLine(degisken.IndexOf("R"));//R harfini ilk bulduğu yerin index numarasını vericek.
            // Eğer bulamazsa - 1 döner.
            // Insert
            Console.WriteLine(degisken.Insert(0," merhaba")); // 0 indeksten başlayarak merhaba kelimesini ekle.
            // LastIndexOf
            Console.WriteLine(degisken.LastIndexOf("a")); // son a nın indeksini getirecek.
            // PadLeft, PadRight
            Console.WriteLine(degisken + degisken1.PadLeft(30));
            //  Remove
            Console.WriteLine(degisken.Remove(10));
            // 10 'ncu indeksten öncesini getirir.
            // Replace
            Console.WriteLine(degisken.Replace("Ra", "Za"));
          
