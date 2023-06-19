# Patika
## Patika çalışmaları

### Selection Sort Projesi
- Soru
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız

-Cevap
Insertion Sort aşamaları:

Başlangıçta dizi: [22, 27, 16, 2, 18, 6]
27, 22'den büyük olduğu için yerlerini değiştiriyoruz: [22, 27, 16, 2, 18, 6]
16, 27 ve 22'den küçük olduğu için onları birer adım geri kaydırıyoruz ve 16'yı doğru konumuna yerleştiriyoruz: [16, 22, 27, 2, 18, 6]
2, 27, 22 ve 16'dan küçük olduğu için onları birer adım geri kaydırıyoruz ve 2'yi doğru konumuna yerleştiriyoruz: [2, 16, 22, 27, 18, 6]
18, 27'den küçük olduğu için onları birer adım geri kaydırıyoruz ve 18'i doğru konumuna yerleştiriyoruz: [2, 16, 18, 22, 27, 6]
6, 27, 22, 18 ve 16'dan küçük olduğu için onları birer adım geri kaydırıyoruz ve 6'yı doğru konumuna yerleştiriyoruz: [2, 6, 16, 18, 22, 27]
-Soru
Big-O gösterimini yapınız

-Cevap
O(n^2)

-Soru
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

-Cevap
Aranan eleman ortada olduğu için Avarage case kapsamına girer

-Soru
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

-Cevap
ilk adımda dizinin en küçük elemanı "2" ile birinci elemanın yerini değiştiriyoruz ==  [2, 3, 5, 8, 7, 9, 4, 15, 6]
ikinci adımda dizinin ikinci en küçük elemanı "3" ile ikinci elemanın yerini değiştiriyoruz == [2, 3, 5, 8, 7, 9, 4, 15, 6]
üçüncü adımda en küçük eleman "4" olduğu için üçüncü eleman ile yerini değiştiriyoruz ==  [2, 3, 4, 8, 7, 9, 5, 15, 6]
dördüncü adımda en küçük eleman "5" olduğu için dördüncü eleman ile yerini değiştiriyoruz ve Selection Sort'a göre dizinin 4. adımdan sonraki hali ==  [2, 3, 4, 8, 7, 9, 5, 15, 6]
