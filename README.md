# ivy.css

_Minimalistic modular CSS-only framework. It isn't complete!_

Well, it isn't definitely CSS only, it's written using Sass. But it's compiled into pure CSS!

I have made this simple CSS framework for learning. As it's experimental, incomplete, unstable and I won't probably actively mantain it, I advise you to don't use it in production. But if you find this project to interest you, you are free to try it. I have made even a demo that is hosted on GitHub pages. I will show basic usage too.

## Usage

Because it's CSS-only, you can use it in any way you want. I recommend to avoid bundling for testing it out.

If you chose to don't use a bundler, you can easily build the framework (you will need Node installed) and copy the `all.css` and `themes/default.css` files from dist directory elsewhere. Then you can include them in your HTML.

I recommend looking into `demo.html` for almost every component, or you can always look into the Sass source. I tried to comment it. But here are some basic ones (for now the only ones):

- `ivy-text` - regular text
- `ivy-title-*` - title text, from 1 to 3 right now
- `ivy-button-filled` - a filled button, you can use the _dangerous_ variant too
- `ivy-button-outline` - it has only an outline, as the name tells you

You have to include a theme too, so if you want to start quickly, I made a default theme, it's in `themes/default.css`. You can include it by adding the `ivy-theme-default` class to `body` (or any other valid parent).
