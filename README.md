# Patika.dev-SQL-dev-8
Patika.dev &amp; FMSS İş Analisti Practicum SQL ödevi

#### test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
<code> CRETAE TABLE employee( id INTEGER PRIMARY KEY, name VARCHAR(50) NOT NULL, birthday DATE, email VARCHAR(50) NOT NULL); </code>

#### Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
<code> 
insert into employee (id, name, birthday, email) values (1, 'Fredelia', '1968-10-07', 'fnewton0@networksolutions.com');
insert into employee (id, name, birthday, email) values (2, 'Zola', '1985-12-26', 'zfalls1@mozilla.org');
insert into employee (id, name, birthday, email) values (3, 'Alyson', '2014-07-15', 'abrambell2@jiathis.com');
insert into employee (id, name, birthday, email) values (4, 'Cassie', '1980-02-13', 'csaunier3@telegraph.co.uk');
insert into employee (id, name, birthday, email) values (5, 'Egan', '1971-10-12', 'ehully4@ask.com');
insert into employee (id, name, birthday, email) values (6, 'Justin', '1979-10-02', 'jamesbury5@tripod.com');
insert into employee (id, name, birthday, email) values (7, 'Bridget', '1977-06-30', 'bisack6@bloglovin.com');
insert into employee (id, name, birthday, email) values (8, 'Shane', '2018-03-14', 'sobington7@intel.com');
insert into employee (id, name, birthday, email) values (9, 'Aurea', null, 'adeblase8@blog.com');
insert into employee (id, name, birthday, email) values (10, 'Nata', '1996-11-09', 'nillingworth9@lycos.com');
insert into employee (id, name, birthday, email) values (11, 'Arabela', '2011-07-05', 'aolliviera@patch.com');
insert into employee (id, name, birthday, email) values (12, 'Thorny', '1985-12-26', 'tlundyb@google.com.au');
insert into employee (id, name, birthday, email) values (13, 'Rutledge', '2008-05-03', 'rdimbylowc@si.edu');
insert into employee (id, name, birthday, email) values (14, 'Margarete', '1972-08-14', 'mabellsd@hostgator.com');
insert into employee (id, name, birthday, email) values (15, 'Mariann', '1982-09-12', 'mbranigane@chronoengine.com');
insert into employee (id, name, birthday, email) values (16, 'Ree', '1992-04-12', 'rfantinif@rambler.ru');
insert into employee (id, name, birthday, email) values (17, 'Arch', '2012-11-17', 'aruddickg@ebay.com');
insert into employee (id, name, birthday, email) values (18, 'Evey', '1984-07-22', 'efraczakh@about.com');
insert into employee (id, name, birthday, email) values (19, 'Barb', '1997-02-26', 'bstanmani@businessweek.com');
insert into employee (id, name, birthday, email) values (20, 'Murdoch', '2018-09-17', 'mellowayj@edublogs.org');
insert into employee (id, name, birthday, email) values (21, 'Molly', '1990-06-22', 'mpratchettk@nyu.edu');
insert into employee (id, name, birthday, email) values (22, 'Ludwig', '2005-01-12', 'lorisl@networkadvertising.org');
insert into employee (id, name, birthday, email) values (23, 'Dory', '2003-09-26', 'dfirpom@360.cn');
insert into employee (id, name, birthday, email) values (24, 'Maxie', '1995-10-31', 'mtoplisn@google.de');
insert into employee (id, name, birthday, email) values (25, 'Erwin', '2014-04-10', 'eharteo@nifty.com');
insert into employee (id, name, birthday, email) values (26, 'Alon', '2000-01-01', 'asteelep@google.com.hk');
insert into employee (id, name, birthday, email) values (27, 'Filmer', '2021-07-02', 'fcoultarq@springer.com');
insert into employee (id, name, birthday, email) values (28, 'Maren', '1992-02-16', 'messamer@unc.edu');
insert into employee (id, name, birthday, email) values (29, 'Torr', '1984-12-19', 'tvialls@flavors.me');
insert into employee (id, name, birthday, email) values (30, 'Nikolai', '2010-01-29', 'ndaudrayt@dmoz.org');
insert into employee (id, name, birthday, email) values (31, 'Jecho', '1993-09-27', 'jtooru@tinyurl.com');
insert into employee (id, name, birthday, email) values (32, 'Pierette', '1989-07-10', 'pblayv@alibaba.com');
insert into employee (id, name, birthday, email) values (33, 'Antonio', '1974-06-15', 'amaccourtw@senate.gov');
insert into employee (id, name, birthday, email) values (34, 'Trey', '1986-03-23', 'thassallx@creativecommons.org');
insert into employee (id, name, birthday, email) values (35, 'Ibbie', '2017-10-02', 'iembersony@wikipedia.org');
insert into employee (id, name, birthday, email) values (36, 'Gretel', null, 'ghollingtonz@constantcontact.com');
insert into employee (id, name, birthday, email) values (37, 'Bobbie', '1972-09-30', 'brenzini10@creativecommons.org');
insert into employee (id, name, birthday, email) values (38, 'Harwilll', '1969-03-03', 'hfogel11@netvibes.com');
insert into employee (id, name, birthday, email) values (39, 'Page', '1975-04-20', 'pkibel12@bloglovin.com');
insert into employee (id, name, birthday, email) values (40, 'Krystalle', '2003-05-31', 'khalms13@free.fr');
insert into employee (id, name, birthday, email) values (41, 'Dud', '1986-04-17', 'dveldens14@stumbleupon.com');
insert into employee (id, name, birthday, email) values (42, 'Cordey', '1973-06-20', 'callain15@usnews.com');
insert into employee (id, name, birthday, email) values (43, 'Marga', '1998-01-21', 'mmangeney16@biblegateway.com');
insert into employee (id, name, birthday, email) values (44, 'Leslie', '2000-08-16', 'lmanna17@1und1.de');
insert into employee (id, name, birthday, email) values (45, 'Hildagarde', '1978-02-17', 'hpickston18@yale.edu');
insert into employee (id, name, birthday, email) values (46, 'Sarita', '1991-08-21', 'shardisty19@ning.com');
insert into employee (id, name, birthday, email) values (47, 'Conny', '1999-03-26', 'chynd1a@51.la');
insert into employee (id, name, birthday, email) values (48, 'Hamel', '2000-03-06', 'hkey1b@woothemes.com');
insert into employee (id, name, birthday, email) values (49, 'Peder', '1999-10-19', 'ptorrecilla1c@webeden.co.uk');
insert into employee (id, name, birthday, email) values (50, 'Andie', '1971-03-05', 'azavittieri1d@people.com.cn'); 
</code>

#### Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
<code> 
UPDATE employee
SET name= 'Patika'
email = 'patikadev.com.tr'
WHERE id = 36
RETURNING*; </code> <br>

<code> 
UPDATE employee
SET name = 'Irem'
WHERE name ='Barb'
RETURNING*; </code> <br>

<code>
UPDATE employee
SET email = 'heythere@people.com.cn'
WHERE birthday = '1999-10-19'
RETURNING*; </code> <br>

<code>
UPDATE employee
SET birtday = '2011-07-05'
WHERE name = 'Pamuk'
RETURNING*; </code>
<br>
<code>
UPDATE employee
SET email= 'istanbul.com.tr'
WHERE birthday = '1990-06-22'
RETURNING*; </code>

#### Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
<code> 
DELETE FROM employee
WHERE id = 10
RETURNING*; </code> <br>

<code>
DELETE FROM employee
WHERE name = 'Mariann
RETURNING*; </code> <br>

<code>
DELETE FROM employee
WHERE email = 'hfogel11@netvibes.com'
RETURNING*; </code> <br>

<code>
DELETE FROM employee
WHERE birthday = '1986-03-23'
RETURNING*; </code> <br>

<code>
DELETE FROM employee
WHERE id = 12
RETURNING*; </code> <br>
