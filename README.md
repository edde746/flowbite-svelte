# FLOWBITE SVELTE

Svelte is a modern and growing front-end compiler. Developers build boilerplate-free components using languages HTML, CSS and JavaScript. Svelte compiles your code to tiny, framework-less vanilla JS.

[Flowbite-Svelte](https://flowbite-svelte.vercel.app/) is an unofficial Flowbite component library for Svelte. All interactivities are handled by Svelte.

## Install SvelteKit and Tailwind CSS

Before anything make sure that you install SvelteKit and Tailwind CSS. If you already have them installed, you can proceed to the next step.

```bash
npm init svelte@next sveltekit-demo
cd sveltekit-demo

npm install
npx svelte-add@latest tailwindcss
```

## Install Flowbite-Svelte


Install Flowbite-Svelte using NPM:

```bash
npm i -D flowbite-svelte
```

Update the `tailwind.config.js` file with the following details:

```bash
const config = {
  content: [
    "./src/**/*.{html,js,svelte,ts}",
    "./node_modules/flowbite-svelte/**/*.{html,js,svelte,ts}",
  ],

  theme: {
    extend: {},
  },

  plugins: [
    require('flowbite/plugin')
  ],
  darkMode: 'class',
};

module.exports = config;
```

Now you are ready to go.