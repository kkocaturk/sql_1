# SQL GIRIS
* SQL declerative bir dildir. 


* **SELECT** komutu en cok kullanilan sql anahtar kelimeisidir


* SQL'de komutlar **case sensitive** degildir!


* SQL, yapılandırılmış bir dildir ve belirli bir söz dizimine sahiptir. SQL kullanarak veritabanlarında sorgular yazabilir, veritabanı şemalarını oluşturabilir, veritabanı nesnelerini yönetebilir ve veritabanı işlemleri gerçekleştirebilirsiniz. SQL, farklı veritabanı yönetim sistemleri arasında genellikle taşınabilirlik sağlayan standart bir dil olarak kabul edilir, yani birçok veritabanı yönetim sistemi SQL'i destekler.



## WHERE KEYWORD

```
SELECT * FROM football_player WHERE Country == 'France';
```


```
SELECT * FORM film WHERE replacement_cost >= 12.99;
```

### WHERE AND LOGIC OPERATORS
* **AND** command'ini kullanarak sorgumuza ekleme yapip daha detayli yapabiliriz.


```
SELECT first_name, last_name FROM actor
WHERE first_name = 'Penelope' AND last_name = 'Monroe';
```

### AND, OR, NOT
* **AND** two condition must be true;
* **OR** if one of the conditions is true then the statement become true ;
* **NOT** it lists the excat opposite of the written statement;

```
SELECT * FROM film WHERE NOT (rental_rate >= 5.00 OR rental_rate = 2.99);
```
- (1.kod)[png/1.png]