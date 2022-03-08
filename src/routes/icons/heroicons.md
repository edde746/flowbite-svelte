---
layout: doc
---

<script>
  import {
    AdjustmentsIconSolid,
    BellIconOutline,
    BriefcaseIconSolid,
    TicketIconOutline,
    ChartSquareBarIconSolid,
    CameraIconOutline,
    BellIconSolid,
    ChevronLeftIconSolid,
  } from "@codewithshin/svelte-heroicons";
</script>

<h1 class="text-3xl w-full dark:text-white py-4">HeroIcons</h1>

<p class="dark:text-white py-4">Flowbite-svelte uses <a class="text-blue-600 hover:underline dark:text-blue-500" href="https://github.com/shinokada/svelte-heroicons" target="_blank">svelte-heroicons</a>.
You can find all the icon names from the <a class="text-blue-600 hover:underline dark:text-blue-500" href="https://github.com/shinokada/svelte-heroicons/blob/main/icon-names.md">repo</a>.</p>

<p class=" dark:text-white py-4">Svelte-heroicons allow you to change icon color and size by using TailwindCSS/Flowbite.</p>

<p class=" dark:text-white py-4">If you need brand icons, use <a class="text-blue-600 hover:underline dark:text-blue-500" href="https://github.com/shinokada/svelte-simpleicons" target="_blank">Svelte-simpleicons</a>.</p>

<h2 class="text-2xl w-full dark:text-white mt-8">Props</h2>

```js
let className = "h-6 w-6"
let viewBox = "0 0 24 24"
```

<h2 class="text-2xl w-full dark:text-white mt-8">Examples</h2>

<p class=" dark:text-white">If you want to change the color, add it to className.</p>

<div class="container flex flex-wrap justify-center rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">

<AdjustmentsIconSolid className="h-8 w-8 text-blue-500 dark:text-red-300" />
<BellIconOutline  className="h-8 w-8 text-red-500 dark:text-green-300" />
<BriefcaseIconSolid  className="h-8 w-8 text-green-500 dark:text-indigo-300" />
<ChartSquareBarIconSolid className="h-8 w-8 text-purple-500 dark:text-pink-300" />
<TicketIconOutline className="h-8 w-8 text-pink-500 dark:text-indigo-300" />
<CameraIconOutline className="h-8 w-8 text-indigo-500 dark:text-white" />
<BellIconSolid className="h-8 w-8 text-gray-500 dark:text-yellow-500" />
<ChevronLeftIconSolid
  className="h-8 w-8 text-yellow-300 dark:text-white"
/>
</div>

```svelte
<script>
import {
  AdjustmentsIconSolid,
  BellIconOutline,
  BriefcaseIconSolid,
  TicketIconOutline,
  ChartSquareBarIconSolid,
  CameraIconOutline,
  BellIconSolid,
  ChevronLeftIconSolid,
} from "@codewithshin/svelte-heroicons";
</script>

<AdjustmentsIconSolid className="h-8 w-8 text-blue-500 dark:text-blue-300" />
<BellIconOutline  className="h-8 w-8 text-red-500 dark:text-purple-300" />
<BriefcaseIconSolid  className="h-8 w-8 text-green-500 dark:text-indigo-300" />
<ChartSquareBarIconSolid className="h-8 w-8 text-purple-500 dark:text-red-300" />
<TicketIconOutline className="h-8 w-8 text-pink-500 dark:text-yellow-300" />
<CameraIconOutline className="h-8 w-8 text-indigo-500 dark:text-white" />
<BellIconSolid className="h-8 w-8 text-gray-500 dark:text-blue-500" />
<ChevronLeftIconSolid
  className="h-8 w-8 text-yellow-300 dark:text-white"
/>
```

<h1 class="text-3xl w-full dark:text-white py-4">References</h1>

<p class="w-full dark:text-white text-base"><a href="https://github.com/shinokada/svelte-heroicons" target="_blank" class="text-blue-600 hover:underline dark:text-blue-500">- Svelte-heroicons</a></p>

<p class="w-full dark:text-white text-base"><a href="https://heroicons.com/" target="_blank" class="text-blue-600 hover:underline dark:text-blue-500">- Heroicons</a></p>

