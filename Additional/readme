# Data Dictionary

This section contains the database structure used in QuizAT - Android Quiz App.

The application uses Firebase Realtime Database to manage users, quizzes, question papers, scheduled quizzes, and student attempts.

---

## User

| Column Name | Data Type | Size | Constraints |
|------------|-----------|------|-------------|
| userId | String | 50 | Primary Key |
| username | String | 30 | Not Null |
| email | String | 100 | Not Null |
| password | String | 100 | Not Null |
| role | String | 15 | Not Null |

---

## Student

| Column Name | Data Type | Size | Constraints |
|------------|-----------|------|-------------|
| studentId | String | 50 | Primary Key |
| name | String | 80 | Not Null |
| username | String | 30 | Not Null |
| email | String | 100 | Not Null |
| password | String | 100 | Not Null |
| role | String | 15 | Not Null |
| course | String | 50 | Not Null |
| enrollmentNo | String | 30 | Not Null, Unique |

---

## Question Paper

| Column Name | Data Type | Constraints |
|------------|-----------|-------------|
| duration | Int | Not Null |
| numOptions | Int | Not Null |
| status | String | Not Null |
| totalQuestions | Int | Not Null |

---

## Attempt

| Column Name | Data Type | Constraints |
|------------|-----------|-------------|
| studentId | String | Foreign Key (Student) |
| answers | Map<String, String> | Not Null |
| score | Int | Not Null |

---

## Quiz

| Column Name | Data Type | Size | Constraints |
|------------|-----------|------|-------------|
| id | String | 50 | Primary Key |
| name | String | 100 | Not Null |
| description | String | 300 | Not Null |
| batch | String | 30 | Not Null |
| examiner | String | 50 | Foreign Key (User) |

---

## Scheduled Quiz

| Column Name | Data Type | Size | Constraints |
|------------|-----------|------|-------------|
| date | String | 10 | Not Null |
| duration | Int | 3 | Not Null |
| quizName | String | 50 | Foreign Key (Quiz) |
| startTime | String | 5 | Not Null |
| totalMarks | Int | 3 | Not Null |
