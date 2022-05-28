# putters
Practice SQL database for putter variations

CREATE TABLE putters (
    id INTEGER PRIMARY KEY,
    head TEXT,
    shaft TEXT,
    grip TEXT,
    price INTEGER
    );
    
INSERT INTO putters VALUES (1, "M375", "Stability", "Garsen", 699);
INSERT INTO putters VALUES (2, "M375", "KBS GREEN", "Garsen", 349);
INSERT INTO putters VALUES (3, "M375", "KBS WHITE", "Garsen", 349);
INSERT INTO putters VALUES (4, "NOSTALGIA", "Stability", "Garsen", 749);
INSERT INTO putters VALUES (5, "NOSTALGIA", "KBS GREEN", "Garsen", 449);
INSERT INTO putters VALUES (6, "NOSTALGIA", "KBS WHITE", "Garsen", 449);
INSERT INTO putters VALUES (7, "NOSTALGIA", "KBS GREEN", "SUPER STROKE", 449);
INSERT INTO putters VALUES (8, "NOSTALGIA", "KBS WHITE", "SUPER STROKE", 449);
INSERT INTO putters VALUES (9, "NOSTALGIA", "KBS CHROME BLACK", "Garsen", 449);
INSERT INTO putters VALUES (10, "NOSTALGIA", "KBS MATTE BLACK", "Garsen", 449);
INSERT INTO putters VALUES (11, "M375", "KBS CHROME BLACK", "Garsen", 349);
INSERT INTO putters VALUES (12, "M375", "KBS MATTE BLACK", "Garsen", 349);
INSERT INTO putters VALUES (13, "M375", "GENERIC CHROME", "Garsen", 329);
INSERT INTO putters VALUES (14, "M375", "GENERIC BLACK", "Garsen", 329);
INSERT INTO putters VALUES (15, "M375", "GENERIC MATTE", "Garsen", 329);

SELECT * FROM putters ORDER BY price DESC;
SELECT AVG(price) FROM putters;
