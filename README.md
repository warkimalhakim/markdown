# PERINTAH MARKDOWN DASAR

Dasar Markdown MD Extension
`Warkim Rapii`

`Markdown bisa ditulis dalan syntax Markdown itu sendiri ataupun (namun terbatas) juga dapat ditulis dengan tag HTML termasuk dengan kombinasi CSS secara inline.`

# HEADINGS

`Ditulis dalam syntax #`

<hr>
```
# HEADING 1
## HEADING 2
### HEADING 3
#### HEADING 4
##### HEADING 5
###### HEADING 6
````

# BOLD

`Ditulis dalam (diantara) syntax ** atau __ (double asterisk & underscores)`

<hr>
```
**TEXT**
**TEXT**
```

# ITALIC

`Ditulis dalam (diantara) syntax * atau _ (single asterisk & underscore)`

<hr>
*TEXT\*
_TEXT_

STRICT
Ditulis dalam (diantara) syntax ~~ (tilde)
================================
~~TEXT~~

ORDER LIST
Ditulis dengan syntax 1 (angka 1 2 3 dan seterusnya, atau bisa angka 1 semua)
SUB LIST ditulis dengan tab
================================

1. Satu
2. Dua
3. Tiga
4. Empat
   1. Empat Satu
5. Lima

UNORDER LIST
Ditulis dengan syntax - (dash)
================================

- Pertama
- Kedua
  - Kedua Pertama
- Ketiga

QUOTATION
Ditulis dengan syntax >
================================

> I am Happy to day

LINK
Ditulis dengan syntax [] diikuti dengan ()
[] -> digunakan untuk plain text
() -> untuk link / redirect
================================
[Klik](https://warkim.com)

IMAGE
Ditulis dengan syntax ![] diikuti dengan ()
![] -> digunakan untuk plain text atau alternative image
() -> untuk path image di local maupun online url
================================
![hatiku memanggil hatimu yang beku](./patah_hati.jpg)

TABLE
Ditulis dengan syntax |
================================
NO | NAMA | KOTA
--|--|--
1 | WARKIM | JAKARTA
2 | WARNER | SYDNEY

INLINE CODE
Ditulis dalam (diantara) syntax `(backtick) ================================`<strong>I am strong</strong>`

BLOCKING CODE
Ditulis dalam (diantara) syntax ``` (triple backtick)
Dapat ditulis juga nama programming / menggunakan bahasa program apa, ditulis setelah
triple backtick pertama (open)
================================

```

console.log('I am Cool')

```

```javascript
let say = "My name Warkim";
console.log(say);
```
