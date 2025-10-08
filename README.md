# E-VotingSystem

# E-Voting System

The E-Voting System is a web-based application designed to facilitate secure and streamlined electronic voting. It provides a platform for managing elections, registering voters, and securely recording and tabulating ballots, replacing traditional paper-based voting methods.

## ✨ Features

The file structure suggests a comprehensive system with both voter and administrative functions:

* **Voter Authentication:** Separate pages for user entry and exit (`login.php`, `logout.php`).
* **Admin Control Panel:** A dedicated section for administrators to manage the system and monitor results (`admin` folder).
* **Ballot Submission:** Core functionality for voters to cast their vote (`submit_ballot.php`).
* **Election Interface:** Main pages for the voting process (`index.php`, `home.php`).
* **Vote Preview:** A step for the voter to review their choices before final submission (`preview.php`).
* **Database Management:** Dedicated directory for database files (`database` folder), likely containing SQL scripts for setup.

## 💻 Technology Stack

The project is primarily built using server-side scripting, common for full-stack web applications:

* **Primary Languages:** PHP (79.0%) and Hack (21.0%).
* **Frontend:** Standard web technologies (HTML, CSS, JavaScript) are inferred, with CSS assets likely stored in the `dist/css` directory.
* **Database:** A relational database (likely MySQL, given the PHP dependency) is used to manage voter details, candidate information, and election results, with setup files in the `database` directory.

## ⚙️ Getting Started

To run this project locally, you will need a local server environment (like XAMPP, WAMP, or MAMP) that supports PHP and MySQL.

### Prerequisites

* PHP runtime environment (Version compatibility may need checking).
* MySQL database server.
* A web server (Apache/Nginx).

### Installation Steps

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/mirfathima/E-VotingSystem.git](https://github.com/mirfathima/E-VotingSystem.git)
    ```

2.  **Server Setup:**
    * Move the cloned `E-VotingSystem` folder to your web server's root directory (e.g., `htdocs` or `www`).

3.  **Database Setup:**
    * Access your database management tool (e.g., phpMyAdmin).
    * Create a new database (e.g., `votesystem`).
    * Import the SQL script found inside the `database` folder to create the necessary tables for voters, candidates, and administrative accounts.

4.  **Configuration:**
    * Update the database connection parameters (hostname, username, password, database name) in the connection file, typically located within the `includes` folder.

5.  **Access the Application:**
    * Open your web browser and navigate to the project's root URL (e.g., `http://localhost/E-VotingSystem/index.php`).

## 📁 Repository Structure

| Folder/File | Description |
| :--- | :--- |
| `admin/` | Contains files for the Administrator Dashboard and management tools. |
| `database/` | Holds the SQL dump or scripts required to initialize the database. |
| `includes/` | Stores common files like database connection, session handling, and function definitions. |
| `images/` | Stores images used throughout the system (e.g., candidate photos, logos). |
| `dist/css/` | Contains compiled stylesheets and frontend assets for styling. |
| `index.php` | The entry point or main landing page of the application. |
| `login.php` | Handles user authentication (voter or admin login). |
| `submit_ballot.php` | Processes and records the final vote submission into the database. |

