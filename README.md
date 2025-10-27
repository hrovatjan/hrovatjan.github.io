# Learn Man Fish

![Learn Man Fish](https://raw.githubusercontent.com/benni-ben/Learn-Man-Fish/1024698e21d42335e3df1fa8c82251aadfd91628/Logo/Learn%20Man%20Fish.svg)


**Learn Man Fish** is an "inspirational" quote generator that can make quotes based on already existing ones. It can be used offline, is simplistic, and can be used daily to motivate you. It includes the quote author's name, as well as their job. It is also very accurate, and always is correct. 

**Learn Man Fish** also relies on *Materialize CSS*, a JS and CSS library based on Material Design Standards(though it is only used in about 25% of the page). 

http://materializecss.com/

![](https://github.com/benni-ben/Learn-Man-Fish/blob/main/SCREENSHOT1.png?raw=true)

### Also, please remember to star the repository!

## Development

**Learn Man Fish** is written in HTML and Javascript(and CSS). All of the JS logic is inside of the HTML file, and can be modified. 

> Want a feature to be added? Open an issue, and I will try to respond whenever I can! I will take any suggestions.


### Functions

 - `randomAuthor()` sets the `quoteAuthor`(authorBox in HTML) to the author's name, followed by a comma, followed again by their "real" job role. Also changes the `quoteAuthor` text shadow color to a random one. Uses the `jobsdb.json` and `quotesdb.json` to create the string, so they must be present for it to function properly. 

 - `randomNumber(min,max)` returns a random number between the provided values, where `min` is the minimum value, and `max` is the maximum value(if min and max are the same, it will just return min).

 - `getQuote()` returns a random quote, unprocessed. Gets quote from `quotesdb.json`.

 - `garbleQuote(quote)` garbles the given quote, processes the text, and then returns it. Returned text has a period at the end.

### Modding

**Learn Man Fish** can be modded fairly easily. Since all of the code is in the HTML file, you can edit parts of it easily. The code is also commented.

If you want to edit the JSONs, be sure to follow the field format, or else the website will not work(or just change the code to accept your custom field).

Also, the quotes are in the `quotesdb.json` file, as well as the authors. Since the authors are randomized, you can change any of them without it breaking. 

## Inspiration

>>> This project is based on `Teach Man Fish`, a garbled quote generator. I felt that I should make my own remake of it, since Teach Man Fish relied mostly on external APIs, and was hard to read the code since it was uncommented and overall was messy. This should fix all of those issues, while making it look more visually appealing.  
