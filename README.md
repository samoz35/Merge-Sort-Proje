# Merge-Sort-Proje

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


<h2>1- Sort türüne göre Aşamalar
</h2>

 [16,21,11,8,12,22] diziyi ikiye bölüyoruz.
- [16,21,11]     [8,12,22]
devamında bir daha ikiye böleriz.
- [16,21]   [11]   [8,12]   [22]
Elde ettiğimiz diziler 2 veya daha az eleman sayısına ulaştığı için bölme işlemini bırakırız.
Sonrasında dizileri kendi içlerinde sıralamaya koyarız.
- [16,21]   [11]   [8,12]   [22]
Sıraladığımız bu dizileri uygun şekilde birleştiririz.
- [11,16,21]   [8,12,22]
Sonrasında bütünü oluşturacak şekilde birleşim yaparız.
- [8,11,12,16,21,22]

 <h2>Big-O gösterimi</h2>

Worst case   : O(n*logn)

Average case : O(n*logn)

Best case    : O(n*logn)
