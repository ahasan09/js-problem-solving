# Improvement Plan: problem-practice

## Overview
Vanilla JS problem practice with a number-to-words converter. Single project, no tests, no build pipeline, limited scope.

## Improvements

### Expand the Problem Set
- Add more algorithm exercises: FizzBuzz, Fibonacci, palindrome check, anagram detection, binary search, linked list operations, binary tree traversal
- Organize into categories: `strings/`, `numbers/`, `arrays/`, `data-structures/`

### Testing
- Add a root `package.json` with Jest configured
- Add unit test files alongside each solution
- Add a `npm test` script running all tests
- Add GitHub Actions CI to run tests on every push

### Code Quality
- Convert to TypeScript with strict mode
- Add ESLint + Prettier
- Separate algorithm logic from DOM code so business logic is testable without a browser

### Build Pipeline
- Add Vite for bundling and a hot-reload dev server
- Add a root `index.html` gallery page listing all exercises with links

### Documentation
- Add a README describing each problem, the approach taken, and the time/space complexity
- Add complexity annotations inline (`// O(n)`, `// O(1) space`)

### DevOps
- Add GitHub Actions CI: lint + test + build
