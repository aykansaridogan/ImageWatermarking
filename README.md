# ImageWatermarking
Görüntü İşleme dersinde yaptığım Görüntü Filigranlama uygulaması


Filigran
(Watermark)

•Filigran diğer adıyla ‘watermark’ tanım olarak, bir görüntünün üzerine eklenen şeffaf damga, yazı, imza ya da logolara verilen addır.

•Dijital filigranlama, filigranlamanın en son şeklidir. Kağıttaki fiziksel filigranlara benzer şekilde, dijital filigranlar sahibi / yaratıcıyı tanımlamak ve görüntü, ses ve video gibi dijital ortamları doğrulamak için kullanılır


Neden Filigran?

- Fotoğraflar / Videolar viral hale geldiğinde, her 
yönden izlenemeyecek şekilde uçarlar. Çoğu 
zaman, sahip / yaratıcı bilgileri kaybolur veya 
unutulur.

- Başkaları tarafından kullanılan fotoğraflarınızı, 
resimlerinizi veya videolarınızı fiziksel ürünlerde, 
reklamlarda ve / veya web'de görme sürprizinden 
kaçının.

- Görünür ve / veya görünmez filigranlar ekleyerek 
oluşturduğunuzu bilmediklerini iddia eden 
intihalcilerin fikri mülkiyet (IP) çatışmalarından, 
maliyetli davalardan ve baş ağrısından kaçının.     


- Çünkü sosyal medyanın yaygın kullanımı, bir 
fotoğrafın / videonun viral hale gelme hızını artırdı.



![image](https://user-images.githubusercontent.com/105684427/171412781-5cd1d392-26d7-48f5-8dd6-80454f097ed0.png)




DWT (Ayrık Dalgacık Dönüşümü ) ile gri-seviyeli görüntü filigranlama yöntemi yapılıyor. Bu damgalama 
yönteminde eklenecek damgalar dört eşit parçalara ayrılmıştır. Saldırılara karşı damgalama yönteminin dayanıklılığını 
artırmak için bu parçaların her biri damga eklenecek görüntülerin DWT işlemi sonucunda elde edilen dört ayrı 
bantlarının farklı alt bölgelerine gizlenmiştir. 
Bu bantlar :
              LL1: Yaklaşık İmge Bandı
              HL1: Yatay Detay Bandı
              LH1: Dikey Detay Bandı
              HH1: Köşegen Detay Bandı

[Uy, Sy,Vy]=svd(LL2); 
kodunda ise LL2 tersi alınamayan matris olduğu için ayrıştırma yapılarak tersi alınıyor.
Smark = this.Sy + Alpha*Sw; bu işlemle filigran gömülüyor. 
Alpha ise bizim gömme kuvvetimizdir.


