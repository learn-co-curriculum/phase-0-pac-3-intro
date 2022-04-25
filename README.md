# Programming as Conversation Part 3: Introduction

## Learning Goals

* Revisit abstraction

## Introduction

Before we jump into more code, let's think for a moment about something you
encounter pretty much every day when you read a news article or email: the way
we organize words to express and clarify meaning. For example, a **paragraph**
is a collection of sentences, introduced by a topic sentence and bundled up or
closed by a closing sentence. A **paragraph** can persuade or offend, direct or
explain. A paragraph has a _function_.

"Code paragraphs" are called, depending on language, "functions," "procedures,"
"methods," or "subroutines." They bundle up expressions and statements to
accomplish a task. Just as "Make a Sandwich" encompasses specific, "atomic"
actions like "get slice of bread," "get jelly," etc., `executeTransfer`
encompasses logic like `if (accountStatus === "open")` or `if (accountBalance >=
transactionAmount)`.

To have code that is easy to read, debug, and maintain, we need to bundle
collections of atomic activities into "code paragraphs" that do work. JavaScript
calls these "functions."

## Abstraction

This process of bundling up small atoms into a _function_ is called
"abstraction." "Abstraction" comes from the Latin word for "to pull away." When
we're further away, many details are hard to see. Only the most relevant shapes
are recognizable. For example, when you're on an airplane overlooking a city,
the details of the cars below — the mileage, what's in the cup holder, the
make or model — are invisible; they're not _essential_. But what we may be
able to see is the vehicle type (car vs. truck) or the color of the car. By
abstracting we see what's true at a higher level, or more _generally_.

Here are a few more "abstractions:"

* [Jerry Seinfeld][jerry], [Ruth Bader Ginsburg][ruth], and [Cardi B][cardi] are
  atomic individuals, but we can refer to them all collectively by the
  abstraction (or they can be _abstracted_ into) "famous New Yorkers"
* Books about a killer dog, a scary alter ego, and a scary clown can be
  _abstracted_ into the name "horror novels (by Stephen King)"
* Individuals with strange powers and (usually) strange clothing can be
  _abstracted_ into "superheroes"

Abstraction is a natural part of learning to converse. When you're first
learning to communicate, you don't know enough to start talking about
abstractions. You prefer to think about real, visible, tangible things. But as
you learn about opposites, how things are similar (and how perhaps one thing is
dissimilar) you grow in your ability to _abstract_.

In fact, the thing that makes most higher learning "higher" is that the
discussion, work, and discovery is focused on uncovering general principles
that allow us to predict how things will work more-or-less most of the time.
Amazingly, this was considered a pretty revolutionary idea at the time when
Galileo and Newton started doing it. The moment that natural philosophers
started looking for these "general rules of how things work," science as we
know it was born.

## Next Steps

In Programming as Conversation 3, we'll learn to take our JavaScript
_expressions_ and _statements_ and bundle them up into abstractions called
_functions_. Before we get to that, however, we first need to learn a little
about _testing_ in JavaScript.

[jerry]: https://en.wikipedia.org/wiki/Jerry_Seinfeld
[ruth]: https://en.wikipedia.org/wiki/Ruth_Bader_Ginsburg
[cardi]: https://en.wikipedia.org/wiki/Cardi_B
