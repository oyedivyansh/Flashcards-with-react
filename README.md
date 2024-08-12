# flashcards-react

Build a set of flashcards that runs in the browser.

Start out with a hard coded set of flash cards:

```js

const cards = [
  {
    question: '2+2',
    answer: 4
  },
  {
    question: 'capital of Malaysia',
    answer: 'Kuala Lumpur'
  },
  {
    question: 'Kilometers in a mile',
    answer: 1.6
  },
];
```

Create an interface that shows these cards one at a time.

When the user clicks a button, show the answer.

When the user clicks a button, advance to the next card.

#### Further
The user can mark a card, "know", "don't know". Each answered card will be put into a different box on the screen. (a sibling component)

#### Further
The user can guess the answer by entering it into a form input.

If the user gets it wrong it can automatically go into "don't know"

If the user gets it right, it goes into "know"

#### Further
At the finish of running throughn all the cards, give stats to the user about their answers.

#### Further
Add more options to the card questions: (you can still hard code the questions)

- multiple choice answers
- embedded youtube videos
- audio file links

#### Further
Create an edit mode where the user can edit any card.

#### Further
Allow the user to create multiple decks of cards

