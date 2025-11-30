Karakter Tabanlı Hayatta Kalma Simülatörü
📌 Proje Açıklaması
Bu proje, C dili kullanılarak geliştirilen metin tabanlı bir hayatta kalma simülatörüdür. Oyuncu, tek karakterli komutlar (A, S, R, E, F, P, X) ile karakterini yönetir. Program, sağlık, enerji, yemek ve sığınak durumlarını takip eder ve oyuncunun verdiği komutlara göre güncellenmiş çıktılar üretir.

⚙️ Kullanılan C Yapıları
SWITCH–CASE → Komut yönetimi

IF–ELSE → Koşullu durumlar (örneğin avlanma başarısı)

Aritmetik Operatörler → Sağlık ve enerji değişimleri

Mantıksal Operatörler → Sığınak kontrolü

FOR Döngüsü → Tehlike dalgası simülasyonu

DO–WHILE Döngüsü → Şifreli ilerleme mekanizması

 Komutlar
A (Avlan): Enerji azalır, yemek bulunur veya sağlık kaybı yaşanır.

S (Sığınak Ara): Sığınak bulunur veya zaten varsa bilgi verilir.

E (Envanter): Yemek ve sığınak bilgisi ekrana yazılır.

R (Dinlen): Enerji ve sağlık artar, yemek varsa tüketilir.

F (Tehlike Dalgası): Döngü içinde sağlık/enerji kaybı simüle edilir.

P (Şifreli İlerleme): Doğru karakter girilene kadar devam eder.

X (Çıkış): Program sonlandırılır.

🖥️ Çalıştırma
Kod dosyasını derlemek ve çalıştırmak için:

bash
gcc main.c -o simulator
./simulator
📊 Örnek Çıktılar
Kod
Komut girin: A
Avlandiniz! Enerji -10, Yemek +1
Durum -> Saglik:95 Enerji:90 Yemek:1 Siginak:Yok
Kod
Komut girin: F
Tehlike dalgasi basladi!
Tur 1: Saglik -5, Enerji -5
Tur 2: Saglik -5, Enerji -5
...
📑 Rapor ve Video
Rapor dosyası (PDF) → Kod mantığının açıklaması

Video (max 15 dk) → Programın çalışmasını ve komutların etkilerini teknik olarak gösterir

🔗 GitHub Linki
