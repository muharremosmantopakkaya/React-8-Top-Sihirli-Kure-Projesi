# React "8 Top" Sihirli Küre Projesi

Bu proje, sıkça bilinen "8 top" sihirli küre oyununun React ile geliştirilmiş bir versiyonudur. Kullanıcıya, büyük topa tıkladığında rastgele mesajlar gösterir.

🌟 Bu proje, Ömer Fatih Tanrıverdi hocamızın katkılarıyla geliştirilmiştir.

## Özellikler

- Tam ekran merkezde bir "büyük top" görseli.
- Büyük topun içinde, merkezde beyaz renkli bir "küçük top" bulunmaktadır.
- Küçük topun ortasında, cevap verilmediyse "8" yazılıdır. Cevap verildiğinde rastgele bir mesaj gösterilir.

## Görsel Önizlemeler

![Bad Cevap Görseli](https://github.com/muharremosmantopakkaya/Microfon-Yazilim-101-React/blob/main/img/bad.png)

![Kesinlikle Cevap Görseli](https://github.com/muharremosmantopakkaya/Microfon-Yazilim-101-React/blob/main/img/kesinlikle.png)

## Kod Özet

### React:
- Başlangıçta `cevap` state değeri null olarak ayarlanmıştır.
- Rastgele bir mesaj seçmek için bir fonksiyon kullanılır.
- Büyük topa tıklanıldığında bu fonksiyon çağrılır ve rastgele bir mesaj seçilir.
- Eğer bir cevap seçilmediyse, küçük topun içinde "8" gösterilir.

### Stil:
- Uygulama merkezi hizalama ile tam ekran görüntülenmektedir.
- Büyük top, siyah renkte ve ekranın merkezinde yer almaktadır.
- Küçük top, beyaz renkte ve büyük topun içinde merkezi konumlandırılmıştır.
