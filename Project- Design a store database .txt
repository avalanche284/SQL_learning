CREATE TABLE store (id INTEGER PRIMARY KEY, name TEXT, screen_size REAL, processor TEXT, cores INTEGER, color TEXT, price REAL);

INSERT INTO store VALUES(1, "iMac 24", 23.5, "Apple M1 chip", 15, "Green", 1299);
INSERT INTO store VALUES(2, "MacBook Pro 16", 16.2, "Apple M1 Max chip", 42, "Space Gray", 2499);
INSERT INTO store VALUES(3, "MacBook Pro 14", 14.2, "Apple M1 Pro chip", 26, "Silver", 1999);
INSERT INTO store VALUES(4, "MacBook Air M1", 13.3, "Apple M1 Chip", 15, "Gold", 999);
INSERT INTO store VALUES(5, "MacBook Air M2", 13.6, "Apple M2 Chip", 18, "Starlight", 1199);
INSERT INTO store VALUES(6, "iPad Pro 12.9‑inch", 12.9, "Apple M2 Chip", 18, "Space Gray", 1099);
INSERT INTO store VALUES(7, "iPad Pro 11-inch", 11, "Apple M2 Chip", 18, "Silver", 799);
INSERT INTO store VALUES(8, "iPad Air", 10.9, "Apple M1 Chip", 16, "Pink", 599);
INSERT INTO store VALUES(9, "iPad 10th", 10.9, "A14 Bionic chip", 10, "Yellow", 449);
INSERT INTO store VALUES(10, "iPad 9th", 10.2, "A13 Bionic chip", null ,"Silver", 329);
INSERT INTO store VALUES(11, "iPad mini", 8.3, "A15 Bionic chip", 11, "Starlight", 499);
INSERT INTO store VALUES(12, "iPhone 14 Pro Max", 6.7, "A16 Bionic chip", 11, "Deep Purple", 1099);
INSERT INTO store VALUES(13, "iPhone 14 Pro", 6.1, "A16 Bionic chip", 11, "Space Black", 999);
INSERT INTO store VALUES(14, "iPhone 14 Plus", 6.7, "A15 Bionic chip", 11, "(PRODUCT)RED", 899);
INSERT INTO store VALUES(15, "iPhone 14", 6.1, "A15 Bionic chip", 11, "Blue", 799);

SELECT * FROM store ORDER BY price;
SELECT MAX(screen_size) FROM store;
