# SQL Ödev 8

1) test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

```CREATE TABLE empyoee (
	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);
``` 

2) Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

```insert into empyolee (id, name, birthday, email) values (1, 'Brook Brounfield', '1955-06-08', 'bbrounfield0@tinypic.com');
insert into empyolee (id, name, birthday, email) values (2, 'Carly Rearie', '1984-02-09', 'crearie1@hp.com');
insert into empyolee (id, name, birthday, email) values (3, 'Donalt Burtonshaw', '1933-01-19', 'dburtonshaw2@businessweek.com');
insert into empyolee (id, name, birthday, email) values (4, 'Kippy Storey', '1926-08-26', 'kstorey3@bloglovin.com');
insert into empyolee (id, name, birthday, email) values (5, 'Selby Scholte', '1993-05-17', 'sscholte4@bloglovin.com');
insert into empyolee (id, name, birthday, email) values (6, 'Zebedee Crassweller', '1900-12-10', 'zcrassweller5@lulu.com');
insert into empyolee (id, name, birthday, email) values (7, 'Arvy Elmes', '1916-01-23', 'aelmes6@senate.gov');
insert into empyolee (id, name, birthday, email) values (8, 'Rubetta Mills', '1901-07-02', 'rmills7@nyu.edu');
insert into empyolee (id, name, birthday, email) values (9, 'Eolande Pharoah', '1927-01-13', 'epharoah8@boston.com');
insert into empyolee (id, name, birthday, email) values (10, 'Dennie Lyven', '1969-10-23', 'dlyven9@issuu.com');
insert into empyolee (id, name, birthday, email) values (11, 'Samantha Sandwick', '1978-08-01', 'ssandwicka@nih.gov');
insert into empyolee (id, name, birthday, email) values (12, 'Ailbert Bentson', '1902-09-28', 'abentsonb@unesco.org');
insert into empyolee (id, name, birthday, email) values (13, 'Miner Elsay', '1946-07-21', 'melsayc@cnbc.com');
insert into empyolee (id, name, birthday, email) values (14, 'Dulcy Statersfield', '1957-04-28', 'dstatersfieldd@quantcast.com');
insert into empyolee (id, name, birthday, email) values (15, 'Beth Anthon', '1975-03-02', 'banthone@istockphoto.com');
insert into empyolee (id, name, birthday, email) values (16, 'Whitney Helder', '1941-05-08', 'whelderf@feedburner.com');
insert into empyolee (id, name, birthday, email) values (17, 'Rhodia Towl', '1958-04-16', 'rtowlg@diigo.com');
insert into empyolee (id, name, birthday, email) values (18, 'Maxwell Feaster', '1966-11-07', 'mfeasterh@gmpg.org');
insert into empyolee (id, name, birthday, email) values (19, 'Zulema Mote', '1949-09-13', 'zmotei@ameblo.jp');
insert into empyolee (id, name, birthday, email) values (20, 'Montague Gerbl', '1955-01-22', 'mgerblj@de.vu');
insert into empyolee (id, name, birthday, email) values (21, 'Yolande Van Dalen', '1997-07-14', 'yvank@ocn.ne.jp');
insert into empyolee (id, name, birthday, email) values (22, 'Angelle Burleton', '1919-09-04', 'aburletonl@stumbleupon.com');
insert into empyolee (id, name, birthday, email) values (23, 'Welsh Sutherden', '1949-04-10', 'wsutherdenm@eepurl.com');
insert into empyolee (id, name, birthday, email) values (24, 'Marcia Merriott', '1903-07-06', 'mmerriottn@slashdot.org');
insert into empyolee (id, name, birthday, email) values (25, 'Filbert Purkins', '1911-03-07', 'fpurkinso@hugedomains.com');
insert into empyolee (id, name, birthday, email) values (26, 'Sibyl Tunaclift', '1904-05-06', 'stunacliftp@hatena.ne.jp');
insert into empyolee (id, name, birthday, email) values (27, 'Berti Bliben', '1973-05-18', 'bblibenq@army.mil');
insert into empyolee (id, name, birthday, email) values (28, 'Caresa Schohier', '1954-01-18', 'cschohierr@tuttocitta.it');
insert into empyolee (id, name, birthday, email) values (29, 'Darius Farrier', '1962-03-16', 'dfarriers@toplist.cz');
insert into empyolee (id, name, birthday, email) values (30, 'Amie Braghini', '1971-04-10', 'abraghinit@amazon.co.uk');
insert into empyolee (id, name, birthday, email) values (31, 'Vinny Butts', '1986-04-05', 'vbuttsu@vimeo.com');
insert into empyolee (id, name, birthday, email) values (32, 'Halli Buckthorp', '1989-07-17', 'hbuckthorpv@admin.ch');
insert into empyolee (id, name, birthday, email) values (33, 'Barnie Vakhrushin', '1990-04-17', 'bvakhrushinw@adobe.com');
insert into empyolee (id, name, birthday, email) values (34, 'Antonia Wickrath', '1920-11-12', 'awickrathx@hubpages.com');
insert into empyolee (id, name, birthday, email) values (35, 'Meta Golda', '1997-02-17', 'mgolday@cloudflare.com');
insert into empyolee (id, name, birthday, email) values (36, 'Laryssa Marmion', '1975-01-19', 'lmarmionz@who.int');
insert into empyolee (id, name, birthday, email) values (37, 'Irwinn Bergen', '1941-06-16', 'ibergen10@slideshare.net');
insert into empyolee (id, name, birthday, email) values (38, 'Mersey Roath', '1970-08-12', 'mroath11@diigo.com');
insert into empyolee (id, name, birthday, email) values (39, 'Eward Lening', '1975-07-29', 'elening12@simplemachines.org');
insert into empyolee (id, name, birthday, email) values (40, 'Keary Kenan', '1903-05-12', 'kkenan13@google.es');
insert into empyolee (id, name, birthday, email) values (41, 'Inge Francisco', '1924-04-05', 'ifrancisco14@wiley.com');
insert into empyolee (id, name, birthday, email) values (42, 'Ashleigh Westhofer', '1933-01-13', 'awesthofer15@sohu.com');
insert into empyolee (id, name, birthday, email) values (43, 'Denney Gerok', '1979-01-02', 'dgerok16@about.me');
insert into empyolee (id, name, birthday, email) values (44, 'Sayre Oselton', '1974-08-08', 'soselton17@gnu.org');
insert into empyolee (id, name, birthday, email) values (45, 'Emmett Gilburt', '1905-02-09', 'egilburt18@github.com');
insert into empyolee (id, name, birthday, email) values (46, 'Waring Kitteridge', '1936-03-15', 'wkitteridge19@printfriendly.com');
insert into empyolee (id, name, birthday, email) values (47, 'Elmo Riddiford', '1987-09-14', 'eriddiford1a@theatlantic.com');
insert into empyolee (id, name, birthday, email) values (48, 'Romola Clarey', '1922-04-02', 'rclarey1b@ycombinator.com');
insert into empyolee (id, name, birthday, email) values (49, 'Madelina Bloodworthe', '1915-08-14', 'mbloodworthe1c@jalbum.net');
insert into empyolee (id, name, birthday, email) values (50, 'Joanne Ensten', '1999-12-12', 'jensten1d@topsy.com');
```

3) Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

```
UPDATE employee SET 
   name = 'Zeynep Gül',
	 birthday = '1990-08-07',
	 email = 'zeynep@gul.com'
WHERE name = 'Caresa Schohier';
```

```
UPDATE employee SET
  name = 'Gökhan Yılmaz',
	birthday = '1984-12-08',
	email = 'gokhan@yilmaz.com'
WHERE birthDay = '1986-04-05';
```
```
UPDATE employee SET 
   name = 'Azra Yüksel'
   WHERE birthday = '1997-02-17';
```
```
UPDATE employee SET
   name = 'Onur Yılmaz',
   birthday = '1995-01-13'
   WHERE id = 13;
```
```
UPDATE employee SET 
  name = 'Asya Öztürk'
  RETURNING * ;
```
4) Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

```
DELETE FROM employee 
WHERE id = 27;
```
``` 
DELETE FROM employee
WHERE id > 11
RETURNING * ;
```
```
DELETE FROM employee 
WHERE name = 'Laryssa Marmion';
```
```
DELETE FROM employee 
WHERE birthday = '1973-05-18';
```
```
DELETE FROM employee 
WHERE email = 'rmills7@nyu.edu'
RETURNING * ;
```
