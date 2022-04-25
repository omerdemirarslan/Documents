# Informations For Interview

### - What Is The Python?

---
---

### - What Is The Paradigm?

---
---

### - What Paradigms Can You Implement In Python?

---
---

### - What Is The Django?

---
---

### - How Extends Django To Django REST Framework?

---
---

### - What Is The MVT (Model View Template) In Django?

---
---

### - How To Ensure Database Conneciton In Django?

---
---

### - What Is The Middleware In Django and How Is It Work?

---
---

### - What Is The ORM (Object Relational Mapping)?

---
---

### - For What Purpose Do We Use Q and F Objects In Django ORM?

---
---

### - What Is The App In Django?

---
---

### - What Are Select Related and Prefetch Related?

---
---

### - What Is The REST API?

---
---

### - Explaning HTTP and HTTPS. What Is Dıfference Beetwen Them?

---
---

### - What Is The HTTP Methods?

---
---

### - What Is Work A Website?

---
---

### - How Is WSGI Works?

---
---

### - What Is Celery and How Is IT Works?

---
---

### - What Is The REDIS?

---
---

### - What Is The RabbitMQ?

---
---

### - What Is The Container Scheduler?

---
---

### - What Is The Kuberetes?

---
---

### - What Are TCP and UDP? Can You Explain Difference Beetwen Them?

---
---

### - What Is The Catastrophic Modelling?

---
    * Katastrofik: Çok kötü bir olay anlamına gelir. Günümüzde, günlük yaşam içerisinde yaşanabilecek; çok büyük bir afet,
        sağlık sektöründe yaşanan büyük bir maddi zorluk veya global alanda yaşanabilecek ekonomik bir problem ve buna
        bağlı olarak İş Durma Riski ni de ifade eder.
---

### - What Is The Reinsurance?

---
    * Bir sigorta ortaklığının, sigorta ettiği miktarın bir bölümünü, ilerde doğabilecek bir zarara karşı, başka bir 
        sigorta ortaklığına yeniden sigorta ettirmesi işi.
---

### - What Is The Unit Test?

---
    * Bir yazılımın en küçük biriminin tek başına test edilmesidir. Bu birim gerek bir fonksiyon, gerek bir fonksiyonun 
        içindeki küçük bir iş yapan kod bloğu olabilir.
        Örneğin; bir fonksiyona gönderilen parametrenin type nın kontrol edilmesi. Save işlemi sonrasında bir get işlemi
        sonrasında bu alanın True/False gelip gelmeme durumu.
        Response da gelen kritik alanlardaki değerlerin eşitlik kontrolünün sağlanması.

        Unutulmamalıdır ki projede unit testler başarı ile çalışıyor olasa dahi, bu durum ürünün son kullanıcı tarafında
        da sorunsuz çalıştığı anlamına gelmez.
        Servislerde yaşanan problemler, entegrasyonların çökmesi gibi durumlarda yapılan testin başarılı olup olmaması
        sonucu değiştirmez.
---

### - What Is The Integration Test?

---
    * Dört temel test seviyesi vardır:
        Unit Testing            - Birim Testi
        Integration Testing     - Entegrasyon Testi
        System Testing          - Sistem Testi
        Acceptance Testing      - Kabul Testi

    * Integration Testing:
        Birim testlerdeki tüm küçük işlemlerin birleşik bir durumda nasıl çalıştığını tespit etmek için yapılan testtir.
        Ayrıca, iki farklı modülün senkronize çalışıp çalışmadığını durumu da kontrol etmek için kullanırız.
        Örneği, E-Ticaret markamıza ait ürünlerin satıldığı farklı bir satış kanalının entegre olduğu bir durumu; yani
        satış kanalına ait servislerin çalışırlığını; buradan gelen siparişlerin doğru bir şekilde akıp akmadığı gibi
        durumları da kontrol etmek için entegraston testi kullanabiliriz.
---


### - What Is The Software Architecture?

---
    * Mimari:
        Sistemin temel organizasyonuna ait somutlaşmış bileşenlerinin birbirleriyle, çevreleri ile ilişkilerinde,
        tasarımına ve gelişimine yol gösteren prensiplerdir. Yazılımı oluşturmadan önce; önden verilmiş kararları ifade
        eder.
        Bazan yazılı yazarken mimariyi oluştururuz mantığı da vardır. Buna evrimsel mimari denir. Türkçedeki karşılığı ise
        "kervan yolda düzülür" dür. Bu çok risklidir tabii.
---

### - What Is The RESTAPI Type In Python?

---
---

### - What Is The multithreading?


---
    Programın çalışması tek bir process üzerinden sağlanırken, bu process üzerinde birden fazla işlem parçacığı
    çalışmaktadır. Process üzerinde çalışan bu çoklu işlem parçacıkları, asenkron olarak farklı görevleri yerine getirmek 
    için kullanılırlar. Bu sayede birbirlerini beklemesi gerekmeyen işlemlerin, tek bir process üzerinde asenkron olarak 
    gerçekleştirilmeleri sağlanır ve performans arttırılmış olur.
---

### - What Is The Multiprocessing?

---
    Multiprocessing ise çoklu process anlamına gelmektedir. Programın çalışması için birden fazla işlem çalışmaktadır.
    Bu işlemler farklı kaynakları kullanmaktadır. Farklı işlemlerin kullanımından kaynaklı programın işlem gücü artmaktadır. 
    Farklı kaynakların kullanılmasıyla programın performansı arttırılmış olur.
---

### - What Is The Docker?

---
    Container teknolojisi olarak docker; aynı işletim sistemi üzerinde, birden çok container yaratarak sanallaştırma
    sağlayan teknolojidir. Uygulamalarımızın kolay kurulumunu, testini, çalışmasını ve deployment ını sağlar.
---

### - What Is The Container?

---
    Docker Daemon tarafından Linux çekirdeği içerisinde birbirinden izole olarak çalıştırılan process’lerin her birine 
    verilen isimdir. Virtual Machine (Sanal Makina) analojisinde Docker’ı Hypervisor’e benzetirsek fiziksel sunucu üzerinde
    halihazırda koşturulmakta olan her bir işletim sisteminin (sanal sunucunun) Docker’daki karşılığı Container’dır.
---


### - What Is The Container Scheduler?

---
---

### - What Is Load Balancing?

---
---

### - What Is CI / CD?

---
    * CI -> Continuous Integration / Sürekli Entegrasyon
        Sürekli entegrasyon, geliştirme ekiplerini sık sık küçük değişiklikler yapmaya ve koddan sürüm kontrol
        havuzlarına giriş yapmaya yönlendiren bir kodlama felsefesi ve uygulamalar dizisidir.
        
        Yazılım geliştirme değişikliklerini sürekli olarak entegre etmek için otomatikleştirilmiş bir süreçtir.
        Süreçleri, kaynak kodun oluşturulmasını, test edilmesini ve doğrulanmasını otomatikleştirir.

    * CD -> Continuous Delivery    / Sürekli Teslim
        Sürekli teslimin amacı, paketlenmiş bir yapıyı üretim ortamına teslim etmektir.  CD, dağıtım süreci de dahil
        olmak üzere tüm teslimat sürecini otomatikleştirir.

        CD sorumlulukları, altyapı sağlamayı, değişiklikleri yönetmeyi (biletleme), yapıtları dağıtmayı, bu değişiklikleri
        doğrulamayı ve izlemeyi ve herhangi bir sorun varsa bu değişikliklerin gerçekleşmemesini sağlamayı içerebilir.
    
    * CI/CD Uygulama geliştirme ekiplerinin kod değişikliklerini daha sık ve güvenilir bir şekilde sunmasını sağlayan
        bir kültürü, çalışma ilkelerini ve uygulamalar koleksiyonunu içerir.
---

### - What Is PostGIS?

---
    PostGIS, GIS (Coğrafi Bilgi Sistemleri – CBS) nesnelerinin veritabanında depolanmasına izin veren bir PostgreSQL
    veritabanı uzantısıdır (extension). Tamamen ücretsizdir ve açık kaynak kodludur. PostGIS, GiST tabanlı R-Tree uzamsal
    dizinleri için destek ve GIS nesnelerinin analizi ve işlenmesi için işlevler içerir. GIS nesnelerinin analizi ve işlenmesi için fonksiyonlar içerir.
---

### - Explaining Object Oriented Programming?

---
    
---

### - Explaning Object Oriented Programming's Basic Properties?

---
    
---

### - What Is The SOLID Prinsibles?

---
    * Single Responsibility Principle – Tek Sorumluluk Prensibi
        Class ya da metodun sadece tek bir sorumluluğu olmalı demektedir
    * Open/Closed Principle – Açık / Kapalı Prensibi
        Projemizde yazmış olduğumuz kodlarımızın geliştirilmeye açık fakat değişime kapalı olması durumudur
    * Liskov ‘s Substitution Principle – Liskov’un Yerine Geçme Prensibi
        Bir class’ın başka bir class’a ait özellikleri miras alma (Inheritance) durumunda, miras alınan class’ın bütün
        özelliklerinin ve metotlarının kullanılmasını ifade eder. 
    * Interface Segregation Principle – Arayüz Ayrımı Prensibi
        Arayüzlerimizde gerekli olmayan eklentileri kullanmamayı ifade etmektedir
    * Dependency Inversion Principle – Bağımlılığın Ters Çevirme Prensibi
        Üst sınıf ve metotların altsınıf ve metotlara bağımlı olmama durumudur
---

### - What Is The PEP8?

---
    Python Enhancement Proposal - Python Geliştime Önerisi
---

### - What Is The Clean Code?

---
    
---

### - What Is The Agile Methodology ?

---
    
---
