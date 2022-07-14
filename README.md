# iD10t Team - Phase 1 Project

## Overview:

### Microsoft would like to begin creating original video content. It is our job to explore what types of movies are doing well at the box office. After exploring the data, Microsoft would like some actionable insights they can use to decide what type of movies to create.

This repo contains all files, links and supplemental resources needed to access the group project created by the iD10t Team. 

In this project we have used exploratory Data Analysis to generate insights on popular movies for our business stakeholder.

Feel free to use the zipped files within the Data folder to run the primary Jupyter Notebook (titled : primary_jupyter_notebook)


## Business Understanding:

To limit the scope of this request we have explored what genres, actors, directors, qualities and release dates of films have the highest return on investment (ROI). 

## Data Understanding and Analysis:

### The data used in this analysis come from five sources including:

     - Box Office Mojo
     - IMDB
     - Rotten Tomatoes
     - The Movie DB
     - The Numbers

### With the scope identified above our team only needed to use information from the IMDB DB and The Numbers. Included is a list of all tables and dataframes. 

The BOM table included data on domestic and foreign gross for roughly 3000 movies.

The IMDB DB is best understood through their ERD:


![movie_data_erd.jpeg](https://github.com/JordanMang/phase_1_id10t_team/blob/master/Images/movie_data_erd.jpeg)

The Rotten Tomatoes tables were a table of reviews and a table of the movies reviewed.

THe Movie DB held release date, movie title, domestic and foreign gross as well as production cost.

The Numbers contained a list of movies, their average rating and the number of votes its average was taken from.


# Results:

### Genre:

![download%20%283%29.png](https://github.com/JordanMang/phase_1_id10t_team/blob/master/Images/download%20(3).png)

If the studio wanted to produce a movie in a genre that would lead to the best ROI. As a new studio, movies that can create a strong return may be more important to demonstrate the studio's viability to Mr. Gates.
If so, movies that don't require a large budget, like a horror, mystery, or musical may be the better option.
With these visualizations, it's important to note that they all had massive appeal, as they come from a dataset of films that did very well, so no matter the choice of genre, it's important to make a good film the public will enjoy.
How you select your actors and your directors will play a very big role in how any movie in any genre will perform.

### Actors and Directors:

![download%20%281%29.png](https://github.com/JordanMang/phase_1_id10t_team/blob/master/Images/download%20(1).png)

![download-6.png](https://github.com/JordanMang/phase_1_id10t_team/blob/master/Images/download-6.png)

Directors draw in audiences! Zack Snyder, Tim Burton and Ridley Scott create universes that pull in over $100 million in box office. These directors have unique, beloved film-making styles and their fans will come out multiple times to see their films.

Movie star appeal has always been a major box office draw. Actors like Dwayne Johnson, Jennifer Lawrence and Kevin HArt not only make us laugh and cry, they aslso inspire us. These actors average over $150 million per film because they have an army of fans waiting for new films. Casting one of these stars may liekly drive high box office sales.

### Release Date:

![test.jpeg](https://github.com/JordanMang/phase_1_id10t_team/blob/master/Images/finalpbw2.jpeg)

![Screen%20Shot%202022-07-13%20at%208.45.01%20PM.png](https://github.com/JordanMang/phase_1_id10t_team/blob/master/Images/finalpbm2.jpeg)

It is also important to note that the release date of a movie plays a key role in its success. When it comes to the box office, it is important to release your film when the highest number of people have the time to see it and this tends to be located around the holidays. It goes without saying that days like Christmas, Thanksgiving and Memorial Day allow people the freedom to attend movie openings. It should also be said that there is a large boost in the summer when there is more daylight and students are on summer break. 

# Reviews:

![ROI.jpeg](https://github.com/JordanMang/phase_1_id10t_team/blob/master/Images/ROI.jpeg)

The production company may not be able to control how it is perceived by the audience and critics, but it is important to note that creating something that is critically acclaimed will actually negatively impact the return on investment. From the graph we can gather that movies that are perceived as an eight, even on the lower end of their ROI, make the most money in box office. At this point we can only hypothesize why this may be but an educated guess would be that the audience would prefer something entertaining rather than something critically acclaimed. You can have confidence that you will have a strong ROI if you see ratings coming in at about an eight out of ten.

## Conclusion:

It is of our recommendation that in the beginning focusing on ROI and working with genres such as horror, musicals and mystery will help a new studio build a solid foundation. When it comes to the selection of directors and actors, Tim Burton and Dwayne Johnson are at the head of profitability. Releasing during a holiday season or during summer will help gain the film more profit by increasing the viewing publics ability to see it in theater. Finally, it is important to remember that catering to the critics can will reduce ROI, the public wants entertainment, not a work of art.

## Next Steps:


Given another week of analysis we would like to explore the relationship between profitable actors and genre to understand which actors net the highest return per genre.

This logic can also be extended to what directors would be profitable for each genre.

Using our time to understand how many big name movies are released on a given week will help us understand the competion of holiday releases.

Lastly, understanding how marketing impacts ROI would be helpful in understanding how much of a budget should given to marketing.
