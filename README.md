# Challenge 01 - React concepts

## 💻 About the challenge
In this challenge, you must create an application to train what you have learned so far in ReactJS 

This will be an application where your main objective is a small to-do application, to train a little more about state manipulation in React.

- Add a new task
- Remove a task
- Mark and unmark a task as complete

### What should I edit in the application?

#### components/TaskList.tsx

This is the component responsible for all the functionality of the application, it is a simple component, but where we will put into practice several parts of the state manipulation.

You must create the functionalities for the three functions present in this file, which are:

- **handleCreateNewTask:** It must be possible to add a new task in the `tasks` state, with the fields `id` that must be generated randomly, `title` that must be a text and `isComplete` that must start as false.
- **handleToggleTaskCompletion:** It must change the status of `isComplete` for a task with a specific ID that is received by parameter.
- **handleRemoveTask:** Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.

## How to run the project

In the project folder via terminal, run the `yarn dev` or `npm run dev` command
- to run the tests run the command `yarn test`

### 📖 [Notion](https://www.notion.so/Desafio-01-Criando-um-hook-de-carrinho-de-compras-5769216778794019a83f544e79167b12)
