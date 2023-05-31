# MDN's Local Library Express Tutorial

[Source](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/skeleton_website)

UML association diagram:

- shows models we define in boxes
- shows relationships between models
- shows **multiplicities**: min & max numbers of each model that may be present in the relationship

For example:

- Lines connecting `Book` & `Genre`: shows that they're connected
- Numbers close to `Book`: show a `Genre` must have 0 or more `Books` (as many as you'd like)
- Numbers close to `Genre`: show a `Book` can have zero or more associated genres

![UML Association Diagram](screenshots/library_website_-_mongoose_express.png)

![Express MVC](screenshots/mvc_express.png)
