# CDC-Diabetes-Health-Indicators-Dataset

Bu proje, CDC Diabetes Health Indicators Dataset kullanarak diyabet hastalığının sağlık göstergeleri üzerinde analiz yapmaktadır. Proje, diyabet risk faktörlerini ve sağlık göstergelerini incelemek için veri bilimsel teknikler kullanarak modelleme yapmayı amaçlamaktadır.

# Proje İçeriği

Bu projede, CDC tarafından sağlanan diyabetle ilgili sağlık göstergeleri veri seti kullanılmıştır. Veri seti, diyabetin toplum üzerindeki etkilerini anlamaya yardımcı olacak sağlık bilgileri sunmaktadır.

# İçerik

diabetes.ipynb: Projenin ana Python kodu. Bu dosya, veri setinin yüklenmesi, temizlenmesi, analiz edilmesi ve modelin oluşturulması süreçlerini içerir.
Data: (Eğer projede yer alıyorsa) Veri seti ve diğer ilgili dosyalar.

# Kullanılan Yöntemler

1. Veri Ön İşleme: Eksik verilerin giderilmesi, kategorik verilerin dönüştürülmesi ve standartlaştırma.
2. Keşifsel Veri Analizi (EDA): Veri setindeki ilişkilerin keşfi ve görselleştirme.
3. Makine Öğrenmesi: Diyabet tahmini için sınıflandırma algoritmalarının uygulanması.

# Gereksinimler

Projeyi çalıştırabilmek için aşağıdaki Python kütüphanelerine ihtiyacınız olacaktır:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
    
Projede yer alan tüm gereksinimleri yüklemek için aşağıdaki komutla gerekli kütüphaneleri kurabilirsiniz:

```bash
pip install -r requirements.txt
```

# Kullanım
1. Bu projeyi bilgisayarınıza klonlayın:
   
```bash
git clone https://github.com/ecegny1/CDC-Diabetes-Health-Indicators-Dataset.git
```

2. Gerekli kütüphaneleri yüklemek için requirements.txt dosyasını kullanın:

```bash
pip install -r requirements.txt
```

3. Ana notebook dosyasını çalıştırarak projeyi başlatabilirsiniz:

```bash
jupyter notebook diabetes.ipynb
```

# Sonuçlar
Bu proje, diyabetin sağlık göstergeleri üzerindeki etkilerini incelemekte ve diyabet riski hakkında tahminler yapmak için makine öğrenmesi modellerini kullanmaktadır. Sonuçlar, diyabetin önlenmesi ve yönetilmesi için sağlık politikaları geliştirmeye yardımcı olabilecek bilgiler sunabilir.
