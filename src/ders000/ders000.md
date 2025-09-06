> Sıfırdan Java dersimize ufak bir temel atarak başlamak istiyorum.

---

## Başlıklar:

* Öncelikle Eclipse IDE arayüzünü öğrenmemiz gerekecek,

* Sonra proje oluşturacağız. Sınıf dosyalarından söz edeceğiz.

* Konsol ekranına çıktı vermeyi öğreneceğiz.

> Eclipse arayüzünü öğrenmek ve Proje oluşturmak istiyorsanız [buraya](./texts/Proje%20Oluşturma.md) tıklayınız.

> Projeye eklemenin nasıl yapıldığını öğrenmek için [buraya](./texts/Ekleme%20Yapma.md) tıklayınız.

---

## .java Dosyaları:

* kaynak kodlarını yazabilmemiz ve depolayabilmemiz için bulunan dosyalardır.

* bu dosyaları `erişim belirtkenleri` ile kullanarak modüler bir yapı elde ederiz.

* .java kaynak dosyalarını ne kadar verimli kullanabilirsek o kadar verimli programlar yazarız.

## Sınıflar:

* .java dosyaları içinde bulunur ve kodların hangi sınıfa ait olduğunu belirler.

* bir komutu, bir sınıf olmadan `yazamayız`.

        `public` ile belirtilmiş bir sınıf, mutlaka .java uzantılı dosya ismiyle aynı olmalıdır.

* Sorunsuz bir progam yazabilmek için bu gereklidir.

* bir .java uzantılı dosya içinde birden fazla sınıf bulunabilir. Bu sınıflar genellikle birbiriyle ilişkili olduğu için aynı dosyaya yazılır.

* doğru bir sistem için her sınıfa özgü dosya oluşturulması önerilir.

**Örnek kod:**

```java
// dosya adı: Main.java

public class Main {
    //kodlar buraya yazılır.
}
```

---

## main metodu:

* `Metod`, kelime anlamıyla *işlev*, *fonksiyon* anlamına gelir.

* `main` ise *ana*, *baş* gibi anlamlar taşır.

* main metodu, çalıştırılabilir bir programa nerden başlaması gerektiğini bildiren metottur.

* çalıştırılabilir bir programda main metodu bulunmadığında `hata verir`.

> Java'da main metodu şöyle tanımlanır:

```java
public class Main {
    public static void main (String[] args) {
        // çalıştırılabilir programın başlangıç noktası
    }
}
```
* şimdilik `public`, `static` gibi anahtar kelimelere takılmayın, bir kulak dolgunluğu yeterlidir.

## Algoritma akışı:

* bir algoritma akışında komutlar yurıdan aşağıya doğru akar.

* her bir komuttan sonra `;` ile işlem adımının bittiği belirtilir.

* boşluk karakteri ve satır atlama, derleyici tarafından görünmez, 

* kodun okunulabilirliği için boşlukları ve satırları iyi ayarlayın.

## Ekrana çıktı verme:

* `System.out.println();` metodu ile çift tırnak içine aldığımız metinsel ifadeleri ekrana çıktı verebiliriz.
    - `println` metodu, çıktıyı konsola verdiktan sonra imleci bir satır aşağı kaydırır.
    - `print` metodu ise imleci olduğu yerde tutar.

```java
class Main {
    public static void main (String[] args) {
        System.out.println("Merhaba Java severler !");
        System.out.print("Merhaba");
        System.out.print("Ben Berat");
    }
}

/*      ÇIKTI:
Merhaba Java severler !
MerhabaBen Berat

*/
```

* şeklinde ilk çalıştırılabilir kodu oluşturmuş bulunmaktayız.

> .java dosyalarındaki örnek kodlara bakmayı unutmayınız.

**Author:** Berat Kurt

![Horse Reaction](./images/horse-stare.gif)