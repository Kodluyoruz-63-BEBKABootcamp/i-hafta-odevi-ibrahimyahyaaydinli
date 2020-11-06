#  Docker Nedir
[Kaynak 1](https://gokhansengun.com/docker-nedir-nasil-calisir-nerede-kullanilir/)
[Kaynak 2](https://www.mediaclick.com.tr/tr/blog/docker-nedir-docker-ne-ise-yarar)


Docker, yazılım geliştiriciler ve sistemciler için geliştirilen açık kaynaklı bir sanallaştırma platformudur.
Docker ile Linux, Windows ve MacOSX üzerinde Linux ve Windows sanal makineler çalıştırabilir ve bu platform sayesinde web sistemlerinin kurulumunu, testini ve dağıtımını 
kolaylıkla
yapabilirsiniz.
Docker’ın sanallaştırma yapısı bilinenin aksine Hypervisor katmanına sahip değildir.Docker Engine üzerinden, bulunduğu işletim sistemine erişip ve sistem araçlarını paylaşımlı
kullanmaktadır.
Docker, LXC sanallaştırma mekanizması üzerine kurulu. Bir Docker imajı, container denilen birimlerde çalıştırılıyor.Container imajları ortak olan sistem dosyalarını 
paylaşıyorlar.
Dolayısıyla disk alanından tasarruf ediliyor.

## VM vs Docker

|Kıyas türü      |VM           |Docker       |
|----------------|-------------|-------------|
|OS|Tam işletim sistemi|Küçültülmüş işletim sistemi imajı|
|İzalasyon|Yüksek|Düşük|
|Çalışır hale gelmesi|Dakikalar|Saniyeler|
|Versiyonlama|Yok|Yüksek|
|Kolay paylaşılabilirlik|Düşük|Yüksek|

Her iki sanallaştırmanın bize sundukları birbirlerine göre avantajları ve dezavantajları mevcut. 
Ancak, Docker tarafından bakarsak bazı avantajların çok önemli derecede olduğunu söylemek doğru olur.

# .Net Core versiyonları

# .NET 5 

* Temel olarak .Net 5 ile hedeflenen, .Net Core, .Net Framework, Xamarin ve Mono’nun avantajlarını tek bir çatı altında toplamaktır.
* .Net 5 mobil, Xbox ve diğer oyun platformları için oyun geliştirebileceğiniz unity’yi destekleyecek.
*  Net 5, tüm önemli masaüstü geliştirme işlevleri ve kitaplıkları ile birlikte gelecektir.


# Markdown
Daha detaylı bir tanım olarak, düz metin biçimlendirme (markup language) sözdizimine (syntax) sahip hafif bir düz metin biçimlendirme dili 
(plain text formatting syntax) olarak ifade edilebilir. 
Aynı isimli araç sadece HTML dilini desteklese de günümüzde pek çok formatta çıktı üretebilmek için de kullanılmaktadır.

Temel içerikleri anlatalım.

## Başlık
Temel HTML yapısından tanıdığımız h1,h2,h3,h4,h5 ve h6 başlık etiketlerini [__Markdownda__](https://www.markdownguide.org/) '#' 
işaretini başlığımızın başına getirerek aynı hedefe ulaşabiliyoruz.Tabi ki etiketimizin sayısının bize burada kaç tane '#' koymamız gerektiğini söylediğini unutmayalım.

## Link
Linki direk olarak paylaşmak zaten bilinen olay tabi ama peki bir kelimeye veyahut bir cümleye link vermek istersek ne yapacağız?
Hedef metnimizi köşeli parantez arasına alıyoruz,linkimizide onun yanına parantez arasında veriyoruz.Şöyle bir iskeletimiz olacak;`[]()`.

## Tablo
Tablo için "|" işaretini ve "-" işaretini kullanacağız.Satırlarımızı ve sütunlarımızı "|", başlık satırımızı "-" ile ayıracağız oluşturacak.
Anlatmak yerine gösterirsek daha anlamlı olacak.
### Örnek;
| Sütun 1 | Sütun 2|

|---------|--------|

|içerik|içerik|

|içerik|içerik|

|içerik|içerik|

| Sütun 1 | Sütun 2|
|---------|--------|
|içerik|içerik|
|içerik|içerik|
|içerik|içerik|

## Emoji
Emojilerimizin belirli isimleri var onları bilirsek tek yapamamız gereken ":" arasına yazmak olacak.
Büyük bir emoji isim listesine [buradan](https://gist.github.com/rxaviers/7360908) ulaşabilirsiniz.

:emoji ismi:
### Örnek
:joy: ----> joy

# [Microsoft Azure Hizmetleri](https://github.com/Kodluyoruz-63-BEBKABootcamp/i-hafta-odevi-salihtekin/blob/main/%C3%B6dev%201.md)

## Ağ İletişimi

Buluttaki ve şirket içindeki altyapı ve hizmetler arasında bağlantı kurar.

## Analiz

Herhangi bir türdeki, hacimdeki veya hızdaki verileri toplayıp, depolayıp, işleyip, analiz eder ve görselleştirir.

## Bilgi İşlem

Bulut işlem kapasitesi ve isteğe bağlı ölçeklendirme özelliklerine erişim elde edilir.

## Blok Zinciri

Tümleşik araç paketiyle blok zinciri tabanlı uygulamalar derleyip ve yönetilebilir.

## Depolama

Verileriler, uygulamalar ve iş yükleri  büyük oranda ölçeklenebilir, güvenli bir bulut depolama alanı edinilebilir.

## Geçiş

Kılavuzlar, araçlar ve kaynaklar sayesinde buluta geçişinizi kolaylaştırıp ve hızlandırır.

## Geliştirici Araçları

İstenilen platform veya dili kullanarak bulut uygulamaları oluşturup, yönetip ve bu uygulamaları sürekli olarak kullanıma sunmak mümkündür.

# Kod ve Metrik Sistemler :thinking:

Bütün programcılar yazdıkları kodun iyi olmasını ister ancak iyinin neye karşılık geldiğini bulmak zordur genelde. Bu noktada günlük hayattan aldığımız birtakım 
dersler vardır aklımızda kalan.

Örneğin yazdığımız kodda mümkün olduğunca az hata çıksın isteriz, eğer hata çıkarsa da en kısa zamanda 
bizim veya başka bir programcının hatayı çözebilmesini isteriz, ürünümüzde bir değişiklik 
yapacaksak bunu ürünümüzün diğer bileşenlerini mümkün olduğunca az etkilemesiniz isteriz.

Bütün bunlar kurumsal dilde, yazdığımız kodun hatasız, esnek, kararlı, anlaşılır, düşük bakım maliyetine sahip olması demektir. 
Ancak normal şartlarda bunları ancak yazdığımız kod ürün haline gelip piyasaya çıktığında görebiliyoruz.

İşte tam bu noktada yazılım metrikleri devreye giriyor. Geliştirme esnasında sürekli ölçüm ve iteratif düzeltmeler ile 
yazılım metriklerini geliştirme sürecinin bir parçası haline getirdiğimizde tasarım ve geliştirme sırasında bize ileride daha büyük 
maliyetler getirecek pek çok hatadan kurtuluyoruz. 
Yazılım mühendisliği ve yazılım kalitesinin ölçümü başlığı altında pek çok kod ölçüm metodu bulunuyor. 
Bunların hepsini uygulamak pratik olarak çok olası değil, öyleyse bizde piyasada en çok kullanılan metrikleri dikkate alarak bir orta yol bulabiliriz.

## Code Coverage

Yazılan testlerin kodun ne kadarını kapsadığını ölçer. Code coverage için %80 gibi bir oran oldukça iyi görünse de aslında az sayıda basit test yazarak dahi bu orana ulaşılabildiği gözlemlendiği için hedeflenen oranın %100 olması önerilir.

## Cohesion

Bu ölçüm sınıfın sorumlu olduğu işlerin kendi içindeki uyumluluğunu ölçer. Her sınıfın tek bir sorumluluğu olmalıdır. [3] [4]. Uyumluluk LCOM (Lack of Cohesion in Methods) adı verilen ölçüt ile bulunur. Değişik türleri bulunan LCOM sınıfta yer alan alanlara metodların ortak erişim sayısını temel alan bir ölçümdür. LCOM3 için bu değer 0 ile 2 arasında değişir ve 1’in üzerindeyse sınıf bölünmelidir.

## Coupling

Bir nesnenin diğeri ile etkileşime girmesine denir. Program içerinde mutlaka etkileşim olacaktır, ancak bu ilişkinin nesnelerin implementasyon detaylarından mümkün olduğunca bağımsız olması istenir. Farklı ilişki türleri üzerinden ölçülebilir. En çok kullanılanlardan birisi CBO’dur.
 Coupling Between Objects (CBO): Miras alınan sınıflar hariç, sınıfın çalışmak için ihtiyaç duyduğu sınıf sayısıdır. Kütüphanelerde bu sayı yüksek olabilir ancak çalıştırılabilir sınıflarda 6 ile 10 arası makul kabul edilebilir.
## Cyclomatic Complexity

Bir metodun içerisinde yer alan karar noktalarının (if, else vb.) sayısıdır. Kabul edilen eşik değer 10’dur. Bunun yanı sıra Essential Complexty denilen bir metrik daha mevcuttur ancak Cyclomatic Complexity’nin daha etkili bir metrik olduğu belirtilmektedir.

## Cyclomatic Density

Koddaki karar noktalarının toplam çalıştırılabilir koda oranıdır. 0.14 ile 0.42 arasındaki değerler için kodun basit ve anlaşılabilir olduğu kabul edilir.

## Response For Class (RFC)

Bir sınıfta yazılan ve çağırılan toplam metotların sayısıdır. Bu değer yükseldikçe kodun bakımı zorlaşır. Önerilen eşik değer 55 dir.

## Weighted Methods for Class (WMC)

Bir sınıfta yazılan toplam metot sayısıdır. Eşik değeri olarak 6 ile 33 arasında değişik rakamlar önerilmektedir. Ancak Cohesion değeri WMC’ye kıyasla daha önemlidir.

## Class Hierarchy Level veya Depth of Inheritance Tree (DIT)

Miras ilişkisinde sınıfın üzerinde kaç tane atası olduğunu gösterir. 6’nın üzerinde ise test edilebilirliği çok düşük olduğunu, 2 nin altında ise OO ilkerinin fazla kullanılmadığına işaret eder. Uygulamanın genelinde 2 ve 3 düzeyinde olması hedeflenmelidir.

## Number of Methods in Class (NOM)

İdeal değerler 6 ile 20 arasında değişse de 40’ın üzerinde sınıf kesinlikle bölünmelidir. Ancak tek başına bir gösterge olmaktan çok LCOM ile birlikte değerlendirilmelidir.

## Specialization Index (SIX)

Kod karmaşıklığını ve bakım maliyetlerini arttırmasından dolayı overload edilmiş fonksiyon sayısının mümkün olduğunca az olması istenir. Bundan dolayı SIX = (Overload Edilmiş Metot Sayısı * DIT) / NOM şeklinde hesaplanır. 1.2 (veya %120)’ye kadar normal kabul edilir.
