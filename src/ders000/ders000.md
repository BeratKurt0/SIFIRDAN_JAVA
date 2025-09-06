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

* her bir komuttan sonra `;` ile işlem adımının bittiği belirtilir.

* boşluk karakteri ve satır atlama, derleyici tarafından görünmez, 

* kodun okunulabilirliği için boşlukları ve satırları iyi ayarlayın.

## Ekrana çıktı verme:

* `System.out.println("metinsel ifade");` ile çift tırnak içine aldığımız metinsel ifadeleri ekrana çıktı verebiliriz.

```java
System.out.println("Hello World !");
```

> Örnek kodlara bakmayı unutmayınız.

**Author:** Berat Kurt