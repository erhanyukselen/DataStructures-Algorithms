# DataStructures-Algorithms

## Data Structures and Algorithms

* Algoritma:Belirli bir durumdan başlayıp belirli bir sonuçta biten pronlemlere çözüm getiren adımlardır.
* Bilgisayar hafızasında 1 kutucuk 1 byte yer tutar. 8 bit 1 byte'a eşittir.
* Recursion:Bir problemin alt problemlere bölünüp hesaplanmasına, nerede son bulacağını belirttiğimiz ifadelere recursion(özyineleme) denir.
* Array:Bir elemana erişmek istediğimizde anında erişebiliriz fakat yeni bir eleman geldiği zaman bütün elemanları başka bir yere taşımamız gerekebiliyor.
* Linked List:Yan yana zorunluluğu olmadan veri tutmamızı sağlayan yapı. Elemanlar hafıza içerisinde dağınık şekilde bulunabilir,
son gelen eleman kendinden bir önceki elemana adresini bildirmek zorundadır.
* Stack Lifo mantığı ile çalışır. Push bu yığına eleman eklmeye, Pop bu yığından eleman çıkarmaktır.
* Queue Fifo mantığı ile çalışır. Enqueue yeni eleman eklemek, Dequeue eleman çıkarmak.
* Hash Table: Etiketiyle birlikte getirilen ürünlere Hush Table denir. Arraylerle kullanılır.
* Collision: Hush function farklı iki değerden aynı sayı üretilirse bu duruma rastlanır çarpışma olarak adlandırılır.
* Big O Notation iki farklı arama yönteminde A algoritması sayfa sayfa, B algoritması yarıya bölüp tarıyor. B daha hızlı çalışır.
* Sorting:Bir eleman dizisini belirli sıralama kurallarına göre sıralama yapar. (Alfabetik, artan, azalan)
* Searhing:Bu yöntemi kullanarak elemanlarımızı sıraladık. Bunun sebebi elemean ararken işimizin kolaylaşması.
* Closest Pair:Birbirine yakın sayıları gruplandırdık ki arama yaparken zamanımızı efektik şekilde kullanabilelim.
* Linear search, tek tek elemanları dolandıktan sonra istediğim elemanın olup olmadığına bakmaktır.
* Binary Search, ikili arama algoritması, diziyi her seferinde ikiye bölerek ikili arama yapar.
* Binary Search Tree Bir düğüm her iki tarafa da referans verebiliyor. Sağ ve sol olarak. Sağ tarafından kendinden büyük elemanlar, sol tarafında ise kendinden küçük elemanlar bulunacak.
* Değişkenler bizim uygulama geliştirirken kullandığımız veri tutucularımızdır. Kullandığımız verinin tipine ve büyüklüğüne bağlı olarak doğru veri tipini seçiyor olmak önemlidir. 
* Uygulama içerisinden bir atama işlemi yada durum karşılaştırması yapmak istediğimizde operatörleri kullanırız. 
* Atama ve İşlemli Atama Operatörleri (=, +=, -=, *=, /=) 
* Mantıksal Operatörler (||, &&, !)
* İlişkisel Operatörler (==,!=, <, >, >=,<=)
* Aritmetik (+, -, *, /, %, ++, --)
* Closest Pair: Birbirine yakın sayıları gruplandırırız ki arama yaparken zamanımızı efektif şekilde kullanalım.
* Mode bulma: Eleman dizisini search ettikten sonra elemanların yan yana olanları sayarak daha hızlı mod bulunabilir.
* Insertion Sort: Liste içerisindeki elemanları küçükten büyüğe sıralarken küçük ile büyüğün yerini değiştirerek ilerler.
* Merge Sort: Listeyi ikiye bölerek başlar, tek eleman kalana kadar ikiye bölüyoruz. Kalan tek elemanları küçükten büyüğe gidicek şekilde sıralıyoruz.
* Quick Sort: Bir pivot seçerek kalan elemanları sağona soluna büyük küçüklüğüne göre sıralıyoruz. Worst case O(n^2) average O(nlogn)
* Binary Search: daha hızlıdır. O(logn)
* Wi-Fi (Wireless Fidelity) 
### Tip Dönüşümleri
Bir değişken tanımlaması yaptığımızda bellekten o değişkenin tipine bağlı olarak bir alan tesis etmiş oluruz. Dolayısıyla tanımladığımız bu değişkene farklı veri tipinde bir değer atanması bellekte işlerin karışmasına neden olabilir. Çoğu zaman uygulama yazarken farklı veri tipleri ile çalışmak durumunda kalabiliriz. Bellekte işleri yoluna koyabilmek için bu tip durumlarda tip dönüşümü yapmamız gerekir.

Tip dönüşümleri 2 şekilde yapılabilir.

Implicit Conversion (Bilinçsiz ya da kapalı dönüşüm)
Explicit Conversion (Bilinçli ya da açık dönüşüm)

### IF-ELSE
 bool condition = true;

if (condition)

{

    Console.WriteLine("Değişken: true");
    
}

else

{

    Console.WriteLine("Değişken: false");
    
}
