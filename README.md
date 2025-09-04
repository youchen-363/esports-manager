# Esports Competition Management System

Welcome to the Esports Competition Management System, a Java application designed for the efficient management of esports tournaments. This project uses `derby.jar` for JDBC database operations. This JAR file is included in the project's repository on GitLab. The recommended IDE for this project is Eclipse. To run the application, follow the steps below.

---

### Installation

1.  Clone the repository:

    ```sh
    git clone [https://gitlab.info.iut-tlse3.fr/khc4298a/SAE-e-sport.git](https://gitlab.info.iut-tlse3.fr/khc4298a/SAE-e-sport.git)
    ```

2.  Open the project with Eclipse.

3.  Add `Derby.jar` to the project by navigating to:
    `Properties -> Java Build Path -> Add External JARs`

---

### Running the Application

1.  Open the **Application** package.

2.  Run the "**Donnees.java**" file to load the datasets.
    
    * Click `Run Application`.

3.  Next, run the **Application.java** file to launch the main application.

---

### Features

#### 1. User Authentication
* **Two user types:** Administrator and Referee.
* **Admins** can manage tournaments, matches, history, and referees.
* **Referees** can choose the winner of a match and the final.

#### 2. Tournament Management
* Create a tournament.
* View all tournaments.
* Import teams for a tournament.
* Assign referees to a tournament.
* Open and close a tournament.
* Determine the tournament winner.

#### 3. Match Management
* Choose match winners.
* Automatically calculate points for standings.
* Create a final.

#### 4. Team Management
* View all teams in the database.
* Modify a team's name and country.
* A team's composition cannot be changed during the current season.

#### 5. Referee Management
* Add and delete referees.

#### 6. Point History Management
* Track points earned by each team across all tournaments played.

---

### License

This project is under the MIT license. You are free to copy, modify, and distribute this code. See the `LICENSE` file for more details.

Thank you for using our Esports Competition Management System! If you have any questions or suggestions, feel free to contact us.
