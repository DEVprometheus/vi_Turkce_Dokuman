# vi Türkçe Kaynak
* özellikle Linux'da 'vi' kullanımını yaygınlaştırmak için hazırlanmış bir diğer Türkçe kaynak
* Bilgisayar dünyasının hemen hemen bu en eski editörünü kullanabilmek için
* vi [dosya.ismi] yazıp, vi'ye girdikten sonra, aşağıdaki
* <  > arasında gördüğünüz karakterlere klavyeden basarak, sağda yazılı işlemleri yaptıklarını
* görebilirsiniz...

Komut Mod
---------
```python
<Esc>   # Komut Mode'a geç
<:w>    # Dosyayı kayded

<:x!>   # Kaydet ve çık
<:wq!>  # Kaydet ve çık 
<1G>    # Dosya başı, ilk satır
<G>     # Dosya sonu, en son satır
```

Editor Mod
----------
```python
<o>     # bulunulan satırın altına yeni bir satır açar
<O>     # bulunulan satırın üstüne yeni bir satır açar
<dd>    # cursorun bulundugu satiri siler
<yyp>   # bulunulan satırı kopyalar ve altına yapıştırır
```

