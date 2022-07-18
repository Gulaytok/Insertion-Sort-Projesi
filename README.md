# Insertion-Sort-Projesi
# [22,27,16,2,18,6] -Insertion Sort aşamalarını yazalım
1.Adım insertion sort yaparken ilk önce bize verilen dizide en küçük elemanı bulup onu en başa yazıyoruz. Çünkü soldan sağa artacak şekilde dizi düzenlememiz gerekli
# en küçük eleman=2, 2 ve 22 yer değiştirecek.
[2,27,16,22,18,6] 
şimdi ise 2'den sonraki elemanlar arasında en küçüğü bulacağız
# en küçük eleman=6, 6 ve 27 yer değiştirecek
[2,6,16,22,18,27]
sadece tek 1 eleman kalana kadar küçükten büyüğe doğrı sıralayacağız
# şimdi de 2 ve 6 dışındaki elemanlar arasında en küçük elemanı bulalım
en küçük eleman=16 ve 16 3. sırada onu yer değiştirmiyoruz.
# 22, 18 ve 27 arasında sıralama yaparsak; 18 ile 22'nin yer değiştirmesi gerekir
[2,6,16,18,22,27] en son sıralama bu şekilde oldu
# Big O Notion gösterimini yapalım
[22,27,16,2,18,6] n
 [2,27,16,22,18,6] n-1
  [2,6,16,22,18,27] n-2
   [2,6,16,18,22,27] 1
# Time Complexity
n=eleman sayısı dersek
ilk aşamada; n işlem
ikinci aşamada; n-1 işlem
üçüncü aşamada; n-2 işlem
ve en son 1'e kadar geldik
toplam işlem sayısına bakacak olursak;
(n)+(n-1)+(n-2)+1=(n^2+n)/2 olur, burada en yüksek dereceliyi alacağımız için time complexity= O(n^2) olur
# 18 sayısı hangi case kapsamına girer?
Time Complexity dizi sıralanmasından sonra 18 sayısı ortada olduğundan dolayı "Average Case" kapsamına girer.
https://app.patika.dev/gulayy


