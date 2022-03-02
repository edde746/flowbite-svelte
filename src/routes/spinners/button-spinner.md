---
layout: doc
---

<script>
  import { SpinnerButton } from "flowbite-svelte";
</script>


<h1 class="text-3xl w-full dark:text-white py-4">Button spinner</h1>


```svelte
<script>
  import { SpinnerButton } from "flowbite-svelte";
</script>
```

<h2 class="text-2xl mt-8 dark:text-white py-4">Default Prop</h2>

```js
let color; // {null|blue}
```

<h2 class="text-2xl mt-8 dark:text-white py-4">Colors</h2>

<div class="container w-full rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
<SpinnerButton />
<SpinnerButton color="blue" />
</div>

```svelte
<SpinnerButton />
<SpinnerButton color="blue" />
```

<h2 class="text-2xl mt-8 dark:text-white py-4">Slot</h2>

<div class="container w-full rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
<SpinnerButton>Here you go ...</SpinnerButton>
<SpinnerButton color="blue" >Here you go ...</SpinnerButton>
</div>

```svelte
<SpinnerButton>Here you go ...</SpinnerButton>
<SpinnerButton color="blue" >Here you go ...</SpinnerButton>
```