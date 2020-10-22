# Contributing

Your contributions are always welcome! Here are some guidelines.

- Try to provide an actionable TL;DR as a description, quoting the original text if you need so.

## Sections

- First level sections are voluntarily not in the alphabetical order: this
list provides a progression to help with the transition to management. From
general to specifics.

- The rough order is like so:

  1. At first we'll find content appealing to software developers or new managers. We're reaching for accessibility and targets the wider audience and provide a gentle introduction.
  1. Then we can have a couple of real use-cases or anecdotes, which makes the topic more practical.
  1. Third we might add a couple of reference material to generalize concepts, or provide generic solution or broader thinking frameworks.
  1. At the end we'll add the most cynical or bleak content, because hey, we can't help it: [on a long enough time line, the survival rate for everyone drops to zero](https://www.goodreads.com/quotes/26639-on-a-long-enough-time-line-the-survival-rate-for). And these content might still have some utility as cautionary tales or signals that things might start to go south.

## List Item

- No need to add the `TL;DR:` prefix in description. It is assumed every description is a kind of short summary.

## Formatting

- A couple of CLI to fix-up some common formatting mistakes:

  - ``sed -i 's/^* /- /g' ./README.md``: replaces star list item markers by
      dashes.
  - ``sed -i "s/‘/\'/g" ./README.md`` and ``sed -i "s/’/\'/g" ./README.md``:
      replaces typographic quotes with simple ones.
  - ``sed -i 's/`$/`\./g' ./README.md``: forces quotes to end with a dot.

- This repository is still in its accumulation phase. Meaning we will not over-think adding stuff to it. The curation phase and fine-tuning can happens in a second time.
