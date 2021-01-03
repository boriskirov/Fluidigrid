### Intro

Fluidigrid is a simple and lightweight CSS helper for building quick and efficient layouts.

### Getting started

- You can copy the [raw](github.com) file and add it to your project.
- You can use the [Fluidigrid Generator] (cssgenerator) to create your own naming convention for custom experience.

### Structure

Fluidigrid setup is simple, it is based on 12 column `grid-template-columns`. Each of the 12 cells are using the `fr` (fractional unit). When going belowe `1024px` the layout switches the `1fr`.

### How to use

You can create your own `grid` html element or add a class `.grid` to the wrapper you want to create the grid layout. Then you should declare start and values for each of your columns to create the layout. Fluidigrid comes with pre-declared naming convention, we use `cs{n}` for column-start-{column number} and `ce{n}` for column-end-{column number}. For example if you want to declare a column which starts from the first to last column you will declare `cs1 ce12`.

### Easy to use

- 2KB file
- Change to `:root`values for customization
- Use the [Fluidigrid Generator] (cssgenerator) to create your own naming convention for custom experienc

#### Check the examples

- [Codesandbox](https://codesandbox.io/s/fluidigrid-d6ttt?file=/src/App.js)
- [Codepen](https://codepen.io/bkirov/pen/VwKXeKj)
- [Glitch](https://glitch.com/edit/#!/fluidigridy)

#### License

Licensed under the [MIT License](MIT.com).

#### Contributions

We are always working on improving Fluiditype, if you want you can always contribute and ask for more, this would help us create something more meaningful.
