# MAKİNE ÖĞRENMESİ NEDİR?

Makine öğrenmesi, bilgisayar sistemlerinin veri üzerinden örüntüler ve bilgi çıkarmayı öğrenmelerini sağlayan bir yapay zekâ alt dalıdır. 
Bu teknoloji, bir programın belirli bir görevi belirli bir performans ölçütüne göre geliştirmesini veya optimize etmesini sağlar. 
Geleneksel programlama yaklaşımından farklı olarak, makine öğrenmesi, bir algoritmanın doğrudan belirli bir görevi yerine getirmesi yerine, veri üzerinden öğrenme ve genelleme yeteneğine odaklanır.

### MAKİNE ÖĞRENMESİ ALGORİTMALARI NELERDİR?

#### 1- KNN(K NEAREST NEİGHBOR) EN YAKIN KOMŞU ALGORİTMASI
K-Nearest Neighbors (KNN), genellikle sınıflandırma ve regresyon problemleri için kullanılan basit bir makine öğrenimi algoritmasıdır. 
Temel fikir, bir veri noktasını çevresindeki K komşu noktanın etrafındaki çoğunluk sınıf veya ortalama değerine dayanarak sınıflandırmak veya tahmin yapmaktır.

  ##### KNN Algoritması Uygulama Adımları;
  
1.	Öncelikle K değeri belirlenir.
2.	Diğer nesnelerden hedef nesneye olan uzaklık hesaplanır. Belirli fonksiyonlar yardımıyla.
3.	Uzaklıklar sıralanır ve en minimum uzaklığa bağlı olarak en yakın komşular bulunur.
4.	En yakın komşu kategorileri toplanır.
5.	En uygun komşu kategorisi seçilir.

![knn1](https://github.com/fatmanurkarsatar/Machine_Learning_Projects/assets/93381609/89b0074a-c1cb-41be-913f-033c5189a064)

#### 2- YAPAY SİNİR AĞLARI(ANN - ARTİFİCİAL NEURAL NETWORKS)

Yapay Sinir Ağları (YSN veya İngilizce kısaltmasıyla ANN), insan beyninin çalışma prensiplerinden esinlenerek tasarlanmış bir makine öğrenimi modelidir. 
Yapay Sinir Ağları, bilgisayar bilimleri ve yapay zeka alanlarında geniş bir uygulama yelpazesi bulunmaktadır. 
Bu model, özellikle karmaşık görevleri gerçekleştirebilen ve desenleri öğrenme yeteneği olan sistemler geliştirmek için kullanılır.
Yapay Sinir Ağları, birçok bağlantılı bilgi işleme birimi veya "nöron" içeren bir ağ yapısına sahiptir. 
Bu nöronlar, biyolojik nöronların işlevselliğini taklit eden matematiksel modellerdir. 

![ysa](https://github.com/fatmanurkarsatar/Machine_Learning_Projects/assets/93381609/8546ebcb-b2da-411e-bf35-118a446234a3)


#### 3- KARAR AĞAÇLARI (DECİSİON TREES)

Karar Ağaçları, sınıflandırma ve regresyon problemlerini çözmek için kullanılan bir makine öğrenimi algoritmasıdır. 
Bu ağaç yapısı, bir dizi karar düğümünden oluşur ve her düğüm, bir özelliğe veya özniteliğe yönelik bir testi temsil eder. 
Her bir dal, bir karar veya tahmin sonucunu ifade eden yaprak düğümlerine kadar gider.

  ##### Karar ağaçları, genellikle şu temel adımları içeren bir öğrenme süreci kullanır:
  
1-Özellik Seçimi: Her düğümde, bir özellik seçilir ve bu özelliğe ilişkin bir test gerçekleştirilir.

2-Kararlar: Her test sonucuna göre kararlar alınır ve ağacın dalları oluşturulur. Bu işlem, özelliklerin ve testlerin sınıflandırma veya regresyon amacına uygun bir şekilde seçilmesini içerir.

3-Dallanma ve Yaprak Düğümler: Ağaç, belirli bir kriterin veya ölçütün belirlendiği düğümler arasında dallanır. Yaprak düğümlerinde, final sınıflandırma veya regresyon tahminleri bulunur.

![kararagac](https://github.com/fatmanurkarsatar/Machine_Learning_Projects/assets/93381609/0bd2be1e-2ce8-4c87-9ce2-908812ef9d95)

#### 4- DESTEK VEKTÖR MAKİNELERİ (SVM - SUPPORT VECTOR MACHINES)

Destek Vektör Makineleri (Support Vector Machines veya SVM), sınıflandırma ve regresyon problemlerini çözmek için kullanılan güçlü bir makine öğrenimi algoritmasıdır. 
SVM, özellikle orta ve yüksek boyutlu veri setlerinde etkili olan bir öğrenme modelidir.
SVM'in temel amacı, iki sınıf arasındaki karar sınırını (veya hiperdüzlemi) maksimize etmek ve bu sınırın her iki tarafındaki veri noktalarını birbirinden ayırmaktır.
SVM, veri noktalarını bu hiperdüzleme göre sınıflandırmak için destek vektörleri kullanır. 
Destek vektörler, karar sınırına en yakın olan ve sınıflandırma performansını etkileyen veri noktalarıdır.

![svm](https://github.com/fatmanurkarsatar/Machine_Learning_Projects/assets/93381609/c35e396e-53d5-4ba6-b689-91632852bf9f)

#### 5- K-MEANS KÜMELEME (K- MEANS CLUSTERİNG)

K-Means, veri kümeleme (clustering) algoritmalarından biridir ve özellikle unsupervised (denetimsiz) öğrenme problemlerinde kullanılır. 
K-Means algoritması, veri noktalarını belirli kriterlere göre gruplara (kümeler) ayırmak için kullanılır.
Her bir küme, benzerlik kriterlerine göre birbirine yakın veri noktalarını içerir.

  ##### K-Means algoritmasının çalışma mantığı şu adımları içerir:
  
1- Küme Merkezlerinin Başlangıç Belirlenmesi: İlk adımda, kullanıcı tarafından belirlenen veya rastgele seçilen k adet küme merkezi (centroid) başlangıç noktaları olarak atanır.
Her bir küme merkezi, bir kümenin temsilcisidir.

2-Veri Noktalarının Kümelenmesi: Her veri noktası, en yakın küme merkezine atanır ve bu şekilde kümelenmiş olur.

3-Küme Merkezi Yeniden Hesaplama: Her küme için yeni bir küme merkezi hesaplanır. Bu hesaplama, o kümeye ait veri noktalarının ortalamasını alarak yapılır.

4-Yeniden Kümelenme ve Merkez Hesaplama: Adımlar 2 ve 3, küme merkezleri ve veri noktalarının kümelenmesi tekrar tekrar güncellenene kadar devam eder.

5-Algoritmanın Sonlanması: Küme merkezleri artık önemli bir değişiklik göstermiyorsa veya belirlenen bir iterasyon sayısına ulaşıldığında, algoritma sonlanır.

![k-means](https://github.com/fatmanurkarsatar/Machine_Learning_Projects/assets/93381609/7f54c91c-3345-47ca-b6d0-dca7fce98d6d)












