# -ODEV9-SQL
dvdrental sorgu senaryoları çözümleri
Sorgu 1- city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
Çözüm 1- SELECT city, country FROM city
INNER JOIN country 
ON city.country_id = country.country_id;
<img width="495" alt="Ekran Resmi 2023-03-08 14 37 37" src="https://user-images.githubusercontent.com/116847744/223703964-b533131e-5331-448c-ae85-d386867d93cb.png">

Sorgu 2- customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
Çözüm 2- SELECT payment_id, first_name, last_name FROM payment
INNER JOIN customer
ON payment.customer_id = customer.customer_id;
<img width="564" alt="Ekran Resmi 2023-03-08 14 46 58" src="https://user-images.githubusercontent.com/116847744/223705444-153892b0-079c-4ea7-a0b1-e8bab790bff8.png">

Sorgu 3- customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
Çözüm 3- SELECT rental_id, first_name, last_name FROM rental
INNER JOIN customer
ON rental.customer_id = customer.customer_id;
<img width="563" alt="Ekran Resmi 2023-03-08 14 49 21" src="https://user-images.githubusercontent.com/116847744/223705890-89da23dc-9001-4afb-8495-e33085c78288.png">
