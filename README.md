Internal WordPress Website for Office Communication

What did you learn about how WordPress stores its files and data?
I learned that WordPress uses two different places to store everything. It keeps all the files like the core code, themes, plugins, and any pictures I upload—in folders on the server (mainly in wp-content). But the actual data like all the content I type into posts, the user accounts, and all the settings that stuff is kept separate in a MySQL database. It's a dual system, separating the look of the site from the content.

Which part was more complex: handling files or managing the database?
Managing the database was definitely more complex. You can just copy and paste files, but if you want to change something in the database, you need special tools and knowledge (SQL commands) because the data is spread across different tables that all link together. If you mess up one file, the site might just look funny, but if you mess up the database, the whole site can crash, which makes that part much riskier to deal with.

Why is version control useful for a WordPress project in an office setting?
Version control is super helpful for us in the office because it brings accountability and safety. Since everyone might touch the site, GitHub tells us who made what change and when. If someone installs a bad plugin or messes up the code, we can instantly roll the entire website back to the last perfect version without losing much time. It basically guarantees that we all work from the same files and gives us a big safety net if anything goes wrong.
