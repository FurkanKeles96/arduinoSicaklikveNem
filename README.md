# arduinoSicaklikveNem
Wemos D1 ve DHT11 ile sıcaklık ve nem kontrolü

Projemizin asıl amacı kısaca uzaktan pencereyi açıp kapatmayı sağlayabilmektir. Ancak şu anda kullanılan
pencere modelleri uzaktan kontrol edilmeye pek elverişli değildir. Bundan dolayı projemizin yaptıkları
şunlardır:

  1. Wemos D1 ve DHT 11 sensörü kullanarak odanın sıcaklığını ve nemini ölçüyor.
  2. MQTT ile Adafruit bağlantısı kurularak sıcaklık ve nem değerlerini grafik olarak gösteriyor.
  3. Firebase Realtime Database ile anlık sıcaklık ve nem değerleri kaydediliyor.
  4. MIT App Inventor ile yapılan mobil uygulama sayesinde de anlık sıcaklık ve nem değerleri
     ölçülebiliyor.
  5. Ek olarak mobil uygulama içinde sanal olarak düşünülen pencere açıp kapatma metodu eklendi. Bu
     sayede uzaktan kontrol etmeyi simüle edebildik.
  6. Uygulamadan açık kapatılan pencere durumu da Firebase üzerindeki veritabanına kaydedildi.
