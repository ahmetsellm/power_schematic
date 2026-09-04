# 5V - 3.3V Voltaj Regülatörü Kartı (LT1117-ADJ)

Bu depo, KiCad kullanılarak tasarlanmış basit ve kararlı bir 5V'tan 3.3V'a voltaj düşürücü regülatör devresinin donanım dosyalarını içerir.

## Donanım Detayları
Devre, LT1117-ADJ ayarlanabilir voltaj regülatörü etrafında şekillenmiştir. İstenen 3.3V çıkış gerilimi, R1 (240Ω) ve R2 (390Ω) dirençlerinin oluşturduğu gerilim bölücü ağ ile sağlanır. Güç hatlarındaki dalgalanmaları önlemek ve kararlılığı artırmak için giriş ve çıkış bölümlerinde filtre kondansatörleri kullanılmıştır.

## Teknik Özellikler
* **Giriş:** 5V
* **Çıkış:** 3.3V
* **Kullanılan Program:** KiCad EDA

## Malzeme Listesi (BOM)
| Referans | Bileşen | Değer | Kılıf (Footprint) |
| :--- | :--- | :--- | :--- |
| U1 | Regülatör | LT1117-ADJ | SOT-223-3 (Yüzey Montaj - SMD) |
| R1 | Direnç | 240Ω | Standart THT (Axial) |
| R2 | Direnç | 390Ω | Standart THT (Axial) |
| C1, C2 | Kondansatör | 10uF | Kutuplu THT (Radial) |

## Ekran Görüntüleri
*(Projeyi GitHub'a yükledikten sonra KiCad üzerinden alacağın şema ve 3D PCB ekran görüntülerini buraya sürükleyip bırakabilirsin)*
