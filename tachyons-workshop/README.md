# Tachyons Workshop

## Goals

+ Have some reusable html snippets you can drop into a web app or website
+ Get comfortable with the Tachyons classnames and how to use them
+ Get comfortable with flexbox

## Getting Started

1. Clone the repo or fork it
2. For each exercise make a new html file named after the exercise e.g. `nav.html` (there's a template `starter.html` file if you'd like to use this)
3. Either use the default tachyons stylesheet link in your html: `<link rel="stylesheet" href="https://unpkg.com/tachyons@4.8.0/css/tachyons.min.css"/>`
4. Or if you're more of a design control freak you can use the custom setup in the `tachyons-postcss-setup` (details on how to use this [here](https://github.com/TechforgoodCAST/prototyping-workshop/tree/master/tachyons-workshop/tachyons-postcss-setup))
5. Make some beautiful components!

## Tips and Tricks

Always have this page open! http://tachyons.io/docs/table-of-styles/, it's super helpful for finding styles and their classnames

Take inspiration from these if you get stuck http://tachyons.io/components/ but try not to copy them (you'll get more out of the workshop if you get used to composing styles).

Some handy classes you'll use a lot:

#### Spacing (padding and margin)
+ `pa1, pa2, pa3 etc` - stand for "padding all 1, 2, 3", each number increasing with more padding
+ `ma1, ma2, ma2 etc` - same as above but with margin
+ `pl1, pl2, pl3 etc` - stand for "padding left 1, 2, 3"
+ `pr1, pr2, pr3 etc` - stand for "padding right 1, 2, 3"

#### Display and Position
+ `db` - "display block"
+ `dib` - "display inline block"
+ `dn` - "display none"
+ `flex` - "display flex"
+ `absolute` - "position absolute"
+ `relative` - you get the idea
+ `fixed`
+ `static`

#### Colors
(all the colors can be found here http://tachyons.io/docs/themes/skins/)

+ `blue` - "makes text blue"
+ `bg-blue` - "with a blue background"
+ `hover-bg-blue` - "hovering over element makes background blue" (to add a nice transition add `bg-animate`)

#### Flexbox
+ `flex` - "display flex"
+ `items-center` - "align items center"
+ `justify-center` - "justify content center"
+ `flex-wrap` - "flex wrap: wrap"

This is a great summary of what flexbox can do: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

## Let's make some components!

### Button

Make a button that looks a bit like this:

<img width="240" alt="screen shot 2017-09-21 at 20 20 05" src="https://user-images.githubusercontent.com/14013616/30714315-4818bf48-9f0a-11e7-9974-de18941983d8.png">

(tip: if you're using the `<button>` html element it has a few rather ugly default styles (user agent styles), so you'll want to set the border to none and give it a slight border-radius for the round edges)

### Navbar

Make a navbar that looks like this:

![nav](https://user-images.githubusercontent.com/14013616/30590775-04880d20-9d38-11e7-946b-6d40e185ccde.png)

Bonus points if you can make the text have a hover color

### Full Screen Hero Banner

Make a hero banner that fills the screen (horizontally) and centers the content inside it

![screen shot 2017-09-19 at 14 55 10](https://user-images.githubusercontent.com/14013616/30595994-bae629c8-9d4a-11e7-8a08-d47fbaa21c0f.png)

### Responsive Grid

Make a responsive grid a bit like this:

![grid](https://user-images.githubusercontent.com/14013616/30595435-21899216-9d49-11e7-8b33-8258f4819861.png)

Or this:

![screen shot 2017-09-19 at 14 48 57](https://user-images.githubusercontent.com/14013616/30595656-b3e0bb8a-9d49-11e7-8bb7-e037805a722b.png)

Bonus points if you can make the widths change at different screen sizes! (hint some tachyons class have responsive suffixes like `-ns`, `-m` or `-l` which correspond to "not small", "medium" and "large")

Even more bonus points if you can start adding content to each box:
+ maybe use your new found centering skills to center text horizontally and vertically in one of them
+ Or add some icons in the bottom right corner

### Form

Make a form like this:


<img width="522" alt="screen shot 2017-09-21 at 20 10 44" src="https://user-images.githubusercontent.com/14013616/30713983-12ac40d8-9f09-11e7-9c1a-8116835257b1.png">

Can you make it responsive so it doesn't fill the whole screen on desktop but fits the screen on mobile (hint: max-width classes will help here `mw4`, `mw5` etc)
