# Reveal.js Markdown Only

> Use `reveal.js` without having to touch a single line of HTML

`reveal.js` is a nice presentation framework but it can be a bit daunting to get started with especially if you are not familiar with HTML. The purpose of this fork is to provide a template that uses markdown, exclusively, for creating slides.

## Installations

In order to use this repository, you need the following prerequisites:

- nodejs installed
- npm installed and configured

To install the dependencies, run `npm install` in the root directory of the repository.

## Getting started

To get started, run `npm start` in the root directory of the repository. You can access the presentation in your browser by opening [http://localhost:8000](http://localhost:8000).

## Usage

> [!TIP]
> 
> Run `npm start` to start the presentation server and follow the tutorial

This is a basic template for a reveal.js presentation that uses markdown. All you have to do is edit the markdown files in the `slides` folder and update the `slides/index.html` file accordingly.

### Step 1. Adding slides

First, you create a new markdown file `example.md` in the `slides` folder.

### Step 2. Updating the slides/index.html file

> [!WARNING]
>
> The order of the slides is determined by the order of the list items in the `index.md` file. Make sure to update the list accordingly.

Add the file name to the `index.md` file in the `slides` folder. 

```md
<!-- in slides/index.md (note: the numbers matter!!!)-->
1. simple.md
2. images.md
3. audio.md
4. code.md
5. tables.md
6. all-in-one.md
7. example.md
```

### Good to know

The number in front of the file name **determine the order of the slides** in the presentation. That means you can easily re-order your slides by changing the order of the list items.

```md
<!-- in slides/index.md-->
1. first-file.md
3. third-file.md
2. second-file.md
```

## Credits

This repo was forked from hakimel/reveal.js (v5.0.0)
