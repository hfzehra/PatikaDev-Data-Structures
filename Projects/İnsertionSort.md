#İnsertion sort
***
***[22,27,16,2,18,6] -> Insertion Sort***
*1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.*

**ÇÖZÜM:**
```
1. [2,27,16,22,18,6] -> 2 ve 22 yer değiştirir
2. [2,6,16,22,18,27] -> 6 ve 27 yer değiştirir
3. [2,6,16,22,18,27] -> 16 için yerdeğiştirme olmaz
4. [2,6,16,18,22,27] -> 18 ve 22 yer değiştirir.
5. [2,6,16,18,22,27] -> yer değiştirme olmaz.

```

*2.Big-O gösterimini yazınız.*

**ÇÖZÜM:**
```
(n-1) defa bu işlem tekrar edilir. Yani:
n + (n-1) + (n-2) +.... 1 = (n.(n+1))/2 = (n²+n)/2

en büyük ifadenin yanında diğerleri önemsiz kalacağı için 

Big(O) = n²
```

*3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.*

```
Wort case: 27
Avarage case: 16 - 18
Best case: 2
```

*4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.*

`18 sayısı avarage case kapsamına girer.  `