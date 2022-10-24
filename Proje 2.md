# Proje 2

## **[16,21,11,8,12,22]** -> Merge Sort	



- **Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**

  1) [16,21,11] & [8,12,22]
  2) [16,21], [11] & [8,12], [22]
  3) [16], [21], [11] & [8], [12], [22]
  4) [16,21], [11] & [8,12], [22]
  5) [11,16,21] & [8,12,22]
  6) [8,11,12,16,21,22]

  - **Big-O gösterimini yazınız.**

     O(n*(logn))

    Yukarıdaki dizinde Merge Sort türüne göre sürekli kendini ikiye bölerek 6 aşama bulunduğundan: Big-O gösterimi O(6*(log6)) şeklinde olacaktır.