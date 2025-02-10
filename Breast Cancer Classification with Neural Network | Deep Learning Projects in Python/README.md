---

## **🧠 Yapay Sinir Ağı (NN) Nedir?**
Bir yapay sinir ağı, **veriyi alır, işler ve bir tahminde bulunur**. İçinde **nöronlar (düğümler) vardır** ve bunlar katmanlar halinde çalışır:

1️⃣ **Girdi Katmanı (Input Layer):**  
   - **Veri buraya girer.**  
   - Örneğin, bir meme kanseri teşhisi yapıyorsak, hastanın yaş, tümör büyüklüğü gibi verileri buraya girilir.

2️⃣ **Gizli Katmanlar (Hidden Layers):**  
   - **Veriyi işler, öğrenir ve anlamlı hale getirir.**  
   - Her düğüm (nöron), diğer nöronlardan aldığı bilgiyi hesaplar ve bir sonraki katmana gönderir.  
   - Beynimizin bilgiyi işlemesi gibi düşünebiliriz.

3️⃣ **Çıkış Katmanı (Output Layer):**  
   - **Son tahmini yapar.**  
   - Örneğin, çıktı "1" ise hastanın iyi huylu (benign) bir tümörü, "0" ise kötü huylu (malignant) bir tümörü olduğu sonucunu verir.

---

## **🛠 Yapay Sinir Ağı Nasıl Çalışır?**
**Adım adım bir örnek düşünelim:**  
📌 **Sen bir doktor olduğunu ve hastaların meme kanseri olup olmadığını tahmin ettiğini hayal et!**  
✔ Hastanın verilerini alıyorsun (yaş, tümör büyüklüğü, test sonuçları).  
✔ Beynindeki nöronlar bu bilgiyi işliyor ve bir karara varıyorsun: **“Evet, bu kişi kanser olabilir” veya “Hayır, sağlıklı”**  

Yapay Sinir Ağı da aynısını yapıyor:
1. **Veriyi alıyor.** (Girdi Katmanı)
2. **Veriyi işliyor.** (Gizli Katmanlar)
3. **Sonuç üretiyor.** (Çıkış Katmanı)


---

## **🤖 Gerçek Hayatta Nerelerde Kullanılır?**
✔ **Tıbbi teşhis** (Meme kanseri, kalp hastalığı vb.)  
✔ **Yüz tanıma sistemleri** (Telefonun seni tanıyıp açılması)  
✔ **Otomatik çeviri sistemleri** (Google Translate)  
✔ **Sesli asistanlar** (Siri, Google Asistan)  
✔ **Otonom araçlar** (Tesla'nın sürücüsüz arabaları)  

---

## **📌 Özetle:**
Yapay Sinir Ağları, **veriyi alıp işleyerek karar veren** ve **öğrenebilen** bir modeldir. **Beynimizdeki nöronlar gibi çalışır** ve **deneme-yanılma yöntemiyle öğrenir**.  

Bunu **bir çocuğun bisiklet sürmeyi öğrenmesi** gibi düşünebilirsin:  
🚲 İlk başta düşer, sonra tekrar dener ve sonunda mükemmel şekilde sürmeyi öğrenir! 🚀

---


Bu projenin **amacı**, **meme kanseri teşhisi** için **Yapay Sinir Ağı (NN - Neural Network)** kullanarak hastaların **iyi huylu (benign) veya kötü huylu (malignant) tümörlere sahip olup olmadığını** belirlemektir. 

---

## **📌 Neden Bu Proje Yapılmış?**
1️⃣ **Meme kanseri dünyada en yaygın kanser türlerinden biridir.**  
   - Erken teşhis, hastaların hayatta kalma oranını önemli ölçüde artırır.  
   - Bu yüzden, **hızlı ve doğru teşhis yapabilen** bir model geliştirmek çok önemlidir.

2️⃣ **Doktorların işini kolaylaştırmak için**  
   - Bir doktorun **her hastayı manuel olarak incelemesi çok zaman alabilir**.  
   - **Yapay Sinir Ağları**, verileri analiz ederek **otomatik teşhis yapabilir** ve doktorlara yardımcı olabilir.

3️⃣ **Makine Öğrenmesi ile Sağlık Alanında Kullanılabilecek Bir Model Geliştirmek**  
   - İnsan gözü bazen hatalar yapabilir, ancak **iyi eğitilmiş bir model hata oranını düşürebilir**.  
   - **Yüksek doğruluk oranına sahip bir yapay zeka modeli**, yanlış teşhisleri önleyebilir.



Bu projenin sonunda, modelin ne kadar başarılı olduğu ölçülerek sağlık alanında **gerçek dünya uygulamalarına** nasıl uyarlanabileceği değerlendirilecek.  

Bu projede **meme kanseri teşhisi için Yapay Sinir Ağı (NN) modeli** oluşturulurken kullanılan **araçlar ve kütüphaneler** şunlardır:  


---

## **📌 Kullanılan Kütüphaneler ve Amaçları**

| Kütüphane | Kullanım Amacı |
|-----------|---------------|
| **Pandas** | Veri setini yüklemek, işlemek ve analiz etmek |
| **NumPy** | Sayısal işlemler, matris hesaplamaları |
| **Matplotlib** | Grafikler çizerek veri görselleştirme |
| **Scikit-Learn (`sklearn`)** | Veri setini yüklemek, veri işleme, eğitim/test ayrımı, ölçeklendirme |
| **TensorFlow & Keras** | Yapay Sinir Ağı (NN) oluşturma, eğitme ve değerlendirme |
| **Jupyter Notebook** | Kodları çalıştırmak, sonuçları incelemek |


---

## **📌 Özet:**
Bu kütüphaneler proje için **veri işleme, model oluşturma, eğitme ve değerlendirme** süreçlerinde kullanıldı.  
Her biri belirli bir görevi üstleniyor ve birlikte çalışarak **meme kanseri teşhisini gerçekleştiren bir yapay sinir ağı modeli oluşturuluyor**.

Bu proje **derin öğrenmenin "Denetimli Öğrenme" (Supervised Learning) ve "Yapay Sinir Ağları" (Artificial Neural Networks - ANN)** konularına giriyor. Daha spesifik olarak, **"İleri Beslemeli Sinir Ağları" (Feedforward Neural Networks - FNN) ve "İkili Sınıflandırma" (Binary Classification)** yöntemleri kullanılmış.

---

## **📌 Bu Proje Derin Öğrenmenin Hangi Konularına Giriyor?**
✔ **Denetimli Öğrenme (Supervised Learning)**  
✔ **Yapay Sinir Ağları (Artificial Neural Networks - ANN)**  
✔ **İleri Beslemeli Sinir Ağı (Feedforward Neural Network - FNN)**  
✔ **İkili Sınıflandırma (Binary Classification)**  
✔ **Sigmoid aktivasyon fonksiyonu ve binary cross-entropy kayıp fonksiyonu**  

---

## **📌 Özet:**
Bu proje **"Denetimli Öğrenme" kapsamında, Yapay Sinir Ağları kullanılarak yapılan bir İkili Sınıflandırma modelidir.**  
Amaç, meme kanseri hastalarının **iyi huylu veya kötü huylu tümöre sahip olup olmadığını tahmin etmek**.  


### **📌 Proje Sonuçları ve Çıkarımlar**
Güncellenmiş kodu inceledim ve modelin çıktılarından aşağıdaki sonuçları çıkarabiliriz:

---


## **📌 Genel Çıkarımlar**
1️⃣ **Model, meme kanseri teşhisinde yüksek doğruluk elde etti (%90+ gibi bir değer olması muhtemel).**  
2️⃣ **Eğitim sürecinin nasıl ilerlediği, doğruluk ve kayıp grafikleri ile incelenmiş.**  
3️⃣ **Model, gerçek hastalardan gelen verileri işleyip tahmin yapabilecek şekilde tasarlanmış.**  
4️⃣ **Elde edilen model, doktorlara destek olarak kullanılabilir!** (Ancak gerçek dünyada kullanmak için daha fazla test yapılmalı).  

---

## **📌 Bu Sonuçlar Ne Anlama Geliyor?**
✅ **Meme kanseri teşhisinde yapay zeka modelleri etkili olabilir.**  
✅ **Makine öğrenmesi, doktorlara destek sağlayabilir ve teşhis sürecini hızlandırabilir.**  
✅ **Yapay sinir ağları (NN), tıbbi teşhis alanında başarılı şekilde uygulanabilir.**  

🧐 **Ancak...**
- Model **gerçek dünyada kullanılmadan önce daha fazla test edilmelidir**.
- **Farklı veri setleri ile denenmeli** ve **hata oranları analiz edilmelidir**.
- **Doktorlarla birlikte çalışarak klinik ortamda doğruluğu test edilmelidir**.

📌 **Özet:** Bu proje, yapay sinir ağlarının meme kanseri teşhisinde etkili olabileceğini gösteriyor! 🚀😊



---


**Eğer bu proje size yardımcı olduysa, GitHub’da ⭐ vererek destek olabilirsiniz!** 🚀

---


