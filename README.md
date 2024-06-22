# Cifar10_Dataset

Teknik Detaylar
1. Giriş
Bu çalışmanın amacı, CIFAR-10 veri setini kullanarak çeşitli makine öğrenimi ve derin öğrenme modellerinin performansını değerlendirmektir. CIFAR-10, 32x32 piksel boyutunda ve 10 farklı sınıfa ait 60.000 renkli görüntü içeren bir veri setidir. Proje kapsamında, modellerin doğruluğu, kesinlik, geri çağırma, F1-Skoru ve ROC AUC gibi metriklerle değerlendirilmiştir.
2. Kullanılan Modeller ve Performansları
•	Evrişimli Sinir Ağı (CNN):
o	Accuracy: %71
o	Precision: %72
o	Recall: %71
o	F1-Score: %71
o	ROC AUC: %96
•	K-En Yakın Komşular (KNN):
o	Accuracy: %34
o	Precision: %46
o	Recall: %32
o	F1-Score: %33
•	Lojistik Regresyon:
o	Accuracy: %37
o	Precision: %37
o	Recall: %37
o	F1-Score: %37
o	ROC AUC: %79
•	Karar Ağacı (Decision Tree):
o	Accuracy: %27
o	Precision: %27
o	Recall: %27
o	F1-Score: %27
o	ROC AUC: %60
•	Rastgele Orman (Random Forest):
o	Accuracy: %48
o	Precision: %48
o	Recall: %48
o	F1-Score: %48
o	ROC AUC: %86
•	LightGBM:
o	Accuracy: %53
o	Precision: %53
o	Recall: %53
o	F1-Score: %53
o	ROC AUC: %90
•	XGBoost:
o	Accuracy: %54
o	Precision: %54
o	Recall: %54
o	F1-Score: %54
o	ROC AUC: %90
•	CatBoost:
o	Accuracy: %45
o	Precision: %44
o	Recall: %45
o	F1-Score: %45
o	ROC AUC: %86
•	Gradient Boosting Machine (GBM):
o	Accuracy: %34
o	Precision: %34
o	Recall: %34
o	F1-Score: %34
o	ROC AUC: %75
•	Destek Vektör Makineleri (SVM):
o	Accuracy: %54
o	Precision: %54
o	Recall: %54
o	F1-Score: %54
o	ROC AUC: %90
3. Değerlendirme Metrikleri
Her model için doğruluk, kesinlik, geri çağırma ve F1-Skoru hesaplanmıştır. ROC AUC skorları, sınıflandırma performansını daha genel bir açıdan değerlendirmek için kullanılmıştır.
4. Sonuçlar ve Tartışma
Deney sonuçlarına göre, CNN ve SVM modelleri genel olarak en yüksek performansı göstermiştir. Özellikle ROC AUC skorları, bu modellerin sınıflandırma yeteneklerinin diğerlerine göre daha üstün olduğunu göstermektedir. Karar ağacı gibi basit modeller ise düşük performans sergilemiş ve daha karmaşık veri yapılarını işleme konusunda zorlanmıştır.
5. Genel Değerlendirme
Bu çalışma, CIFAR-10 veri seti üzerinde farklı makine öğrenimi ve derin öğrenme algoritmalarının performansını karşılaştırarak, her bir modelin güçlü ve zayıf yönlerini ortaya koymayı amaçlamıştır. Sonuçlar, veri bilimi uygulamaları için model seçiminde rehber oluşturabilecek niteliktedir.

