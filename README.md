# Movie-Recommender-System
## TMDb 5000 Movie Dataset
####  Data Description
The TMDb 5000 movie dataset is a comprehensive collection of movie-related data, featuring attributes such as movie titles, release dates, genres, budgets, revenues, and user ratings. It includes metadata like plot summaries, taglines, and production details (companies and countries), along with financial metrics and popularity scores. 
#### Data Attributes
+ budget: The budget allocated for the movie, in USD.
+ genres: List of genres associated with the movie (e.g., Action, Comedy).
+ homepage: File path or URL to the movie’s homepage.
+ id: Unique identifier for the movie.
+ keywords: keywords associated with the movie
+ original_language: The original language of the movie.
+ original_title: The original title of the movie.
+ overview: A brief summary of the movie's plot.
+ popularity: A score indicating the movie's popularity, often based on metrics like views and user interactions.
+ production_companies: List of production companies involved in making the movie.
+ production_countries: List of countries where the movie was produced.
+ release_date: The release date of the movie in DD-MM-YYYY format.
+ revenue: Box office revenue earned by the movie, in USD.
+ runtime: Duration of the movie in minutes.
+ spoken_languages: The languages spoken in the movie
+ status: The status of the movie whether released or not
+ tagline: A tagline associated with the movie.
+ title: Title of the movie.
+ vote_average: Average user rating of the movie, typically on a scale from 1 to 10.
+ vote_count: Number of votes or ratings the movie has received.
## TMDb 5000 Credit 
#### Data  Description
The TMDb credits dataset provides detailed information about the cast and crew involved in movies. It includes attributes such as the movie’s unique ID, names of actors and actresses, and their roles (e.g., lead actor, supporting actress). For crew members, it lists their roles, such as director, writer, or producer. This dataset is essential for understanding the contributions of individuals to films and is useful for analyzing relationships between cast/crew and movie success.
#### Data Attributes
+ movie_id: A unique identifier for the movie, which links the credits data to specific films in the TMDb movie dataset.
+ title: Title of the movie.
+ cast
  + cast_id: A unique identifier for each cast member in the context of a particular movie.
  + character: The name of the character played by the actor or actress in the movie.
  + credit_id: A unique identifier for each credit entry, useful for distinguishing different roles or entries for the same person.
  + gender: The gender of the cast member (e.g., Male, Female).
  + id: A unique identifier for the cast member, which links to other datasets for more detailed information about the person.
  + name: The name of the cast member.
  + order: The order in which the cast member is listed, often reflecting the prominence or importance of their role.
+ crew
   + credit_id: A unique identifier for each crew credit.
   + department: The department or area of work (e.g., Directing, Writing, Production) where the crew member contributed.
   + gender: The gender of the crew member.
   + id: A unique identifier for the crew member, linking to additional details about the person.
   + job: The specific job or role performed by the crew member (e.g., Director, Producer, Writer).\
   + name: The name of the crew member.
