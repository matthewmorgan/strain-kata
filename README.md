# Strain

Implement the `keep` and `discard` operation on collections. Given a collection
and a predicate on the collection's elements, `keep` returns a new collection
containing those elements where the predicate is true, while `discard` returns
a new collection containing those elements where the predicate is false.

For example, given the collection of numbers:

- 1, 2, 3, 4, 5

And the predicate:

- is the number even?

Then your keep operation should produce:

- 2, 4

While your discard operation should produce:

- 1, 3, 5

Note that the union of keep and discard is all the elements.

The functions may be called `keep` and `discard`, or they may need different
names in order to not clash with existing functions or concepts in your
language.

## Restrictions

Keep your hands off that filter/reject/whatchamacallit functionality
provided by your standard library!  Solve this one yourself using other
basic tools instead.

## Source

Suite and description come from exercism.io, which credits a conversation with James Edward Gray II [https://twitter.com/jeg2](https://twitter.com/jeg2)

## Submitting Incomplete Solutions
It's possible to submit an incomplete solution so you can see how others have completed the exercise.
## Requirements

You should use [NodeJS v8](https://nodejs.org/en/download/) or above.

Install assignment dependencies:

```bash
npm install
```

## Linting your code

Check your code for style issues:

```bash
npm run lint
```

## Making the test suite pass

Run Jest in watch mode, with coverage info like this:

```bash
npm run watch:cover
```

In the test suite all tests but the first have been skipped.

Once you get a test passing, you can enable the next one by
changing `xtest` to `test`.
