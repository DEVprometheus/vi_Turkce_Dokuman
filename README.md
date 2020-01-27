# vi Türkçe Kaynak
* özellikle Linux'da 'vi' kullanımını yaygınlaştırmak için hazırlanmış bir diğer Türkçe kaynak
* Bilgisayar dünyasının hemen hemen bu en eski editörünü kullanabilmek için
* vi [dosya.ismi] yazıp, vi'ye girdikten sonra,
  <br>aşağıdaki;
  <  > arasında gördüğünüz karakterlere klavyeden basarak, sağda yazılı işlemleri yaptıklarını görebilirsiniz...

Komut Mod
---------
```python
<Esc>   # Komut Mode'a geç
<:w>    # Dosyayı kaydet

<ZZ>   # Kaydet ve çık - en basit ve en hızlı
<:x!>   # Kaydet ve çık - bi diğer
<:wq!>  # Kaydet ve çık - bir diğer
<:q!>   # yapılan hiç bir değişikliği kayedetmeden çıkar
<1G>    # Dosya başı, ilk satır
<G>     # Dosya sonu, en son satır
<i>     # insert, dosya içine yazmaya başlayabilirsiniz
<x>     # cursorun üzerinde bulunduğu karakteri siler
<A>     # cursoru üzerinde bulunduğu satırın sonuna atar ve edit moda geçer
<I>     # cursoru üzerinde bulunduğu satırın başına atar ve edit moda geçer
```

Editor Mod
----------
```python
<o>     # bulunulan satırın altına yeni bir satır açar
<O>     # bulunulan satırın üstüne yeni bir satır açar
<dd>    # cursorun bulundugu satiri siler
<yyp>   # bulunulan satırı kopyalar ve altına yapıştırır
```
