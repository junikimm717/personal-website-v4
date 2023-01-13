<script setup lang="ts">
const links = [
  { href: "/", title: "Home" },
  { href: "/projects", title: "Projects" },
  { href: "/academic", title: "Academics" },
  { href: "/volunteering", title: "Volunteering" },
];
</script>
<template>
  <div
    class="flex flex-row flex-wrap items-center gap-3 py-2 text-lg font-bold"
  >
    <NuxtLink
      v-for="link in links"
      :href="link.href"
      class="font-bold hover:text-green-800 hover:decoration-green-800 dark:hover:text-green-500 dark:hover:decoration-green-500 hover:underline"
      exact-active-class="underline decoration-green-800 dark:decoration-green-500"
    >
      {{ link.title }}
    </NuxtLink>
  </div>
</template>
