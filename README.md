# Sezgisel-Optimizasyon-Benzetilmis-Tavlama
Benzetilmiş tavlama tekniği ile gezgin satıcı problemi çözümü

YÖNTEM

Benzetilmiş tavlama, eniyileme problemi için tasarlanmış olasılıksal yaklaşımlı bir algoritmadır. Diğer olasılıksal yaklaşımlar gibi (genetik algoritmalar, tabu arama vb.) en iyi çözümün en kısa zamanda bulunmasını hedefler. Algoritmanın çalışması aslında isminin de geldiği demir tavlama işlemine benzer. Yani nasıl demir tavlama işlemi sırasında bir demir parçayı ısıtıp sonra soğumaya bırakıyorsak, herhangi bir sayısal ölçüme de benzeri yaklaşım uygulanabilir.

PROBLEM

Bu ödevde Gezgin Satıcı Problemi çözümlenmiştir. Amaç, bir satıcının bulunduğu şehirden başlayarak her şehre sadece bir kez uğradıktan sonra başladığı şehre dönen en kısa turu bulmaktır. Problem, çizge kuramı dilinde, şehirlerin noktalarla, şehirler arası yolların kenarlarla temsil edildiği (yalın) bir çizge üzerinde, en kısa Hamilton turunun bulunmasıdır. Hamilton turu, bir çizge üzerindeki her noktadan sadece bir kez geçen ve başladığı noktada biten, 19. yüzyılda yaşamış matematikçi William Hamilton’ın adıyla anılan turdur.Örneğin n noktadan oluşan bir tam çizge, yani Kn tamçizgesi (n−1)!/2 Hamilton turu içerir.

Bu örneğimizde 7 şehir vardır.Yani 6!/2=720 tur vardır.

![image](https://user-images.githubusercontent.com/49057258/151440123-81b16b9a-dddc-4b03-8f43-ef891ab07f0d.png)

