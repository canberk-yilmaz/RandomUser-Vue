# **Vue.js** İle Rastgele Kullanıcı Yaratma Projesi

## Projenin Görünüşü

![Project view](img/Project-Uno.png)

Küçük projelerde kurulum yapılmadan CDN aracılığı ile Vue.js kullanılabilir. Bunun için JS dosyasının body bölümüne aşağıdaki kod yapıştırıldı.

` <script src="https://unpkg.com/vue@3.2.1"></script>`

JS dosyasında ilk olarak örnek bir veri üzerinden resim, ad, soyad ve email bilgileri paylaşıldı. Butona tıklandığında ise alternatif bir kullanıcı verisi önceki verilerle yer değiştirildi.
Kullanıcı erkekse resimin çerçevesi ve buton rengi mavi, kadınsa pembe olarak uygulamaya alındı. Bunun için api'dan gelen cinsiyet verisi class olarak atandı.

Asenkron olarak tanımlanan `getUser()` fonksiyonu `v-on:click` ile butona event olarak tanımlandı. Bu butona tıklandığında api'dan çekilen veriler gelen arrayden değişkenlere atanarak proje tamamlandı.
