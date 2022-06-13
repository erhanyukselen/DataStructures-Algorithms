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
* LAN (Local Area Network)
* WAN (Wide Area Network)
* DNS (Domain Name Server)
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

### Inheritance (Kalıtım) 
* Bir sınıfın başka bir üst sınıftan miras almasına kalıtım denir. Miras veren sınıf tüm özelliklerini alt sınıfa aktarmış olur.
* Sözdizimi : <code> Kalıtım Alacak Alt Sınıf : Miras Verecek olan Üst Sınıf </code>
* Her sınıf kendi kalıtım aldığı sınıfın metotlarına erişebiliyor. Çünkü üst sınıfından belirli davranışları miras almıştır.

### Polymorphism (Çok Biçimcilik)
* Çok biçimcilik ile birlikte hayatımıza sanal yani virtual metotlar giriyor. Virtual metotlar ile nesne yönelimli programlama ilkesi olan polymorphism'i uygularız. Sanal metotlar kalıtım alınan yani miras veren sınıf içerisinde yazılan ve daha sonra alt sınıflarda yeniden yazılabilen metotlardır. Bunu da virtual ve override anahtar kelimeleri sağlar.

### Interface (Arayüzler)

* Interface yani arayüzler nesneye dayalı programlamanın önemli özelliklerinden biridir. Sınıfların içermesi gereken metotların imzalarının yer aldığı, özelliklerin tanımlandığı bir taslak gibi düşünebiliriz.
* Kesin belirlenmiş bir kural olmamasıyla beraber interface isimleri "I" ile başlar. I ile başlayan bir isim gördüğümüzde kolaylıkla bunun bir arayüz olduğunu anlarız. Dolayısıyla standartlara bağlı kalmakta fayda var.
* Interface içerisindeki property'lere bir değer ataması yapılmaz, metotların ise gövdesi yazılmaz. Sadece implemente eden sınıfın ne iş yaptığının bir arayüzüdür interface'ler. Ve bir sınıf aynı anda birden fazla arayüzden kalıtım alabilir.
* Peki interface'lere neden ihtiyaç duyarız? Kalıtım alan sınıfın sorumluluğunun çerçevesinin çizilmesine yardımcı olur diyebilir. Aynı sorumluluğu başka bir yoğurt yiyiş tarzıyla yapması gereken bir sınıf geldiğinde aynı interface den kalıtım alır ama yapacağı işi farklı şekilde yapar.

### Abstract Class
* Abstract class ları sadece kalıtım için kullanılan sınıflar gibi düşünebilirsiniz. Bazı özellikleri ile sınıflara benzerlerken bazı özellikleriyle arayüzlere benzerler. Abstract sınıfları arayüz ve virtual metotların birleşimi gibi davranış gösterirler.
## Abstract sınıfların özellikleri

* Normal sınıflar gibi new() anahtar kelimesi ile türetilemezler.
* Interface ler gibi metot bildirimi yapabilirsiniz.
* Sanal metotları override eder gibi abstract metotlar override edilebilir.
* Abstract metotların gövdesi yazılamaz.
* Bir abstract class bir abstract metot içeriyorsa, abstract sınıftan türeyen tüm sınıflar bu metodu override etmek zorundadır.
* Bir sınıf sadece tek abstract sınıftan kalıtım alabilir.
* Abstract sınıf başka bir abstract sınıftan kalıtım alabilir. Dolaylı olacak türeyen sınıfta birden fazla abstract dan kalıtım almış olur. Ve bağlantılı olduğu tüm abstract sınıfların bildirimi yapılmış olan abstract metotlarını override etmek zorundadır.
* ÖNEMLI: Abstract sınıf içerisinde metot bildirimi yapabilmek için metodun erişim belirtecinden sonra "abstract" anahtar kelimesi mutlaka yazılmalıdır.
* ÖNEMLI: Abstract metotdan türetilmiş sınıf içerisinde abstract metodun kullanılabilmesi için de override anahtar kelimesinin kullanılması gerekir.

## Nesne Yönelimli Programlama Nedir ?
Nesne Yönelimli Programlama (Object Oriented Programming), sınıflar ve nesneler kavramına dayanan bir programlama yaklaşımıdır. Bu yaklaşımın amacı, ihtiyaç duyulan programı daha küçük parçalara bölerek, yönetilebilir ve yeniden kullanılabilir hale getirmektir. Her küçük parçanın kendine ait özelliği, verileri ve diğer küçük parçalarla nasıl iletişim kuracağı bilgileri bulunur.

## Sınıf(Class) Nedir ?
NYP sınıflar ve nesneler üzerine kurulmuştur, "Sınıflar" bir problemi soyutlamak ve genelleştirmek için kullanılan yapılardır veya kılavuzlardır. Sınıflar, bir nesneye ait tüm özellikleri temsil eder. Bu özellikler nesnenin ne tür nitelikleri ve davranışları olacağını belirler.

Mesela "Araba" bir sınıftır. Arabalara ait nitelikler renk, hız, vites sayısı, yakıt türü vb. bir sürü nitelik olabilir. Park sensörü, oto pilot, hız sabitleme gibi arabaların kendilerine özel davranışları da olabilir. Bir araba üretilirken, bir yapım kılavuzuna ihtiyaç vardır. Programlama da bu kılavuzlara "Sınıf (Class)" denir.

## UML ve Sınıf Diyagramları
Modelleme Nedir ?
Gerçek hayattaki problemleri bilgisayarın sanal ortamında çözebilmek için, her şeyden önce problemin uygun şekilde bilgisayar ortamına aktarılması gerekmektedir. Bu işlem “soyutlama (abstraction)” ya da “modelleme (modeling)” olarak anılır.

Modelleme, insanın problem çözmek üzere eskiden beri kullandığı bir yöntemdir. Büyükçe bir problemin tamamını zihinde canlandırıp çözmeye çalışmak yerine, oluşturulacak model ya da modeller üzerinde hedef sistemin görünüşü, davranışı ya da bazı durumlarda verdiği tepkiler gözlemlenebilir


## UML (Unified Modeling Language) Nedir ?
UML’ in Türkçe deki karşılığı “Birleşik Modelleme Dili” olsa da aslında bir programlama dili değil yazılım mühendisliğinde nesne tabanlı modellemede kullanılan standart olmuş görsel modelleme dilidir. Bir yazılımın hayata geçirilmesinde farklı görev tanımlamaları bulunmaktadır (Tasarımcılar, programcılar, analistler, testçiler, kalite sorumluları, kullanıcılar) gibi. Bir yazılım için her kişinin farklı bakış açısı vardır. Müşteri açısından projeye baktığımızda müşteriyi işlerin sıralandırılması, sisteme artıları ve eksileri , işler arasındaki ilişkiler ilgilendirirken bir fonksiyonun detayları ilgilendirmemektedir. Analist açısından baktığımızda nesne özellikleri, fonksiyonlar ve alacakları parametreler yeterli iken tasarımcı açısından parametrelerin veri tipleri, fonksiyonun performansı, yaşam süresi gibi bilgiler de önemli olmaktadır.

## Sınıf Diyagramları (Class Diagram)
Nesne yönelimli programlamada her bir nesnenin konseptini belirten yapılara sınıf (class) adı verilmektedir. Sınıflar çok farklı yapılarda ve işlevlerde olabilirler. Bununla birlikte, genellikle programlamada bütün iş tek bir sınıfın üzerine yüklenmez. Kuracağınız sistem ile ilgili önce temel sınıflar belirlenip daha sonra bunlar arasındaki bağlantıların açıklanması gerekir. Bunu bir yazılım geliştirme sürecinin tasarım aşamasında yaparız. Burada sınıfların modellemesi için UML kullanırız ve Sınıf Diyagramları adı veririz.

Programlamada sınıfların niteliklerini "değişkenler" , davranışlarını da "metotlar" tanımlar.
