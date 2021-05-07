# Megaton Punch

> Everything makes sense suddenly. I'm really happy about it. I realized how to make the core game all of a sudden and the rest sort've fell into place. 

## KirbyClone

I'm taking a bit of the style from Kirby Samurai (easier coding idea) / Kirby Megaton Punch (harder visual/graphics idea) / Possibly even the RPG element (via hourly puzzle modes that operate in Battle Royale style against 100 monkeys)

Default to 100 monkeys at all times as opponents. Program in multiplayer cards later


---

## Dev Notes

> npm i -D @sveltejs/adapter-static@next

Install the static adapter so that you can deploy to Amplify from repo

> const static = require('@sveltejs/adapter-static');

Add this to the svelte config along with switching the "adapter" method.

> https://stackoverflow.com/a/30766041
> https://realfavicongenerator.net/

Favicons made quick and easy thanks to this guy's comment. 

> https://fonts.google.com/specimen/Nanum+Brush+Script?subset=korean&preview.text=deathMetta&preview.text_type=custom#standard-styles

Adjusting fonts and moving around some styles.

# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte);

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm init svelte@next

# create a new project in my-app
npm init svelte@next my-app
```

> Note: the `@next` is temporary

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

Svelte apps are built with _adapters_, which optimise your project for deployment to different environments.

By default, `npm run build` will generate a Node app that you can run with `node build`. To use a different adapter, add it to the `devDependencies` in `package.json` making sure to specify the version as `next` and update your `svelte.config.cjs` to [specify your chosen adapter](https://kit.svelte.dev/docs#configuration-adapter). The following official adapters are available:

- [@sveltejs/adapter-node](https://github.com/sveltejs/kit/tree/master/packages/adapter-node)
- [@sveltejs/adapter-static](https://github.com/sveltejs/kit/tree/master/packages/adapter-static)
- [@sveltejs/adapter-netlify](https://github.com/sveltejs/kit/tree/master/packages/adapter-netlify)
- [@sveltejs/adapter-vercel](https://github.com/sveltejs/kit/tree/master/packages/adapter-vercel)
- ...more soon

[See the adapter documentation for more detail](https://kit.svelte.dev/docs#adapters)
