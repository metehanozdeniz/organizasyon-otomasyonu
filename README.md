# **ALGORİTMA VE PROGRAMLAMA – 1 DERSİ**

# **FİNAL PROJESİ**

# PROJE KONUSU

Bir organizasyon şirketi yurt dışında geziye giden kafileye organizasyon hizmeti sağlamaktadır. Müşterilerin farklı seçim alternatifleri bulunmaktadır.

- Müşteriler 75 TL'ye kahvaltı, 100 TL'ye akşam yemeği veya hiç ödemeyerek yemek hizmeti almayabilirler.
- Otel hizmet almak zorunlu değildir. Fakat otel hizmeti almak isteyenler için iki otel seçeneği mevcuttur. Müşteriler 2 yıldızlı otelde 200 TL'ye ve 3 yıldızlı otelde 300 TL'ye konaklayabilirler.
- Müşterilerin yurt dışına çıkışı için iki farklı vasıta seçeneği sunulmuş olup, otobüs ile gidenler 150 TL'ye, uçak ile gidenler ise 250 TL'ye gidebilirler.

Bu verilerin saklanması için iç içe struct veri tipi kullanıldı. _ **musteri\_bilgileri** _ adında bir struct tanımlandı. Struct yapısında müşteri numarası, müşterinin adı, müşterinin soyadı, kahvaltı hizmeti, akşam yemeği hizmeti, otel hizmeti ve otelde konaklayacaksa kaç yıldızlı otelde kalıp kalmayacağı tanımlandı. Ayrıca bu struct yapısının içinde tekrar _ **tasit** _ isminde bir struct tanımlanarak müşterinin yurt dışına hangi vasıta ile gideceği bilgisi tutuldu. Bu iç içe struct yapısının boş görünmemesi için başlangıçta dinamik bellek fonksiyonları kullanılarak _ **ornek\_veriler** _ isminde bir fonksiyon ile örnek verilerle dolduruldu.

Bu iç içe struct yapısı için _ **ekleme, silme, güncelleme ve listeleme** _ işlemleri dinamik bellek tahsis fonksiyonları kullanılarak ayrı ayrı fonksiyonlarda yapıldı.

Müşterilerin aldığı hizmetler için ödemesi gereken tutarın hesaplama işlemi, _ **fatura\_hesapla** _ isimli bir fonksiyonda yapıldı.

Müşterilerin hangi vasıta ile yurt dışına gideceğinin listelemesini yapan _ **vasita\_listele** _ isimli fonksiyon oluşturuldu.

Bu yapılan işlemler için aktif olarak kullanılabilir bir menü hazırlandı. Menünün daha anlaşılabilir görünmesi için ilgili menü seçenekleri renklendirildi.

# PROJE GEREKSİNİMLERİ

Proje GCC derleyici ile hazırlanmış olup çalışması için sadece GCC derleyicisine gereksinim duymaktadır. Kullanılan GCC versiyonu 6.3.0 dır.
