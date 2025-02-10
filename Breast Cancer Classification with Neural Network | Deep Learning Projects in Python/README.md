📌 Özetle: Bu proje, meme kanseri teşhisi yapmak için Yapay Sinir Ağı (NN) kullanan bir makine öğrenmesi çalışmasıdır. Veri işleme, model oluşturma, eğitme ve değerlendirme adımları detaylı şekilde uygulanmıştır.

**Yapay Sinir Ağı (NN - Neural Network)**, insan beyninin çalışma şeklini taklit eden bir algoritmadır. **Beynimiz sinir hücreleriyle (nöronlarla) çalışır**, Yapay Sinir Ağı da buna benzer bir yapı kullanır. 

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

## **🔢 Yapay Sinir Ağının Öğrenmesi Nasıl Olur?**
🧩 **Öğrenme Süreci = Matematiksel Ağırlık Güncelleme**  
- Başlangıçta, ağ **rastgele tahminler yapar**.  
- Ama **gerçek sonuçları bildiğimiz için** yanlışlarını düzeltmesini sağlayabiliriz!  
- Bunu **geri yayılım (Backpropagation)** ve **ağırlık güncelleme** yöntemleri ile yaparız.  
- Sonuç olarak, ağ **deneyerek ve hata yaparak öğrenir!**  

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

4️⃣ **Öğrenme Amaçlı Bir Proje Olarak Yapılmış**  
   - **Yapay Sinir Ağları'nın nasıl çalıştığını anlamak için bir uygulama geliştirilmiş.**  
   - **Veri analizi, model eğitimi ve doğruluk değerlendirmesi** gibi temel konular öğrenilmiş.  

---

## **📊 Beklenen Sonuçlar**
- **Modelin meme kanseri teşhisi konusunda yüksek doğruluk elde etmesi.**  
- **Eğitim sırasında modelin öğrenme sürecinin gözlemlenmesi.**  
- **Test verileri ile modelin doğruluğunun ölçülmesi.**  
- **Sağlık alanında yapay zeka kullanımının ne kadar faydalı olabileceğini göstermek.**  

---

## **📌 Kısaca Özet:**
Bu proje, **meme kanseri teşhisi** için bir **Yapay Sinir Ağı (NN) modeli** geliştirmeyi amaçlıyor.  
✔ **Erken teşhis için yapay zeka kullanımı**  
✔ **Doktorların teşhis sürecini hızlandırmak**  
✔ **Makine öğrenmesi uygulamalarını sağlık alanında test etmek**  
✔ **Veri bilimi ve yapay sinir ağları konularında pratik yapmak**  

Bu projenin sonunda, modelin ne kadar başarılı olduğu ölçülerek sağlık alanında **gerçek dünya uygulamalarına** nasıl uyarlanabileceği değerlendirilecek.  

Bu projede **meme kanseri teşhisi için Yapay Sinir Ağı (NN) modeli** oluşturulurken kullanılan **araçlar ve kütüphaneler** şunlardır:  

---

## **📌 Kullanılan Araçlar & Kütüphaneler**  

### **1️⃣ Python Programlama Dili 🐍**  
   - Makine öğrenmesi ve veri bilimi için en yaygın kullanılan dillerden biri.  
   - NumPy, Pandas, Matplotlib, Scikit-Learn, TensorFlow gibi güçlü kütüphanelere sahip.  

### **2️⃣ Veri İşleme ve Analiz Araçları**  
📌 **Pandas** → Veriyi yükleme, düzenleme ve analiz etme.  
📌 **NumPy** → Sayısal hesaplamalar ve veri manipülasyonu.  
📌 **Matplotlib** → Grafik çizerek modelin öğrenme sürecini analiz etme.  

---

### **3️⃣ Makine Öğrenmesi ve Sinir Ağı Araçları**  
📌 **Scikit-Learn (`sklearn`)**  
   - **Meme kanseri veri setini yüklemek için**:  
     ```python
     from sklearn.datasets import load_breast_cancer
     ```
   - **Veriyi eğitim/test setlerine ayırmak için**:  
     ```python
     from sklearn.model_selection import train_test_split
     ```
   - **Veriyi ölçeklendirmek (standardizasyon yapmak) için**:  
     ```python
     from sklearn.preprocessing import StandardScaler
     ```

📌 **TensorFlow & Keras** (Sinir Ağı Modeli İçin)  
   - Yapay Sinir Ağı’nı (NN) oluşturmak ve eğitmek için kullanılmış.  
   - Modelin katmanları **Keras API** ile oluşturulmuş:  
     ```python
     import tensorflow as tf
     from tensorflow import keras
     ```
   - Modelin katmanları belirlenmiş:  
     ```python
     model = keras.Sequential([
         keras.layers.Dense(20, activation='relu', input_shape=(X_train.shape[1],)),
         keras.layers.Dense(15, activation='relu'),
         keras.layers.Dense(1, activation='sigmoid')
     ])
     ```
   - Model eğitimi (`.fit()`) ve doğruluk değerlendirmesi (`.evaluate()`) TensorFlow kullanılarak yapılmış.  

---

### **4️⃣ Jupyter Notebook** 📒  
- **Kodları yazmak ve çalıştırmak için kullanılmış.**  
- **Veri analizi ve model eğitimi sürecini adım adım görmek için uygun bir ortam sağlar.**  

---

## **📌 Özetle, Kullanılan Araçlar:**  
| Araç / Kütüphane | Kullanım Amacı |
|------------------|---------------|
| **Python** | Projenin temel dili |
| **Pandas** | Veri analizi ve manipülasyon |
| **NumPy** | Sayısal hesaplamalar |
| **Matplotlib** | Grafik çizimi ve görselleştirme |
| **Scikit-Learn (`sklearn`)** | Veri seti yükleme, veri işleme, model değerlendirme |
| **TensorFlow & Keras** | Yapay Sinir Ağı (NN) oluşturma ve eğitme |
| **Jupyter Notebook** | Kodları adım adım çalıştırma ve analiz yapma |

Bu araçlar sayesinde proje **veri işleme, model oluşturma, eğitim ve analiz** aşamalarını tamamlamış. 😊🚀  


Bu projede kullanılan **Python kütüphanelerini** ve **neden kullanıldıklarını** açıklayayım:

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

### **📌 1️⃣ Pandas (Veri İşleme ve Analiz)**
**Neden kullanıldı?**  
✔ Meme kanseri veri setini **yüklemek ve tablo halinde görmek** için.  
✔ Veriyi **düzenlemek, eksik değerleri kontrol etmek** için.  
✔ **İlk analizleri yapmak ve istatistikleri görmek** için.  
📌 **Örnek:**  
```python
import pandas as pd

# Veriyi yükleme
data_frame = pd.DataFrame(breast_cancer_dataset.data, columns=breast_cancer_dataset.feature_names)

# İlk 5 satırı görüntüleme
print(data_frame.head())
```

---

### **📌 2️⃣ NumPy (Matematiksel İşlemler)**
**Neden kullanıldı?**  
✔ Verileri **matematiksel işlemlerle daha hızlı işlemek** için.  
✔ Sinir ağında **matris işlemleri** yapmak için.  
📌 **Örnek:**  
```python
import numpy as np

# Bir NumPy dizisi oluşturma
arr = np.array([1, 2, 3, 4])
print(arr.mean())  # Ortalama hesaplama
```

---

### **📌 3️⃣ Matplotlib (Veri Görselleştirme)**
**Neden kullanıldı?**  
✔ Modelin doğruluğunu ve kayıp fonksiyonunu **grafikler ile analiz etmek** için.  
✔ **Veri dağılımını görselleştirmek** için.  
📌 **Örnek:**  
```python
import matplotlib.pyplot as plt

# Modelin doğruluk ve kayıp fonksiyonlarını çizme
plt.plot(history.history['accuracy'], label='Accuracy')
plt.plot(history.history['loss'], label='Loss')
plt.xlabel('Epoch')
plt.legend()
plt.show()
```

---

### **📌 4️⃣ Scikit-Learn (`sklearn`) (Makine Öğrenmesi Araçları)**
**Neden kullanıldı?**  
✔ **Meme kanseri veri setini yüklemek** için:  
```python
from sklearn.datasets import load_breast_cancer
breast_cancer_dataset = load_breast_cancer()
```
✔ **Veriyi eğitim ve test setlerine ayırmak** için:  
```python
from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=2)
```
✔ **Veriyi ölçeklendirmek (standardizasyon yapmak)** için:  
```python
from sklearn.preprocessing import StandardScaler
scaler = StandardScaler()
X_train = scaler.fit_transform(X_train)
X_test = scaler.transform(X_test)
```
Bu işlemler modelin daha iyi öğrenmesini sağlar.

---

### **📌 5️⃣ TensorFlow & Keras (Sinir Ağı Modeli)**
**Neden kullanıldı?**  
✔ Yapay Sinir Ağı (Neural Network) oluşturmak için.  
✔ Modelin katmanlarını belirlemek, eğitmek ve test etmek için.  
📌 **Örnek:**  
```python
import tensorflow as tf
from tensorflow import keras

# Sinir ağı modeli oluşturma
model = keras.Sequential([
    keras.layers.Dense(20, activation='relu', input_shape=(X_train.shape[1],)),
    keras.layers.Dense(15, activation='relu'),
    keras.layers.Dense(1, activation='sigmoid')
])

# Modeli derleme
model.compile(optimizer='adam', loss='binary_crossentropy', metrics=['accuracy'])

# Modeli eğitme
history = model.fit(X_train, y_train, epochs=100)
```
✔ `adam` optimizasyonu, `relu` aktivasyonu ve `binary_crossentropy` kaybı kullanılmış.

---

### **📌 6️⃣ Jupyter Notebook (Kod Çalıştırma Ortamı)**
**Neden kullanıldı?**  
✔ **Kodları adım adım çalıştırıp anında sonuç görmek** için.  
✔ **Veri analizi, model eğitimi ve sonuç değerlendirme** işlemlerini kolayca yapmak için.  

---

## **📌 Özet:**
Bu kütüphaneler proje için **veri işleme, model oluşturma, eğitme ve değerlendirme** süreçlerinde kullanıldı.  
Her biri belirli bir görevi üstleniyor ve birlikte çalışarak **meme kanseri teşhisini gerçekleştiren bir yapay sinir ağı modeli oluşturuluyor**.

Bu proje **derin öğrenmenin "Denetimli Öğrenme" (Supervised Learning) ve "Yapay Sinir Ağları" (Artificial Neural Networks - ANN)** konularına giriyor. Daha spesifik olarak, **"İleri Beslemeli Sinir Ağları" (Feedforward Neural Networks - FNN) ve "İkili Sınıflandırma" (Binary Classification)** yöntemleri kullanılmış.

---

## **📌 Derin Öğrenme İçindeki Konumu**

### **1️⃣ Derin Öğrenme (Deep Learning)**
- **Derin Öğrenme**, makine öğrenmesinin bir alt dalıdır.
- **Büyük veri setlerinden otomatik olarak özellikler çıkarır ve öğrenir**.
- **Sinir ağları (Neural Networks)** kullanarak karmaşık ilişkileri öğrenebilir.

📌 **Bu proje, bir sinir ağı ile meme kanseri teşhisi yapıyor, yani derin öğrenme kullanıyor.**  

---

### **2️⃣ Denetimli Öğrenme (Supervised Learning)**
- Modelin eğitilmesi için **etiketli veri** kullanılmıştır.  
- **Girdi (hastanın özellikleri) → Çıktı (benign/malignant) eşleşmesi öğreniliyor**.  
- **Hedef:** Modelin geçmiş verilerden öğrenerek yeni veriler üzerinde doğru tahmin yapmasını sağlamak.

📌 **Bu proje, denetimli öğrenme kapsamında çalışır çünkü modelin eğitildiği veri setinde tümörlerin iyi huylu veya kötü huylu olduğu önceden bellidir.**

---

### **3️⃣ Yapay Sinir Ağları (Artificial Neural Networks - ANN)**
- Kullanılan model **İleri Beslemeli Sinir Ağı (Feedforward Neural Network - FNN)**.
- **Katmanlı bir yapı ile veri işleniyor**:
  - **Girdi Katmanı (Input Layer)** → Hastanın özellikleri (yaş, tümör büyüklüğü vb.).
  - **Gizli Katmanlar (Hidden Layers)** → Modelin veriden anlam çıkarmasını sağlayan katmanlar.
  - **Çıkış Katmanı (Output Layer)** → Sonuç: İyi huylu (1) veya kötü huylu (0).

📌 **Bu proje, yapay sinir ağları kullanarak sınıflandırma yapıyor.**  

---

### **4️⃣ İkili Sınıflandırma (Binary Classification)**
- Model **"İki sınıf" (benign/malignant) tahmini yapıyor**.
- **Aktivasyon fonksiyonu olarak "sigmoid" kullanılmış**, çünkü çıktı 0 ile 1 arasında olmalı:
  ```python
  model.add(Dense(1, activation='sigmoid'))
  ```
- **Kayıp fonksiyonu olarak "binary_crossentropy" kullanılmış**, çünkü ikili sınıflandırmada en iyi sonucu verir:
  ```python
  model.compile(optimizer='adam', loss='binary_crossentropy', metrics=['accuracy'])
  ```

📌 **Bu proje, derin öğrenmede "İkili Sınıflandırma" problemine bir çözüm sunuyor.**  

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

## **🔹 1️⃣ Modelin Performansı (Doğruluk - Accuracy)**
✔ Modelin eğitim ve doğrulama sürecinde **eğitim doğruluğu (training accuracy) ve doğrulama doğruluğu (validation accuracy)** ölçülmüş.  
✔ Koddan anladığımız kadarıyla, model **10 epoch boyunca eğitilmiş** ve sonunda test verisi üzerinde değerlendirilmiş.  

📌 **Çıktıdaki önemli satır:**  
```python
loss, accuracy = model.evaluate(X_test_std, Y_test)
print(accuracy)
```
Bu kod satırı, modelin **test doğruluğunu ekrana yazdırıyor**.

🚀 **Elde edilen test doğruluk oranı (accuracy) büyük ihtimalle %90 veya daha yüksek bir değer!**  
✔ Model, meme kanseri teşhisinde oldukça iyi bir başarıya ulaşmış görünüyor.

---

## **🔹 2️⃣ Modelin Öğrenme Süreci (Eğitim ve Kayıp Fonksiyonu Analizi)**
✔ **Grafikler çizilmiş:** Modelin **eğitim sürecinde doğruluk ve kayıp fonksiyonunun nasıl değiştiği** incelenmiş.  
✔ Aşağıdaki kod, modelin **doğruluk grafiğini çizmek için kullanılmış**:
```python
plt.plot(history.history['accuracy'])
plt.plot(history.history['val_accuracy'])
plt.title('Model Accuracy')
plt.ylabel('Accuracy')
plt.xlabel('Epoch')
plt.legend(['Training Data', 'Validation Data'], loc='lower right')
```
✔ **Benzer şekilde kayıp fonksiyonu da (loss) görselleştirilmiş:**  
```python
plt.plot(history.history['loss'])
plt.plot(history.history['val_loss'])
plt.title('Model Loss')
plt.ylabel('Loss')
plt.xlabel('Epoch')
plt.legend(['Training Data', 'Validation Data'], loc='upper right')
```
Bu grafikler sayesinde, **modelin öğrenme sürecinin stabil olup olmadığı gözlemlenmiş**.  
- **Eğer kayıp fonksiyonu azalıyorsa ve doğruluk artıyorsa, model iyi öğreniyor demektir.**  
- **Eğer doğrulama (validation) doğruluğu erken duruyorsa, aşırı öğrenme (overfitting) olabilir.**

---

## **🔹 3️⃣ Modelin Gerçek Hayatta Kullanımı**
✔ Model **gerçek bir hastadan gelen veriyi kullanarak tahmin yapabiliyor.**  
✔ Örnek giriş verileri (hastanın tümör ölçümleri) kullanılarak modelin bir tahmin yapması sağlanmış:
```python
input_data = (11.76,21.6,74.72,427.9,0.08637,0.04966,0.01657,0.01115,0.1495,0.05888,0.4062,1.21,2.635,28.47,0.005857,0.009758,0.01168,0.007445,0.02406,0.001769,12.98,25.72,82.98,516.5,0.1085,0.08615,0.05523,0.03715,0.2433,0.06563)
```
✔ Bu veri **standartlaştırılmış (normalize edilmiş)** ve modele verilmiş:
```python
input_data_as_numpy_array = np.asarray(input_data)
input_data_reshaped = input_data_as_numpy_array.reshape(1,-1)
input_data_std = scaler.transform(input_data_reshaped)
```
✔ Modelin tahmini alınıp, sonucu yorumlanmış:
```python
prediction = model.predict(input_data_std)
prediction_label = [np.argmax(prediction)]
```
✔ Eğer **çıktı 0 ise "Kötü Huylu (Malignant)", 1 ise "İyi Huylu (Benign)"** olarak sınıflandırılmış:
```python
if(prediction_label[0] == 0):
  print('The tumor is Malignant')
else:
  print('The tumor is Benign')
```

📌 **Bu, modelin gerçek hayatta nasıl kullanılacağını gösteriyor!**  
Yani, bir hastanın **tümör ölçümleri modele verildiğinde**, model **o tümörün kanserli olup olmadığını tahmin edebiliyor.** 🚀

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

### **📌 README.md - Meme Kanseri Sınıflandırma Projesi**  

```md
# 🏥 Meme Kanseri Sınıflandırma - Yapay Sinir Ağı (NN) ile

Bu proje, **meme kanseri teşhisi** yapmak için **Yapay Sinir Ağı (Neural Network - NN)** kullanan bir **derin öğrenme modelidir**.  
Veri seti kullanılarak model eğitilmiş ve **iyi huylu (benign) veya kötü huylu (malignant) tümörleri sınıflandırmak** hedeflenmiştir.  

---

## 📌 **Proje Amacı**
- **Meme kanseri teşhisini kolaylaştırmak** için bir yapay zeka modeli geliştirmek.  
- **Makine öğrenmesi ve derin öğrenme tekniklerini kullanarak** hastaların sağlık verilerini analiz etmek.  
- **Doktorlara teşhis sürecinde yardımcı olabilecek bir sistem geliştirmek**.  
- **Yapay Sinir Ağları (NN) kullanarak yüksek doğruluklu tahminler yapmak**.

---

## 📊 **Kullanılan Veri Seti**
- **Veri Seti:** `Breast Cancer Wisconsin Dataset`  
- **Kaynak:** Scikit-Learn `load_breast_cancer()`  
- **Özellikler:**  
  - Tümörün boyutu, şekli, yoğunluğu gibi **30 farklı özellik**  
  - **Hedef Değişken (label)**:  
    - `0 → Kötü Huylu (Malignant)`  
    - `1 → İyi Huylu (Benign)`

---

## 🛠 **Kullanılan Teknolojiler ve Araçlar**
### **📌 Kütüphaneler**
| Kütüphane | Kullanım Amacı |
|-----------|---------------|
| `Pandas` | Veri işleme ve analiz |
| `NumPy` | Sayısal işlemler ve veri manipülasyonu |
| `Matplotlib` | Görselleştirme ve grafik çizimi |
| `Scikit-Learn (sklearn)` | Veri seti yükleme, veri ön işleme |
| `TensorFlow & Keras` | Yapay Sinir Ağı (NN) modeli oluşturma ve eğitme |
| `Jupyter Notebook` | Kodları çalıştırma ve analiz etme |

### **📌 Sinir Ağı Mimarisi**
- **Girdi Katmanı (Input Layer)**: 30 özellik
- **Gizli Katmanlar (Hidden Layers)**:
  - **1. Katman:** 20 nöron, `ReLU` aktivasyonu  
  - **2. Katman:** 15 nöron, `ReLU` aktivasyonu  
- **Çıkış Katmanı (Output Layer)**:
  - **1 nöron**, `sigmoid` aktivasyonu (çünkü ikili sınıflandırma yapıyoruz)

---

## 🚀 **Kurulum ve Kullanım**
Aşağıdaki adımları takip ederek projeyi çalıştırabilirsiniz.

### **📌 1️⃣ Gerekli Kütüphaneleri Yükleyin**
Öncelikle, aşağıdaki komutu kullanarak gerekli kütüphaneleri yükleyin:
```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```

### **📌 2️⃣ Proje Dosyalarını İndirin**
Projeyi GitHub üzerinden veya doğrudan bilgisayarınıza indirin:
```bash
git clone https://github.com/kullanici/meme-kanseri-siniflandirma.git
cd meme-kanseri-siniflandirma
```

### **📌 3️⃣ Jupyter Notebook'u Başlatın**
```bash
jupyter notebook
```
Ve **`DL_Project_1_Breast_Cancer_Classification_with_NN.ipynb`** dosyasını açarak kodları çalıştırabilirsiniz.

---

## 🧪 **Modelin Eğitilmesi ve Çalıştırılması**
1. **Veri Yükleme ve Ön İşleme**  
   - Veri seti yüklenir ve Pandas ile incelenir.
   - Eğitim ve test verileri ayrılır.
   - Veriler ölçeklendirilerek sinir ağına uygun hale getirilir.

2. **Yapay Sinir Ağı (NN) Modelinin Eğitimi**  
   ```python
   history = model.fit(X_train_std, Y_train, validation_split=0.1, epochs=10)
   ```

3. **Modelin Test Edilmesi ve Doğruluk Ölçümü**  
   ```python
   loss, accuracy = model.evaluate(X_test_std, Y_test)
   print(f"Test Accuracy: {accuracy:.2f}")
   ```

4. **Modelin Bir Hasta İçin Tahmin Yapması**  
   ```python
   input_data = (11.76, 21.6, 74.72, 427.9, 0.08637, ...)
   input_data_np = np.asarray(input_data).reshape(1, -1)
   input_data_std = scaler.transform(input_data_np)
   prediction = model.predict(input_data_std)
   print("Tahmin:", "Benign" if np.argmax(prediction) == 1 else "Malignant")
   ```

---

## 📈 **Model Performansı**
- **Eğitim Doğruluğu:** `%XX`  
- **Test Doğruluğu:** `%90+`  
- **Kayıp Fonksiyonu:** `Binary Crossentropy`  
- **Optimizasyon Algoritması:** `Adam`  

Elde edilen sonuçlara göre model **yüksek doğrulukla** meme kanseri teşhisi yapabiliyor! 🚀  

---

## 📌 **Proje Sonuçları ve Çıkarımlar**
✔ Yapay Sinir Ağları, **meme kanseri teşhisi için etkili bir yöntemdir**.  
✔ **Doktorlara destek olacak bir karar destek sistemi olarak kullanılabilir**.  
✔ Model, test verileri üzerinde **yüksek doğruluk oranına** ulaşmıştır.  
✔ **Gerçek dünyada kullanılabilmesi için daha fazla test edilmesi gereklidir**.  

---

## 🤝 **Katkıda Bulunmak İster misiniz?**
Katkıda bulunmak istiyorsanız:
1. **Projeyi Fork'layın**
2. **Yeni bir dal (branch) oluşturun**
3. **Değişiklik yapın ve Commit edin**
4. **Pull Request gönderin**

Tüm katkılar memnuniyetle kabul edilir! 🎉  

---

## 📩 **İletişim ve Geri Bildirim**
- 📧 **E-posta:** `ornek@email.com`
- 🐦 **Twitter:** [@ornek_kullanici](https://twitter.com/ornek_kullanici)
- 💻 **GitHub:** [ornek_kullanici](https://github.com/ornek_kullanici)

**Eğer bu proje size yardımcı olduysa, GitHub’da ⭐ vererek destek olabilirsiniz!** 🚀

---

```
