# WarehouseApp


# **REQUIREMENTS**


# **POJO CLASS**


**ID:** String veya int olur, ancak int olması daha iyi; otomatik ataması
gerek.

**Ürün İsmi:** String olacak

**Üretici firma, marka:** String

**Miktar:** Integer (Default değer=0)

**Birim:** String (çuval, koli, teneke vs.)

**Raf:** Hem rakam hem harf olabilir (String, default değer=null)

Bu kısımda OOP'den Encapsulation ve Polymorophism kullanılacak.
Constructor, getter ve setter kullanılacak.



# **Class (Methodlar)**

**urunTanimlama** urunun ismi, ureticisi ve birimi girilecek. id alınacak.( Ürün burada depoya henüz giriş yapmadı.)

**urunListele** Tanimlanan urunler listelenecek.(PrintF kullanılacak, tablo gibi gözükecek bu kısım)

**Miktar** **default değer**=0

**Raf** **default değer**=null



**urunGirisi** Ürünün depoya giriş yaptığı nokta. ID'sini gireceğiz .

**urunuRafaKoy** Listeden urunu sececegiz ve id numarasina gore urunu
rafa koyacagiz. (Ürünü bir raftan alıp diğerine koyabilmeliyiz.)

**urunCikisi** İstenen ürünü seçeceğiz ve ürünün çıkışını ID no ile
yapacağız. Sadece miktarda değişiklik olacak.
( Ç ıkış yaparken stok 0'da
küçük olamaz, stoktan fazla ürün çıkışı yapılamaz.)
