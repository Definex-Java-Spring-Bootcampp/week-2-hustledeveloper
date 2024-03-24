[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/A05Yfs1j)
# 2.Hafta Ödevi


<details>
<summary> 1. Senkron ve Asenkron iletişim nedir örneklerle açıklayın? `(10 PUAN)`
 </summary>

Senkron İletişim:

Senkron iletişimde, bir taraf diğer taraftan yanıt alana kadar bekler. Bu, bir telefon görüşmesi veya bir sohbet uygulaması gibi gerçek zamanlı iletişimde yaygın olarak kullanılır.

Örnek:

Bir müşteri mağazaya girer ve kasiyerle konuşur.
Bir öğrenci sınıfta öğretmene soru sorar.
Asenkron İletişim:

Asenkron iletişimde, bir taraf mesajı gönderir ve yanıt için beklemez. Alıcı mesajı daha sonra alır ve yanıt verir. E-posta veya anlık mesajlaşma gibi gecikmeli iletişimde yaygın olarak kullanılır.

Örnek:

Bir müşteri bir mağazaya e-posta gönderir ve birkaç saat sonra yanıt alır.
Bir öğrenci öğretmene e-posta gönderir ve öğretmen ertesi gün yanıt verir.
Senkron ve Asenkron İletişimin Avantajları ve Dezavantajları:

Senkron İletişim:

Avantajlar:

Daha hızlı ve daha duyarlıdır.
Gerçek zamanlı geri bildirim sağlar.
Sorunları daha hızlı çözmek için kullanılabilir.
Dezavantajlar:

Her iki taraf da aynı anda müsait olmalıdır.
Gecikmelere karşı hassastır.
Daha karmaşık ve zorlayıcı olabilir.
Asenkron İletişim:

Avantajlar:

Daha esnek ve rahattır.
Her iki tarafın da aynı anda müsait olması gerekmez.
Gecikmelere karşı daha toleranslıdır.
Daha basit ve daha az zorlayıcı olabilir.
Dezavantajlar:

Daha yavaş ve daha az duyarlı olabilir.
Gerçek zamanlı geri bildirim sağlamaz.
Sorunları çözmek daha uzun sürebilir.
Hangi Tür İletişim Kullanılmalı?

Kullanılacak iletişim türü, duruma ve ihtiyaçlara bağlıdır. Gerçek zamanlı iletişim ve hızlı yanıt gerektiren durumlarda senkron iletişim tercih edilir. Daha esnek ve rahat bir iletişim şekli gerektiren durumlarda asenkron iletişim tercih edilir.
</details>



<details>
<summary> 2. RabbitMQ ve Kafka arasındaki farkları araştırın? `(10 PUAN)` </summary>


RabbitMQ ve Kafka Arasındaki Farklılıklar
RabbitMQ ve Kafka, mesajlaşma için kullanılan iki popüler platformdur. Her ikisinin de kendine özgü avantajları ve dezavantajları vardır.

Mesaj Teslimi:

RabbitMQ: RabbitMQ, mesaj teslimi için üç farklı garanti seviyesi sunar: en az bir kez, tam olarak bir kez ve en fazla bir kez.
Kafka: Kafka, mesaj teslimi için tam olarak bir kez garanti sunar.
Ölçeklenebilirlik:

RabbitMQ: RabbitMQ, yatay olarak ölçeklenebilir, bu da daha fazla işlemci ve bellek ekleyerek daha fazla yük kaldırabileceği anlamına gelir.
Kafka: Kafka, hem yatay hem de dikey olarak ölçeklenebilir.
Performans:

RabbitMQ: RabbitMQ, düşük gecikme süresi ve yüksek mesaj işleme hızı sunar.
Kafka: Kafka, RabbitMQ'dan daha yüksek mesaj işleme hızı sunabilir, ancak gecikme süresi daha yüksek olabilir.
Kullanım Alanları:

RabbitMQ: RabbitMQ, mikro hizmetler, e-ticaret ve oyun gibi çeşitli alanlarda kullanılır.
Kafka: Kafka, büyük veri akışı işleme, log toplama ve veri akışı gibi alanlarda kullanılır.

</details>



<details>
<summary> 3. Docker ve Virtual Machine nedir? `(5 PUAN)` </summary>

Docker ve Virtual Machine (VM), uygulamaları çalıştırmak için kullanılan sanallaştırma teknolojileri olsa da, aralarında bazı temel farklılıklar vardır.

Sanallaştırma Nedir?

Sanallaştırma, fiziksel bir sunucunun donanım kaynaklarını (CPU, bellek, disk) birden fazla sanal ortama ayırarak birden fazla işletim sistemi ve uygulamayı çalıştırma yeteneğidir.

Virtual Machine (VM):

Tanım: Bir VM, fiziksel bir makinenin yazılımsal bir öykünmesidir.
Nasıl Çalışır? Bir VM, kendi işletim sistemine, uygulamalarına ve dosyalarına sahip ayrı bir ortamdır. Bu işletim sistemi, bir hypervisor adı verilen yazılım tarafından yönetilen altta yatan fiziksel donanımın üzerinde çalışır.
Avantajları:
İzolasyon: Farklı VM'ler birbirlerinden izole edilmiştir, bu nedenle bir VM'deki bir sorun diğerlerini etkilemez.
Esneklik: Farklı işletim sistemlerini aynı fiziksel sunucuda çalıştırabilirsiniz.
Taşınabilirlik: VM'ler kolayca taşınabilir, farklı fiziksel veya sanal sunuculara aktarılabilir.
Dezavantajları:
Yüksek kaynak kullanımı: Her VM kendi işletim sistemine sahip olduğundan, fiziksel donanım kaynaklarını daha fazla tüketir.
Yavaş başlangıç: Bir VM, fiziksel bir makineden daha yavaş başlatılır.
Karmaşık yönetim: Birden fazla VM'yi yönetmek karmaşık olabilir.

Docker:

Tanım: Docker, konteyner adı verilen uygulamaları çalıştırmak için hafif ve taşınabilir bir sanallaştırma teknolojisidir.
Nasıl Çalışır? Docker konteynerleri, işletim sistemi çekirdeğini paylaşır, ancak her konteynerin kendi dosya sistemi ve uygulamaları vardır. Bu, VM'lere kıyasla daha az kaynak tüketimi sağlar.
Avantajları:
Hafiflik: Docker konteynerleri, VM'lerden daha hafiftir ve daha hızlı başlatılır.
Hızlı başlangıç: Konteynerler, işletim sistemi çekirdeğini paylaştığından hızla başlatılır.
Kaynak verimliliği: Konteynerler, VM'lerden daha az kaynak tüketir.
Taşınabilirlik: Docker konteynerleri, farklı ortamlara kolayca taşınabilir.
Dezavantajları:
İzolasyon: Konteynerler VM'ler kadar izole edilmemiştir, bu nedenle bir konteynerdeki bir sorun diğerlerini etkileyebilir.
Donanım erişimi sınırlı: Konteynerlerin doğrudan donanım kaynaklarına erişimi yoktur.


</details>


<details>
<summary> 4. Docker ile RabbitMQ ve PostgreSQL ve ya MySQL kurulumu yapın? `(5 PUAN)` </summary>

Docker ile rabbitmq ve database kurulumu için docker-compose.yml dosyası

```YML
version: '3.1'

services:
   mysql-db:
      image: mysql:latest
      container_name: mysql-container
      ports:
         - "3307:3306"
      environment:
         MYSQL_ROOT_PASSWORD: your_root_password
         MYSQL_DATABASE: jwt
         MYSQL_USER: myuser
         MYSQL_PASSWORD: pass
      volumes:
         - mysql-data:/var/lib/mysql
   rabbitmq:
      image: "rabbitmq:management"
      container_name: "rabbitmq-container"
      environment:
         - RABBITMQ_DEFAULT_USER=guest
         - RABBITMQ_DEFAULT_PASS=guest
      ports:
         - "5672:5672"  # AMQP port
         - "15672:15672" # RabbitMQ Management UI port
      networks:
         - my-network

volumes:
   mysql-data:
networks:
   my-network:
      driver: bridge


```

</details>


<details>
<summary> 5. Docker komutlarını örneklerle açıklayın. `(5 PUAN)`
 </summary>


Docker Komutları ve Örnekleri
Docker, konteynerleri oluşturmak, yönetmek ve çalıştırmak için kullanılan bir platformdur. Docker komutları, bu işlemleri gerçekleştirmek için kullanılır.

Bazı temel Docker komutları ve örnekleri:

1. docker run:

Bir konteyneri çalıştırır.
Örnek: docker run hello-world
2. docker pull:

Bir görüntüyü Docker Hub'dan indirir.
Örnek: docker pull nginx
3. docker push:

Bir görüntüyü Docker Hub'a yükler.
Örnek: docker push my-image
4. docker build:

Bir Dockerfile'ı kullanarak bir görüntü oluşturur.
Örnek: docker build -t my-image .
5. docker ps:

Çalışan konteynerlerin bir listesini gösterir.
Örnek: docker ps
6. docker stop:

Bir konteyneri durdurur.
Örnek: docker stop my-container
7. docker rm:

Bir konteyneri siler.
Örnek: docker rm my-container
8. docker images:

Yerel depoda bulunan görüntülerin bir listesini gösterir.
Örnek: docker images
9. docker rmi:

Yerel depoda bulunan bir görüntüyü siler.
Örnek: docker rmi my-image
10. docker logs:

Bir konteynerin günlüklerini gösterir.
Örnek: docker logs my-container
</details>


<details>
<summary> 6. Microservice ve Monotlith mimarilerini kıyaslayın. `(15 PUAN)`
 </summary>

Microservice ve Monolith Mimarilerinin Karşılaştırması

Microservice Mimari:

Tanım: Bir uygulamayı, her biri kendi özel işlevini yerine getiren küçük, bağımsız hizmetlerden oluşan bir koleksiyona bölen bir mimari stildir.
Avantajları:
Ölçeklenebilirlik: Her hizmet bağımsız olarak ölçeklendirilebilir.
Geliştirilmiş dağıtım: Hizmetler bağımsız olarak geliştirilebilir ve dağıtılabilir.
Hata toleransı: Bir hizmet arızalanırsa, diğer hizmetler etkilenmez.
Teknoloji çeşitliliği: Farklı hizmetler için farklı teknolojiler kullanılabilir.
Dezavantajları:
Karmaşıklık: Birden fazla hizmetin yönetilmesi ve koordine edilmesi karmaşık olabilir.
Ağ trafiği: Hizmetler arasında iletişim kurmak için daha fazla ağ trafiği gerekir.
Güvenlik: Her hizmetin güvenliğini ayrı ayrı yönetmek gerekir.

Monolith Mimari:

Tanım: Tüm uygulama işlevselliğini tek bir büyük birimde birleştiren bir mimari stildir.
Avantajları:
Basitlik: Geliştirmesi ve yönetmesi daha basittir.
Daha az ağ trafiği: Tüm işlevsellik tek bir birimde olduğundan daha az ağ trafiği gerekir.
Daha hızlı geliştirme: Tek bir kod tabanı ile geliştirmek daha hızlıdır.
Dezavantajları:
Ölçeklenebilirlik: Monolit uygulamalar ölçeklendirmek zordur.
Geliştirme zorluğu: Büyük bir kod tabanı ile geliştirmek zor olabilir.
Hata toleransı: Bir hata tüm uygulamayı etkileyebilir.
Teknoloji kısıtlaması: Tüm uygulama için tek bir teknoloji kullanılmalıdır.
</details>


<details>
<summary> 7. API Gateway, Service Discovery, Load Balancer kavramlarını açıklayın. `(10 PUAN)`
 </summary>

API Gateway, Service Discovery ve Load Balancer Kavramları
API Gateway:

Tanım: Farklı hizmetler tarafından sunulan API'lere tek bir erişim noktası sağlayan bir sistemdir.
Avantajları:
Güvenlik: API'leri tek bir noktada güvenli hale getirebilirsiniz.
Gözlemleme: API'lerin kullanımını izleyebilirsiniz.
Sürüm kontrolü: API'lerin farklı sürümlerini yönetebilirsiniz.
Yük devretme: Farklı hizmetlere yükü dengeleyebilirsiniz.
Dezavantajları:
Karmaşıklık: Ek bir karmaşıklık katmanı ekleyebilir.
Tek hata noktası: API Gateway arızalanırsa tüm API'ler etkilenir.

Service Discovery:

Tanım: Bir ağdaki hizmetlerin konumunu ve özelliklerini otomatik olarak bulma ve kaydetme işlemidir.
Avantajları:
Hizmetlerin otomatik olarak bulunması: Hizmetlerin IP adreslerini ve port numaralarını manuel olarak yönetmeniz gerekmez.
Yüksek kullanılabilirlik: Bir hizmet arızalanırsa, Service Discovery otomatik olarak başka bir hizmete yönlendirebilir.
Yük devretme: Farklı hizmetlere yükü dengeleyebilirsiniz.
Dezavantajları:
Karmaşıklık: Ek bir karmaşıklık katmanı ekleyebilir.
Bağımlılık: Service Discovery'nin arızalanması tüm hizmetleri etkileyebilir.

Load Balancer:

Tanım: Birden fazla sunucuya gelen trafiği dağıtarak tek bir sunucunun aşırı yüklenmesini önleyen bir sistemdir.
Avantajları:
Performans: Tek bir sunucunun aşırı yüklenmesini önleyerek performansı artırır.
Yüksek kullanılabilirlik: Bir sunucu arızalanırsa, Load Balancer otomatik olarak trafiği diğer sunuculara yönlendirebilir.
Ölçeklenebilirlik: Daha fazla sunucu ekleyerek sistemi kolayca ölçeklendirebilirsiniz.
Dezavantajları:
Karmaşıklık: Ek bir karmaşıklık katmanı ekleyebilir.
Maliyet: Ek bir maliyet oluşturabilir.
</details>


<details>
<summary> 8. Hibernate, JPA, Spring Data framework’lerini örneklerle açıklayın. `(10 PUAN)`
 </summary>

Hibernate, JPA ve Spring Data Framework'leri
Hibernate:

Tanım: Java'da nesne-ilişkisel eşleme (ORM) için kullanılan bir framework'tür.
Avantajları:
Nesne-ilişkisel eşleme: Java nesnelerini veritabanı tablolarıyla eşlemenizi sağlar.
SQL sorgularından soyutlama: SQL sorguları yazmadan nesnelerle çalışmanızı sağlar.
Geliştirilmiş performans: Sorgu önbelleğe alma ve otomatik veri güncelleme gibi performans optimizasyonları sunar.
Dezavantajları:
Karmaşıklık: Karmaşık kurulum ve konfigürasyon gerektirebilir.
Öğrenme eğrisi: Öğrenmesi ve kullanması zor olabilir.

```java
@Entity
public class Person {

   @Id
   @GeneratedValue(strategy = GenerationType.IDENTITY)
   private Long id;

   private String name;

   private int age;

   // ...

}

public class Main {

   public static void main(String[] args) {

      SessionFactory sessionFactory = new Configuration().configure().buildSessionFactory();

      Session session = sessionFactory.openSession();

      Person person = new Person();
      person.setName("John Doe");
      person.setAge(30);

      session.beginTransaction();
      session.save(person);
      session.getTransaction().commit();

      session.close();

   }

}

```
JPA (Java Persistence API):

Tanım: Java'da nesne-ilişkisel eşleme (ORM) için bir standarttır.
Avantajları:
Standart: Farklı ORM framework'leri arasında taşınabilirlik sağlar.
Basitlik: Hibernate'den daha basit ve kullanımı kolaydır.
Dezavantajları:
Daha az özellik: Hibernate'den daha az özellik sunar.
Daha az performans: Hibernate'den daha az performanslı olabilir.
Örnek:

```java
@Entity
public class Person {

   @Id
   @GeneratedValue(strategy = GenerationType.IDENTITY)
   private Long id;

   private String name;

   private int age;

   // ...

}

public class Main {

   public static void main(String[] args) {

      EntityManagerFactory emf = Persistence.createEntityManagerFactory("my-persistence-unit");

      EntityManager em = emf.createEntityManager();

      Person person = new Person();
      person.setName("John Doe");
      person.setAge(30);

      em.getTransaction().begin();
      em.persist(person);
      em.getTransaction().commit();

      em.close();

   }

}

```
Spring Data:

Tanım: Hibernate ve JPA gibi ORM framework'leri için üst düzey bir soyutlama katmanı sağlayan bir framework'tür.
Avantajları:
Soyutlama: ORM framework'lerinden soyutlama sağlayarak daha basit bir API sunar.
Depolamaya bağımsızlık: Farklı veri tabanları ile kolayca çalışmanızı sağlar.
Kolay kullanım: Kullanımı kolay ve öğrenmesi basittir.
Dezavantajları:
Daha az esneklik: Hibernate ve JPA'ya kıyasla daha az esneklik sunar.
Daha az performans: Hibernate ve JPA'dan daha az performanslı olabilir.
Örnek:


```java
public interface PersonRepository extends CrudRepository<Person, Long> {

}

public class Main {

   @Autowired
   private PersonRepository personRepository;

   public static void main(String[] args) {

      Person person = new Person();
      person.setName("John Doe");
      person.setAge(30);

      personRepository.save(person);

      Person foundPerson = personRepository.findById(person.getId()).get();

      System.out.println(foundPerson.getName());

   }

}

```
</details>

9. [**KredinBizde**](https://github.com/Definex-Java-Spring-Bootcampp/kredinbizde-service) Uygulamasına aşağıdaki özellikleri ekleyin. `(30 PUAN)`
    - Email adresi ile kullanıcının bütün başvurularını listeleyen end-point’i yazın.
    - Bankaların kredi kartlarını ve bu kartların kampanyalarını listeleyen end-point’i yazın.
    - Sistemdeki bütün kampanyaları en güncelden eski tarihe doğru listeleyen end-point’i yazın.
    - Kredi başvurularını kaydeden end-point’i yazın.
---
*Eğitmen - Cem DIRMAN*  
*Kolay Gelsin*
