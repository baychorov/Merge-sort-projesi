# Merge-sort-projesi
patika.dev merge sort projesi 

[16,21,11,8,12,22]  dizisinin merge sort algoritmasına göre sıralanışı ; 

I   - [16,21,11] | [8,12,22]
II  - [16,21] | [11] | [8,12] | [22] 
III - [16] | [21] | [11] | [8] | [12] | [22] 
IV  - [11,21] | [16] | [8,22] | [12] 
V   - [11,16,21] | [8,12,22] 
VI  - [8,11,12,16,21,22] 
dizi sıralanmış oldu. 

sıralanacak diziyi her seferinde ikiye böldüğümüz için 2^x = n ---> log2n = x ---> böldüğümüz için oluşan karmaşıklık O(logn) olur. Aynı zamanda diziler bölündükten sonra birleştirme esnasında en az 1 kere karşılaştırma yapılacağından n kadar karşılaştırma yapılır ve O(n) olur. 
Bu iki aşamanın birleşimi bize tüm algoritmanın karmaşıklığını verir ki buda O(nlogn) olacaktır. 
