#git ile commit edilmiş değişiklikler gitHub reposuna nasıl push yapılır?
*Önce gitHub hesabında bir repository açın. Sonra sırasıyla.

##Çalışmaları git ile commitleme 
git init
git add .
git commit -m "ilk commit"

##Globale göndermeyi 4 adımda yapabilirsiniz.

git config --global user.name "erdincDonmez" 
ile kudllanıcı adını belirt.

git config --global user.email "erdinc_donmez@yahoo.com" 
ile hesap e-postanı belirt.

git remote add origin https://github.com/erdincdonmez/dotNetDers

git push -u origin master