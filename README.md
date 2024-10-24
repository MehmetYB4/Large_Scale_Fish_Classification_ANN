<h1 align="center">Balık Türleri Sınıflandırma Projesi 🐟</h1>

###

<p align="left">Bu proje, balık türlerini sınıflandırmak için bir derin öğrenme modeli geliştirmeyi amaçlar. Proje, Python dilinde yazılmış olup TensorFlow ve Keras kütüphanelerini kullanmaktadır.</p>

###

<h2 align="left">Proje Amacı 🎯</h2>

###

<p align="left">Bu projenin amacı, balık türlerini doğru bir şekilde sınıflandırabilen bir derin öğrenme modeli geliştirmektir. Model, balık resimlerini girdi olarak alır ve bu resimlerin hangi türe ait olduğunu belirler.</p>

###

<h2 align="left">Veri Seti 📊</h2>

###

<h2 align="left">Kod Yapısı 📁</h2>

###

<p align="left">Proje, Kaggle platformunda yer alan "A Large Scale Fish Dataset" veri setini kullanır. Bu veri seti, 9 farklı balık türüne ait resimler içerir:<br><br>    •Hourse Mackerel<br>    •Black Sea Sprat<br>    •Sea Bass<br>    •Red Mullet<br>    •Trout<br>    •Striped Red Mullet<br>    •Shrimp<br>    •Gilt-Head Bream<br>    •Red Sea Bream<br><br>    Toplam resim sayısı: 9000<br>    Resimler PNG formatındadır.</p>

###

<p align="left">Kod aşağıdaki adımlardan oluşur:<br><br>1. Modülleri İçe Aktarma 📦: Gerekli kütüphanelerin projeye dahil edilmesi.<br>2. Veri Setini Yükleme 📊: Balık türlerinin resimlerinden oluşan veri setinin yüklenmesi.<br>3. Veri Setini İnceleme 🔍: Veri setinin analiz edilmesi.<br>4. Veri Ön İşleme 🔄: Veri setinin ön işleme tabi tutulması, eğitime uygun hale getirilmesi<br>5. Modelleme 🤖: Model mimarisinin oluşturulması ve Modelin eğitilmesi.<br>6. Model Performansı ve Değerlendirme Metrikleri 📊: Grafiksel değerlendirme.<br>7. Test Verileri Üzerinde Sınıf Tahminleri 📝: Modelin sınıf tahminleri</p>

###

<h2 align="left">Kullanılan Kütüphaneler 📚</h2>

###

<p align="left">•TensorFlow & Keras: Derin öğrenme modeli oluşturmak için kullanılır.<br>•Pandas: Veri işleme ve manipülasyon için kullanılır.<br>•NumPy: Matris ve dizi işlemleri için kullanılır.<br>•Matplotlib & Seaborn: Görselleştirme ve veri analizi için kullanılır.</p>

###

<h2 align="left">Model Yapısı 🤖</h2>

###

<p align="left">Model, TensorFlow/Keras kullanılarak inşa edilmiştir ve aşağıdaki ana bileşenlerden oluşur:<br><br>Kullanılan ana katmanlar:<br>•Dense (Yoğun Katman): Tam bağlantılı katmanlar.<br>•Flatten (Düzleştirme Katmanı): Veriyi düzleştirir.<br>•Dropout (Bırakma Katmanı): Aşırı öğrenmeyi önler.<br>•BatchNormalization: Eğitim sırasında katman çıkışlarını normalize eder.<br><br>Adam optimizasyon algoritması kullanılmıştır.<br>Model, Sequential (Ardışık Model) mimarisini kullanır.</p>

###

<h2 align="left">Model Performansı 📈</h2>

###

<p align="left">Modelin eğitim ve validasyon sonuçları şu şekildedir:<br><br>    •Eğitim Loss: 0.2818<br>    •Validasyon Loss: 0.2421<br>    •Eğitim Accuracy (Doğruluğu): %90.74<br>    •Validasyon Accuracy (Doğruluğu): %91.56<br><br>Bu sonuçlar, modelin eğitim verisinde iyi performans gösterdiğini ve validasyon seti üzerinde de oldukça tutarlı olduğunu göstermektedir.</p>

###

<h2 align="left">Projeye Katkı 🛠️</h2>

###

<p align="left">Bu projeye dair her türlü öneriye açığım. Bir dal (branch) oluşturup, yaptığınız değişiklikleri pull request ile göndermeniz yeterli!.</p>

###

<h2 align="left">Kaggle Linki 📊</h2>

###

<p align="left">https://www.kaggle.com/code/mehmetyusuf/large-scale-fish-classification-ann</p>

###

<h2 align="left">Teşekkürler! 🙌</h2>

###

<p align="left">Bu projeye ilgi gösterdiğiniz ve katkı sağladığınız için teşekkür ederiz!</p>

###

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original-wordmark.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" height="40" alt="tensorflow logo"  />
</div>

###

<div align="center">
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"  />
</div>

###

<div align="center">
  <img src="https://profile-counter.glitch.me/MehmetYB4/count.svg?"  />
</div>

###
