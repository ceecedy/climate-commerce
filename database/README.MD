# Database Directory

This directory contains the `database.db` file, which is used for the duckdb to load the database.

However, due to the file size exceeding 50 MB, I decided **not to push it to the remote Git repository**. GitHub has a file size limit of 100 MB per file for repositories, and as `database.db` is larger than that, I chose to exclude it from version control.

You can just run the transformation files and it will build the database file itself if you will try this project on your own. 

### Important Notes:
- The `database.db` file is **excluded from version control** by being added to the `.gitignore` file.
- Please ensure you have the proper access to the database file if you need it for development or testing purposes.

Thank you for understanding!
