## ✅ GAN Temelleri (Generator, Discriminator, Adversarial Loss)  
- **Generator ve Discriminator**  
  - **Generator (Üreteç)**: Gerçek veriye benzer sahte veriler üretme  
  - **Discriminator (Ayrımcı)**: Gerçek ve sahte verileri ayırt etme  
- **Adversarial Loss**  
  - **Loss Fonksiyonu**: Üreteç ve ayrımcı arasında karşılıklı eğitim  
  - **Minimax Oyun**: İki modelin sırasıyla birbirini zorlama prensibi  

## ✅ Klasik GAN Mimarisinin Çalışma Mantığı  
- **İki Ağı Modelleri**  
  - **Generator**: Noise (rastgele gürültü) girişinden veri üretir  
  - **Discriminator**: Üretilen veri ile gerçek veri arasındaki farkları değerlendirir  
- **Adversarial Eğitim**  
  - Eğitim sırasında generator ve discriminator birbirini optimize eder  
  - Eğitim hedefi, generator'ın sahte verileri gerçek gibi yapabilmesi  

## ✅ Mode Collapse Sorunu ve Çözümleri  
- **Mode Collapse**  
  - Generator'ın çok benzer veya tek tip veri üretmesi  
  - Discriminator'ın sadece belirli türde verileri ayırt edebilmesi  
- **Çözüm Yöntemleri**  
  - **Mini-Batch Discrimination**: Farklı veri örnekleri üretmek için batch-based strateji  
  - **Feature Matching**: Discriminator'ın özellikleriyle generator'ı eşleştirmek  
  - **Unrolling GANs**: Discriminator'ı daha uzun süre eğitmek  

## ✅ GAN’lerde Eğitim Stabilizasyon Teknikleri  
- **Wasserstein GANs (WGANs)**  
  - Kayıp fonksiyonu yerine Wasserstein uzaklık kullanımı  
  - Eğitimde daha stabil sonuçlar elde etmek  
- **Gradient Penalty**  
  - Eğitim sırasında gradyanların sabit kalmasını sağlamak  
- **Batch Normalization ve Spectral Normalization**  
  - Eğitimde stabiliteyi artırmak için normalizasyon teknikleri  

## ✅ Conditional GANs (cGANs)  
- **Conditional GANs (Koşullu GAN'ler)**  
  - **Koşul Bilgisi**: Generator ve discriminator'a ek veri (etiket, sınıf bilgisi) verilerek daha spesifik veri üretme  
  - **Özellikler**: Koşullu veri kullanımıyla daha hassas ve kontrollü çıktı üretimi  
  - **Uygulamalar**: Resim oluşturma, görüntü düzenleme, stil transferi  
