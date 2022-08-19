# Hayvanat Bahçesi Yönetimi

Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlıyorsunuz.

- Hayvanlar:
    - Atgiller (atlar, zebralar, eşekler),
    - Kedigiller (kaplanlar, aslanlar),
    - Kemirgenler (sıçanlar, kunduzlar) gibi gruplardaki türlerle karakterize edilir.
- Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.
    - isim, yaş, tür adı, ağırlık, boy vb.
- Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()
- Sistem yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()

Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.

Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlayın.

![](/images/zoo_classification.png)


