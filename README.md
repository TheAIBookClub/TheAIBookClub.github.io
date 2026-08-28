# AI Book Club 📚

We read one AI/ML book every month, discuss it asynchronously on [Discord](https://discord.com/invite/6BremEf9db), and chat with the authors when we finish.

**Website:** https://theaibookclub.github.io/

## Adding a new book

Everything lives in a single `index.html`:

- **Now reading:** edit the `.book-card` block in the `#reading` section.
- **Past readings:** add one line to the `VIDEOS` array at the bottom of the file, e.g.
  `{id:"<youtube-id>", tag:"ml", title:"Meet the Author: <Book Title>"}` (tags: `ml` or `de`).
