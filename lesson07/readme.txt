I) Tim hieu pattern trong Form Input

+0-9. => Những ký tự hay được dùng

[ky tu se chua]
[0-9]* : gom >= 0 ky tu (null, 0, 34, 3454, )
[0-9]+ : >= 1
[0-9]? : 0 hoac 1 ky tu
[0-9]{3} : gom 3 ky tu thoi
[0-9]{m,n}: so ky tu tu m toi n (m=3, n= 16)
[0-9]{m,} : >=m
[0-9]{,n}: <= n
[abc]{2,3} -> gom cac ky tu a,b,c: 2->3
[a-z]
[\-A-Z]
[^abc] : ko bao gom cac ky tu a,b,c

II) Javascript
- Kien thuc core can ban
	- Khai bao bien
	- Bieu thuc + toan tu
	- Menh de dieu kien
	- Vong lap (for, while, do..while)
	- Function
	- Mang: Array
	- Doi tuong: Object -> Structure (C)
- Kien thuc rieng cua Javascript so vs ngon ngu khac (C)
	- Xu ly su kien
	- Tuong tac vs tags (html) <-> Javascript
	- localStorage: Luu tru du lieu
	- JSON