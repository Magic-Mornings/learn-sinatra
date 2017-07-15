# Learn Sinatra

Sinatra is a lightweight framework for creating web applications with Ruby.

Official documentation at http://www.sinatrarb.com/intro.html

## The Challenge:

1. Optional: Follow the tutorial at https://code.tutsplus.com/tutorials/singing-with-sinatra--net-18965 to learn the basics of Sinatra.
2. Get "Hello World" served when you visit `localhost:4567/`
3. Create an `/is-prime` route that takes a number as a URL parameter (ex: `/is-prime/4`).  The page should display a message saying whether the number is prime (ex: '4 is not prime!'). If the number is prime, the page should have a green background, and if it's not prime, the background should be red.
4. Create a `/mad-libs` route that renders a form prompting the user to enter at least 4 words (noun, verb, adjective, etc.). When the user submits the form, show them a new page where they'll see a story that uses all the words they entered.
5. Create a `/jokes` route that displays a random joke from http://www.icndb.com/api/. Every time you refresh the page it should show a new joke. (Hint: see https://blog.engineyard.com/2014/doing-an-api-mashup-with-sinatra)
6. Create a calculator that accepts nested routes with numbers and operators so that `localhost:4567/calculator/8/plus/10/divided/9` takes you to a page that says '2'.
7. Create a `/guess-the-number` route where the user must attempt to guess a secret random number between 1 and 100. They should submit their answer using a text field and button. After they submit a guess they will be told if their guess is too high, too low, or correct, and they can keep guessing until they guess the right answer.
8. Create a `/to-do` route. When a user first visits, they should see a header that says 'My To-Do List' and a text field with a submit button. Every time the user submits a task, it should be added to the page in a list. (Hint: see https://learn.co/lessons/sinatra-activerecord-setup)
9.  Next to each task in the to-do list, add a link that says 'Complete'. When the link is clicked, the task should be shown in strikethrough (`<s></s>`) and it should no longer have a 'Complete' link next to it.
