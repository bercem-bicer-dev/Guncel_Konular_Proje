# 🛡️ Safety 4.0 ve Endüstriyel Siber Güvenlik Analizi
### Otomatik Kenar Bantlama Makinesi Besleme Ünitesi ve Referans Otomasyon Sistemi

## 🎯 Proje Hakkında

Bu depo, **Yazılım Mühendisliği Güncel Konular** dersi kapsamında **AIMSAD** kaynaklı **Otomatik Kenar Bantlama Makinesi Besleme Ünitesi** üzerinde gerçekleştirilen kapsamlı iş güvenliği, fonksiyonel emniyet, otomasyon ağı siber güvenliği ve yapay zekâ dayanıklılık analizlerini içermektedir.

Çalışmada geleneksel makine emniyeti standartları ile modern siber güvenlik ve Yapay Zekâ (AI) güvenliği prensipleri entegre edilerek, Avrupa Birliği'nin güncel mevzuatlarına (AB Makine Tüzüğü 2023/1230 ve Siber Dayanıklılık Yasası - CRA) tam uyumlu bir mühendislik yaklaşımı sergilenmiştir.

---

## 🏗️ Hedef Makine ve Referans Sistemler

1. **Ana Hedef Makine:** 
   * **Otomatik Kenar Bantlama Makinesi Besleme Ünitesi (AIMSAD Kaynaklı)**
   * *Kritik Tehlikeler:* Panel besleme sıkışma/ezilme noktaları, yüksek sıcaklıktaki tutkal kazanı (termal yanık riski), yüksek devirli ön freze/kesici bıçaklar ve uzaktan bakım modülüne yönelik siber saldırı yüzeyleri.
2. **Referans Makineler:**
   * **Şişeleme Hattı (Bottling Line):** Yüksek hızlı döner mekanizmalar, basınçlı dolum ve otomatik ret sistemleri.
   * **PaketPro 3000:** Yüksek sıcaklıkta çalışan yapıştırma çeneleri, film kesme bıçakları ve pnömatik paketleme üniteleri.

---

## 🛡️ Temel Standartlar ve Mühendislik Çerçeveleri

* **ISO 12100 & ISO 13849:** Risk değerlendirmesi, fonksiyonel emniyet ve emniyetle ilgili kontrol sistemlerinin performans seviyeleri ($PLr / SIL$).
* **IEC 62443:** Endüstriyel otomasyon sistemleri için Zone & Conduit (Bölge ve Geçiş) ağ mimarisi ve güvenlik seviyeleri (SL 1–3).
* **AB Makine Tüzüğü (2023/1230):** Siber-fiziksel güvenlik gereksinimleri ve siber müdahalelerin makine emniyetine etkileri.
* **Siber Dayanıklılık Yasası (CRA - Cyber Resilience Act):** Zafiyet yönetimi, Yazılım Malzeme Listesi (SBOM) ve zorunlu siber olay bildirim takvimi.
* **Safety 4.0:** Yapay zekâ destekli kalite denetimi ve anomali tespiti, *Human Override* (insan müdahalesi), *Fallback* ve deterministik *Fail-Safe* mekanizmaları.

---

## 🧪 Laboratuvar Modülleri ve İçerikleri

| Laboratuvar Modülü | Odak Alanı | Temel Çıktı / Rapor |
| :--- | :--- | :--- |
| **Lab 1** | Safety Architecture | Safety Function Map, Koruma ve Kontrol Yolu Ayrımı, STO Entegrasyonu |
| **Lab 2** | Ağ Segmentasyonu | IEC 62443 Zone & Conduit Mimarisi, Güvenlik Duvarı Kuralları |
| **Lab 3** | Tehdit Modelleme | STRIDE Analizi, ISO 12100 Risk Matrisi ($S \times F$) |
| **Lab 4** | Olay Müdahalesi | OT/IT Olay Müdahale ve İyileştirme Planları (24s / 72s Kuralı) |
| **Lab 5** | Zafiyet Yönetimi | SBOM Envanteri, CVSS 9.8 Değerlendirmesi, Yama/Telafi Edici Kontroller |
| **Lab 6** | CRA Mevzuat Uyuşumu | Siber olay simülasyonu, adli bilişim kanıt koruma vs. resetleme refleksi |
| **Lab 7** | Yapay Zekâ Güvenliği | AI Fail-Safe Karar Yapısı, Güven Eşikleri (Confidence Threshold) |

---
🚀 Dokümantasyon ve Erişim
Tüm laboratuvar modüllerine ait detaylı mühendislik raporları, şematik mimari diyagramlar ve risk analizi matrisleri PDF formatında docs/ ve analysis/ klasörleri içerisinde yer almaktadır.

👤 Yazar ve Akademik Bilgiler
Ders: Yazılım Mühendisliği Güncel Konular

Uzmanlık Alanı: Endüstriyel Otomasyon, Fonksiyonel Emniyet (Safety) ve OT Siber Güvenliği (Cybersecurity).
