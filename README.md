About the project:
ENG
This project aims to predict wine quality based on the physicochemical properties of Portuguese red wines using machine learning.
The Support Vector Regression (SVR) model was used to predict the quality scores.

A slight improvement in performance has been observed. There are small but meaningful differences in the R² score and error metrics. 
This indicates that hyperparameter tuning with grid search has improved the model's accuracy and provided more precise predictions.
The model can accurately predict a significant portion of the data, but still performs below 50% success.
This suggests that there is room for improvement, and the model can be further optimized.

TR
Bu proje, Portekiz kırmızı şaraplarına ait fizikokimyasal özelliklere dayanarak şarap kalitesini tahmin etmeyi amaçlayan bir makine öğrenimi uygulamasıdır. 
Destek Vektör Regresyonu (SVR) modeli kullanılarak kalite puanları tahmin edilmiştir.

Performansta hafif bir iyileşme gözlemlenmiş. R² skoru ve hata metriklerinde küçük ancak anlamlı farklar var.
Bu, grid search ile hiperparametre ayarının modelin doğruluğunu iyileştirdiğini ve daha hassas tahminler sunduğunu gösteriyor.

Model, verilerin büyük bir kısmını doğru şekilde tahmin edebiliyor, ancak hala %50'nin altında bir başarı gösteriyor.
Bu, geliştirme için yer olduğunu ve modelin mükemmelleştirilebileceğini gösteriyor.

Variables: fixed acidity: Sabit asidite

volatile acidity: Uçucu asidite

citric acid: Sitrik asit

residual sugar: Kalıntı şeker

chlorides: Klorürler

free sulfur dioxide: Serbest kükürt dioksit

total sulfur dioxide: Toplam kükürt dioksit

density: Yoğunluk

pH: pH

sulphates: Sülfatlar

alcohol: Alkol içeriği

quality: Şarap kalitesi (target variable)

We used the scikit-learn library to train and predict our model and to evaluate the model performance.

