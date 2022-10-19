[Patika.dev](https://www.patika.dev/tr) 

### Proje 2 [16,21,11,8,12,22] -> Merge Sort

### 1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
	- [16,21,11,8,12,22] (Başlangıç)
	- [16,21,11] [8,12,22] (2. adım)
	- [16,21][11] | [8][12,22] (3. adım)
	- [16][21][11] | [8][12][22] (4. adım)
	- [16] [11,21] | [8] [12,22] (5. adım)
	- [11,16,21] | [8,12,22] (6. adım)
	- [8,11,12,16,21,22] (Son adım)
	
### 2) Big-O gösterimini yazınız.
	- O(n*(logn)) formülünden n=6 olduğundan cevap = O(6*(log6))
