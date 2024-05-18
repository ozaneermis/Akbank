# Most Streamed Spotify Songs 2023
![Spotify_Logo_CMYK_Green](https://github.com/ozaneermis/Spotify-2023/assets/74829981/3a6f1419-b1da-4ad2-87ce-edfd92dbdf4f)

* Bu veri kümesi, Spotify'da listelenen 2023'ün en ünlü şarkılarının bir listesini içerir. 
* Bu projede müzik dinleme platformu olan Spotify üzerinden veri analizi yapılmıştır.
* Exploratory Data Analysis yapılmıştır :
  
  * Outliers verilerini winsorize yöntemini uygulayarak sütunlar arasındaki korelasyon iyileştirilmiştir.
  * Key sütununa one-hot encoding uygulanmıştır.
  * Key ve BPM arasındaki ilişkiye bakılmıştır

Bu kodu indirip kullanmak isteyenler aşağıdaki path kısmına
<p> Bilgisayarda spotify-2023.csv dosyasının yolunu kopyalıyıp yapıştırması yeterli
>df = pd.read_csv('//content/drive/MyDrive/Data/spotify-2023.csv', encoding='latin1')


