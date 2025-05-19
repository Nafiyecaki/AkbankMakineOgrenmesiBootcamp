# 🧠 Stroke Prediction - Akbank Makine Öğrenmesi Bootcamp

## 🔍 Proje Amacı
Bu projede, bireylerin sağlık ve yaşam tarzı özelliklerine göre felç (stroke) geçirme risklerini tahmin eden bir makine öğrenmesi modeli geliştirilmiştir.

## 📊 Veri Seti
- Kaynak: [Kaggle – Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
- Boyut: 5.110 örnek, 12 özellik
- Hedef Değişken: `stroke` (1 = felç geçirdi, 0 = geçirmedi)

## ⚙️ Kullanılan Yöntemler
- Veri Analizi (EDA)
- Eksik verilerin doldurulması
- Kategorik verilerin etiketlenmesi (`LabelEncoder`)
- Veri dengeleme: **SMOTE**
- Modelleme:
  - Logistic Regression
  - Random Forest
  - K-Nearest Neighbors
- Hiperparametre optimizasyonu: **GridSearchCV**

## 📈 Model Performans Sonuçları (Final Model: Logistic Regression)
- **Accuracy**: 0.75
- **Recall (stroke = 1)**: 0.80
- **Precision**: 0.14
- **F1-Score**: 0.24
- Model, yüksek riskli bireyleri belirlemede etkilidir ancak yanlış pozitif sayısı yüksektir. Bu model, ön tarama aracı olarak kullanılabilir.

## 📊 Görselleştirmeler
- Confusion Matrix
- Hedef değişken dağılımı
- ROC eğrisi (isteğe bağlı)

## 🔗 Kaggle Notebook
👉 [Kaggle notebook bağlantını buraya yapıştır]

## 💡 Geliştirme Önerileri
- Deep learning modelleri ile karşılaştırma
- Özellik mühendisliği ile yeni değişkenler ekleme
- Web arayüzü (Streamlit/Flask) ile kullanıcıya sunma
- Aynı veri seti ile gözetimsiz öğrenme (K-Means gibi)

## 📁 Dosya Yapısı
- 📦 AkbankMakineOgrenmesiBootcamp
- 📄 README.md
- 📄 stroke_prediction.ipynb
- 📄 requirements.txt (isteğe bağlı)
 
