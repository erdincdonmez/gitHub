git ignore git sisteminin takip etmesini istemediğimiz dosyaları belirriğimiz özelliğidir.
.gitignore 

.env

- Dizinleri ise klasörün sonuna `/` işareti ekleyerek  belirtiriz. 

node-modules/ dist/ logs/

- `*` yıldız karakteriyle ise belirtilen ilk örnekte `.log` uzantısına sahip dosyaların tümünü, ikinci örnekte ise `files` klasör içerisindeki bütün dosyaları izlemeyi bırakacaktır. 

.log files/

- Eğer ki bir klasörümüzü içerisindeki bir dosya haricinde izlenmesini istemiyorsak `!` işareti ile bunu sağlayabiliriz. Bu örnekte `files` klasörü içerisindeki `example.txt` haricindeki dosyalar izlenmeyecektir. Files klasörü içerisindeki sadece **example.txt** git akışında görülecektir.

!files/example.txt

- Yukarıdaki örnekte dikkat edilmesi gereken önemli bir ayrıntıyı açıklayacak olursak eğer ki daha öncesinde `files` klasörü `.gitignore` dosyasına eklenmişse sonrasında ise `!`  içerisindeki dosya ile işlem yapmak işe **yaramayacaktır.**

files/ !files/example.txt

- `.gitignore` dosyasında yorum satırı oluşturmak için ise `#` karakteri kullanılır.