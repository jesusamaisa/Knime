# KNIME Çalışma Akışları Deposu 🚀

Bu depo, KNIME Analytics Platform üzerinde **veri işleme, analiz ve makine öğrenmesi** tekniklerini içeren çeşitli çalışma akışlarını barındırmaktadır. Her bir akış, KNIME ile yapılabilecek işlemlere dair örnekler ve en iyi uygulamaları göstermektedir.

---

## İçindekiler 📚

* [Giriş](#giriş-🔍)
* [Gereksinimler](#gereksinimler-🛠️)
* [Başlarken](#başlarken-🚀)
* [Çalışma Konuları](#çalışma-konuları-🧠)
* [Kullanım](#kullanım-🧪)
* [Katkı Sağlama](#katkı-sağlama-🤝)
* [Lisans](#lisans-📄)

---

## Giriş 🔍

**KNIME**, açık kaynaklı bir veri analizi, raporlama ve entegrasyon platformudur. Bu depo, temel veri filtrelemeden ileri düzey makine öğrenmesi ve tahmin modellerine kadar çeşitli konuları ele alan örnek akışları içermektedir.

---

## Gereksinimler 🛠️

Bu akışları çalıştırmak için aşağıdaki gereksinimlere sahip olmanız gerekir:

* **KNIME Analytics Platform** (sürüm 4.6 veya üzeri önerilir)
* KNIME ile uyumlu **Java Runtime Environment**
* **PMML Eklentisi** (karar ağaçlarını dışa/içe aktarmak için)
* **Python Entegrasyonu** (Python kodlarının çalıştığı akışlar için)

---

## Başlarken 🚀

1.  Depoyu klonlayın:
    ```bash
    git clone [https://github.com/jesusamaisa/Knime.git](https://github.com/jesusamaisa/Knime.git)
    ```
2.  KNIME'ı açın ve `File > Import KNIME Workflow...` seçeneğine tıklayın.
3.  Klonladığınız dizine gidin ve istediğiniz akış klasörünü seçin.
4.  Akışı çalıştırmak için kök node'a sağ tıklayıp `Execute` deyin.

---

## Çalışma Konuları 🧠

Bu depoda yer alan çalışma akışları aşağıdaki konuları kapsamaktadır:

* **Cinsiyet** – Cinsiyet verilerinin işlenmesi ve kodlanması
* **Column_Filtering** – Kolon filtreleme işlemleri
* **Eksik_Veriler** – Eksik verilerin doldurulması ve yönetimi
* **Example Workflows** – Temel örneklerden oluşan koleksiyon
* **GroupBy_Aggregate_Ungroup_KolonBolme** – Gruplama, toplama, bölme işlemleri
* **Histogram_PieChart_LineChart** – Görselleştirme grafikleri
* **Join_Concatenation** – Veri birleştirme ve ekleme
* **MetaNode** – Tekrar kullanılabilir modüller
* **Musteri_segmentasyonu** – Müşteri segmentasyonu örneği
* **PMML_decisiontree** – PMML ile karar ağacı kullanımı
* **Python_Snippet** – Python kodlarının KNIME ile entegrasyonu
* **Row_Filtering** – Satır bazlı filtreleme
* **RuleBasedRowFiltering** – Kurala dayalı satır filtreleme
* **Scatter_Matrix** – Dağılım matrisi grafikleri
* **Tahmin_Borsa_Ornegi** – Borsa tahmini örneği
* **VeriTipleri_VeriRenklendirme** – Veri tipi dönüşümü ve renklendirme
* **dosya_donusturme** – Dosya format dönüşümleri
* **first** – KNIME'a giriş niteliğinde bir akış
* **kfold_Crossval** – K-Katlı çapraz doğrulama
* **kümeleme_KMeans** – K-Means kümeleme algoritması
* **lineer_regnasyon** – Doğrusal regresyon modeli
* **loop** – Döngüler ve yinelemeli işlemler
* **naivebayes** – Naive Bayes sınıflandırması

---

## Kullanım 🧪

* Her akışı kendi verinize göre **özelleştirin** 🔧.
* Giriş düğümlerini kendi veri kaynaklarınızla **değiştirin** 📂.
* Performansı **Node Monitor** ve **KNIME Console** ile takip edin 📊.
* Sonuçları **CSV, Excel veya PMML** olarak dışa aktarın 📤.

---

## Katkı Sağlama 🤝

Katkılarınızı memnuniyetle kabul ediyoruz! Aşağıdaki adımları izleyin:

1.  Depoyu **fork'layın**.
2.  Yeni bir dal oluşturun:
    ```bash
    git checkout -b ozellik/yeni-akis
    ```
3.  Değişikliklerinizi commit'leyin:
    ```bash
    git commit -m "Yeni akış eklendi"
    ```
4.  Dalları gönderin:
    ```bash
    git push origin ozellik/yeni-akis
    ```
5.  Bir Pull Request oluşturun.

---

## Lisans 📄

Bu proje **MIT Lisansı** altında lisanslanmıştır. Özgürce kullanabilir, düzenleyebilir ve paylaşabilirsiniz.
