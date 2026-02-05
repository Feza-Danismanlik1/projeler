gantt
    title FERO Platform – 2026 Tarihsel Yol Haritası
    dateFormat  YYYY-MM-DD
    axisFormat  %b %Y

    %% ==================================================
    %% ŞUBAT 2026 — FERO CORE / OPERASYONEL TEMEL
    %% ==================================================
    section Şubat 2026 – FERO Core (Faz I)
    ISG Rapor Aktarımı & Doküman Yapısı      :s1, 2026-02-01, 10d
    Excel / PDF Otomasyon                    :s2, after s1, 8d
    Firmalara Hizmet Gönderimi               :s3, after s2, 5d

    Araç Takibi Altyapısı (Ortak)             :s4, 2026-02-05, 12d

    TMGD Hizmet Formları (Ek-3 / TMFB)        :s5, 2026-02-08, 10d
    MSDS Aktarımı & Sınıflandırma             :s6, after s5, 6d

    Firma Eğitim Kayıtları                    :s7, 2026-02-15, 5d
    Çevre Hizmet Formları & Araç Takibi       :s8, 2026-02-18, 6d

    OSGB Sağlık Süreçleri                     :s9, 2026-02-10, 12d
    OSGB Onay Akışları                        :s10, after s9, 6d
    Laboratuvar Entegrasyonları               :s11, after s10, 5d
    Sistem Testleri & Excel Çıktıları         :s12, after s11, 4d

    FERO Operasyonel Çekirdek Canlı           :milestone, m1, 2026-02-28, 1d

    %% ==================================================
    %% MART 2026 — CHATBOT & AKILLI KATMAN
    %% ==================================================
    section Mart 2026 – Chatbot & AI
    Chatbot Python Sunucuya Taşıma            :c1, 2026-03-01, 7d
    Mesaj + Ses Tabanlı Altyapı               :c2, after c1, 8d
    State Machine Akış Tasarımı               :c3, after c2, 10d

    Akıllı Asistan Dönüşüm Milestone          :milestone, m2, 2026-03-25, 1d

    %% ==================================================
    %% NİSAN 2026 — OTOMASYON & HATIRLATICI (FAZ II)
    %% ==================================================
    section Nisan 2026 – Otomasyon (Faz II)
    ISG & OSGB Eğitim Modülleri               :o1, 2026-04-01, 8d
    Eğitim Hatırlatıcı Altyapısı              :o2, after o1, 7d
    Periyodik Kontrol Süreçleri               :o3, after o2, 8d

    Standart Excel / PDF Şablonları           :o4, 2026-04-10, 7d
    Bakanlık Excel Uyumları                   :o5, after o4, 5d
    Ortam Ölçümleri (ISG Entegrasyonu)        :o6, after o5, 6d

    Proaktif Hatırlatma Sistemi Aktif         :milestone, m3, 2026-04-30, 1d

    %% ==================================================
    %% MAYIS 2026 — PLATFORM OLGUNLAŞMASI
    %% ==================================================
    section Mayıs 2026 – Platform Olgunlaşması
    Chatbot Animasyonları                     :p1, 2026-05-01, 6d
    State Machine Tamamlama                   :p2, after p1, 8d
    Chatbot ↔ FERO Entegrasyonu               :p3, after p2, 10d
    Merkezi Bildirim & Reminder Sistemi       :p4, after p3, 8d

    Akıllı Karar Destek Platformu             :milestone, m4, 2026-05-31, 1d

    %% ==================================================
    %% HAZİRAN 2026 — DENETİM & SÜRDÜRÜLEBİLİRLİK (FAZ III)
    %% ==================================================
    section Haziran 2026 – Denetim & Sürdürülebilirlik
    Sosyal Uygunluk Denetimleri               :d1, 2026-06-01, 12d
    ISO & Kalite Yönetim Sistemleri           :d2, after d1, 10d
    Otomotiv Denetimleri (IATF / VDA / CQI)   :d3, after d2, 10d
    İSG / ADR / TMGD / Çevre Denetimleri      :d4, after d3, 8d
    Karbon Ayak İzi Altyapısı                 :d5, after d4, 10d

    Denetim Platformu Aktivasyonu             :milestone, m5, 2026-06-30, 1d

    %% ==================================================
    %% TEMMUZ – AĞUSTOS 2026 — FER-SA-DENS
    %% ==================================================
    section Temmuz–Ağustos 2026 – FER-SA-DENS
    PCB & Kalıp Üretimi                       :f1, 2026-07-01, 20d
    Endüstriyel Donanım Geliştirme            :f2, after f1, 20d
    YOLO v8 → YOLO v11 Geçişi                 :f3, 2026-07-15, 25d
    Uzaktan Güncelleme & CI/CD                :f4, after f3, 15d
    Model Yeniden Eğitimi (Saha Verisi)       :f5, after f4, 15d

    Saha + AI Entegrasyonu                    :milestone, m6, 2026-08-31, 1d

    %% ==================================================
    %% MART – EYLÜL 2026 — KATAFOREZ AI (PARALEL)
    %% ==================================================
    section Mart–Eylül 2026 – Kataforez AI
    Saha Analizi & Fizibilite                 :k1, 2026-03-01, 60d
    Hızlı Prototip                            :k2, 2026-06-01, 20d
    Ürünleştirme & CI/CD                     :k3, 2026-07-01, 70d

    Dikey AI Ürün Milestone                   :milestone, m7, 2026-09-15, 1d

    %% ==================================================
    %% BELİRSİZ — 3K COSMETIC
    %% ==================================================
    section Belirsiz – 3kCosmetic
    Müşteri Geri Dönüşü Bekleniyor            :active, b1, 2026-03-01, 90d
