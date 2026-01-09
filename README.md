# 🎮 The E-Sports Tournament Challenge (Java)

Bu proje, yüzlerce oyuncunun katıldığı büyük ölçekli bir e-spor turnuvasını simüle eden bir Java uygulamasıdır. Sistem; oyuncu verilerini ve oyun baz puanlarını CSV dosyalarından okuyarak her oyuncu için 15 farklı maç simüle eder, puanları hesaplar ve sezon sonunda performanslarına göre madalya ataması yapar.

---

### 🌟 Temel Özellikler

* 
**🏗️ Nesne Yönelimli Yapı:** Oyuncu (Gamer), Oyun (Game) ve Maç (Match) gibi temel varlıklar sınıflar halinde tasarlanmıştır.


* 
**📊 Veri Yönetimi:** `ArrayList` kullanımına izin verilmeyen bu projede, veriler tamamen **1D ve 2D diziler** (Arrays) üzerinde yönetilir.


* 
**🎲 Rastgele Simülasyon:** Her maçta oynanan oyunlar ve bu oyunların tur sayıları (1-10 arası) rastgele belirlenir.


* 
**📈 Dinamik Puanlama:** Ham puanlar (Raw Points) üzerine oyuncu tecrübesine dayalı "Skill Points" ve maç performansına dayalı "Bonus Points" eklenerek nihai maç puanı hesaplanır.



---

### 🎓 Puanlama ve Madalya Sistemi

Sistem, sezon boyunca toplanan toplam puana göre oyunculara madalya atar.

| Madalya | Toplam Puan Eşiği |
| --- | --- |
| 🥇 **GOLD** | 2000 ve üzeri 

 |
| 🥈 **SILVER** | 1200 - 1999 

 |
| 🥉 **BRONZE** | 700 - 1199 

 |
| ❌ **NONE** | 700 altı 

 |

---

### 🔍 Analiz Sorguları (Queries)

Uygulama, turnuva sonunda aşağıdaki analizleri gerçekleştirir:

1. 
**En Yüksek Puanlı Maç:** Sezonun en skorer tekil maçı.


2. 
**En Düşük Puanlı Maç Analizi:** Maç içindeki en etkili oyun ve katkısı.


3. 
**En Başarılı Oyuncu:** Toplam puan, ortalama ve madalya bilgisi ile raporlanır.


4. 
**Madalya Dağılımı:** Tüm oyuncuların madalya sayıları ve yüzdelik dağılımı.



---

### 🛠️ Kurulum ve Kullanım

1. 
**Gerekli Dosyalar:** `games.csv` ve `gamers.csv` dosyalarının proje kök dizinindeki `Files/` klasöründe olması gerekir.


2. 
**Karakter Kodlaması:** Türkçe karakter desteği için proje **UTF-8** olarak ayarlanmalıdır.


3. **Derleme ve Çalıştırma:**
```bash
javac EsportsManagementApp.java
java EsportsManagementApp

```



---

### 📝 Örnek Çıktı Formatı

```text
Highest-Scoring Gamer:
Nickname: VoltRider
Name: Kerem Aslan
Total Points: 2678
Average Per Match: 178.53
Medal: GOLD

```

---

> [!IMPORTANT]
> Bu proje **CENG211 Programming Fundamentals** dersi ödevi kapsamında geliştirilmiştir. Dinamik veri yapıları (`List`, `ArrayList`) yerine tamamen statik diziler kullanılmıştır.
> 
> 
