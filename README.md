# NoSQL Challenge: UK Food Hygiene Ratings Analysis #
## Project Overview ##
In the "nosql-challenge" project, I undertook a data engineering and analysis task focused on the UK Food Standards Agency's hygiene ratings. This involved importing, updating, and analyzing data within a NoSQL (MongoDB) environment, using Python and Jupyter Notebooks for interaction and analysis.

## Key Accomplishments ##
### Database Setup and Data Import ### 
- Successfully imported establishments.json into a MongoDB database named uk_food, with a collection named establishments.
- Utilized PyMongo and Pretty Print (pprint) in Jupyter Notebook for effective database interaction.
- Validated the database setup by listing databases in MongoDB, ensuring the presence of uk_food and establishments.
### Database Update ###
- Added a new record for "Penang Flavours," a recently opened restaurant.
- Updated the BusinessTypeID for "Penang Flavours" using the appropriate value from the dataset.
- Removed all records associated with the Dover Local Authority from the database.
- Performed type conversions for latitude, longitude, and RatingValue fields using update_many() to ensure data accuracy.
### Exploratory Data Analysis ###
- Conducted a series of complex queries to provide insights for "Eat Safe, Love" magazine.
- Queries included identifying establishments with specific hygiene scores, filtering establishments by location and rating, and sorting results based on various criteria.
- Transformed query results into Pandas DataFrames for enhanced data presentation and analysis.
### Analytical Questions Addressed ###
- Identified establishments with a hygiene score of 20.
- Filtered establishments in London with a RatingValue greater than or equal to 4.
- Located top-rated establishments near "Penang Flavours" based on hygiene scores and geographical proximity.
- Analyzed the distribution of establishments with a hygiene score of 0 across different Local Authority areas.
## Technical Proficiency ##
- Demonstrated expertise in using MongoDB for NoSQL database management and PyMongo for database operations.
- Applied Python for data manipulation, query execution, and analysis.
- Utilized Jupyter Notebooks as a platform for executing Python code and presenting findings.
## Repository Management ##
Maintained an organized and well-documented GitHub repository ('nosql-challenge') for the project.
Ensured code clarity with comprehensive comments and structured formatting.
