```mermaid
timeline
    title 2026 – FERO Ana Akış + Paralel Projeler (Güncel Timeline)

    %% =====================================================
    %% FERO (LARAVEL CRM) – ANA AKIŞ
    %% =====================================================
    section FERO (Laravel CRM) – Faz I (Operasyonel Temel)

      2026-02-03 : ISG – Rapor Aktarımı & Doküman Otomasyonu
                : 03–14 Şubat<br/>Raporların sisteme aktarılması<br/>Excel/PDF dışa aktarımlar<br/>Excel çıktılarında bilgilerin oto. doldurulması

      2026-02-10 : ISG – Hizmet Gönderimi
                : 10–21 Şubat<br/>Firmalara hizmetlerin sistem üzerinden gönderilmesi
                : ISG / ÇEVRE / TMGD – Araç Takibi Altyapısı (Ortak)
                : Başlangıç: 10 Şubat<br/>Tahmini süre: ~3 gün (2 kişi)<br/>Ortak araç takibi altyapısının kurulması
                : ÇEVRE – Hizmet Formları
                : 10–21 Şubat<br/>Hizmet formlarının oluşturulması

      2026-02-17 : ÇEVRE – Firma & Araç Takibi
                : 17–28 Şubat<br/>Firma ve araç takibi (hangi araç, personel, nereye)

      2026-03 : TMGD – Faz I Başlangıç (Çevre sonrası)
             : TMGD işleri çevre tarafı oturduktan sonra başlar<br/>(uzun soluklu geliştirme)
             : TMGD – Hizmet Formları (Uzun Süreli)
             : Ek-3, TMFB, Yıllık Faaliyet Belgeleri<br/>Yeni bilgi ve varyasyonların eklenmesi<br/>Tahmini süre: 1–2 ay
             : TMGD – MSDS Yönetimi
             : MSDS aktarımı<br/>Tehlikeli/tehlikesiz ayrımı<br/>Hizmet formlarıyla paralel ilerler
             : TMGD – Firma Eğitim Kayıtları
             : Firma eğitim kayıtlarının açılması<br/>Eğitim türleri ve ilişkiler
             : TMGD – Güvenlik & Önlem Planları (Uzun Süreli)
             : Güvenlik planının yıllık faal. rap. eklenmesi<br/>Kimyasal tür/miktar/ADR'ye göre otomatik plan<br/>Tahmini süre: ~2 ay

      2026-02-06 : OSGB – Göz/Kulak PDF Otomasyonu
                : 06 Şubat<br/>Her tetkik türü için arka planda özel handler

      2026-02-11 : OSGB – Onay Akışları
                : 11 Şubat<br/>Doktor/Hemşire/Danışma alanlarının devreye alınması<br/>Doktor “Red” → teknisyene geri düşer → düzenleme → tekrar onay

      2026-02-13 : OSGB – Günlük Excel
                : 13 Şubat<br/>Tek tuşla günlük hasta kayıtlarından Excel raporu

      2026-02-20 : OSGB – Laboratuvar Entegrasyonları
                : 20 Şubat<br/>Dış laboratuvarlardan test sonuçlarının API ile çekilmesi<br/>PDF olarak sisteme yansıtılması

      2026-02-24 : OSGB – Müşteri Paneli Sağlık Raporları
                : 24 Şubat<br/>Onaylandı/Reddedildi/Bekliyor, imzalı PDF
                : OSGB – Excel Çıktıları
                : 24–28 Şubat<br/>Danışma kayıtları, Firmalar, Hizmet fiyatları, Ödeme yöntemleri

      2026-02-28 : OSGB – Sistem Testleri & Hata Giderme
                : 28 Şubat<br/>OSGB personeli test eder, hatalar giderilir

      2026-03 Sonu : ➜ Faz I Çıktısı
             : ISG + ÇEVRE + OSGB çekirdeği aktif<br/>TMGD modülü uzun soluklu olarak devam eder

    section FERO (Laravel CRM) – Faz I (Veri Aktarımı)

      2026-03 : Veri Envanteri & Temizlik
             : Eski sistem tabloları / alanlar analizi<br/>Temizleme, tutarlılık, tekrar kayıt ayıklama

      2026-04 : Mapping & Aktarım Planı
             : Eski → yeni model eşleştirmeleri<br/>Batch aktarım stratejisi<br/>Doğrulama kuralları

      2026-05 : Büyük Hacimli Aktarım & Kontroller
             : Batch aktarım<br/>Performans ve tutarlılık kontrolleri<br/>Tahmini toplam süre: ~3 ay
             : ➜ Veri Aktarımı Çıktısı
             : Kritik veriler yeni sisteme taşınmış<br/>Canlı sistemle uyum doğrulanmış

    section FERO (Laravel CRM) – Faz II (Otomasyon)

      2026-04 : Eğitimler & Hatırlatıcılar
             : ISG & OSGB eğitimleri (yüksekte çalışma vb.)<br/>Yenileme periyotları ve reminder altyapısı
             : Periyodik Kontroller + Şablonlar (Uzun Süreli)
             : Standart Excel/PDF şablonları<br/>Tahmini süre: ~2 ay

      2026-05 : Elektrik Raporları (Bakanlık Excel Uyumları)
             : Bakanlığın Excel formalarını otomatik doldurma<br/>Periyodik kontrollerle paralel ilerler
             : Ortam Ölçümleri
             : ISG modülüne eklenmesi

      2026-06 Sonu : ➜ Faz II Çıktısı
             : Sistem artık proaktif hatırlatan yapıya geçer

    section FERO (Laravel CRM) – Faz III (Denetim)

      2026-06 : Yıllık Denetimler – Şablon/Altyapı
             : Denetim içerikleri sistem üzerinden hazırlanabilir hale getirilir
             : Sosyal Uygunluk Denetimleri
             : SEDEX, Inditex, BSCI, SA8000 vb.

      2026-07 : Kalite Yönetim Sistemleri
             : ISO 9001, 14001, 45001 vb.
             : Otomotiv Denetimleri
             : IATF 16949, VDA serileri, OEM denetimleri

      2026-08 : Çevre & Sürdürülebilirlik Denetimleri
             : ISO 14064, Karbon, Atık yönetimi, REACH
             : İSG & Yasal Uyum Denetimleri
             : 6331 uyum, risk, acil durum, PKD
             : Tehlikeli Madde & Lojistik Denetimleri
             : ADR uygunluk, TMGD, SDS uyum
             : Karbon Ayak İzi Hesaplama
             : Karbon altyapısı ve hesaplama modülü

      2026-09 Sonu : ➜ Faz III Çıktısı
             : Denetim & sürdürülebilirlik platformu

    %% =====================================================
    %% MOBİL (AYRI PROJE)
    %% =====================================================
    section FERO Mobile (Ayrı Proje)

      2026-03 : Mobil – Planlama & Altyapı
             : Teknoloji/mimari, Auth & rol bazlı erişim, API ihtiyaçları

      2026-04 : Mobil – Temel Ekranlar
             : Dashboard, Bildirimler, Rapor görüntüleme, Navigasyon

      2026-05 : Mobil – API Entegrasyonları
             : Veri çekme, sayfalama, caching, hata yönetimi

      2026-06 : Mobil – Offline/Dayanıklılık
             : Kısıtlı offline senaryolar, Yeniden senkronizasyon

      2026-07 : Mobil – Stabilizasyon
             : Performans, Loglama, UX iyileştirmeleri

      2026-08 : Mobil – Genişleme
             : Ek rapor ekranları, Bildirim aksiyonları

      2026-09 : Mobil – Pilot Kullanım
             : Sınırlı kullanıcı grubu, Geri bildirim + kritik bug fix

      2026-10 : Mobil – Sertleştirme
             : Güvenlik kontrolleri, Performans testleri

      2026-11 : Mobil – Yayına Hazırlık
             : Store gereksinimleri (iOS/Android), Release süreçleri

      2026-12 : Mobil – Hedeflenen Yayın
             : Yayınlama, İzleme & hızlı müdahale<br/>⚠️ Tek kişi olduğu için kapsam/risk yönetimi kritik

    %% =====================================================
    %% CHATBOT (AYRI PROJE)
    %% =====================================================
    section fero-chatbot (Ayrı Proje)

      2026-03 : Python Sunucuya Taşıma
             : 03 Mart – 15 Nisan<br/>Sesli ve mesaj tabanlı kullanım
             : Animasyon & State Machine
             : 17 Mart – 15 Mayıs<br/>Akıllı akışlar ve animasyon

      2026-05 : FERO Entegrasyonu
             : 19 Mayıs – 30 Mayıs<br/>Ana sisteme yeniden entegre edilmesi

    %% =====================================================
    %% FER-SA-DENS (AYRI PROJE)
    %% =====================================================
    section FER-SA-DENS (Ayrı Proje)

      2026-03 : Faz I – Prototip Montaj (Acil)
             : Montaj aşamasında takılındı, hızlanmak gerekiyor

      2026-05 : Faz II – Endüstriyel Ürünleşme
             : PCB baskı + kalıp anlaşması<br/>YOLO v8 → v11, CI/CD kurulması<br/>Montaj sonrası verilerle model güncelleme

      2026-08 : Faz III – Saha Öğrenmesi
             : Sahalardan toplanan verilerle modellerin güncellenmesi

    %% =====================================================
    %% UZMAN KATAFOREZ AI (AYRI PROJE)
    %% =====================================================
    section Uzman Kataforez AI (Ayrı Proje)

      2026-03 : Faz I – Fizibilite (3 Ay)
             : Saha analizi<br/>Danışman firma ile gerekliliklerin belirlenmesi

      2026-06 : Faz II – Hızlı Prototip (2 Hafta)

      2026-07 : Faz III – Ürünleşme
             : Diğer firmalara genellenebilir yapı, CI/CD ve saha süreçleri

    %% =====================================================
    %% 3KCOSMETIC (AYRI PROJE)
    %% =====================================================
    section 3kCosmetic (Ayrı Proje)

      TBD     : Beklemede
             : Müşteri dönüşüne göre süreç güncellenecek<br/>En son ~3 hafta önce toplantı planlandı, haber gelmedi

