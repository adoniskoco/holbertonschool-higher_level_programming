# README for MySQL Scripts

This repository contains various SQL scripts designed to manipulate MySQL databases. Below is a description of each task and its associated script file.

### Task List

1. **Task: List privileges for MySQL users `user_0d_1` and `user_0d_2`**
   - **File:** `0-privileges.sql`
   - Description: This script lists all privileges granted to the users `user_0d_1` and `user_0d_2` on the MySQL server running on localhost.

2. **Task: Create MySQL user `user_0d_1`**
   - **File:** `1-create_user.sql`
   - Description: This script creates a new MySQL user `user_0d_1`.

3. **Task: Create MySQL user `user_0d_2` and database `hbtn_0d_2`**
   - **File:** `2-create_read_user.sql`
   - Description: This script creates the database `hbtn_0d_2` and the MySQL user `user_0d_2`.

4. **Task: Create a table `force_name`**
   - **File:** `3-force_name.sql`
   - Description: This script creates a table called `force_name` in the MySQL server.

5. **Task: Create a table `id_not_null` with a NOT NULL constraint**
   - **File:** `4-never_empty.sql`
   - Description: This script creates the table `id_not_null`, ensuring that the `id` field cannot be NULL.

6. **Task: Create a table `unique_id` with a unique constraint**
   - **File:** `5-unique_id.sql`
   - Description: This script creates the table `unique_id` with a unique constraint on the `id` field.

7. **Task: Create the database `hbtn_0d_usa` and table `states`**
   - **File:** `6-states.sql`
   - Description: This script creates the `hbtn_0d_usa` database and the `states` table within that database.

8. **Task: Create the database `hbtn_0d_usa` and table `cities`**
   - **File:** `7-cities.sql`
   - Description: This script creates the `hbtn_0d_usa` database and the `cities` table within that database.

9. **Task: List all cities in California from the `hbtn_0d_usa` database using a subquery**
   - **File:** `8-cities_of_california_subquery.sql`
   - Description: This script lists all cities in California in the `hbtn_0d_usa` database using a subquery.

10. **Task: List all cities in the `hbtn_0d_usa` database**
    - **File:** `9-cities_by_state_join.sql`
    - Description: This script lists all cities in the `hbtn_0d_usa` database by joining the `states` and `cities` tables.

11. **Task: List all shows in `hbtn_0d_tvshows` with at least one linked genre**
    - **File:** `10-genre_id_by_show.sql`
    - Description: This script lists all shows in the `hbtn_0d_tvshows` database that have at least one genre linked.

12. **Task: List all shows in `hbtn_0d_tvshows`**
    - **File:** `11-genre_id_all_shows.sql`
    - Description: This script lists all shows in the `hbtn_0d_tvshows` database, regardless of genre.

13. **Task: List all shows in `hbtn_0d_tvshows` without a genre linked**
    - **File:** `12-no_genre.sql`
    - Description: This script lists all shows in the `hbtn_0d_tvshows` database that do not have any genre linked.

14. **Task: Count the number of shows linked to each genre in `hbtn_0d_tvshows`**
    - **File:** `13-count_shows_by_genre.sql`
    - Description: This script lists all genres in `hbtn_0d_tvshows` along with the number of shows linked to each genre.

15. **Task: List all genres of the show `Dexter`**
    - **File:** `14-my_genres.sql`
    - Description: This script lists all genres linked to the show `Dexter` in the `hbtn_0d_tvshows` database.

16. **Task: List all Comedy shows in `hbtn_0d_tvshows`**
    - **File:** `15-comedy_only.sql`
    - Description: This script lists all shows in the `hbtn_0d_tvshows` database that are classified under the Comedy genre.

17. **Task: List all shows and their linked genres in `hbtn_0d_tvshows`**
    - **File:** `16-shows_by_genre.sql`
    - Description: This script lists all shows in `hbtn_0d_tvshows` along with all the genres linked to each show.