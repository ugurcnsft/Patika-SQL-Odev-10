1#SORU - city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz LEFT JOIN sorgusunu yazınız.

1#CEVAP - SELECT city, country FROM city
LEFT JOIN country ON city.country_id = country.country_id;

1#<img width="960" alt="1" src="https://github.com/ugurcnsft/Patika-SQL-Odev-10/assets/129968939/b375c7a2-06be-43e1-9a2c-b05e681e6d24">

2#SORU - customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz RIGHT JOIN sorgusunu yazınız.

2#CEVAP - SELECT first_name, last_name, payment_id FROM customer
RIGHT JOIN payment ON payment.customer_id = customer.customer_id;

2# <img width="960" alt="2" src="https://github.com/ugurcnsft/Patika-SQL-Odev-10/assets/129968939/8704ddc3-3736-46bd-80af-d96a8b175149">

3#SORU - customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz FULL JOIN sorgusunu yazınız.

3#CEVAP - <img width="960" alt="3" src="https://github.com/ugurcnsft/Patika-SQL-Odev-10/assets/129968939/e11c126b-5895-4f75-b664-5c61da6041db">
