# Part 2

## Goals

- Understand the complexity that callbacks could bring and ways to elemenate those complexities.

## Questions

### Question

Design a system using NodeJs that:

- Hosted on github, each change should be checked out to a branch, please add all the mentors as collaborators.
- Use node version 12 via NVM.
- Solve the next task in 3 ways, the first one using callbacks, the second one using promises, the third one using Async/Await.
- Loop inside all files in a directory (an example folder is given) (1 level, no need for recursion here) and for each file:
  - Read the file content, size, creation date, modification date and store all this data in a new collection in your mongodb (let's call it `files`)

### Evaluation criteria

- Setting up all the changes in a github repo
- Use NVM to manage and switch between node versions.
- Setting up mongodb
- Function structure will be considered at this time.
- Solving the question in callbacks, promises and Async/Await way.
