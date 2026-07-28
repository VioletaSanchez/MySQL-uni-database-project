INSERT INTO students (student_name, student_email)
VALUES
	("Violeta", "violeta@email.com"),
	("Daphne", "daphne@email.com"),
	("Christian", "christian2@email.com"),
	("Jasper", "jasper_autumn@email.com"),
	("Eri", "eri_gb@email.com");

INSERT INTO courses (courses_name, courses_price)
VALUES
	("Javascript", 1000),
	("MySQL", 800),
	("API development", 900),
	("CSS styling", 850),
    ("Git", 980);

INSERT INTO professors (professors_name, professors_email, professors_department)
VALUES
	("Tai", "tai@uni.com", "Database"),
	("John", "john@email.com", "Style"),
    ("Benjamin", "ben_bnm@gmail.com", "Style"),
    ("Maria", "mb_ink@email.com", "Remote"),
    ("Liz", "LHL@uni.com", "Database");
    
INSERT INTO grades (grades_students_id, grades_courses_id, grades_score, grades_professors_id)
VALUES
	(36, 31, 7, 27),
    (37, 31, 9, 27),
    (38, 31, 6, 27),
    (39, 31, 10, 27),
    (40, 31, 10, 28),
    (36, 33, 8, 29),
    (37, 33, 9, 29),
    (38, 33, 9, 29),
    (39, 33, 5, 29),
    (40, 33, 7, 29),
    (36, 35, 9, 29),
    (37, 35, 10, 29),
    (38, 35, 10, 29),
    (39, 35, 7, 29),
    (40, 35, 8, 29);