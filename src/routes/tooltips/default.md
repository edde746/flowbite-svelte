---
layout: doc
---

<script>
import {Tooltip, Button} from 'flowbite-svelte'
</script>

<h1 class="text-3xl w-full dark:text-white">Default Tooltip</h1>

<h2 class="text-2xl w-full dark:text-white">Tooltip top</h2>

<div class="container flex flex-wrap justify-center rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <Tooltip tip="My tooltip content" top>
    <Button />
  </Tooltip>
</div>

```svelte
<script>
import {Tooltip, Button} from 'flowbite-svelte'
</script>

<Tooltip tip="My tooltip content" top>
  <Button />
</Tooltip>
```


<h2 class="text-2xl w-full dark:text-white">Tooltip bottom</h2>

<div class="container flex flex-wrap justify-center rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <Tooltip tip="My tooltip content" bottom>
    <Button />
  </Tooltip>
</div>

```svelte
<script>
import {Tooltip, Button} from 'flowbite-svelte'
</script>

<Tooltip tip="My tooltip content" bottom>
  <Button />
</Tooltip>
```

<h2 class="text-2xl w-full dark:text-white">Tooltip right</h2>

<div class="container flex flex-wrap justify-center rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <Tooltip tip="My tooltip content" right>
    <Button />
  </Tooltip>
</div>

```svelte
<script>
import {Tooltip, Button} from 'flowbite-svelte'
</script>

<Tooltip tip="My tooltip content" right>
  <Button />
</Tooltip>
```


<h2 class="text-2xl w-full dark:text-white">Tooltip left</h2>

<div class="container flex flex-wrap justify-center rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <Tooltip tip="My tooltip content" left>
    <Button />
  </Tooltip>
</div>

```svelte
<script>
import {Tooltip, Button} from 'flowbite-svelte'
</script>

<Tooltip tip="My tooltip content" left>
  <Button />
</Tooltip>
```