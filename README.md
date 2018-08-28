## About

As a (very) junior developer wanting to expand my horizons into functional languages, it seemed to me that Haskell was a good spot to jump into the deep-end of the pool. Having had experience with Scheme (a Lisp derivative) in the past, I found that I did not appreciate parsing through thousands of parenthesis when trying to parse through code.

I chose to replicate a game largely because it seemed to be a fun, low commitment way to test out my knowledge of the programming language, with there being a relatively low bar for what can be considered an MVP. Additionally, Duck Hunt is a classic, simple game, and hopefully will not be too hard to implement.

This project is currently in development, and if anyone has any tips for writing development-level Haskell, all input would be much appreciated!
	
## Tech Stack

This webpage is currently developed with the following technologies :

* [Yesod](https://www.yesodweb.com/) - A (Haskell) web framework for producing type-safe, RESTful web applications.
* [Shakespeare](https://hackage.haskell.org/package/shakespeare) - A family of type-safe templating languages which includes:
	* [Hamlet](http://hackage.haskell.org/package/hamlet) - A type-safe tool for the generation of HTML code.
	* [Julius](https://hackage.haskell.org/package/shakespeare-js-1.1.0/docs/Text-Julius.html) - A Shakespearean module for creating javascript templates with variable interpolation.
	* [Lucius](https://hackage.haskell.org/package/shakespeare-2.0.15/docs/Text-Lucius.html) - A superset of CSS.
	
* [Haskell](https://www.haskell.org/) - Declarative, statically typed code, and also the back end of this project.
