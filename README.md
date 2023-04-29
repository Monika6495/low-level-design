# low-level-design
This repo contains code of low level design bootcamp
Requirement of book my show app:
Actors - customer, movie operators ( eg pvr), system ( Book my show)

Common Modules: Sign-up, login, payment.

Customer Flow: 
1. Home Page -> by default location is selected through gps, according to the location content is displayed.
2. User can search for a movie or event or can select a category eg. movies, ipl, comedy shows.
3. If user choose a category eg movie ,they will get movies option 
4. Inside a category also , user should be able to filter by language.
5. Select a movie of choice, click on book tickets
6. Select the experience category eg, 2D or 3D.  ( If user type the movie name then directly this step).
7. See all the available theaters where movie is shown with the timings.
8. Choose an appropriate theatre.
9. Select timings and no of seats required.
10. Now user is presented a view of the theatre, select the seats.
11. Go to the payment gateway / selected if any add on's like popcorn is needed.
12. User should be able to hold the seats for 5, 10 min before doing payment.
13. Make the payment.
14. Get the tickets via email, sms, whatapp etc

Movie/Event operator Flow:

1. Register an event or movie by filling up the details like event title, venue, banners, schedule , tickets etc.
2. Once the request is raised , book my show might check it on some parameters as they can't promote anything and everything.
3. Operator have to give service charge to book my show for easing and promoting their events.
4. Once the content is approved , it is displayed on book my show and people can book it.

System ( Book my show):

1. Since BMS is a 3rd party vendor it needs to get events/ movie information . Theatre server can have some api which is called to get these information from the db's to get this information like available seats, price etc

2. Rating and reviews given by users are stored in book my show  db and is displayed accordingly.




