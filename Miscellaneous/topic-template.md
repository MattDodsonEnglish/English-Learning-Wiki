# Template for Technical Topics

If you think the world is missing some technical information, why not write it?
By recognizing a gap, you already understand what the world's documentation is missing, so you know how to fill it.

For max visibility I put the template first. Before you write, it may be helpful to read the section, [How you can write good documentation](#How-you-can-write-good-documentation) first.

## A topic template
```
[Content] // commentary
```

Each section may be better served as its own page. Use common sense.

```
# [Title] // Use a title that says why it's useful:

// "How to make a cheese omellete" is better than "Omelettes"
// But maybe, "How to End Morning Hunger with just Eggs, Butter, and Cheese"
// is best of all.

[Description] // In 1-4 sentences, explain how this topic can improves the reader's life

## [Optional: Overview that orients the user] 

// Shorter is better. If possible, don't include an overview at all. 
// Make sure the user knows where to go (e.g. in the UI)
// Make sure the user knows how this topic can help them accomplish a task

## [How to accomplish a task] //use titles that summarize the content
// (It might be easier to make a title after writing)

// Break the instructions down into shorter instructions of 3-7 items.

1. Buy food at the grocery story. (If you have food, skip to step 2)

1.1. Buy eggs
1.2. Buy butter
1.3. Buy cheese

2. Make omelette (if you don't have eggs, go to step 1)

2.1. Break eggs into bowl 

// yada yada
// Very long instructions can be broken into subsections

## [Optional: Concept] //Title explains how concept improves task achievement

// always think, "why does this help the user?"

## [Optional: reference] 

// Include information that an advanced user wants to look up
// Use tables and bullet points

## [Related topics]

[Links to other related topics]
```

## How you can write good documentation

You don't need to be a writing expert to write great documentation.
Really, if you just follow these guidelines, your documentation will probably be better than the average document found on the web. 

### Put the most useful content first

I initially had this help section at the beginning of this document.
But let's be honest, it's not this page's most useful content.

### Good documentation is goal-oriented, accurate and clear

The most important thing is that the _documentation makes the user's life easier_.
Orient the topic towards how the user can achieve their goals.
When you include conceptual information, be sure to ask yourself, "Why does the user need to know this? Will this help them achieve their goals?" 

Good documentation is

* **Easy to use:**
  * task-oriented─how does this help the reader do their job
  * accurate─if you've ever followed instructions that broke something, you understand the importance of accuracy
* **Easy to understand**: 
  * Clearly written
  * Uses concrete examples

### Put conceptual information, reference, and technical details in their own section

Preferably after the how-to.

Although user goals should be the first and second priority, sometimes it does help to include conceptual information and references. Always ask, does the user need to know this?
It might be useful to explain that synchronous calls are faster for one function but slow the overall system down;
it's probably useless to provide detailed diagrams of your backend's messaging infrastructure.
It might be useful to provide a reference of different examples of all configurable parameters;
it's probably useless to document the function of every button in the UI.

If the concept is very long, put it on its own page.
Stripe is known for good documentation;
see their knowledge base articles for examples of [reasonably-sized long articles](https://stripe.com/docs/billing/subscriptions/fixed-price) and [reasonably-sized short ones](https://stripe.com/docs/stripe-cli).

### When possible, have a someone else check it

A second pair of eyes always helps.

## See more

* [Microsoft style guide](https://docs.microsoft.com/en-us/style-guide/welcome/).
Instead of wondering whether something should be **bold** or `monospace`
just look it up.
* Diataxis.fr . A fancy name for a great documentation framework.
