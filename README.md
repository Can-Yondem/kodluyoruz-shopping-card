# Shopping Cart
![Shopping Card](./shopping-cart.png)
## Proje Nasıl Çalıştırılır

* Projeyi fork'ladıktan ya da indirdikten sonra projenin bulunduğu klasörde "npm install" komutu ile gerekli paketlerin yüklenmesi gerekiyor.

* Daha sonra "npm run start" komutu ile uygulama başlatılabilir.

## Proje Hakkında
Bu projede ürünleri listelememiz için ihtiyacımız olan bütün data (products array'i) constant.js içinde bulunuyor. Uygulamada 3 tane component kullanıyoruz. Bunlardan ilki Navbar, diğer ikisi ise ürünleri listelerken kullanılan component'lerdir. ProductCard her bir ürün için gösterilecek kart yapısını temsil ediyor. ProductsGrid component'inde ise products array'inde map yaparak her bir ürüne karşılık gelecek ProductCard component'inin render edilmesi sağlanıyor.

## MIT
[MIT](https://opensource.org/licenses/MIT)