---
layout: doc
---

<script>
  import {BadgeIcon} from 'flowbite-svelte'
  import {InformationCircleIconOutline} from '@codewithshin/svelte-heroicons'
  let link="/"
</script>


<h1 class="text-3xl w-full text-gray-900 dark:text-white py-4">Badges with icon</h1>

<p class="text-lg w-full text-gray-900 dark:text-white py-4">You can use <a href="https://github.com/shinokada/svelte-heroicons" target="_blank" class="text-blue-600 hover:underline dark:text-blue-500">Svelte-heroicon.</a></p>

```svelte
<script>
  import {BadgeIcon} from 'flowbite-svelte'
  import {InformationCircleIconOutline} from '@codewithshin/svelte-heroicons'
  let link="/"
</script>
```

<h2 class="text-2xl w-full text-gray-900 dark:text-white py-4">Props</h2>

```js
let textSize = "text-xs"; // 'text-xs'|'text-sm'|'text-base' |'text-lg' |'text-xl'|'text-2xl'|'text-3xl'|'text-4xl'
let name = "Read more";
let color = "blue"; // 'blue'| 'gray'| 'red'| 'yellow'| 'purple'| 'green'| 'indigo'| 'purple'| 'pink'
```

<h2 class="text-2xl w-full dark:text-white py-4">Size xs</h2>

<div
  class="container flex flex-wrap justify-evenly rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
<BadgeIcon name="Default" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Gray" color="gray" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Red" color="red" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Green" color="green" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Yellow" color="yellow" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Indigo" color="indigo" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Purple" color="purple" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Pink" color="pink" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
</div>

```svelte
<BadgeIcon name="Default" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Gray" color="gray" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Red" color="red" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Green" color="green" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Yellow" color="yellow" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Indigo" color="indigo" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Purple" color="purple" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Pink" color="pink" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
```

<h2 class="text-2xl w-full dark:text-white py-4">Size sm</h2>

<div
  class="container flex flex-wrap justify-evenly rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
<BadgeIcon name="Default" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Gray" color="gray" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Red" color="red" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Green" color="green" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Yellow" color="yellow" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Indigo" color="indigo" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Purple" color="purple" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Pink" color="pink" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
</div>

```svelte
<BadgeIcon name="Default" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Gray" color="gray" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Red" color="red" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Green" color="green" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Yellow" color="yellow" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Indigo" color="indigo" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Purple" color="purple" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Pink" color="pink" textSize="text-sm" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
```

<h2 class="text-2xl w-full dark:text-white py-4">Size base</h2>

<div
  class="container flex flex-wrap justify-evenly rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
<BadgeIcon name="Default" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Gray" color="gray" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Red" color="red" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Green" color="green" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Yellow" color="yellow" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Indigo" color="indigo" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Purple" color="purple" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Pink" color="pink" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
</div>

```svelte
<BadgeIcon name="Default" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Gray" color="gray" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Red" color="red" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Green" color="green" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Yellow" color="yellow" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Indigo" color="indigo" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Purple" color="purple" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
<BadgeIcon name="Pink" color="pink" textSize="text-base" ><InformationCircleIconOutline className="h-4 w-4 mr-1"/></BadgeIcon>
```