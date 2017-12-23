# Cern-TTP8
21-27 Ocak 2018 tarihleri arasında yapılacak olan 8.Türk Öğretmen Çalıştayına ait belgelerin paylaşıldığı bir depodur. Bu çalıştayda yapılması düşünülen Moun dedektörü [Cosmic Watch](http://www.cosmicwatch.lns.mit.edu)  ve Python kullanarak CERN deneylerinden veri analizi nasıl yapılacağını gösteren [Parçacık Fiziği Oyun Alanı](http://particle-physics-playground.github.io) web siteleri kullanılarak ortak bir lise müfredatı geliştirmeye çalışılacaktır. 

## 1. Cosmic Watch Muon Dedektör Projesi 
Bu proje MIT Fizik [öğrencileri](http://www.cosmicwatch.lns.mit.edu/about#people) tarafından başlatılmış olup yaklaşık 100$ malolduğu belirtilmektedir. Bu projede algılayacı olarak plastik scintillator (plastik ışıldıyıcı) ve ışık toplayacı olarak da  photomultiplier (ışıl çoğaltıcı kulanılmaktadır. Muon dedektörü pil ile çalışmakta ve bu dedektör ile birlikte gelen yazılım ile ilginç deneyler yapılmaktaır. 
### 1.1 Cosmic Muons
Astrofiziksel parçacıkların (kozmik ışınların) atmosfer ile etkileşmesi sonucu Muon parçacıkları oluşur. Birçok kozmik ışınlar kendi galaksimizde (Samanyolu) oluşur ve bu ışınlar Supernova patmaları sonucu uzaya fırlatılan çekirdeklerdir. Bu kozmik ışınların %90'u proton, %9'u helyum çekirdeği ve geri kalan %1'i ise ağır çekirdeklerdir. Bu kozmik ışınlar atmosferdeki çekirdeklerle çarpıştığında, birçok parçacık ortaya çıkar. Bu parçacıklardan bazıları Piyon ve Kaonlardır. Piyonlar ve Kaonlar, Muonların oluşumu için öncü parçacıklardır. 

Kozmik ışınların atmosfer tabakası ile etkileşmelerinin sonunda muon parçacıkları oluşur. Muonların yükleri +1 veya -+ dir, yaklaşık olarak elektronlardan 200 kat fazla kütleye sahiptirler. Muonlar hakkında daha fazla bilgiye sahip olmak için [Particle Advanture ](http://www.particleadventure.org) web sitesini ziyaret edelibirsiniz. Muonlar kararsızdır ve bir elektron, bir nötrino ve bir antinötrinoya bozulurlar. Durağan halde muonların ömrü yaklaşık olarak 2.2 mikrosaniyedir. Muonlar yeryüzünden  yaklaşık 10 km üzerinde oluştuğundan dolayı, Galilean özel göreciliğine göre çok az bir kısmı yeryüzüne ulaşıp, muön dedektörü tarafından algılanabilir. Bununla birlikte, müonla yüksek enerjili parçacıklardır ve göreli zaman genişlemesi sonucu yaşam ömürlerini uzatırlar. Bunun sonucunda, müonlar  dünya yüzeyinde algılanacak kadar yaşayabilirler. 

Deniz seviyesinde dik bir muon algılayıcısının 1 cm^2'sine 1 dk.da düşen muon akısı yaklaşık olarak 1 dir. Deniz yüzeyine gelen muonlara, başka parçacık kalıntıları foton ve protonlar da eşlik eder. Yalnızca muonları algılamak için muon dedektörleri metal bir koruyucu kılıf içine konur. 

### 1.2 Cosmic Wathch Muon Dedektörü Nasıl Yapılır?
* Cosmic Watch algılayıcısının nasıl yapılacağı hakkında [adımlar](http://www.cosmicwatch.lns.mit.edu/detector#steps).
* Cosmic Watch ile ilgili [sıkca sorulan sorular](http://www.cosmicwatch.lns.mit.edu/faq).
* Cosmic Watch'un [github deposu](https://github.com/spenceraxani/CosmicWatch-Desktop-Muon-Detector). 
* Cosmic Watch'un nasıl yapılacağını anlatan [el kitapçığı](

#### 1.2.1 Silicon Photomultiplier( SiPM-Silikon Işık Çoğaltıcısı)
En pahalı olan bir malzeme olarak gözüküyor. Sensl sayfasında tanesi $119.00 satılıyor. Şu anda özel olarak indirimi uyguluyorlar. Şu andaki fiyatı yaklaşık 60$ ve 15$ yaklaşık fiyatı var. [Sensl sayfasından](http://sensl.com/estore/muon60035/) sipariş edebilirsin. Surface Mount Technology-Surface Mount Device (SMT,SMD) kullanarak üretilmiş. 

##### SMT ile kafama takılanlar:
* SMD'yi devreye nasıl monte edeceğiz. Bununla ilgili *Sensl*'in web sayfasında nasıl monte edeceğin üzerine bir belge yayınlamışlar. Bu belgeye [burdan](https://github.com/ofenerci/Cern-TTP8/blob/master/Malzemeler/TN-Handling%20and%20Soldering%20Guideline%20for%20%20SMT%20Devices.pdf) burdan ulaşabilirsin. 
* SMD'nin 4'nün bir arada olduğu bir chip [ArrayC-60035-4P-BGA](http://sensl.com/estore/arrayc-60035-4p-bga/) var. Bu chipin fiyatı $165.00 dır. Tekinin fiyatı yaklaşık $41.00'a geliyor. Cosmic Watch dedektöründe bunu kullanabilir miyim? Bu 4'lü olanının tek olarak satılan [microFC-60035-SMT]((http://sensl.com/estore/muon60035/) ne farkı var? 
* Bu parçayı Türkiye'den elde edebilir miyiz? 

#### 1.2.2 PCB 








