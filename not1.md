# Laravele Giriş

Laravelde model oluşturmak için :
```
php artisan make:model Modeladi
```

Model oluştururken tekil isimde olması gerekli ve büyük harfle başlar.

Model App dizini altında Modeladi.php olarak oluşur.

Modele tablo tanımlamak için 

~~~~
protected $table = 'tabloadi';
~~~~

Tabloda erişilebilir alanların tanımlaması dizi içine yapılıyor. Hemen altına 

~~~~
protected $fillable = ['yaziadi','yazimetni','eklenmatarihi'];
~~~~

Gibi tanımlanabiliyor. Ancak biz tüm alanların erişilebilir yani içerisine yazılabilir olduğunu belirtmek istersek :

~~~~
protected $guarded = {];
~~~~

olarak tanılama yapıyoruz.
