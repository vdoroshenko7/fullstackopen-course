# Full Stack Open

Exercises for [Full Stack Open](https://fullstackopen.com/en/), Helsinki
University's full-stack web development course.

## Structure

One repo for the whole course. Each exercise *group* — not each part — gets
its own subfolder with its own `package.json`:

```
part1/unicafe
part1/anecdotes
part2/phonebook
part3/phonebook-backend
...
```

Apps that span multiple parts (the phonebook: Part 2 → 3; the bloglist:
Part 4 → 7) keep living in the same subfolder as work progresses, rather
than being duplicated per part.

## Commits

One commit per exercise, e.g. `part1: exercise 1.3 unicafe`.

## Node

Managed via [nvm](https://github.com/nvm-sh/nvm). Parts 0-6 and 8 want
Node v22, Part 10 wants v20.11.0, other parts want v18.13+ — run `nvm use
<version>` if a part calls for something other than the default.
