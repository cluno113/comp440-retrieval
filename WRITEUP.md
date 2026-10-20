# COMP 440: Representing and Retrieving Knowledge

Claude writes your answers here as you say them. A sentence or two is enough for each. Your
Part 0 predictions stay as you first wrote them; Part 5 asks what you would change.

**Name:** Claire Kuno
**Date:** October 20, 2026

## Part 0: Predictions

### Questions that name a character, place or thing: which method will do better, and why?

TF-IDF because it looks at plot summary in correspondence with a question, so instead of finding ranks of words, it will better isolate parts of the document that carries an answer close to the character, place, or thing.

### Vague descriptions: which method will do better, and why?

Embeddings will do better because it isn't looking for words that are rare or special, it is looking into words that are related. Vague questions will lead to vague answers, but at least they will be on topic.

## Part 1: Build the TF-IDF model

### The settings you chose, and why

- REMOVE_STOP_WORDS = True: Removing stop words helps to de-convolute the data and keeps important keywords that are distinctive to a movie.
- MIN_MOVIES = 2: Minimum movies helps to keep common correlation between summaries ensuring accuracy.
- REPEATS_COUNT_LESS = True: Repeats count less helps to ensure that the data is not identical and keeps variance.

## Part 2: Top terms

### Your movies: what do the top terms get right and wrong about what makes each one distinctive?

I think tedium for Dirty Dancing is from a summarizer with a negative review on the movie. But, they mostly get major themes of the movie such as 'Greek' for Mamma Mia and 'stepping' for Dirty Dancing.

## Part 3: Your own searches

### Your questions, as you typed them

1. A young girl meets an old man at a bar. The old man is a famous actor on a business trip in Tokyo. Their strange relationship takes them around the city and they navigate their relationships with their partners while engaging in a soul connection with each other.
2. A trouble man with lots of financial troubles hires someone to kidnap his wife in an attempt to earn ransom from his wife's father.
3. A man and a woman are neighbors with distant partners. When both of their partners leave, they find themselves healing their loneliness from their marriages with each other. They navigate the streets of Hong Kong as friends, and develop stronger feelings as their lives slowly become more intertwined and dependent on one another.

### Did the movies you meant come up? What did TF-IDF get right and wrong?

TFIDF got important keywords right, but because I didn't mention any names, it had a hard time identifying my first movie 'Lost in Translation' and my third movie 'In the Mood for Love'. I think its because words like woman and man are not very specific.

## Part 4: The question bank

### Which kind of question did TF-IDF handle best, and which worst? By how much?

XXXX

### The misses you looked at: what do they have in common?

XXXX

## Part 5: Embeddings

### What is a sentence embedding, in your own words?

XXXX

### Where does each method do better, and why?

XXXX

### Your Part 0 predictions: which held, and which would you change?

XXXX

### How might you combine the two methods?

XXXX
