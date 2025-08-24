Proje 2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Aşamalar (Merge Sort)

Başlangıç dizi: [16, 21, 11, 8, 12, 22]

1) Bölme (Divide)

[16, 21, 11] | [8, 12, 22]

Sol: [16] | [21, 11] → [21] | [11]

Sağ: [8] | [12, 22] → [12] | [22]

2) Birleştirme (Conquer/Merge)

[21] + [11] → [11, 21]

[16] + [11, 21] → [11, 16, 21]

[12] + [22] → [12, 22]

[8] + [12, 22] → [8, 12, 22]

3) Son Birleştirme

[11, 16, 21] + [8, 12, 22] →
Karşılaştırmalar: 11↔8 → 8, 11↔12 → 11, 16↔12 → 12, 16↔22 → 16, 21↔22 → 21, kalan 22

Sonuç: [8, 11, 12, 16, 21, 22]

Big-O Gösterimi

Zaman: Best = Average = Worst = O(n log n)

Uzay: Ek bellek O(n) (yardımcı dizi kullanıldığı için)
