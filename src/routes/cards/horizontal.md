---
layout: doc
---

<script>
  import { HorizontalCard } from "svelte-flow";
</script>

<h1 class="text-3xl w-full dark:text-white">Horizontal Card: Setup</h1>

```svelte
<script>
  import { HorizontalCard } from "svelte-flow";
</script>
```

<h1 class="text-3xl w-full dark:text-white">Horizontal Card</h1>

```svelte
<HorizontalCard
  img="/images/image-4.jpeg"
  header="Horizontal card"
  link="/"
>
  Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nam sint,iam.
</HorizontalCard>
```

<div class="container flex flex-wrap mt-8 mx-auto justify-center">
  <HorizontalCard
    img="/images/image-4.jpeg"
    header="Horizontal card"
    link="/"
  >
    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nam sint,iam
    quos sed rem provident, aspernatur sunt illum eum ipsam quas. Sed ipsum ex
    non.
  </HorizontalCard>
</div>

```svelte
<HorizontalCard>
  Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nam sint.
</HorizontalCard>
```

<div class="container flex flex-wrap mt-8 mx-auto justify-center">
  <HorizontalCard>
    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nam sint,iam
    quos sed rem provident, a
  </HorizontalCard>
</div>

<h1 class="text-3xl w-full dark:text-white pb-8">References</h1>

<p class="dark:text-white text-base"><a href="https://flowbite.com/docs/components/card/" target="_blank">- Flowbite Card</a></p>