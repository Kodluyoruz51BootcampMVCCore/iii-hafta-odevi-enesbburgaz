## III. Hafta Ödevleri:
- [ ] Task vs process- task vs Thread vs .. ve c# task vs thread vs .. kıyaslamalarını ve task haricinde diğer yöntemler nelerdir araştırınız.
- [ ] Extension Nedir? --> Extra paket ekleme.
- [ ] SQLite, bunu doğru şekilde (en güncel yol ile) nasıl kullanmalıyız? (Aktif halde kullanıp uygulama)

#### Task ve Thread Nedir? Farklılıkları Nelerdir?
Thread: Thread yapıları işletim sistemi işlemlerine benzemektedir. OS içerisinde işlemler birbirine paralel olarak çalışmaktadır. Thread yapısında ise, threadler bir process içerisinde birbirlerine paralel olarak çalışmaktadırlar. İşlemler birbirlerine tamamen izoledir. Threadler birbirlerine tamamen izole değillerdir. Aynı hafızayı paylaşırlar bundan dolayı birlikte çalışan threadler arasından veriler rahatça paylaşılmaktadır.
Task:Async programlama ile daha sıklıkla kullanılan Task yapısı thread yapısına göre üst seviyede. Task yapısını kullanarak daha gelişmiş işlemler yapabiliriz. Thread pooling yapısını otomatik olarak kullanıp birbiri ardına eklenebilecek olan işlemleri daha iyi organize etmektedir.

#### Extension Nedir?
Nesne yönelimli bilgisayar programlamasında, bir genişletme yöntemi, orijinal nesne derlendikten sonra bir nesneye eklenen bir yöntemdir. Değiştirilen nesne genellikle bir sınıf, bir prototip veya türdür. Genişletme yöntemleri bazı nesne yönelimli programlama dillerinin özellikleridir.

#### SQLite kullanımı
Bu [link üzerinden](http://bekenty.com/use-sqlite-in-net-core-3-with-entity-framework-core/) inceleyebilirsiniz.
