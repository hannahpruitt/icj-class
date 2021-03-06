# Make it pretty and publish

Previous: [Loops](static-03-loops.md)

While we aren't finished with this project, I'd like you to clean up what we have and publish it.

## Base styles update

- There is a margin on the bottom of the nav that is pushing down the jumbotron. There is a style in `src/sass/nav.scss` that you can remove to fix it.

## Index updates

For these, you'll need to do some documentation reading and exploration for the solutions.

- When viewed on a desktop, the intro text on the index is really wide and not very readable. Play with the column [grid](https://getbootstrap.com/docs/4.5/layout/grid/) on the index so that the content uses full width on mobile, but fewer columns at the `md` and higher breakpoints. The content should be centered on the page, though, which you can do by applying an [offset](https://getbootstrap.com/docs/4.5/layout/grid/#offsetting-columns) to move the column over to the right.
- Go back into the pirate ships page and then peruse the [Bootstrap cards](https://getbootstrap.com/docs/4.5/components/card/#background-and-color) docs and look at how you can modify the look of those with colors and styles. Make them look a little nicer. Your choice, but make sure you can read the link text. You can use SCSS to change that color if you wish.

## Publish and check

- Push all your code to Github.
- Use Settings to set up Gihub Pages to use the `master/docs` directory.
- Add your published link to your Gitub repo at the top.

---

Next: [Baking pages](static-05-bake-explain.md)

Previous: [Loops](static-03-loops.md)
