# Breast-Cancer-Wisconsin
# Meme Kanseri Teşhisi: Yapay Zeka ile Karar Ağacı Modeli

Bu proje, [BLM463] Veri Madenciliği dersi kapsamında hazırlanmış olup, Wisconsin Breast Cancer veri seti üzerinde Decision Tree algoritması kullanılarak gerçekleştirilmiştir. Amaç, tümör özelliklerine bakarak kanser teşhisi yapılabilen bir makine öğrenmesi modeli geliştirmektir.

## 👩‍⚕️ Proje Özeti

- **Proje Adı:** Meme Kanseri Teşhisi - Karar Ağacı ile Makine Öğrenmesi
- **Model:** Decision Tree Classifier
- **Veri Kaynağı:** UCI Machine Learning Repository - Breast Cancer Wisconsin Diagnostic Data Set

## 📊 Kullanılan Teknolojiler

- Python (Jupyter Notebook)
- scikit-learn
- pandas, NumPy
- seaborn, matplotlib
- sklearn.tree & GridSearchCV

## 🔬 Proje Adımları

1. **Veri Seti Yükleme:**  
   `fetch_ucirepo()` ile UCI veri seti yüklendi.

2. **Ön İşleme & Analiz:**  
   Eksik veriler kontrol edildi, hedef değişken dağılımı analiz edildi.

3. **Model Eğitimi:**  
   Decision Tree modeli oluşturuldu, ardından Grid Search ile hiperparametre optimizasyonu yapıldı.

4. **Değerlendirme:**  
   Accuracy, Precision, Recall, F1-score, Specificity gibi metriklerle değerlendirme yapıldı.

5. **Görselleştirme:**  
   Confusion Matrix, ROC eğrisi ve karar ağacı görselleri oluşturuldu.

## 🔍 Model Performansı

| Metrik        | Değer  |
|---------------|--------|
| Accuracy      | %95.6  |
| Precision     | %94.8  |
| Recall        | %93.5  |
| Specificity   | %96.8  |
| F1-Score      | %94.1  |
| AUC Score     | 0.97   |

## 📁 Proje Dosyaları

- `verimadenciligisonhali.ipynb`: Notebook dosyası, tüm adımları içermektedir.
- `BLM463_Proje_MerveGok_21360859027.pdf`: Rapor&Dökümantasyon.
- `README.md`: Bu dosya.

## 🎥 Sunum Videosu

📺 [YouTube Video Linki – Proje Tanıtımı ve Model Açıklaması](https://youtu.be/XXXXXXXXXXX)  
> (Videoda proje anlatımı, model mantığı, kod detayları ve sonuç görselleştirmeleri bulunmaktadır.)

## 🔗 GitHub Kod Linki

📌 [GitHub Proje Deposu](https://github.com/kullaniciadi/veri-madenciligi-kanser-projesi)



---

