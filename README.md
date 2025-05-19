# AkbankMakineOgrenmesiBootcamp

# 🧠 Stroke Prediction with Logistic Regression

## 🔍 Proje Amacı
Bu projede, bireysel sağlık ve demografik verilerden yola çıkarak bireyin felç (stroke) geçirme riskini tahmin etmek amaçlanmıştır. 

## 📊 Kullanılan Veri Seti
- Kaynak: [Kaggle – Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
- Boyut: 5K kayıt
- Özellikler: yaş, cinsiyet, hipertansiyon, sigara durumu, vücut kitle endeksi vb.

## 🧪 Kullanılan Modeller
- Logistic Regression ✅
- Random Forest
- K-Nearest Neighbors
- SMOTE ile dengesiz veri sorunu çözüldü
- Hiperparametre optimizasyonu için GridSearchCV kullanıldı

## ✅ En Başarılı Model
- **Logistic Regression (C=0.01, penalty='l2')**
- Recall (stroke=1): **%80**
- Accuracy: **%75**
- F1-score: **0.24**
- Model, yüksek riskli bireyleri tespit etmede etkili ancak daha ileri filtreleme gerekebilir.

## 🔗 Kaggle Notebook
👉 [(https://www.kaggle.com/code/nafiyeak/akbankmakineo-renmesi)]

## 🛠 Geliştirilebilir Noktalar
- Veri arttırımı (data augmentation)
- Yeni özellik mühendisliği (feature engineering)
- Deep learning modelleriyle karşılaştırma
- Streamlit ile mini bir arayüz eklenebilir (bonus)

