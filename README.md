# Digital Logic Design Books

A community-driven JavaScript dataset of solved **Digital Logic Design** questions.

This repository currently includes structured chapter-wise solutions from **Logic and Computer Design Fundamentals** in [`dld-books-solutions.js`](./dld-books-solutions.js).

## Project Goals

- Build a clean, structured collection of DLD solved problems.
- Keep answers short, practical, and easy to search.
- Expand coverage to more chapters and books over time.

## Repository Structure

- `dld-books-solutions.js`: Main dataset exported as JavaScript objects.
- `package.json`: Project metadata.

## Usage

### 1. Clone the repository

```bash
git clone https://github.com/SENODROOM/Digital-Logic-Design-Books.git
cd Digital-Logic-Design-Books
```

### 2. Import the data in JavaScript

```js
import { logic_and_computer_design_fundamental } from './dld-books-solutions.js';

console.log(logic_and_computer_design_fundamental.Ch1[0]);
```

## Data Format

Each question entry follows this structure:

```js
{
  id: '1-1',
  category: '...',
  title: '...',
  question: '...',
  shortAnswer: '...'
}
```

## Contributing

Contributions are welcome and needed.

If you want to help, you can:

- Add new solved questions.
- Improve correctness of existing answers.
- Improve wording and formatting for readability.
- Add solutions from additional DLD books.
- Report mistakes through issues.

### Contribution Steps

1. Fork the repository.
2. Create a branch: `git checkout -b feat/your-change`.
3. Make your changes.
4. Commit clearly: `git commit -m "Add ChX solved problems"`.
5. Push and open a Pull Request.

Please keep submissions consistent with the existing object structure and chapter grouping.

## Issues

Found an error or missing solution?

Open an issue here: [GitHub Issues](https://github.com/SENODROOM/Digital-Logic-Design-Books/issues)

## License

ISC
