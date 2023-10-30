# Reveal.js Markdown Only

> Use `reveal.js` without having to touch a single line of HTML

`reveal.js` is a nice presentation framework but it can be a bit daunting to get started with especially if you are not familiar with HTML. The purpose of this fork is to provide a template that uses markdown, exclusively, for creating slides.

## Getting started

```bash
# install dependancies
npm install

# start development server
npm start
```

Once you start the server, you can access the presentation in your browser by opening [http://localhost:8000](http://localhost:8000).

## Usage

> Run `npm start` to start the presentation server and follow the tutorial

This is a basic template for a reveal.js presentation that uses markdown. All you have to do is edit the markdown files in the `slides` folder and update the `slides/index.md` file accordingly.

### Step 1. Create slides

Create your slides as markdown file (i.e. `slide-01.md`) in the `slides` folder. You can view some examples [here](./slides).

### Step 2. Add the slide to the presentation

> The order of the file name **determines the order of the slide** in the presentation.

Add the slides to your presentation by adding the file name (i.e. `slide-01.md`) to the `index.md` file in the `slides` folder. 

```md
<!-- in slides/index.md (note: the numbers matter!!!)-->
1. simple.md
2. images.md
3. audio.md
4. code.md
5. tables.md
6. all-in-one.md
7. slide-01.md
```

**Order matters**. Slides are ordered based on their position in the numbered list. That means you can easily re-order your slides by changing the order of the list items.

```md
<!-- in slides/index.md-->
1. slide-01.md
3. slide-02.md
2. slide-03.md

<!-- presentation order -->
`slide-01.md -> slide-03.md -> slide-02.md`
```

## Credits

This repo was forked from hakimel/reveal.js (v5.0.0)
