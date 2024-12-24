# moss-kit

The smallest amount of CSS to make a great looking site that removes CSS completely. Inspired by the million other CSS frameworks that do the exact same thing. I wanted to make something that was so simple that it would be easy to understand and easy to use. I expect to break some rules alonge the way in order to make a very good looking and explicit looking site, without CSS that would make sites extremely fast. The idea is to also experiment with this in Next.js sites to see if we can cut Core Web Vitals even further if you use this over other frameworks. To dev on this follow the instructions below. I really wanted to also have a published NPM package and learn how to make that work so here we are. Moss was born. Hope you enjoy, contribute with questions and ideas or code and have fun with it.

## Inspiration and Alternatives to use before you start

This is not a replacement for any of these frameworks, it is a replacement of CSS completely. We break some rules to remove CSS completely.

- [Tailwind CSS](https://tailwindcss.com/)
- [Shadcn](https://ui.shadcn.com/)
- [Bootstrap](https://getbootstrap.com/)
- [Basscss](https://basscss.com/)
- [Pico](https://picocss.com/)
- [Quick CSS](https://quick.css/)

## Adding Moss to your project

```bash
npm install moss-kit
```

Adding the CSS to your project is as simple as adding the following to your `index.html` file.

```html
<link rel="stylesheet" href="https://unpkg.com/moss-kit@latest/dist/moss.css" />
```

To modify this add any stylesheeting below the moss.css file.

## Developing Moss

To develop on this project you can run the following commands.

```bash
npm install 
npm run dev
```

## Design Decisions

There are no classes or decisions to make, write your application and the application will be styles. 

## Breaking the Rules

Grids, columns and row. Where do you even start? I wanted to make it so you could have a great looking performant site and not even think so I decided to break some rules. Leaning on native HTML elements such `aside`, `section`, `article` and `main` to recreate the concept of a grid system. 

- `main` is going to be the main content of the page and contains what would traditionally be a `.container` class. In moss we're gonna make that our wrapper. 
- `section` is going to be the column of our pages. 
- `aside` is going to be the row of our pages with a grid class with a preset gutter / spacer
- `article` is going to be the row of our pages with a grid class with a preset gutter / spacer
- `header` is going to be prestyles to match the navigation bar of 99% of sites we see
- `footer` is going to be the footer but an options for us

## AI Sidekicks

I'm using Cursor for most of this as my editor but I'm going to handroll all the code for the packge. I'm leaning on Cursor here and there but it's missing the mark on design and breaking the rules where I want to. 

I'm also using Claude to help with naming and giving me an entire list of HTML elements to mess with. 

I copied the [simple.css list of HTML elements](https://github.com/kevquirk/simple.css/blob/main/index.html) and fed that to Claude to get the most basic list of HTML elements to work with and give me a lot of content examples. 

The moss-kit logo was made by Dall-E 3.

I am a human right now writing this. Maybe this gets good and is useful enough to be used in AI projects to build good looking sites w/o CSS or utilities classes, maybe it doesn't.

You probably want to use [v0](https://v0.dev/) to build your site with Tailwind and ShadCN but maybe Moss is an option for you if you want to cut the CSS completely. Idk. Have fun and lets build somethign and learn together. 

## License

MIT
