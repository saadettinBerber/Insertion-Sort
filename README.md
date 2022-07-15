# Insertion-Sort
Sıralama algoritmasıdır. Küçükten büyüğe sıralar. Şimdi de çalışma mantığını anlatalım
## Verilen Diziyi Insertion Sort algoritmasına göre sıralayınız.
[22,27,16,2,18,6]
- [-22-,27,16,--2--,18,6] // Dizinin içindeki en küçük elemanı buldum ve ilk elemanla yer değiştirdim.
- [2,27,16,22,18,6]       // 1. adımdan sonra elde ettiğim dizinin son hali.
- [2,-27-,16,22,18,--6--] // Artık dizinin içinden en küçük ikinci elemanı bulup ikinci elemanla yer değiştirmem gerek.
- [2,6,16,22,18,27] // 2. adımdan sonra elde ettiğim dizinin son hali.
- [2,6,- --16-- -,22,18,27] // Dizinin üçüncü elemanı ile üçüncü en küçük elemanı bulup yer değiştirmem gerek.
- [2,6,16,22,18,27] // 3. adımda zaten 16 olması gereken yerde olduğu için aynı yerde kaldı.
- [2,6,16,-22-,--18--,27] // Dizinin dördüncü elemanı ile dördüncü en küçük elemanı yer değiştirecek.
- [2,6,16,18,22,27] // Gördüğünüz gibi dizi küçükten büyüğe sıralandı. 
- İşlemlerimiz bitti.
### Time Complexity
- Average case: Aradığımız sayının ortada olması.
- Worst case: Aradığımız sayının sonda olması.
- Best case: Aradığımız sayının dizinin en başında olması.
- Yukarıda verilen diziyi sıraladık. 
- Yukarıda verilen tanımlara da bakarak 18 sayısı hangi case kapsamına girer sorusunun cevabı AVARAGE case olur
## Insertion Sort Big-O Gösterimi
- Big-O Gösterimi : O(n²)
# Patika.Dev
www.patika.dev
