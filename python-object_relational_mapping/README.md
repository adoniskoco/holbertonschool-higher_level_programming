## Tasks Overview

### 1. `0-select_states.py`
- **Description**: Lists all states from the database `hbtn_0e_0_usa`.
  
### 2. `1-filter_states.py`
- **Description**: Lists all states from the database `hbtn_0e_0_usa` where the state name starts with "N".

### 3. `2-my_filter_states.py`
- **Description**: Takes an argument and displays all states from the `hbtn_0e_0_usa` database that match the given name.

### 4. `3-my_safe_filter_states.py`
- **Description**: Similar to `2-my_filter_states.py`, but with protection against SQL injection by using safe query techniques with parameterized queries.

### 5. `4-cities_by_state.py`
- **Description**: Lists all cities from the database `hbtn_0e_4_usa`.

### 6. `5-filter_cities.py`
- **Description**: Takes the name of a state as an argument and lists all cities from that state using the `hbtn_0e_4_usa` database.

### 7. `model_state.py`
- **Description**: Contains the class definition for a `State` using SQLAlchemy's `Base` class for ORM (Object-Relational Mapping).

### 8. `7-model_state_fetch_all.py`
- **Description**: Lists all `State` objects from the `hbtn_0e_6_usa` database using SQLAlchemy ORM.

### 9. `8-model_state_fetch_first.py`
- **Description**: Prints the first `State` object from the `hbtn_0e_6_usa` database.

### 10. `9-model_state_filter_a.py`
- **Description**: Lists all `State` objects from the `hbtn_0e_6_usa` database that contain the letter "a" in their name.

### 11. `10-model_state_my_get.py`
- **Description**: Prints a `State` object with a specific name passed as an argument from the `hbtn_0e_6_usa` database.

### 12. `11-model_state_insert.py`
- **Description**: Adds a new `State` object with the name "Louisiana" to the `hbtn_0e_6_usa` database.

### 13. `12-model_state_update_id_2.py`
- **Description**: Changes the name of a `State` object (with id = 2) in the `hbtn_0e_6_usa` database.

### 14. `13-model_state_delete_a.py`
- **Description**: Deletes all `State` objects with a name containing the letter "a" from the `hbtn_0e_6_usa` database.

### 15. `model_city.py`
- **Description**: Contains the class definition for a `City` using SQLAlchemy's `Base` class, similar to `model_state.py`.

### 16. `14-model_city_fetch_by_state.py`
- **Description**: Lists all `City` objects from the `hbtn_0e_14_usa` database, displaying each city's name along with the associated state's name.