# Languages
Over the course of studying interesting languages, I came up with / found some useful language concepts.

## Concepts
### Simplicity
Simplicity is the core concept of Toki Pona ([official site](https://tokipona.org/), [English wikipedia](https://en.wikipedia.org/wiki/Toki_Pona), [Toki Pona wikipedia](https://wikipesija.org/wiki/toki_pona)). Toki Pona is a constructed language by Sonja Lang with only about 130 words, which makes it incredibly easy to learn.
### Consistency
Consistency is the core concept of Lojban (pronounced [ˈloʒban], [English Wikipedia](https://en.wikipedia.org/wiki/Lojban)), succedor of Loglan. It is a very consistent language with strict rules, which prevent ambiguous sentences. Lojban can be easily translated for robots and shows connections with combinatory logic and programming languages.

## Languages
### Upgraded Toki Pona
One part I dislike about Toki Pona is unconsistency. It is way better than some other languages like English and French (see [here](https://www.youtube.com/@loic.suberville/)), but still not as good as Lojban. For example, *li* isn't used in first and second person (with *mi* or *sina*) unlike the third person where it is mandatory. Another fatal flaw in Toki Pona is its numbering system, where you can use basically just *wan*, *tu* and sometimes *luka* (which translates to *one*, *two* and *five*). (It is important to note that there are alternative unofficial numbering systems.)

Toki Pona is a good language, but it could be even better if it was a bit more consistent and had a good numbering system.

### Universal language
This idea does NOT aim to make a language suitable for everyday speaking. Instead, the goal of this idea is to create a consistent language which can express anything that any other language can express and thus can be used for linguistic research.

Let's look at english prepositions: on, in, at. In Czech, there are only two prepositions of this kind: v, na. It is not possible to directly assign those prepositions together. Instead, we could utilize this language. The Universal language would have a preposition for a certain meaning and would be useful for translating languages, but mainly for linguistic purposes and researching languages. Take a look at the table below:

|Preposition|Meaning|English equivalents|Czech equivalents|
|-----------|-------|-------------------|-----------------|
|prep1|X is located on Y|on|na|
|prep2|X is inside of Y|in|v|
|prep3|specifying a time|in, on, at|v|
|prep4|X is in country Y|in|v, na|

Let's say you have English sentence *"I am **on** top of a hill."* This sentence would be translated into Universal language with a preposition *prep1*. The correct preposition in Czech is then *na*: *"Jsem **na** vrcholku hory."* Let's try different example - we have Czech sentence *"**V** pondělí sněžilo."* To Universal language, this would get translated using a preposition *prep3*. From the above table we can see that English has more prepositions for specifying a time - and in this case the correct one is only *on*: *"It snowed **on** Monday."* So right now, even without proper Universal language existence, we can see what are different prepositions actually used for!

Similar table could be done with tenses - English has 12+1, Czech has 3 and as far as I know, some languages don't have tenses (is this zero or one tenses?) (eg. Toki Pona, but this isn't accurate, since you can combine *tenpo* with many different words).

Another example: some languages use grammatical case to specify the object and subject (Czech, Finnish, Latin), some use the word order (English). For example in English, you cannot swap the sentences *"A person killed a hypo."* and *"A hypo killed a person."* - because the word order specifies what is the subject (who is killing) and what is the object (who is being killed). In Czech (Finnish, Latin, etc.), you can change the word order: *"Člověk zabil hrocha."* = *"Hrocha zabil člověk."* = *"Člověk hrocha zabil."* = *"Zabil hrocha člověk."* = ... (Only the first two sentences are neutral, the rest are rather unusual, but still valid.) If you want to swap the subject and object in Czech, you have to change the grammatical case: *"Hroch zabil člověka."* = *"Člověka zabil hroch."* = ... The universal language would help us with translating between languages with and without grammatical cases. Possible implementation is that sentence in the Universal language has to follow strict word order AND grammar case.
