# Women in Tech Academy Bitirme Projesi

<img width="900px" src="https://user-images.githubusercontent.com/94361819/182606493-1bc1601a-bda2-4156-9209-66f62cc5ed91.gif"></a>

## Bu repository [SistersLab-Women in Tech Academy](https://sisterslab.co/women-in-tech-academy/) Python Eğitimi Bitirme Projesini yayınlamak amacıyla oluşturulmuştur.

**Toplum Gönüllüleri Vakfı tarafından desteklenen Women in Tech Academy Projesi, üniversite 3. & 4. sınıf veya üniversite mezunu 20-28 yaş aralığındaki genç kadınları, eğitimlerle uzmanlaştırıp yazılım sektöründe iş gücüne katılımını hedeflemektedir.**

**Proje kapsamında, NBA verilerini içeren 5 farklı csv dosyası analiz edilmiştir. Analizler görselleştirmeler ile desteklenmiştir.**

## Analizde Kullanılan Kütüphaneler:

- Numpy
- Pandas
- Matplotlib

## Veri Setlerinin Açıklamaları:

Veri setleri games_details, games, players, ranking ve teams'tir.

- games_details (df1): Oyun idlerine göre oyuncular hakkında detaylı bilgileri içerir.

- games (df2): Maç istatistiklerini ve maçlar hakkında genel bilgiler bu dosyada yer almaktadır.

- players (df3): Oyuncular hakkında bilgileri içeren dosyadır.

- ranking (df4): Her takımın sezonlara göre yaptığı maç sayısı, kazandığı maç sayısı vb. bilgileri içerir.

- teams (df5): Takıma ait  detaylı bilgileri içerir.


## Yapılan analiz işlemleri  aşağıda listelenmiştir:

- Dosyaların Okunması, satır-sütun sayılarının bulunması, sütun adlarının güncellenmesi.
- Verilerde yer alan NaN değerlerin sayısının bulunması ve sütunlara göre yüzdelik olarak kayıp veri oranının hesaplanması.
- Ev sahibi ve deplasman takımlarının kazanma sayılarının bulunması ve görselleştirilmesi, bulunan sayıların yüzdelik olarak hesaplanması.
- Ev sahibi ve deplasman takımlarının ortalama assist, ortalama rebound sayılarının ve ortalama puanlarının karşılaştırılması ve görselleştirilmesi.
- Ev sahibi ve deplasman takımlarının  ortalama üçlük atış başarı oranı  ve ortalama sayı atış başarı oranlarının hesaplanması ve görselleştirilmesi.
- Maçlara göre takımların kaç oyuncusunun olduğunun gösterilmesi.
- Oyun idlerine göre takımlarda hangi oyuncuların yer aldığının gösterilmesi
- Oyuncuların üçlük atış başarı oranı üzerinden kategorizasyonunun yapıldığı **3_pts_success** sütunun eklenmesi.
- Oyuncuların o maç içerisinde aldığı puanı, rebound, assist, top çalma ve blok sayısını toplayarak bu değerden turnover ve faul sayısını çıkartarak oyuncuların performanslarını ölçmek amacıyla hesaplanan **"fp"** (fancy player) sütunun eklenmesi.
- Eklenen **"fp"** sütunu üzerinden:
  - takımların en yüksek fp puanının hesaplanması ve görselleştirilmesi
  - oyun idlerine göre alınan en yüksek fp puanlarının hesaplanması 
  - sezonlara göre alınan en yüksek fp puanlarının hesaplanması ve görselleştirilmesi 
vb. işlemler yapılmıştır.
- Takımların en yüksek rebound, assist, steal ve blok sayılarının gruplandırılması ve görselleştirilmesi
- Takımların en yüksek faul ve turnover sayılarının hesaplanması ve görselleştirilmesi
- Hangi oyunlarda ev sahibi takımın kazandığının hangilerinde deplasman takımının kazandığının gösterilmesi.
-Game idlere göre ev sahibi takım ve deplasman takımın puanlarının karşılaştırılması.
- Sezonlara göre ev sahibi takımın kazandığı ve kaybettiği maçların sayısının görselleştirilmesi.
-Takımların ev sahibi ve deplasman olarak maçlarda aldıkları puana göre kategori edildiği home ve away sütunlarının eklenmesi ve bu kategorizasyonun görselleştirilmesi.



Detaylara .ipynb uzantılı kod dosyasından erişebilirsiniz. 

Akademi kapsamında yazdığım [medium](https://medium.com/@elvanuzun98) yazılarımı inceleyebilirsiniz.








