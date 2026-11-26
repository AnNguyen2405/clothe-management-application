[Clothe management application]

A desktop application for organizing and managing a clothing inventory or wardrobe, built with Java and JavaFX. The UI was designed with Scene Builder (FXML), and data is persisted in a MySQL database. The database was initially hosted on Azure and later moved to a local MySQL server (localhost).

Developed as the final project for the OOP Programming with Java module at Frankfurt University of Applied Sciences by a team of three.

Features
Add, edit, view, and delete clothing items
Categorize items by type, size, color, brand, season, etc. (adjust to your actual fields)
Search and filter the collection
Persistent storage in MySQL
Clean GUI designed in Scene Builder using FXML
Architecture
Layer	Technology
Language	Java [version]
UI framework	JavaFX
UI design	Scene Builder (FXML)
Database	MySQL
Database access	JDBC
Hosting	Azure initially, later localhost
Build tool	[Maven / Gradle]

The project follows OOP principles, with a clear separation between model classes (e.g., ClothingItem), controllers handling FXML views, and a data access layer communicating with MySQL.

JavaFX UI (FXML)  -->  Controllers  -->  DAO / Service  --JDBC-->  MySQL

Note on Hosting

The database was originally deployed on Azure during development. For ease of setup and reproducibility, the project was later switched to a local MySQL instance, so no cloud account is required to run it.

Team
Name	Role
Nguyen Thanh An	Developed the back-end structure as well as database design
Doan Quoc Hung	Develop the front-end design as well as project overall integration
Luong Gia Bao	Developed OOP design as well as maintaining project's compatibility between back-end and front-end
