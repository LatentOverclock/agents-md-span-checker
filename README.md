# agents-md-span-checker

Frontend-only mathematical app: checks whether input vectors are in the span of a given group of vectors.

## Inputs
- Input 1: vectors to test
- Input 2: group (generator vectors)

## Output
- For each test vector: YES/NO whether it is in the span
- Explanation via rank criterion: `rank(A) == rank([A|v])`

## agents-md usage
- `agents-md/` included as git submodule
- root `agents.md`
- requirements in `project.md`

## Deploy
This is static and GitHub Pages ready (serve `index.html` from main branch root).
