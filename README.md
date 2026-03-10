# ESP32 Tabanlı Uzaktan Kontrollü RC Araç Sistemi

Bu proje, uzaktan kontrol edilebilen kompakt bir RC araç için özel elektronik kartların tasarlanması, güç dağıtım altyapısının oluşturulması, motor sürme yapısının kurgulanması ve kablosuz kontrol sisteminin entegre edilmesi amacıyla geliştirilmiştir.

Projede, hazır geliştirme kartları yerine mümkün olduğunca sisteme özel PCB tasarımları oluşturularak hem elektronik donanım geliştirme süreci hem de gömülü sistem entegrasyonu uygulamalı olarak ele alınmıştır.

## Proje Özeti

Bu çalışmada, küçük ölçekli bir uzaktan kontrollü aracın çalışması için gerekli olan temel elektronik altyapı özel olarak tasarlanmıştır. Sistem; mikrodenetleyici tabanlı kontrol, motor sürme, güç yönetimi, haberleşme ve bağlantı katmanlarını içeren modüler bir donanım mimarisi üzerine kurulmuştur.

Amaç yalnızca hareket eden bir araç oluşturmak değil, aynı zamanda gerçek bir mühendislik projesi yaklaşımıyla; üretilebilir, düzenli ve işlevsel bir elektronik sistem geliştirmektir.

## Projenin Amacı

Bu projenin temel amacı aşağıdaki alanlarda uygulamalı deneyim kazanmaktır:

- ESP32 tabanlı gömülü sistem geliştirme
- Özel PCB tasarımı oluşturma
- Motor sürücü devresi entegrasyonu
- Batarya ile çalışan sistemlerde güç dağıtımı tasarlama
- Kablosuz haberleşme tabanlı araç kontrolü geliştirme
- Gerçek bir ürün mantığıyla donanım bloklarını tek sistemde birleştirme

## Sistem Mimarisi

RC araç sistemi aşağıdaki temel donanım bloklarından oluşmaktadır:

### Mikrodenetleyici Katı
Araç kontrolü için ESP32 tabanlı bir yapı kullanılmıştır. Bu yapı; kablosuz haberleşme, kontrol sinyalleri üretimi ve çevresel birimlerle veri alışverişi için ana denetleyici görevini üstlenmektedir.

### Motor Sürücü Katı
Araç hareketinin sağlanabilmesi için DC motorların ileri-geri kontrolü ve gerekli yönlendirme sinyalleri motor sürücü altyapısı üzerinden gerçekleştirilmiştir.

### Güç Katı
Sistemin batarya ile çalışmasına uygun olarak güç girişleri, regülasyon yapıları, filtreleme elemanları ve güç dağıtım bağlantıları tasarlanmıştır. Böylece hem kontrol katı hem de sürücü katı için uygun besleme altyapısı oluşturulmuştur.

### Bağlantı ve Arabirim Katı
Motorlar, güç hattı, kontrol sinyalleri ve yardımcı bağlantılar için kart üzerinde uygun konnektör ve pin yapıları planlanmıştır. Bu yaklaşım montaj, test ve bakım süreçlerini kolaylaştırmayı hedeflemektedir.

## Kart Tasarım Yaklaşımı

Bu proje kapsamında elektronik kartlar yalnızca çalışacak şekilde değil, aynı zamanda düzenli ve üretilebilir olacak şekilde tasarlanmıştır. Tasarım sürecinde aşağıdaki başlıklara dikkat edilmiştir:

- Şematik ve PCB tasarımının birbiriyle tutarlı ilerletilmesi
- Güç ve sinyal hatlarının işlevlerine göre ayrılması
- Motor akım yollarının kontrol sinyallerinden ayrıştırılması
- Bileşen yerleşiminde kısa ve mantıklı bağlantılar oluşturulması
- Regülatör, sürücü ve mikrodenetleyici etrafında uygun yerleşim planı yapılması
- Konnektörlerin montaj ve erişim açısından uygun konumlandırılması
- Kartın kompakt yapıda ancak servis edilebilir olacak şekilde planlanması

## Gerçekleştirilen Çalışmalar

- RC araç için ihtiyaç duyulan donanım blokları belirlendi
- ESP32 tabanlı kontrol yapısı oluşturuldu
- Motor sürücü entegrasyonu planlandı
- Güç girişi ve regülasyon yapısı tasarlandı
- Özel PCB kart yerleşimi hazırlandı
- Konnektör ve arabirim yerleşimi yapıldı
- Sistem bağlantıları, kontrol mantığı ve montaj yapısı birlikte değerlendirildi

## Kullanılan Teknolojiler ve Bileşenler

- ESP32
- DC motor sürücü yapısı
- Li-Po batarya altyapısı
- Gerilim regülasyon devreleri
- PCB tasarım yazılımı
- Şematik ve PCB yerleşim araçları

## Teknik Kazanımlar

Bu proje kapsamında aşağıdaki alanlarda uygulamalı deneyim kazanılmıştır:

- Gömülü donanım mimarisi oluşturma
- PCB tasarımı ve yerleşim planlama
- Güç yönetimi tasarımı
- Motor sürme altyapısı kurma
- Kablosuz kontrollü sistem tasarlama
- Sistem seviyesinde elektronik entegrasyon

## Proje Görselleri

![Şematik Görünüm](images/sematik.png)

![PCB Üst Görünüş](images/pcb-ust.png)

![3D PCB Görünüşü](images/pcb-3d.png)

![Prototip Sistem](images/prototip.png)

## Geliştirme Potansiyeli

Bu proje aşağıdaki yönlerden geliştirilebilir:

- Daha kompakt çok katmanlı PCB tasarımı
- Akım ölçümü ve batarya izleme yapısının eklenmesi
- Daha gelişmiş motor kontrol algoritmaları
- Sensör entegrasyonu
- Kamera veya görüntü aktarım modülü eklenmesi
- Mobil uygulama arayüzünün geliştirilmesi
- EMI/ESD koruma yapılarının güçlendirilmesi

## Sonuç

Bu proje, uzaktan kontrollü bir aracın elektronik altyapısını özel kart tasarımı yaklaşımıyla ele alan kapsamlı bir uygulama çalışmasıdır. Mikrodenetleyici kontrolü, motor sürme, güç dağıtımı ve kart tasarımı gibi farklı mühendislik başlıklarını tek bir sistem altında birleştirmesi açısından güçlü bir donanım geliştirme projesidir.
