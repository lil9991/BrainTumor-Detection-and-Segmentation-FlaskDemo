<div>
<h2>Proje Adı</h2>
<p>Brain Tumor Detection and Segmentation/Beyin Tümörü Tespiti ve Bölütleme</p>
</div>

<div><h2>Projenin Hedefi</h2>
Beyin tümörü, insan hayatını olumsuz etkileyen, ölümcül bir hastalıktır. Hastalığın erken teşhisi, hastanın yaşama şansını büyük oranda arttırmaktadır. Beyin tümörünü saptamak için genel yöntem Manyetik Rezonans Görüntüleme (MRI) taramalarıdır. MR görüntülerinden beyindeki anormal doku büyümesi hakkında bilgi belirlenir. Projenin temel hedefi bu görüntüleri kullanarak Derin Öğrenme yöntemleri ile erken teşhis için yardımcı sistem geliştirmek. 
</div>
<div><h2>Proje Adımları</h2>
  <li>Derin Öğrenme Yötemlerinin Kullanılması</li>
  <li>Web Geliştirme</li>
</div>

<div><h2>Kullanılan Yöntemler</h2>
  <li>Nesne tespiti : YOLOv4</li>
  <li>Segmentasyon  : Mask R-CNN</li>
   <h3>Segmentasyon(Bölütleme) nedir? </h3>
     <p> Görüntü segmentasyonu, görüntülerin analizi, artırılmış gerçeklik, yapay görme ve daha pek çok alanda sayısız uygulamaya sahip görüntü işlemenin bir dalıdır.
      Segmentasyon, bir giriş görüntüsünü, verilen görüntüdeki ilgi alanı (RoI) ile güçlü korelasyona sahip farklı bölümlere ayırmayı içerir [1]. Bu sayede her piksel       için etiketler çıkartılır ve bu etiketlere dair tahminler yapılarak birtakım çıkarımlarda bulunulur. Instance ve Semantic olarak 2 farklı türü vardır. </p>
     <img src="https://www.anolytics.ai/wp-content/uploads/2019/10/Nested-Classifications-for-Instance-Segmentation-1.png"  width="400" height="300" />
      
 
 <h3>Sağlıkta Segmentasyonun önemi? </h3>
  Medikal görüntü analizi alanı büyüyor ve tıbbi görüntülerdeki organların, hastalıkların veya anormalliklerin bölümlendirilmesi zorlu hale geliyor. Medikal görüntü      segmentasyonunun en önemli faydalarından biri, yalnızca gerekli alanları izole ederek anatomik verilerin daha kesin analizine izin vermesidir.
  Bu yöntem, Tümör gibi hastalıkların büyümesini kontrol etmeye, ilaç dozunu ve radyasyona maruz kalma dozunu kontrol etmeye yardımcı olur. Son zamanlarda, derin sinir ağları modelleri, çeşitli görüntü segmentasyon görevlerinde uygulama göstermiştir. Bu önemli büyüme, derin öğrenme stratejilerinin başarılarından ve yüksek performansından kaynaklanmaktadır. 
  
   <h3>Mask R-CNN:</h3>
     <ul>
     <lo>Instance Segmentasyon türüdür.</lo> <br>
     <lo>ResNet tabanlı CNN modelleri içerir.</lo> </ul>
  
 <h3>Mask R-CNN Çalışma Aşamaları:</h3>
   <ul>
     <lo>İlk aşamada görüntü taranır ve önerileri üretilir.</lo><br>
     <lo>İkinci aşamada ise önerilen nesnelerin sınıfıları belirlenir sonrasında sınırlayıcı kutular(bounding box) ve maskeler oluşturulur. </lo> </ul>
 
 <img
  src="https://miro.medium.com/max/1154/0*_p3LGIufAVslUhEw"
  width="500" height="400"> <br>
Proje kapmasımda kullanılan Mask R-CNN kod kaynaklarına [buradan](https://pysource.com/2021/08/10/train-mask-r-cnn-for-image-segmentation-online-free-gpu/) erişim sağlayabilirisniz. 
</div>

<div><h2>Yazılım Araçları</h2>
  <li>Visual Studio Code</li>
  <li>Google Colaboratory</li>
  <li>Roboflow</li>
  <li>Kaggle</li>
</div>  
  
<div> <h2>Veri Seti Oluşturma:</h2> 
Proje kapsamında her bir yöntem için 310 görüntü, toplamda 620 görüntü etiketlenmiştir. <br> </br>
 
<img src="https://github.com/lil9991/BrainTumor-Detection-and-Segmentation-FlaskDemo/blob/main/img/yolo.png"
  width="300" height="300"> 
  <img align = "left" src="https://github.com/lil9991/BrainTumor-Detection-and-Segmentation-FlaskDemo/blob/main/img/mask.png"
  width="300" height="300"> <br>
  <p> Veri Etiketleme Aracı : Make Sense AI <p>  
</div> 


<div><h2>Eğitimler Sonuçları</h2>
  <li>YOLOv4</li>
  
  <img src="https://github.com/lil9991/BrainTumor-Detection-and-Segmentation-FlaskDemo/blob/main/img/yolo.png"
  width="300" height="300"> 
  <li>Mask R-CNN</li>
  <img src="https://github.com/lil9991/BrainTumor-Detection-and-Segmentation-FlaskDemo/blob/main/img/yolo.png"
  width="300" height="300"> 
 </div>
 
<div>
<h2>Web Geliştirme</h2>
 <li>Arayüz : HTML, CSS ve JavaScript</li>
 <li>Backend: Flask</li>
 </div>

<div><h2>Proje Çıktısı</h2></div>

<div><h2>Kaynakları</h2></div>
https://www.hindawi.com/journals/jhe/2022/9580991/ <br>
https://merveelifsarac.medium.com/cnn-r-cnn-fast-r-cnn-mask-r-cnn-c90a1a4d76fb <br>

