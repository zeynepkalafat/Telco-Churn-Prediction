# Telco-Churn-Prediction


### İş Problemi

Şirketi terk edecek müşterileri tahmin edebilecek bir makine öğrenmesi modeli geliştirilmesi istenmektedir. 
Modeli geliştirmeden önce gerekli olan veri analizi ve özellik mühendisliği adımlarını gerçekleştirilecektir.


### Veri Seti Hikayesi

Telco müşteri kaybı verileri, üçüncü çeyrekte Kaliforniya'daki 7043 müşteriye ev telefonu ve İnternet hizmetleri sağlayan hayali bir telekom şirketi hakkında bilgi içerir. 
Hangi müşterilerin hizmetlerinden ayrıldığını, kaldığını veya hizmete kaydolduğunu gösterir.


### Değişkenler

* CustomerId ( Müşteri İd’si )
* Gender ( Cinsiyet )
* SeniorCitizen ( Müşterinin yaşlı olup olmadığı (1, 0) )
* Partner ( Müşterinin evli olup olmadığı (Evet, Hayır) )
* Dependents ( Müşterinin bakmakla yükümlü olduğu kişiler olup olmadığı (Evet, Hayır) )
* tenure ( Müşterinin şirkette kaldığı ay sayısı )
* PhoneService ( Müşterinin telefon hizmeti olup olmadığı (Evet, Hayır) )
* MultipleLines ( Müşterinin birden fazla hattı olup olmadığı (Evet, Hayır, Telefon hizmeti yok) )
* InternetService ( Müşterinin internet servis sağlayıcısı (DSL, Fiber optik, Hayır) )
* OnlineSecurity ( Müşterinin çevrimiçi güvenliğinin olup olmadığı (Evet, Hayır, İnternet hizmeti yok) )
* OnlineBackup ( Müşterinin online yedeğinin olup olmadığı (Evet, Hayır, İnternet hizmeti yok) )
* DeviceProtection ( Müşterinin cihaz korumasına sahip olup olmadığı (Evet, Hayır, İnternet hizmeti yok) )
* TechSupport ( Müşterinin teknik destek alıp almadığı (Evet, Hayır, İnternet hizmeti yok )
* StreamingTV ( Müşterinin TV yayını olup olmadığı (Evet, Hayır, İnternet hizmeti yok ) 
* StreamingMovies ( Müşterinin film akışı olup olmadığı (Evet, Hayır, İnternet hizmeti yok )
* Contract ( Müşterinin sözleşme süresi (Aydan aya, Bir yıl, İki yıl )
* PaperlessBilling ( Müşterinin kağıtsız faturası olup olmadığı (Evet, Hayır) )
* PaymentMethod ( Müşterinin ödeme yöntemi (Elektronik çek, Posta çeki, Banka havalesi (otomatik), Kredi kartı (otomatik) )
* MonthlyCharges ( Müşteriden aylık olarak tahsil edilen tutar )
* TotalCharges ( Müşteriden tahsil edilen toplam tutar )
* Churn ( Müşterinin kullanıp kullanmadığı (Evet veya Hayır) )

##### 21 Değişken 7043 Gözlem
##### Bağımllı değişken : Churn

##### Değişkenler müşteri hizmetleri, hesap ve demografik veriler hakkında bilgiler içerir.
- Müşterilerin kaydolduğu hizmetler : phone, multiple lines, internet, online security, online backup, device protection, tech support, streaming TV, streaming movies
- Müşteri hesap bilgileri : ne kadar süredir müşteri oldukları, sözleşme, ödeme yöntemi, kağıtsız faturalandırma, aylık ücretler, toplam ücretler
- Müşteriler hakkında demografik bilgiler : cinsiyet, yaş aralığı, evlilik durumu, bakmakla yükümlü oldukları kişiler olup olmadığı


