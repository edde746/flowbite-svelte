---
layout: doc
---

<script>
  import {ButtonGroup, ButtonGroupOutline} from 'flowbite-svelte'
  import {UserCircleIconSolid, AdjustmentsIconSolid, CloudDownloadIconSolid} from "@codewithshin/svelte-heroicons"
  let buttons1 = [
  {
    name: "Profile",
    link:"/",
    icon: UserCircleIconSolid
  },
  {
    name: "Settings",
    link:"/",
    icon: AdjustmentsIconSolid
  },
  {
    name: "Messages",
    link:"/",
    icon: CloudDownloadIconSolid
  },
];
  let buttons2 = [
  {
    name: "Profile",
  },
  {
    name: "Settings",
  },
  {
    name: "Messages",
  },
];
</script>


<h1 class="text-3xl w-full text-gray-900 dark:text-white py-4">Outline Button Group</h1>

<h2 class="text-2xl w-full text-gray-900 dark:text-white py-4">Setup</h2>

```svelte
<script>
  import {ButtonGroup, ButtonGroupOutline} from 'flowbite-svelte'
  import {UserCircleIconSolid, AdjustmentsIconSolid, CloudDownloadIconSolid} from "@codewithshin/svelte-heroicons"
  let buttons1 = [
  {
    name: "Profile",
    link:"/",
    icon: UserCircleIconSolid
  },
  {
    name: "Settings",
    link:"/",
    icon: AdjustmentsIconSolid
  },
  {
    name: "Messages",
    link:"/",
    icon: CloudDownloadIconSolid
  },
];
  let buttons2 = [
  {
    name: "Profile",
  },
  {
    name: "Settings",
  },
  {
    name: "Messages",
  },
];
</script>
```

<h2 class="text-2xl w-full text-gray-900 dark:text-white py-4">Props</h2>

```svelte
let buttons = [
  {
    name: "Profile",
    link:"/", // optional
    icon: UserCircleIconSolid // optional
  },
  {
    name: "Settings",
    link:"/", // optional
    icon: AdjustmentsIconSolid // optional
  },
  {
    name: "Messages",
    link:"/", // optional
    icon: CloudDownloadIconSolid // optional
  },
];
```

<h2 class="text-2xl w-full dark:text-white py-4">Outline default</h2>

<div
  class="container flex flex-wrap justify-evenly rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <ButtonGroupOutline buttons={buttons2}/>
</div>

```svelte
<ButtonGroupOutline buttons={buttons2}/>
```


<h2 class="text-2xl w-full dark:text-white py-4">Outline with icon</h2>

<div
  class="container flex flex-wrap justify-evenly rounded-xl my-4 mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  
<ButtonGroupOutline buttons={buttons1}/>
</div>

```svelte
<ButtonGroupOutline buttons={buttons1}/>
```

