## Patika.dev Merge Sort Projesi
---

### Proje 2
**[16,21,11,8,12,22] -> Merge Sort**

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
---

1. **[16,21,11]** **[8,12,22]**
2. **[16,21]** **[11]** **[8,12]** **[22]**
3. **[16]** **[21]** **[11]** **[8]** **[12]** **[22]**
4. Liste tek eleman kalıncaya kadar bölündü. Birleştirme yaparken aynı zamanda sıralama yapılır.

---

1. **[16,21]** **[11]** **[8,12]** **[22]**
2. **[11,16,21]** **[8,12,22]**
3. **[8,11,12,16,21,22]**

Big O -> O(nlogn)
