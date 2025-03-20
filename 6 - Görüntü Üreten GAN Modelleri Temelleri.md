## ✅ DCGAN (Deep Convolutional GAN)  
- **DCGAN Nedir?**  
  - Derin evrişimli sinir ağları kullanarak görüntü üretimi  
  - Görüntülerin daha net ve kaliteli olması için evrişimsel katmanlar  
- **DCGAN Mimarisinin Temelleri**  
  - **Generator**: Rastgele gürültüden yüksek kaliteli görüntüler üretir  
  - **Discriminator**: Gerçek ve sahte görüntüleri ayırt eder  
- **Uygulamalar**: Genellikle düşük çözünürlüklü görüntüler için kullanılır, ancak DCGAN bir temel olarak birçok geliştirilmiş GAN modeline dayanmaktadır  

## ✅ StyleGAN ve StyleGAN2 ile Gerçekçi Yüz Üretimi  
- **StyleGAN Temelleri**  
  - Yüksek çözünürlüklü, gerçekçi yüzler üretme  
  - **Stil Vektörleri**: Yüz özelliklerinin bağımsız olarak kontrol edilmesi (örneğin, yüz ifadeleri, saç renkleri vb.)  
- **StyleGAN2**  
  - StyleGAN'in iyileştirilmiş versiyonu  
  - **Farklar**: Daha fazla denetim, daha yüksek kalite ve görsel tutarlılık  
- **Uygulamalar**: Gerçekçi yüz üretimi, avatar oluşturma, sahte medya üretimi  

## ✅ CycleGAN ile Görüntü Dönüşümü (Zebraları Atlara Çevirmek vb.)  
- **CycleGAN Nedir?**  
  - Farklı veri setleri arasında görüntü dönüşümü (zebraları atlaya dönüştürmek gibi)  
  - Koşulsuz görüntü çevirisi yapar  
- **Mimari**  
  - İki generator (zebra -> at, at -> zebra) ve iki discriminator kullanımı  
- **Cycle Consistency Loss**  
  - Görüntü dönüşümünün geri alınabilir olması için tutarlılık kaybı eklenir  
- **Uygulamalar**: Fotoğraf filtreleri, stil transferi, görüntü restorasyonu  

## ✅ Pix2Pix ile Görüntü Tamamlama  
- **Pix2Pix Nedir?**  
  - Görüntüden görüntüye çeviri (örneğin, el çizimi haritalarını gerçekçi fotoğraflara dönüştürme)  
  - Koşullu GAN modeli kullanarak düşük kaliteli görüntüleri yüksek kaliteli hale getirme  
- **Mimari**  
  - **Conditional GAN**: Girilen görüntüye dayanarak hedef görüntüyü üretme  
- **Uygulamalar**: Fotoğraf restorasyonu, harita ve çizimden fotoğrafa dönüşüm  

## ✅ Super-Resolution GANs (SRGAN, ESRGAN)  
- **Super-Resolution GAN (SRGAN)**  
  - Düşük çözünürlüklü görüntülerden yüksek çözünürlükte görüntüler üretme  
  - **Perceptual Loss**: İnsan gözüyle daha uyumlu görüntüler üretmek için görsel algı kullanımı  
- **Enhanced Super-Resolution GAN (ESRGAN)**  
  - SRGAN'ın geliştirilmiş versiyonu  
  - Daha gerçekçi detaylar ve kaliteli görüntüler üretme  
- **Uygulamalar**: Fotoğraf iyileştirme, video çözünürlük artırma, medikal görüntüleme  
