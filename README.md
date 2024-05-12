# AI2




# Makine Öğrenimi Projesi: El Yazısı Rakam Tanıma
Bu proje, bir sinir ağı modeli oluşturarak el yazısı rakamları tanımak için kullanılır.
Model, MNIST veri kümesinden elde edilen 28x28 piksel boyutundaki gri tonlamalı görüntülerle eğitilir.
İlk olarak, giriş katmanı olarak Flatten katmanı eklenir, giriş verisi düzleştirilir.
Daha sonra, 128 nöronlu bir gizli katman ve 10 nöronlu bir çıkış katmanı eklenir.
Gizli katmanda ReLU aktivasyon fonksiyonu kullanılırken, çıkış katmanında softmax aktivasyon fonksiyonu kullanılır.
Bu model, el yazısı rakamlarını doğru bir şekilde sınıflandırmak için eğitilir.

















