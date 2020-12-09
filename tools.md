# Tools that help you learn

This page collects some tools that I think are useful. 

## Corpora 

Corpora are collections of huge amounts of language. 
The corpora I use to teach English are:

* [COCA](https://www.english-corpora.org)- the granddaddy of corpora. I'm not going to make any apologies for the
UI, but COCA is a huge base that supports many tools for customization, like
part-of-speech tagging and regex. I give a demonstration of how I recently used
it below.

* [Youglish](https://youglish.com/)─ Youglish finds instances of words occurring
in Youtube videos. They state youglish is about pronunciation, but really it gives
all kinds of interesting contextual information: like the relative word frequency,
and formality. Sometimes I use it just to find contexts of where an unusual word or phrase
is used-


If you search for a word
or expression on a good corpus, you'll find lots of helpful context information.
For example, you'll find how frequently words occur,  or _collocate,_ with
others words. Handling collocations well are one of the keys to really advanced
speech.

Here's an example of how a student and I recently used a corpus. He asked me
about the times when the preposition "to" is followed by an ` -ing` form of the verb. As in 

> I look forward **to meeting** you

I told him that forward to was a rare exception. Then I realized I was doing the
worst thing a teacher could do: bullshitting. I really had no idea when "-ing"
follows "to," but I knew how I could check.

We went to the Coca corpus and did a quick search using wild card expansion for
`to *ing`. There were some false hits, like `to bring` so I searched again
using the "verb" part of speech `to [v?g*]` 

Here we found many collocations, ordered by most frequent. Some examples, using "going."

* [when it]comes to going
* forward to going
* prior to going
* [in] addition to going

 So both teacher and student used the corpus to get what they need: he got a list of common collocations, which he could memorize using Anki(#anki), and I found out that its better check the data
than to bullshit. I also realized that "to+ing" occurs whenever the "ing" could be replaced by 
common noun. E.g. "Prior to the crime," "when it comes to the crime," and "I look forward to the crime." 


## Reading

* [Slova](slova.cc) A very useful site that counts the number of times a word occurs in 
a text or on a youtube video. When unknown words appear more frequently in a text,
you know they're probably more important to learn. You can save your words and export them, which 
makes it perfect to use in conjunction with [Spaced repetition](#spaced-repetition).

Anyone who's read in a foreign language will tell you that sometimes its just not practical to look
up every unfamiliar word. However, if a word occurs frequently, a reader probably does want to learn
it. The best approach, used by many teachers, is to "pre-teach" important words. However, it's impossible to pre-teach yourself. This site helps with that.

I personally use Slova often for Spanish.

## Spaced-repetition

* [Anki](https://apps.ankiweb.net/). What I personally use. There are many others, like mnemosyne.

Language learning is a field where a certain amount of brute memorization is actually necessary.
[Spaced Repetition](https://en.wikipedia.org/wiki/Spaced_repetition) is a proven tool to improve long term recall of information.

Besides vocabulary, spaced repetition is very memorizing for collocation and tricky grammar. As my "forward to going" example showed above, English prepositions are notoriously tricky. The rules for when to use them are often completely arbitrary, or even non-existent. Even when there are rules, it's so tricky to remember them that it's better just to memorize and not look for a system. Think of it like
trigonometry: although there are formal methods for calculating `SIN`, for the vast majority of us non-mathematicians, it more than suffices just to mash the button on the calculator.
