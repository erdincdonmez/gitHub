# Git kullanımı
Git kullanımında önce git init ile git i aktif etmek gerekir.

## git komutları
* git init
* git status
* git branch
* ls -al
* git add .
* git status
* git diff
* git commit -m "Burada md dosyası içeriğine ekleme yapıldı"

## git commitine bir şeyleri daha eklemek için
* git add .
* git commit --amend
* git commit --amend -m "bu mesaj anmed ile commite eklenmiş mesaj"
- git log -n 1
- git log -n 2
- git log -n 1

- git revert 9b73cee7 ilgili loga geri alır.

- git reset --hard 9b73cee7
ilgili log arasındakileri siler.

git diff 9b73cee73..ac3bfb248961 bu iki id ile başlayan loglar arasındaki farkı göster.
git diff 9b73cee73..ac3bfb248961 readme.md bu iki id ile başlayan loglardaki readme.md dosyasını karşılaştır.

## Git ile çalışırken bir iş verirlerse;
bu durumda master üzerinde çalışmak yerine bir branch açıp orada çalışmak daha mantıklıdır.
git branch mevcut brachleri gösterir
git branch header header adında bir brach oluşturur.
git branch mevcut brachleri gösterir.
git checkout header diyerek kendi oluşturduğumuz brach a geçebiliriz.
git checkout -b footer kullanım şekliye branş oluşturup ona geçmemizi sağlar. Burada hali hazırda hangi branştaysak ondan kopya branş çıkartmış oluyoruz..
git branch -d deneme deneme branşını oluştur
git checkout header  header branşına geç
header branşında iken bir dosya oluştur.
git status mevcut durumu görüntüle
git add . geğişiklikleri kabul et.
git commit -m "Header-1 | header dosyası düzenleme" ile commitle
git checkout master dediğinizde diğer branşta oluşturduğunuz dosyayı göremeyiz.
touch foother.md dosya oluştur
[izleyebilirsin] (https://bit.ly/3ANLEZz) 
