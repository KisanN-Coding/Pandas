# Datasets Used

Below are the datasets used across the notebooks with short descriptions:

## 1. `students.csv` (25 rows, 3 columns)

* **student\_id** → Unique identifier for students
* **name** → Student’s name
* **partner** → Assigned project/study partner

## 2. `courses.csv` (12 rows, 3 columns)

* **course\_id** → Unique identifier for course
* **course\_name** → Name of the course (e.g., Python, SQL)
* **price** → Course price/fees

## 3. `reg-month1.csv` (25 rows, 2 columns)

* **student\_id** → Maps student to a course
* **course\_id** → References `courses.csv` for course details

## 4. `reg-month2.csv` (28 rows, 2 columns)

* **student\_id** → Maps student to a course
* **course\_id** → References `courses.csv` for course details

## 5. `matches.csv` (636 rows, 18 columns)

Contains details of **IPL matches**.

* **id** → Match ID
* **season** → Year of the season
* **city**, **date**, **venue** → Match location details
* **team1**, **team2** → Competing teams
* **toss\_winner**, **toss\_decision** → Toss details
* **winner**, **win\_by\_runs**, **win\_by\_wickets** → Match outcome
* **player\_of\_match**, **umpire1**, **umpire2**, **umpire3** → Match officials

## 6. `deliveries.csv` (179,078 rows, 21 columns)

Ball-by-ball details of **IPL matches**.

* **match\_id** → References `matches.csv`
* **inning**, **over**, **ball** → Delivery details
* **batting\_team**, **bowling\_team** → Teams involved
* **batsman**, **bowler**, **non\_striker** → Players involved
* **runs (wide\_runs, bye\_runs, legbye\_runs, noball\_runs, batsman\_runs, extra\_runs, total\_runs)** → Run details
* **player\_dismissed**, **dismissal\_kind**, **fielder** → Wicket details

## 7. `imdb-top-1000.csv` (1000 rows, 10 columns)

Top 1000 movies dataset from IMDb.

* **Series\_Title** → Movie name
* **Released\_Year** → Release year
* **Runtime** → Duration
* **Genre** → Movie genre
* **IMDB\_Rating** → IMDb rating
* **Director** → Director of the movie
* **Star1** → Leading actor/actress
* **No\_of\_Votes** → Number of votes received
* **Gross** → Box office collection
* **Metascore** → Critic score

---

