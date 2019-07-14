# Web-App-Flashcards
Language translation and learning web app.  
It will include both browser-side and server-side programming.

## Key features of our app
1. Google login and getting word translations from the Google Translate API.
2. Front end with React.
3. Set up a database to store the flashcards with sqlite3 module.
4. Lets users review and flip the flashcards.  

## App View
![flow](https://github.com/jiajunliangucdavis/Web-App-Flashcards/blob/master/View%20and%20Flow/flow.jpg)
![login](https://github.com/jiajunliangucdavis/Web-App-Flashcards/blob/master/View%20and%20Flow/login.png)
![create](https://github.com/jiajunliangucdavis/Web-App-Flashcards/blob/master/View%20and%20Flow/create.png)
![review](https://github.com/jiajunliangucdavis/Web-App-Flashcards/blob/master/View%20and%20Flow/review.png)
![correct](https://github.com/jiajunliangucdavis/Web-App-Flashcards/blob/master/View%20and%20Flow/correct.png)

## Note
1. The submission will initially contain an empty database, Flashcards.db. 
2. Please save more cards and also try more times to see those random "new" review cards... It could be the same review card for several times. Once you have saved and seen couple cards and answered them correctly, the whole cards' displaying order will be more random. Prefer more cards saved!
3. The card flipping behavior is quite sweet. You can flip back and forth without changing the card; you can get a new card by clicking "next button" whenever you are in front card view or back card view. A new card will be always ready for you whenever you click "start review" or just old user logging in.
4. Enjoy playing with it! 
5. Some old users may only use translation service without saving any flashcard. Then our app could redirect them to the create cards view each time until they actually save any flashcards.

## How to run
0. Run "node miniServer6.js".
1. Go to http://server162.site:56899/login.html
2. No matter new user or old user, both click login.
3. First-time user redirects to google and enter password while old user goes directly to next step.
4. From there, check to see if the user has any flashcards. If so, redirect to the review cards view. Otherwise redirect to the create cards view.
